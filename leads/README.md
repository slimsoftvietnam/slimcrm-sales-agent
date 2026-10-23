# Lead pipeline

Google Sheets is the human-facing pipeline. A prospect appears in `dang_follow` only after the user approves its numbered follow-up package. Unselected prospects remain in `de_xuat`. SlimCRM CRM is not currently connected.

- Keep one row per company/contact and deduplicate by company domain plus public professional profile URL.
- Add source URLs, last-checked date, separate Company Fit and Person Fit, and a factual reason for each score.
- Use a stable `lead_id`; keep candidate/draft, active follow-up, handoff and opt-out states distinct. Set dates only within the approved continuous follow-up scope and record actual send results.
- Do not close follow-up after a set number of touches. Permanently stop only on explicit opt-out. Pause for Sales handoff when the lead requests a meeting/advice/pricing/terms; resume when Sales returns it. Bounce/wrong contact blocks that route only.
- Keep an append-only activity history in the designated activity store. Never turn a planned touch into a sent event.
- Store only public professional contact details needed for business outreach. Never guess email addresses, phone numbers, buying intent, or CRM seat counts.
- Follow-up packages remain drafts until the manager selects their number after seeing the exact recipient, verified route, channel, sender account, opening message, cadence, and follow-up scope. Future messages may be personalized within the approved scope. The approval applies to that lead only.

## Required lead record

For every candidate, label `Loại đề xuất` as new or re-engagement. A re-engagement candidate needs a fresh sourced signal, no opt-out, no active Sales handoff, and a checked prior activity/approval scope. Do not contact an old record just because it is old. The Google Sheet is the current source of truth; the existing local CSV is only a fallback and may contain no customer records.

## Pipeline stages and Sheet tabs

Use the per-shift checklist in `role/SALES_AGENT_CHECKLIST.md`. Tabs are organized by stage: `de_xuat`, `dang_follow`, `ban_giao_sales`, `tam_dung`, `da_tu_choi`, plus `activity` and `tong_quan`. Use `lead_id` across tabs. Lifecycle: `draft` → `proposed` → `approved_follow_up` → `active_follow_up` (ongoing) → `sales_handoff` or `opted_out`; route issues can be blocked without closing the lead.

`pipeline.csv` remains a local export/working fallback; it is not a second authority when the active Sheet is configured. Do not claim automatic synchronization until implemented and verified.
