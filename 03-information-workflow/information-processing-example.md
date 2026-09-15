# Information Processing Workflow

## Workplace Task

Turning project information into a structured project update.

## 1. Raw Input

The raw input may contain project information such as:

- Project name
- Current status
- Completed activities
- Ongoing activities
- Risks or issues
- Target dates
- Next actions
- Project owner

Only information provided in the source material is used.

## 2. Prompt

> I am a Project Coordinator preparing a structured project update.
>
> Organize the provided project information into the following categories:
> - Project Status
> - Key Progress
> - Risks/Issues
> - Target Date
> - Next Actions
> - Project Owner
>
> Use concise and professional language.
> Do not invent or assume missing information.
> If information is not provided, write `[Not Specified]`.

## 3. AI Output

The AI organizes the information into a structured format:

| Category | Information |
|---|---|
| Project Status | Current status from the source |
| Key Progress | Completed or ongoing activities |
| Risks/Issues | Identified risks or issues |
| Target Date | Provided target date |
| Next Actions | Upcoming actions |
| Project Owner | Provided owner |

## 4. Human Review

The Project Coordinator reviews the AI output and checks:

- Each statement against the original information.
- That no information has been invented.
- That missing information is marked `[Not Specified]`.
- That dates and project status are accurate.
- That the information is placed under the correct category.

Any inaccurate or unsupported information is corrected or removed.

## 5. Final Structured Output

After human review, the information is presented in a final structured table:

| Category | Final Information |
|---|---|
| Project Status | Verified project status |
| Key Progress | Verified progress |
| Risks/Issues | Verified risks/issues or `[Not Specified]` |
| Target Date | Verified target date or `[Not Specified]` |
| Next Actions | Verified next actions |
| Project Owner | Verified owner or `[Not Specified]` |

## Workflow

**Raw Input → Prompt → AI Output → Human Review → Final Structured Output**

## Key Principle

AI is used to organize and structure information, while the human remains responsible for checking the accuracy of the final output.
