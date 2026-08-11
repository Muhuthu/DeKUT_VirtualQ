# Usability Testing Plan — Virtual Queue Management App

## Purpose

To evaluate whether real users can successfully complete core tasks in the current Figma prototype, and to surface specific usability problems that can be fixed before final submission. This directly satisfies the assignment's usability-testing requirement (≥5 users) and feeds the iteration phase.

## Participants

- Minimum 5 students, ideally not the same 5 who completed the earlier research questionnaire (fresh eyes reduce bias), though overlap is acceptable if recruiting is difficult.
- Aim for a mix of first-time and experienced service-point users, matching the two personas.

## Method

- **Format:** Moderated walkthrough. One team member guides the participant through the Figma prototype (using Figma's Present/Prototype mode on a phone or laptop), reads out tasks one at a time, and observes/records without helping unless the participant is fully stuck.
- **Recording:** Note completion (yes/no/partial), time taken (rough estimate is fine), number of wrong taps/backtracks, and any comments the participant makes out loud.
- **Think-aloud:** Ask participants to narrate what they're thinking/expecting as they go — this surfaces *why* something is confusing, not just *that* it is.

## Tasks

Each task maps to a functional requirement so failures can be traced directly back to `docs/requirements.md`.

| # | Task given to participant | Related requirement | Success criteria |
|---|---|---|---|
| 1 | "You need to submit a form at the Registry office. Find out if it's currently busy before deciding to go." | FR-2.2, FR-2.3 | Participant reaches Service Point Details and correctly reads queue status without help |
| 2 | "Join the queue for the Registry office." | FR-3.1 | Participant completes Join Queue flow and reaches the Digital Ticket screen |
| 3 | "Without me explaining it — what do you think this screen (Digital Ticket) is telling you?" | FR-3.2, NFR-6 | Participant correctly identifies queue number, QR code purpose, and estimated wait unprompted |
| 4 | "Check how close you are to being served." | FR-3.3, FR-3.4 | Participant finds and correctly interprets Live Queue Status without confusion |
| 5 | "You've changed your mind and no longer want to wait. Leave the queue." | FR-3.5, NFR-2 | Participant finds Leave Queue, sees and understands the confirmation step |
| 6 | "Set your notifications so you get an SMS when your turn is close." | FR-4.3 | Participant reaches Notification Preferences and toggles the correct setting |
| 7 | "Look at your past visits to any service point." | FR-5.1 | Participant finds Ticket History and can describe what's shown |
| 8 | "You had a good experience today — leave a rating." | FR-6.1 | Participant finds and completes the rating/feedback flow |

*(Optional, if testing with someone in a staff-adjacent role, e.g. a student leader or willing participant): staff-side tasks — call next customer, verify a ticket, mark service complete — mapped to FR-7.x.*

## Recording Template

| Participant # | Task # | Completed? (Y/N/Partial) | Time / attempts | Wrong turns or hesitation | Notable comment (think-aloud) |
|---|---|---|---|---|---|
| | | | | | |

*(Duplicate this table per participant, or keep one long table — whichever is easier to manage across your 5 participants × 8 tasks.)*

## Post-Task Questions (ask after all tasks)

1. Which task felt hardest, and why?
2. Was there any point where you weren't sure what to do next?
3. Did anything happen that you didn't expect?
4. On a scale of 1–5, how confident would you feel using this for real?

## Severity Rating (for logging issues afterward)

Use this scale when writing up findings, so iteration priorities are clear:

- **Critical** — task could not be completed at all
- **Major** — task completed but only with significant confusion/backtracking
- **Minor** — task completed smoothly but participant commented on friction or confusion
- **Cosmetic** — no functional impact, purely a visual/wording suggestion

## Next Step

Once testing is complete, findings go into `usability-testing/findings.md` (severity-rated issue list), which feeds directly into `iterations/` — where you'll document the specific before/after design change made in response to each Major or Critical issue.