# Before & After Prompt Example

## Workplace Task

Creating a concise project status update from project information.

---

## Before

### Prompt

> Summarize this project update.

### Initial Result

> The project is progressing. Some tasks are completed, while other tasks are still in progress. There are some issues that may affect the timeline. The team is continuing to work on the remaining activities.

### What Was Missing

* The output was too general.
* The project status was not clearly structured.
* Risks and next steps were not separated.
* The format was not suitable for a professional project update.

---

## After

### Improved Prompt

> **Context:** I am a Project Coordinator preparing a project status update for management.
>
> **Task:** Summarize the provided project information into a concise status update.
>
> **Requirements:**
>
> * Separate the output into: Overall Status, Key Progress, Risks/Issues, and Next Steps.
> * Use clear and professional business language.
> * Keep the summary concise and easy to scan.
> * Do not invent information that is not provided.
> * If information is missing, write `[Not Specified]`.
>
> **Output Format:**
>
> | Section        | Summary |
> | -------------- | ------- |
> | Overall Status |         |
> | Key Progress   |         |
> | Risks/Issues   |         |
> | Next Steps     |         |

### Improved Result

The improved prompt produces a more structured and management-friendly status update, with clear sections for progress, risks, and next steps. Missing information can also be identified instead of being assumed.

---

## What Improved

| Improvement         | Description                                                              |
| ------------------- | ------------------------------------------------------------------------ |
| Clear Role          | Defined the role as a Project Coordinator.                               |
| Clear Task          | Specified that the goal is to create a project status update.            |
| Structured Output   | Added clear sections for status, progress, risks/issues, and next steps. |
| Professional Tone   | Requested concise and professional business language.                    |
| No Fabrication      | Instructed AI not to invent information.                                 |
| Missing Information | Added `[Not Specified]` when information is unavailable.                 |
| Usable Format       | Added a table that can be easily reviewed and reused.                    |

## Key Learning

A more effective prompt provides clear context, task requirements, constraints, and an expected output structure. This makes the AI response more consistent and easier to review.
