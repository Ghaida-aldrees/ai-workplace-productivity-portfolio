# Prompt Library — Project Coordinator

This prompt library contains reusable generative AI prompts designed to support common Project Coordinator tasks. Each prompt follows the C.A.R.E. framework and is designed to produce structured, practical, and reviewable outputs.

| Prompt Name | Workplace Task | Framework | Prompt | Expected Output |
|---|---|---|---|---|
| Project Status Summary | Summarizing project updates | C.A.R.E. | **Context:** I am a Project Coordinator preparing a project status update. **Action:** Summarize the information provided and identify the current status, key progress, risks, issues, and pending actions. **Role:** Act as a project coordination assistant. **Expected Output:** Present the result in a concise table with Status, Progress, Risks/Issues, and Next Actions. Do not add information that is not provided. | A concise project status summary |
| Meeting Action Items | Extracting actions from meeting notes | C.A.R.E. | **Context:** I have meeting notes from a project discussion. **Action:** Extract all action items and identify the owner, deadline, priority, and status only when explicitly stated. **Role:** Act as a Project Coordinator. **Expected Output:** Present the result in a structured action-item table. Use [Not Specified] when information is missing. | Action-item tracking table |
| Stakeholder Follow-up | Writing a professional follow-up | C.A.R.E. | **Context:** I need to follow up with a project stakeholder regarding a pending item. **Action:** Draft a concise and professional follow-up message that clearly states the pending action and requested update. **Role:** Act as a Project Coordinator. **Expected Output:** Provide a professional message with a clear purpose, action requested, and polite closing. Do not create missing details. | Professional follow-up message |
| Project Risk Summary | Summarizing project risks | C.A.R.E. | **Context:** I am reviewing project information that contains potential risks or issues. **Action:** Identify and summarize the risks or issues explicitly mentioned in the source. **Role:** Act as a Project Coordinator. **Expected Output:** Present a table containing Risk/Issue, Impact, Owner, Status, and Next Action. Mark unavailable information as [Not Specified]. | Structured risk and issue summary |
| Executive Project Update | Preparing an executive-level update | C.A.R.E. | **Context:** I need to prepare a concise project update for management. **Action:** Convert the provided project information into a short executive summary highlighting overall status, key achievements, major risks/issues, and required actions. **Role:** Act as a Project Coordinator. **Expected Output:** Use concise professional language and clear headings. Do not add assumptions or unsupported information. | Executive project update |
| Project Meeting Summary | Summarizing a project meeting | C.A.R.E. | **Context:** I have notes from a project meeting. **Action:** Summarize the main discussion points, decisions, action items, and unresolved points. **Role:** Act as a Project Coordinator. **Expected Output:** Organize the information under Key Discussion Points, Decisions, Action Items, and Open Points. Use [Not Specified] where necessary. | Structured meeting summary |
| Weekly Project Report | Consolidating weekly updates | C.A.R.E. | **Context:** I have updates from different project activities for the week. **Action:** Consolidate the information into a weekly project report. **Role:** Act as a Project Coordinator. **Expected Output:** Present a concise report covering overall status, completed activities, upcoming activities, risks/issues, and actions. Do not invent missing information. | Weekly project report |
| Task Prioritization | Prioritizing project tasks | C.A.R.E. | **Context:** I have a list of project tasks that need to be organized. **Action:** Prioritize the tasks using the information provided, considering urgency, dependencies, and project impact when explicitly stated. **Role:** Act as a Project Coordinator. **Expected Output:** Provide a prioritized table with Task, Priority, Reason, and Next Step. Clearly distinguish stated information from assumptions. | Prioritized task list |

## Example Outputs

### Example 1 — Meeting Action Items

**Input:**  
A project meeting identified three pending actions: the project team needs to confirm the timeline, the IT team needs to review a pending dependency, and the business team needs to provide missing requirements. No deadlines or priorities were specified.

**Example Output:**

| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|
| Confirm project timeline | Project Team | [Not Specified] | [Not Specified] | Open |
| Review pending dependency | IT Team | [Not Specified] | [Not Specified] | Open |
| Provide missing requirements | Business Team | [Not Specified] | [Not Specified] | Open |

### Example 2 — Executive Project Update

**Input:**  
The project team completed the planned testing activities. One dependency remains pending, and the next project activity is scheduled after the dependency is resolved.

**Example Output:**

**Overall Status:** [Not Specified]

**Completed:**  
- Planned testing activities completed.

**Key Issue:**  
- One dependency remains pending.

**Next Action:**  
- Resolve the pending dependency before proceeding with the next activity.

## Usage Notes

- Use these prompts as reusable starting points for Project Coordinator tasks.
- Review AI-generated outputs before using or sharing them.
- Never provide confidential, private, or sensitive organizational information.
- If information is missing from the source, use [Not Specified] rather than making assumptions.
