# Call Plan — Template

> **Purpose:** Prepares AWS sales team members before external customer meetings. AI agent generates the Call Plan based on sales input, Engagement Plan context, and the current sales stage.
>
> ✅ *After generating, agent always asks sales to review and revise as needed.*

---

## 1. Meeting Details

> *💡 Sales provides: date, customer, attendees. Agent pulls opportunity context from Engagement Plan and fills the rest. Date/time/location may not be confirmed yet — mark as `[待确认]` if unknown. Decision roles may be unknown for first meetings — mark as `[待确认]` and add a discovery question in Section 4 to clarify.*

| Field | Value |
|---|---|
| **Date & Time** | `{date}` `{time}` `{timezone}` |
| **Duration** | `{duration}` |
| **Format** | `{In-person / Virtual / Hybrid}` |
| **Location / Link** | `{location or meeting link}` |
| **Opportunity Name** | `{auto from Engagement Plan}` |
| **Current Sales Stage** | `{auto from Engagement Plan}` |

### Customer Attendees

| Name | Title | Role in Decision |
|---|---|---|
| `{name}` | `{title}` | `{EB / Champion / Decision Maker / Influencer / Evaluator / End User}` |
| `{name}` | `{title}` | |
| `{name}` | `{title}` | |

### AWS Attendees

| Name | Title | Role in Meeting |
|---|---|---|
| `{name}` | `{title}` | `{Lead / Support / SME / Executive Sponsor}` |

---

## 2. Target Meeting Outcomes

> *💡 Agent drafts based on current sales stage and Engagement Plan roadmap. Sales reviews and adjusts.*
>
> *The user's stated meeting objective takes priority. Agent then cross-references the current stage's **exit criteria** (from meddpicc-stage-mapping.md) and suggests additional outcomes that align with advancing to the next stage.*

| # | Customer Perspective | Our Perspective |
|---|---|---|
| 1 | `{what the customer hopes to achieve}` | `{what we need to achieve}` |
| 2 | `{outcome}` | `{outcome}` |

**Target Stage Progression:** ( `{current stage}` ) → ( `{target stage}` )

---

## 3. Success Criteria

> *💡 Agent drafts dual-perspective criteria. These will be auto-pulled into the PMR Outcome Assessment after the meeting.*
>
> *Criteria must be **observable and assessable** — something you can clearly judge as achieved or not after the meeting. Avoid vague or subjective criteria.*
>
> *If sales provides criteria that are too vague, offer a concrete example to guide them:*
> - ❌ Too vague: "Customer is interested"
> - ✅ Assessable: "Customer agrees to schedule a follow-up technical deep-dive within 2 weeks"
> - ❌ Too vague: "Good conversation"
> - ✅ Assessable: "Customer shares their current vendor contract timeline and budget cycle"

| # | Customer Would Consider It Successful If… | We Would Consider It Successful If… |
|---|---|---|
| 1 | `{criterion}` | `{criterion}` |
| 2 | `{criterion}` | `{criterion}` |
| 3 | `{criterion}` | `{criterion}` |

---

## 4. Information Exchange

> *💡 Agent auto-selects MEDDPICC elements based on current sales stage, plus other deal-specific needs from Engagement Plan gaps. Questions and delivery items must be tailored to the specific meeting objectives — not generic.*
>
> *For every Call Plan, agent must prepare **industry-relevant use cases** and **customer references** matched to the customer's industry. If no exact match exists, use the closest adjacent industry and note the gap.*

### Information to Gather

| # | Question | Category | Target Attendee | Purpose |
|---|---|---|---|---|
| 1 | `{question}` | `{MEDDPICC element / Technical / Org / Budget / Timeline / Other}` | `{name/role}` | `{How this serves the meeting objectives}` |
| 2 | `{question}` | | `{name/role}` | `{purpose}` |
| 3 | `{question}` | | `{name/role}` | `{purpose}` |

### Information to Deliver

| # | What to Share | Format | Purpose |
|---|---|---|---|
| 1 | `{e.g., Industry insight on cloud adoption trends}` | `{Data point / Slide / Case study}` | `{e.g., Build credibility and establish relevance}` |
| 2 | `{e.g., Similar customer success story}` | `{Case study / Reference call}` | `{e.g., Address specific objection about migration risk}` |
| 3 | `{e.g., Preliminary architecture overview}` | `{Whiteboard / Diagram}` | `{e.g., Validate technical hypothesis from Section 2 objectives}` |

---

## 5. Potential Objections & Responses

> *💡 Agent drafts based on CXO Persona profiles (for executive-level attendees), competitive context from EP, and current sales stage. Sales reviews and adds.*

| # | Anticipated Objection | Our Response |
|---|---|---|
| 1 | `{objection}` | `{response}` |
| 2 | `{objection}` | `{response}` |
| 3 | `{objection}` | `{response}` |

---

## 6. Meeting Agenda

> *💡 Agent drafts agenda to achieve the Target Outcomes and Success Criteria. Sales reviews and adjusts.*
>
> *If the user provided specific start/end times, use actual clock times (e.g., 14:00–14:05). If no specific times were given, use relative time offsets (e.g., 00:00–00:05) or duration (e.g., 5 min).*

| Time | Topic | Owner | Purpose |
|---|---|---|---|
| `{00:00–00:05}` | Welcome & introductions | `{name}` | Set the tone |
| `{00:05–00:15}` | `{topic}` | `{name}` | `{purpose}` |
| `{00:15–00:35}` | `{topic}` | `{name}` | `{purpose}` |
| `{00:35–00:50}` | `{topic}` | `{name}` | `{purpose}` |
| `{00:50–00:55}` | Recap & alignment on next steps | `{name}` | Confirm outcomes |
| `{00:55–01:00}` | Close | `{name}` | — |

---

## 7. Potential Next Steps

> *💡 Agent drafts 2-3 concrete next steps to propose to the customer at the end of the meeting. These should be aligned with the Target Outcomes (Section 2) and the current stage's exit criteria. Each next step should be specific, actionable, and include a suggested timeline. Sales reviews and adjusts.*

| # | Proposed Next Step | Timeline | Owner | Purpose |
|---|---|---|---|---|
| 1 | `{e.g., Schedule a technical deep-dive with your CTO and our SA}` | `{e.g., Within 2 weeks}` | `{AWS / Customer / Joint}` | `{e.g., Validate technical fit and move toward POC}` |
| 2 | `{e.g., Share a tailored business case with ROI analysis}` | `{e.g., Within 1 week}` | `{AWS}` | `{e.g., Support internal budget discussion}` |
| 3 | `{e.g., Arrange a reference call with a similar customer}` | `{e.g., Within 2 weeks}` | `{AWS}` | `{e.g., Build confidence through peer validation}` |

---

*Call Plan Template | Version: 1.0*
