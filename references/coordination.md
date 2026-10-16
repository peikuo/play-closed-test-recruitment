# Coordination records and message examples

See [participation audit](participation-audit.md) for human ownership and safe state updates, and [round summaries](progress-summary.md) for the tables generated after each round.

## Minimal contact record

Keep one entry per author, not per post. Let the user select a private local records directory; avoid automatic cloud sync and public repositories. Save links and sanitized summaries, not passwords or browser sessions. At task end offer retention/cleanup options and follow host deletion permissions.

Record public author ID, app, source/invitation permalinks, group/opt-in links, free/language/eligibility conditions and individual restrictions, plus:

- Invitation and direct-response verification times.
- Counterpart group membership, self-reported opt-in/install/use and each evidence level.
- Our group join, opt-in, installation, launch and functional trial separately.
- Local sanitized screenshot path, feedback link/time and attachment delivery result.
- Open issues, next step, last successful verification and latest attempted check/scope.

Missing evidence means unknown, not false. Do not store private-message text, member emails, account tokens or full chat screenshots. Aggregates retain source, timestamp, whether the owner is included and whether the value is a lower bound. Merge cross-channel identities only with evidence.

## Platform moderation and contact audit

Before a new contact on any website or community, record the platform/community/thread permission basis, author deduplication result, proposed message and destination, and the user's approval. An author recruiting testers does not automatically invite private messages or unrelated promotion. Draft only a relevant reply that fits the actual post; do not mass-distribute the invitation example below. Monitor existing replies read-only in scheduled runs and return new outreach drafts for human review.

Keep a sanitized moderation state: affected channel, notice time, stated reason, sending paused, whether an expiry is actually verified, and next review step. Do not save private moderation letters or account-specific appeal URLs in shared/public resources. A notice listing possible behaviors does not establish which particular message caused enforcement; separate confirmed restrictions from suspected causes. User anecdotes and self-imposed message caps are not official safe limits. Check the current rules of each platform and community when acting. For Reddit specifically, consult [Reddit Rules](https://redditinc.com/policies/reddit-rules) and [Spam guidance](https://support.reddithelp.com/hc/en-us/articles/360043504051-Spam); these are platform-specific references, not universal rules for other sites. Stop affected-channel recruitment sends on warnings, removals, limits or bans; never replace an account or channel to bypass the restriction. Resuming requires review with the user, confirmed permitted access and compliant conduct, not merely the expected passage of time.

## Adaptable messages

Invitation:
> Hi [name], would you like a free one-for-one test exchange: [their app] for [our app]? [Truthful current status]. Group: [group]. Test: [opt-in]. Please let me know once you join and opt in. Thanks, [sender].

Feedback:
> I installed [app/version] and opened [screen] on [device]. I tried [action]; [observed result]. I haven't tested [remaining feature]. Here is a real screenshot. [For bugs: steps, expected result, actual result].

Broken link:
> [Exact page error] appears after [step]. Could you send the full group and opt-in links and confirm the supported region/device? I haven't been able to install it yet.

Unmatched identity:
> Could you confirm whether you joined [our app] and opted in? I cannot yet match your membership. Your Google Groups display name is enough; no email is needed publicly.

Adapt to actual facts. Do not promise unconfirmed daily frequency, dates or a complete fourteen-day service.

## Common failures

- App unavailable: check account alignment, group eligibility, opt-in, region and release availability; record exact error. Do not change our release settings without authorization.
- Incompatible device: verify real model, Android and architecture. A 64-bit release may not work on a 32-bit phone. Failure to install is not completed reciprocity.
- Truncated URL: request the full URL rather than guessing a group name.
- Filtered post: verify once, then use an authorized appropriate channel; no repeated mass posting or moderation bypass.
- Missed chat: public comments do not cover private messages. Check the specific authorized conversation; exclude replies to others.
- Upload failure: require a visible sent message and attachment. Preserve the local image and ask for an appropriate alternative destination; preview/timeouts do not prove delivery.
- Count fluctuation: threshold completion is not continuous participation. Do not invent countdowns; retain a buffer and evidence of feedback/use.
- Monitoring cost: check relevant changes, rotate scope when appropriate and resume from a short baseline. No change means no notification.
