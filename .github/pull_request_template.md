## Summary

<!--
Write 1 to 3 short sentences. Explain outcome and who it helps.

Example:
This PR shows clearer card error messages on checkout.
It helps customers understand what went wrong and what to try next.
-->

## Why

<!--
Explain why this change exists. Link issue or ticket if known.

Example:
Support saw customers retry payments because the old message only said "Payment failed".
This change shows the payment provider reason when it is safe to show.
-->

## What changed

<!--
Use 3 to 6 bullets. Group by behavior or reviewer-relevant change. Do not list every file.

Example:
- Shows an expired card message when the provider returns that reason.
- Keeps a generic message for unknown payment errors.
- Adds log context for failed payment attempts.
-->

-

## How to test

<!--
List checks you actually ran. Include commands, manual steps, API calls, or review evidence.
Prefer at least one project-specific check.
If you could not test, replace this section with the reason and say what would be needed to test it.

Example:
- `npm test -- checkout-errors`
- `npm run lint`
- Opened checkout with an expired test card. Expected error appeared.
-->

- Replace this line with a command or manual check.

## QA / Smoke Test

<!--
Optional. Use for user flows, UI, API changes, webhooks, jobs, deploy config, or data paths.
Each bullet should include one action and one expected result.

Example:
- Start checkout with an expired test card. Expected: the error says the card is expired.
- Start checkout with a declined test card. Expected: the error says the card was declined.
-->

-

## Screenshots / Recordings

<!--
Optional. Add links only. Do not commit screenshots or recordings.

Example:
- Before: https://example.com/before.png
- After: https://example.com/after.png
-->

## Risk

<!--
Pick one level. Add concrete reason.
Mention user-visible behavior, data writes, migrations, auth, billing, permissions, deploy config, rollback, or test evidence when relevant.

Example:
🟡 Medium

Reason: This changes customer-facing checkout text. No data writes, auth, billing logic, or migrations changed. Rollback is one commit revert.
-->

🟢 Low / 🟡 Medium / 🔴 High

Reason:

## Notes for reviewers

<!--
Optional. Include review focus, known limits, or follow-up work.

Example:
Please focus on whether the messages are clear and safe to show to customers.
-->

## Related

<!--
Optional. Include only known issue or ticket links.

Example:
- Fixes https://github.com/example/repo/issues/123
-->
