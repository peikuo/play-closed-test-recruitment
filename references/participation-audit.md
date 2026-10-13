# Human participation, test reports and records

## Participation audit

Preserve project authorization and individual exceptions. Track:

| Item | Owner and evidence | Status |
|---|---|---|
| Product brief | AI summarizes; user confirms facts and goals | Pending/confirmation time |
| Recruitment and reciprocity | User selects channels, budget, messages and phone scope | Scope and authorization source |
| Monitoring | User chooses interval/timezone/model; host supports it | Configured/pending/paused/ended |
| Device and sensitive steps | User connects/unlocks, handles verification/agreements/permissions | Waiting/completion evidence |
| Short trial | AI or user performs observed actions | Untested/partial/tested scope |
| Sustained human use | User naturally uses app across days | User report/verified evidence/unknown |
| Feedback and improvements | User/developer confirms defect, fix and retest | Pending feedback/fix/retested |
| Production handoff | AI assembles facts; submission needs separate explicit authorization; platform decides | Ineligible/ready/handed off; later states need evidence |

Do not auto-complete human tasks or infer use from successful scheduler runs. Do not invent official daily durations or guarantee approval dates. Remind only concrete actionable next steps, without repeated polling prompts.

## Brief report after installation

Include app/version/time, necessary non-sensitive device/Android specifications, actual install/launch/core-flow actions, expected and observed results, minimal issue reproduction, untested features and language/eligibility/network constraints. Record real sanitized screenshot paths and actual attachment delivery. Tell the user which feature or subjective experience to test next and when a retest is needed.

Example: installed and entered the board; choosing a color changed highlighting; no full game completed. Ask the user to finish a game and assess clarity of rules. Do not rewrite this as all functions working or fourteen days of testing.

## Local state and events

Use one project-local state entrypoint shared by interactive and scheduled work. Log important changes with time, actor (AI/user/counterpart/platform), action, source, outcome, authorization basis, privacy check and next step. Store sanitized summaries and public links, not sensitive originals.

Keep last successful verification separate from latest attempt. Failures do not erase facts. Use independent stage states, not one done flag. Retain corrections for mistaken attribution. Counts carry source, owner inclusion, exact/lower-bound interpretation and timestamp. Deduplicate public authors and retain cross-channel identity confidence.

Scheduling records contain interval, timezone, model, allowed channels/actions, meaningful notification conditions, human tasks and stopping criteria. Low-cost models may perform authorized read-only incremental checks; complex judgments belong to an appropriately capable authorized actor. External models do not automatically have local authenticated access.

## Concurrency and duplicate actions

Use one writer or host locks/transactions. Reread latest state before writes, retain version/update time, merge verified events on conflict and save via atomic replacement. Never overwrite new actions with an old snapshot. Before sending/joining, check completed and uncertain pending actions. After a timeout, verify publication before considering resend. Without concurrency protection, execute sequentially and avoid overlapping checks or duplicate schedules.
