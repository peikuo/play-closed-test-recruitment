---
name: play-closed-test-recruitment
license: MIT
description: Recruit and coordinate Google Play closed-test participants and one-for-one exchanges. Verify group membership, Play eligibility, real installations and feedback, and maintain evidence records. Use for tester recruitment and coordination, not app development, release configuration or review applications.
---

# Google Play Closed-Test Recruitment

Recruit people who will actually use the app, retain test eligibility and provide honest feedback. Meeting the participant threshold does not guarantee approval. Check current official requirements and the account's Console before interpreting eligibility; historical case numbers are not permanent policy.

## Scope and prerequisites

Support genuine Android closed-test recruitment, reciprocal eligibility coordination, limited device testing, feedback and follow-up, primarily through Google Groups and Reddit. Check community rules and available tools before using other channels. Do not inflate participation, exchange ratings, change release settings or promise approval. This is not comprehensive software quality certification.

This workflow does not supply browser access, authentication, phone control or a scheduler. Read [tools and compatibility](references/tools-and-compatibility.md) before execution. Missing tools limit the corresponding work; identify the user's handoff steps. Recommended environment: GPT-powered Codex, where partial practical validation was performed. Claude is untested and experimental. Ordinary GPT chat does not imply access to execution tools.

## Understand the user's project first

Read only relevant project materials, code, documentation and available app screens. Understand the problem, audience, main features, version and known limitations before inviting anyone. Prepare a short brief: one-sentence value proposition, audience, two or three core test flows, expected outcomes, feedback destination, free features and eligibility conditions. Mark unknown facts and resolve necessary gaps with the user. Do not exaggerate features or start mass outreach from a name and link alone. Invitations and evidence should explain the product and how a tester can help.

## Restore context and authorization

Resume from existing records. Confirm app name, group/opt-in/store URLs, language, free scope, regions, device requirements, feedback destination, target and authorized contact actions. Ask only for missing information that affects action; preserve earlier authorization and individual exceptions such as requiring proof of reciprocal use first.

Searching, drafting and reading can precede external actions. Sending, joining groups, opting in and operating a phone each require applicable user authorization. Recruitment permission does not automatically authorize payment, rating exchanges, account creation, private cloud access, permission changes or release settings. Use supported browser tools and a real authorized device. Without a phone, coordinate eligibility but do not claim installation.

## Scheduled checks and cost

Let the user choose the interval before creating a schedule; retain an existing explicit interval. Offer options such as hourly, every two hours or daily and explain responsiveness versus cost. Suggest Luna or another lower-cost model supported by the host, including non-GPT alternatives where available. Verify actual model and scheduler support; do not invent prices or external-model availability. Ask for a choice or disclose use of the existing platform default when unspecified. Never silently replace a specified model.

Record interval, timezone, model, scope, notification conditions, permissions and stopping conditions. Create or update an authorized existing schedule without duplicates. Read a short local baseline for each incremental check rather than replaying long chats. Escalate complex judgments only as needed and within agreed model/access permissions. Scheduled agents cannot exceed the main task's authority. Stay quiet when nothing meaningful changes; failures are unconfirmed. End according to user instructions and stage-specific stopping conditions. Reaching the recruitment threshold does not automatically end continuous-participation monitoring or establish approval. Notify once if prolonged inability to verify materially threatens the goal, with a concrete recovery step. See [participation audit](references/participation-audit.md).

## Privacy

Online model processing is not offline execution. Files, screenshots and tool outputs passed to a model may be processed by its service; never promise that all data stays on the device. Filter locally where possible and provide only necessary sanitized facts to models or authorized checking agents. Do not send raw member tables, private-chat screenshots, credentials or unrelated project files as bulk context. If necessary material cannot be sanitized, explain the processing scope and let the user handle it or choose a suitable environment.

Do not upload private user data to posts, chats, public repositories, release packages or third-party test apps. This includes member emails, private-message text, account identifiers/tokens, notifications, personal files, real location, private cloud content and personal dashboard pages. Keep sensitive identity matching in the controlled environment and out of shared baselines. Use approved public product information, sanitized observations and synthetic sample data externally.

Inspect the entire screenshot, including status bars, notifications and background accounts. Recapture or redact private content, then inspect the resulting image before sending. Screenshot authorization does not waive privacy checks. If a workflow requires private content, use samples or hand it to the user. Publish only generic instructions and anonymized cases, never runtime records or raw phone/chat evidence.

## Recruitment and coordination

1. Read recent posts in user-selected communities. Prefer suitable language, free basic testing, an explicit reciprocal offer and simple eligibility. Deduplicate by author, not app or thread. A group is an access channel, not proof that an exchange is suitable.
2. Read the full post and our reply branch. Match author, nesting, recipient and time. A developer's installation reply to someone else is not a response to us. Public comments, chats and group threads are separate channels; report only checked scope.
3. Respect community rules and rate limits. Do not mass-message, repeatedly chase silent contacts or bypass moderation, bans or verification. Mark refusals and stop future contact. Send a short authorized one-for-one invitation with our app, group and opt-in links, truthful current status and requested confirmation. Ask for complete links or free conditions when missing. Do not trade five-star ratings or invent usage duration.
4. Match new members to public authors, source posts or explicit responses. Compare necessary member identifiers in memory; store public display names and evidence, not emails. Ask for a display name when uncertain instead of accusing someone of failing to reciprocate.
5. Join ordinary test groups and check opt-in eligibility within authorization. Check whether browser and phone use the same Google account. Store visibility is not membership proof; email lists may provide eligibility independently of groups.
6. When eligible and authorized, install a free app, launch it and try a suitable core flow. If authorization covers launch only, stop there. Hand private data, purchases, agreements and sensitive permissions to the user; prefer sample data. Record installation, launch and functional trials separately. Write a brief report covering app/version, device environment, actions, expected/actual results, issues and untested scope. Send authorized sanitized feedback and give concrete next steps for the user's own testing. AI short trials cannot replace sustained natural human use.
7. Send real screenshots and specific observations. If only launch was tested, say 'installed and launched'. A screenshot is not proof of continuous participation for fourteen days.
8. Verify the published message and actual attachment delivery before recording completion. Drafts, previews, clicks and timeouts do not prove success. After one evidence-based recovery attempt fails, preserve the pending action and explain the blocker. Do not bypass security or verification.
9. Maintain evidence of continuous participation, feedback and actual improvements. A buffer above the threshold is a user-selected target. Do not reuse the original start time to claim continuity after a tester leaves and rejoins. Use current Console eligibility for application readiness; approval requires independent evidence.

## Separate evidence states

| State | Evidence | Does not establish |
|---|---|---|
| Invited / agreed | Published invitation / direct reply to us | Membership or use |
| Group member | Matched member page or member settings | Play opt-in or download |
| Self-reported Play participation | Explicit counterpart statement | Independent verification or use |
| Page/screenshot-confirmed opt-in | Identity/time-matched opt-in page; attribute screenshot source | Exact Console identity or use |
| Console aggregate eligibility | Current exact count or completion indicator | Individual names, installation or use |
| Installed / launched | Package, installed store state or real device screen | Complete functional testing or continuous participation |
| Functional trial | Observed actions/results, screenshot and feedback | Guaranteed approval |

Label counterpart reports, user reports, device/page verification and unknowns. A threshold checkmark supports a lower bound, not an invented exact count. If refreshed evidence contradicts an older page, use the fully loaded current authoritative result and retain the correction.

## Human participation and records

Use [participation audit](references/participation-audit.md) to track device connection/unlock, verification/agreements/permissions, real experience, sustained use, feedback confirmation, fixes, retesting and application handoff. Record owner, evidence, status and confirmation time. Do not mark human tasks complete without observation or user confirmation. Explain specific handoffs; already-authorized routine work needs no repeated approval.

Use [coordination records](references/coordination.md) for contact states, scope, successful checks and next steps. Failed checks must not replace last successful timestamps. An inaccessible channel cannot be reported as having no replies. Synchronize invitations, responses, joins, installs and deliveries promptly so scheduled and interactive work stay aligned.

Notify only meaningful responses, identity/count changes, installation blockers or required user actions. Do not repeatedly report the same tool limitation. If delegation is authorized, a single read-only checking agent can receive a short sanitized baseline; avoid duplicate browsing and leave mutations to the authorized actor. Read [case study](references/case-study.md) for retrospectives; it documents recruitment, not production approval.

## Official reference

[Google Play testing requirements for new personal accounts](https://support.google.com/googleplay/android-developer/answer/14151465). Recheck current applicability, thresholds and Console state during execution. Do not invent an official daily minimum usage duration.
