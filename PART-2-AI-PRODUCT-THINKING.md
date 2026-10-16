# Part 2 — AI Product Thinking (under 300 words)

## COKA ClimateBrief: a guided early-stage design brief

**What it does / who it serves:** COKA ClimateBrief is a guided assistant for prospective Studio COKA clients, especially people planning a home or small building who do not know what information an architect needs at the start.

**Problem:** Early enquiries often arrive as vague ideas. Important context—site, intended use, budget range, comfort priorities, accessibility needs and local climate considerations—may be missing, leading to slow clarification and mismatched expectations.

**User journey:** A visitor answers a short, mobile-friendly questionnaire and can describe their goals in their own words. The AI turns the answers into a structured draft brief, highlights missing information, and suggests questions to discuss with the studio. The user reviews and edits it before choosing whether to send it to Studio COKA. The output is an intake aid, not architectural advice or a design approval.

**Technology and MVP:** Use an OpenAI API model for summarisation and structured JSON output, behind a small serverless endpoint so the API key is never exposed in browser code. Build the interface in HTML/React, validate required fields, and store nothing by default; provide a clear consent step if the user chooses to submit the brief. Start with a narrow prototype: questionnaire, generated summary, editable result and copy/download action. Test with sample enquiries before adding any CRM integration.

**Risks and safeguards:** AI can invent details or offer unsuitable climate recommendations. Instruct it to use only supplied facts, label assumptions, ask follow-up questions when information is missing, and include human review. Avoid collecting sensitive personal information; explain data handling and retention. Do not claim regulatory compliance or replace a qualified architect's judgment.
