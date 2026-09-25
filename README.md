# Claude Business Plan Maker

A Claude skill that interviews you about your business and generates a complete, investor-ready business plan as a Word document.

Turn a business idea into a full business plan (.docx) through a short interview with Claude. No blank page, no generic template.

## What it does

- Asks a small set of batched questions covering company basics, strategy, funding path, and financials, rather than one long form
- Drafts a full business plan following a proven structure: executive summary, company description, market analysis, organization & management, products/services, marketing & sales strategy, operational plan, financial plan, and appendices
- Automatically includes or omits IPO/outside-investment-specific language depending on whether you're pursuing external funding or running a self-funded, owner-operated business
- Never invents precise financial figures. If you don't have real numbers yet, it clearly labels projections as estimates/assumptions rather than presenting them as fact
- Writes the executive summary last, synthesized from everything else in the plan, the same way a real executive summary should be built
- Delivers the finished plan as a downloadable .docx file, ready to edit further or share

## Requirements

- A claude.ai account (Free, Pro, Max, Team, or Enterprise all support skills)
- The **"Code execution and file creation"** capability enabled in your Claude settings

## Installation

1. Download `business-plan-maker.skill` from this repository
2. In claude.ai, go to **Settings > Capabilities** and turn on **"Code execution and file creation"**. This is required for any custom skill to run
3. Go to **Settings > Customize > Skills**
4. Click **"Upload skill"** and select the downloaded `business-plan-maker.skill` file
5. Make sure the toggle next to **business-plan-maker** is switched on

That single file contains everything the skill needs, no other download or setup is required.

## Usage

Start a new conversation and describe your business idea, asking for a business plan. For example:

> "I'm starting a mobile dog grooming business, can you help me write a business plan?"

Claude will recognize the skill applies, ask a few batched questions about your business, and generate the finished document.

## What's inside the skill

- `SKILL.md`, the instructions Claude follows to run the interview and draft the plan
- `reference_template.docx`, a genericized business plan template (no real company data) that defines the structure and voice of every generated plan

`Business_Plan_Template.docx` in this repository is the same template on its own, useful if you'd like to preview or fill it in manually without installing the skill.

## License

Released under the **MIT License**. Use it, modify it, redistribute it, or build on it however you like, just keep the original copyright and license notice included. See [LICENSE](LICENSE) for the full text.

## Disclaimer

This skill assists with drafting a business plan; it does not replace professional legal, financial, or investment advice. If your circumstances call for that, consult a qualified advisor before relying on any plan it produces.
