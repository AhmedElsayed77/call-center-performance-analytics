# Data

The original source files are not included in this repository. The Power BI file contains the imported tables.

| File | Rows | Grain |
|---|---|---|
| Calls data | 1,028 | One row per day, skill (Complain / Inquiry) and language (AR / ENG) |
| CSAT data | 551 | One row per customer survey |

**Calls columns:** Date, Offered Calls, Ans Calls, Aban Calls, Ans Calls After Service Level, Hold Time, ACW Time, Talk Time (seconds), Skill, Language.
**CSAT columns:** Date, Satisfaction (5 levels), Resolved on first call (Yes / No).

**Preparation:** removed a trailing space in a column name, unified "NO" and "No", added within-service-level calls, total handle time, a satisfaction score (1 to 5), and a first-call-resolution score (1 or 0), and built a calendar table.
