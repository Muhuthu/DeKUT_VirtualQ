# Design Iteration Log — Virtual Queue Management App

*Each iteration below is a direct response to a specific finding from `usability-testing/usability-testing-results.md`. This is the before/after evidence required by the assignment brief.*

*Companion files: before/after screenshots should live alongside this file once exported from Figma; `visual-walkthrough.md` provides a written visual description of each change, useful anywhere a screenshot can't be embedded.*

---

## Iteration 1 — Notification Preferences Discoverability

**Source finding:** Major issue — 2/5 participants (P01, P05) struggled to locate Notification Preferences; P02/P03 hesitated. Participants expected it to be reachable directly from the active ticket screen, not buried in profile navigation only.

**Before:** Notification Preferences accessible only via Profile → Notification Preferences — no shortcut from the active queue/ticket screen.

**Change made:** Added a direct shortcut/icon to Notification Preferences from the active Digital Ticket / Live Queue Status screen, in addition to keeping the existing Profile → Notification Preferences path. Notification channel labels (Push / SMS / In-app) were made visually distinct.

**Expected improvement:** Fewer navigation steps and less searching for users who want to adjust notifications while actively in a queue — directly targets the most common point of confusion observed in testing.

**Verification plan:** Re-test Task 6 ("Set your notifications so you get an SMS when your turn is close") with new participants in a future round; target full completion without hesitation.

**Visual description:** See `visual-walkthrough.md`, "How the Iterations Changed What's Visible," point 1.

---

## Iteration 2 — Leave Queue Visibility

**Source finding:** Major issue — P05 did not notice the Leave Queue option at all; P01 hesitated before finding it. Participants expected it positioned closer to the queue status information itself.

**Before:** Leave Queue action present but not visually prominent on the active ticket/queue screen.

**Change made:** Increased visual prominence of the Leave Queue action on the active queue screen (e.g. clearer placement/contrast near the queue position display), while retaining the existing confirmation step — testing showed the confirmation itself was seen as useful, not a problem, so it was not removed or weakened.

**Expected improvement:** Users can find and use Leave Queue without hesitation, while the confirmation step continues to prevent accidental cancellations (balances NFR-2, error prevention, against discoverability).

**Verification plan:** Re-test Task 5 ("Leave the queue") with new participants; target zero missed/overlooked instances.

**Visual description:** See `visual-walkthrough.md`, "How the Iterations Changed What's Visible," point 2.

---

## Iteration 3 — QR Code Explanation

**Source finding:** Minor issue — 3/5 participants (P01, P02, P05) could identify the QR code but were unsure of its purpose or who should scan it.

**Before:** Digital Ticket screen displayed the QR code with no accompanying explanation of its use.

**Change made:** Added a short explanatory label beneath/beside the QR code: *"Show this QR code at the service counter."*

**Expected improvement:** Users understand on first exposure that the QR code is for staff verification at the counter, without needing to guess or ask.

**Verification plan:** Re-test Task 3 (unprompted "what do you think this screen is telling you?") with new participants; target correct, unprompted identification of the QR code's purpose across all participants.

**Visual description:** See `visual-walkthrough.md`, "How the Iterations Changed What's Visible," point 3.

---

## Summary

| Iteration | Issue Severity | Status |
|---|---|---|
| 1. Notification Preferences shortcut | Major | Implemented |
| 2. Leave Queue visual prominence | Major | Implemented |
| 3. QR code explanatory label | Minor | Implemented |

All Major and Minor issues identified in usability testing were addressed. No Critical issues were found, so no Critical-priority iteration was required. This iteration cycle — prototype → test → identify problems → refine → (re-test) — reflects the assignment's required iterative design process, grounded in real participant evidence rather than internal assumptions.