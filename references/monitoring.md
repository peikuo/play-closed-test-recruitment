# Scheduled read-only monitoring

## Configuration

Ask the user for an interval before creating a new schedule; preserve an existing explicit interval. Explain responsiveness versus cost with options such as hourly, every two hours or daily. Confirm timezone, relevant channels, model, notification conditions and stopping conditions. Prefer updating an existing authorized schedule over creating a duplicate.

Suggest a supported lower-cost model for incremental reads, including non-GPT providers when the host supports them. Verify actual model/executor access rather than inventing capabilities or prices. Ask for a choice or disclose the existing host default. Never silently substitute a specified model. External models do not automatically inherit authenticated local access.

## Each run

Read a short latest private baseline, not the full chat. Check relevant direct reply branches, authorized incoming notifications/chats and a bounded set of suitable new candidates. Do not turn coordination access into unrelated inbox browsing. If an authorized worker is used, it checks once read-only; the parent does not duplicate browsing. Record checked and unchecked scope, source and time, preserve successful historical facts, and return drafts/actionable findings to the interactive actor. Scheduled checks never send, join, opt in or install.

Respect contact and moderation gates in SKILL.md. A timeout or missing tool means unconfirmed, not no response. Close only temporary tabs created by the check. Follow host-specific response requirements.

## Notifications and stopping

Stay quiet without actionable change. Notify meaningful responses, identity/count progress, new blockers or required human steps; do not repeatedly announce the same limitation. If prolonged inability to verify materially threatens the goal, notify once with a concrete recovery option. Do not escalate cost or authority without authorization.

The user chooses whether monitoring ends at recruitment, sustained participation or another stage. A count threshold is not approval and does not automatically end continuity monitoring. When pausing, deleting or migrating a schedule, first preserve necessary private state outside scheduler-owned directories, since removal may delete their files. Keep runtime state out of public repositories and release packages.
