# Usability Testing Plan — Virtual Queue Management App

## Purpose

The usability testing was conducted to evaluate whether students could successfully complete the core tasks in the Virtual Queue Management App prototype. The testing focused on identifying usability problems, areas of confusion, and opportunities for improvement before the final implementation.

The sessions also helped determine whether the interface supported the main functional requirements defined for the system.

## Participants

Five university students participated in the usability testing. The participants were selected to provide a mixture of students with different levels of familiarity with university service points and different levels of confidence when using digital applications.

| Participant | Age | Year of Study | Technology Comfort | Service Point Experience |
|-------------|-----|---------------|--------------------|--------------------------|
| P01 | 19 | First Year | Moderate | Limited |
| P02 | 20 | Second Year | High | Moderate |
| P03 | 21 | Third Year | High | High |
| P04 | 22 | Final Year | Very High | High |
| P05 | 18 | First Year | Moderate | Limited |

### Participant Profiles

**P01 — First-Year Student**

A first-year student who is comfortable using common mobile applications but has limited experience with university administrative processes. The participant was particularly interested in knowing queue status and service requirements before visiting an office.

**P02 — Second-Year Student**

A regular smartphone user with moderate experience using university service points. The participant was comfortable navigating the prototype but initially required some time to understand the purpose of the digital ticket.

**P03 — Third-Year Student**

An experienced university service-point user who frequently uses digital applications. The participant navigated most tasks quickly and provided feedback on the visibility of queue information and notifications.

**P04 — Final-Year Student**

A highly confident technology user who has used several university administrative services. The participant focused strongly on efficiency and expected the application to provide quick access to queue status and history.

**P05 — First-Year Student**

A relatively new university student with moderate technology experience. The participant was able to complete most tasks but experienced some hesitation when navigating to notification preferences and leaving a queue.

## Method

- **Format:** Moderated usability walkthrough using the Figma prototype in Present/Prototype mode.
- **Testing environment:** Participants interacted with the prototype using a laptop or mobile device.
- **Testing approach:** Tasks were presented one at a time without explaining the expected navigation path.
- **Observation:** The facilitator recorded task completion, approximate time, wrong taps, backtracking, hesitation, and participant comments.
- **Think-aloud:** Participants were encouraged to explain what they expected to happen while completing each task.
- **Assistance:** Participants were not guided unless they became completely stuck. Any assistance provided was recorded as part of the observation.

## Tasks

Each task mapped to a functional requirement so that usability problems could be traced back to specific system functionality.

| # | Task given to participant | Related Requirement | Success Criteria |
|---|---------------------------|----------------------|------------------|
| 1 | "You need to submit a form at the Registry office. Find out if it's currently busy before deciding to go." | FR-2.2, FR-2.3 | Participant reaches Service Point Details and correctly reads queue status without help |
| 2 | "Join the queue for the Registry office." | FR-3.1 | Participant completes Join Queue flow and reaches the Digital Ticket screen |
| 3 | "Without me explaining it — what do you think this screen (Digital Ticket) is telling you?" | FR-3.2, NFR-6 | Participant correctly identifies queue number, QR code purpose, and estimated wait |
| 4 | "Check how close you are to being served." | FR-3.3, FR-3.4 | Participant finds and correctly interprets Live Queue Status |
| 5 | "You've changed your mind and no longer want to wait. Leave the queue." | FR-3.5, NFR-2 | Participant finds Leave Queue and understands the confirmation step |
| 6 | "Set your notifications so you get an SMS when your turn is close." | FR-4.3 | Participant reaches Notification Preferences and selects the correct setting |
| 7 | "Look at your past visits to any service point." | FR-5.1 | Participant finds Ticket History and correctly describes the information shown |
| 8 | "You had a good experience today — leave a rating." | FR-6.1 | Participant finds and completes the rating/feedback flow |

---

# Usability Test Results

## Participant 01

| Task | Completed? | Approx. Time | Attempts / Wrong Turns | Observation |
|------|------------|--------------|-------------------------|-------------|
| 1 | Yes | 42 sec | 1 | Initially looked at the home screen before finding Service Points |
| 2 | Yes | 35 sec | 0 | Completed the queue joining process without assistance |
| 3 | Partial | 55 sec | 2 | Identified queue number and wait time but was unsure about the QR code |
| 4 | Yes | 30 sec | 1 | Found Live Queue Status after briefly checking the ticket screen |
| 5 | Yes | 48 sec | 1 | Found Leave Queue but hesitated before confirming |
| 6 | Partial | 1 min 10 sec | 3 | Took time to locate notification settings and initially selected the wrong notification option |
| 7 | Yes | 35 sec | 1 | Found Ticket History through the profile area |
| 8 | Yes | 28 sec | 0 | Completed the rating flow easily |

### Notable Comments

> "I can see my position, but I'm not immediately sure what the QR code is for."

> "I expected the notifications to be somewhere on the ticket screen."

---

## Participant 02

| Task | Completed? | Approx. Time | Attempts / Wrong Turns | Observation |
|------|------------|--------------|-------------------------|-------------|
| 1 | Yes | 30 sec | 0 | Quickly located the service point and queue information |
| 2 | Yes | 28 sec | 0 | Completed the process smoothly |
| 3 | Yes | 42 sec | 1 | Correctly identified queue number and estimated waiting time; understood QR code after examining it |
| 4 | Yes | 25 sec | 0 | Quickly located Live Queue Status |
| 5 | Yes | 35 sec | 0 | Completed the cancellation process confidently |
| 6 | Yes | 45 sec | 1 | Found notification settings after checking the profile menu |
| 7 | Yes | 25 sec | 0 | Found history quickly |
| 8 | Yes | 25 sec | 0 | Completed rating without difficulty |

### Notable Comments

> "The ticket is clear, but I would probably want the QR code explanation to be visible."

---

## Participant 03

| Task | Completed? | Approx. Time | Attempts / Wrong Turns | Observation |
|------|------------|--------------|-------------------------|-------------|
| 1 | Yes | 25 sec | 0 | Quickly identified the queue status |
| 2 | Yes | 24 sec | 0 | Completed queue joining without hesitation |
| 3 | Yes | 32 sec | 0 | Correctly interpreted all information on the ticket |
| 4 | Yes | 20 sec | 0 | Found Live Queue Status immediately |
| 5 | Yes | 31 sec | 0 | Completed the task without difficulty |
| 6 | Yes | 38 sec | 0 | Located notification preferences quickly |
| 7 | Yes | 22 sec | 0 | Easily located Ticket History |
| 8 | Yes | 20 sec | 0 | Completed rating flow immediately |

### Notable Comments

> "The queue number and estimated time are the things I'd want to see first."

> "The flow is straightforward once you know where everything is."

---

## Participant 04

| Task | Completed? | Approx. Time | Attempts / Wrong Turns | Observation |
|------|------------|--------------|-------------------------|-------------|
| 1 | Yes | 23 sec | 0 | Quickly found service point information |
| 2 | Yes | 20 sec | 0 | Completed the flow quickly |
| 3 | Yes | 30 sec | 0 | Correctly interpreted all ticket information |
| 4 | Yes | 18 sec | 0 | Found queue status immediately |
| 5 | Yes | 29 sec | 0 | Completed the cancellation process |
| 6 | Yes | 31 sec | 0 | Quickly located notification preferences |
| 7 | Yes | 20 sec | 0 | Found Ticket History immediately |
| 8 | Yes | 19 sec | 0 | Completed the feedback flow |

### Notable Comments

> "I like being able to check the queue before travelling to the office."

> "The history is useful because I can see previous visits."

---

## Participant 05

| Task | Completed? | Approx. Time | Attempts / Wrong Turns | Observation |
|------|------------|--------------|-------------------------|-------------|
| 1 | Yes | 45 sec | 1 | Needed time to understand where service points were listed |
| 2 | Yes | 40 sec | 1 | Initially selected the wrong service point before correcting it |
| 3 | Yes | 48 sec | 1 | Correctly identified queue number and estimated time but asked about QR code |
| 4 | Yes | 38 sec | 1 | Found Live Queue Status after checking the digital ticket |
| 5 | Partial | 1 min 05 sec | 3 | Initially did not notice the Leave Queue option |
| 6 | Partial | 1 min 15 sec | 3 | Had difficulty finding notification preferences |
| 7 | Yes | 42 sec | 1 | Found Ticket History after exploring the profile section |
| 8 | Yes | 30 sec | 0 | Completed the rating process successfully |

### Notable Comments

> "I wasn't sure where to go when I wanted to leave the queue."

> "I think notifications should be easier to find."

---

# Overall Task Performance

The results showed that most participants were able to complete the primary queue-management tasks successfully. The main usability difficulties were concentrated around **notification settings, understanding the QR code, and locating the Leave Queue action**.

| Task | Successful Participants | Main Observation |
|------|-------------------------|------------------|
| 1. Check Queue Status | 5/5 | Generally easy to complete |
| 2. Join Queue | 5/5 | Clear and straightforward |
| 3. Understand Digital Ticket | 4/5 fully, 1/5 partial | QR code purpose was not immediately clear to some participants |
| 4. Check Queue Progress | 5/5 | Easy to locate and understand |
| 5. Leave Queue | 4/5 fully, 1/5 partial | Leave Queue action could be more visible |
| 6. Configure Notifications | 3/5 fully, 2/5 partial | Most significant navigation issue |
| 7. View Ticket History | 5/5 | Generally easy to locate |
| 8. Leave Rating | 5/5 | Simple and understandable |

## Key Findings

### 1. Queue Status Was Easy to Understand

All five participants successfully found the current queue status. Participants generally understood the purpose of the queue information and considered it useful when deciding whether to visit a service point.

**Result:** No major usability problem identified.

**Severity:** Cosmetic / No issue.

---

### 2. Joining a Queue Was Straightforward

All participants successfully joined the Registry queue. The process required little assistance and participants generally understood what would happen after selecting the Join Queue action.

**Result:** The queue joining flow was considered effective.

**Severity:** No issue.

---

### 3. QR Code Purpose Was Not Immediately Clear

Several participants understood that the QR code was associated with their digital ticket but were unsure about what they were expected to do with it.

**Observed problem:**

- Participants could identify the QR code.
- Some were unsure whether it should be scanned by staff or by themselves.
- Participants suggested adding a short explanation.

**Severity:** Minor

**Suggested improvement:**

Add a short label such as:

> "Show this QR code at the service counter."

---

### 4. Live Queue Status Was Easy to Find

All participants successfully located the Live Queue Status feature. The queue position and progress information were generally understood.

**Result:** No significant usability problem identified.

**Severity:** No issue.

---

### 5. Leave Queue Action Needs Better Visibility

One participant had significant difficulty finding the Leave Queue option, while others hesitated before confirming that they wanted to leave.

**Observed problem:**

- The action was not immediately visible to all participants.
- Participants expected the option to be located closer to the queue status information.
- The confirmation step was considered useful because leaving the queue is an important action.

**Severity:** Major

**Suggested improvement:**

Make the Leave Queue action more visible on the active ticket/queue screen while retaining a confirmation dialog to prevent accidental cancellation.

---

### 6. Notification Preferences Were the Main Usability Issue

Two participants experienced difficulty locating Notification Preferences. Participants expected notification settings to be accessible either from the active ticket or directly from a prominent settings area.

**Observed problem:**

- Participants searched multiple areas before finding notification settings.
- Some expected notification controls to appear on the queue ticket.
- The SMS option was not immediately distinguishable to every participant.

**Severity:** Major

**Suggested improvement:**

- Make Notification Preferences easier to access.
- Provide a clear "Notifications" entry in the profile/settings area.
- Clearly label notification channels such as SMS and push notifications.
- Consider providing a shortcut from the active queue screen.

---

### 7. Ticket History Was Understandable

All participants were able to locate their previous visits. Participants understood that the history contained information about previous queue interactions.

**Result:** The feature was considered easy to understand.

**Severity:** No issue.

---

### 8. Rating and Feedback Flow Was Easy to Complete

All participants successfully completed the rating task. The flow required little explanation and did not produce significant confusion.

**Result:** No major usability issue identified.

**Severity:** No issue.

---

# Post-Task Questions

## Question 1: Which task felt hardest, and why?

| Participant | Response |
|-------------|----------|
| P01 | "Finding the notification settings took me the longest." |
| P02 | "The QR code wasn't immediately obvious to me." |
| P03 | "Nothing was particularly difficult, but notifications could be easier to find." |
| P04 | "The notification settings were less obvious than the other features." |
| P05 | "Leaving the queue and finding notifications were the hardest." |

## Question 2: Was there any point where you weren't sure what to do next?

The most common points of uncertainty occurred when participants were trying to locate notification preferences and when interpreting the purpose of the QR code.

## Question 3: Did anything happen that you didn't expect?

Participants generally reported that the prototype behaved as expected. The main unexpected element was uncertainty about what the QR code would be used for at the service counter.

## Question 4: On a scale of 1–5, how confident would you feel using this for real?

| Participant | Confidence Rating |
|-------------|-------------------|
| P01 | 4/5 |
| P02 | 4/5 |
| P03 | 5/5 |
| P04 | 5/5 |
| P05 | 4/5 |

**Average confidence rating: 4.4/5**

Overall, participants demonstrated a high level of confidence in using the proposed system.

---

# Usability Issues and Severity

| Issue | Participants Affected | Severity | Proposed Action |
|-------|-----------------------|----------|-----------------|
| Notification settings difficult to locate | P01, P05 and some hesitation from P02/P03 | Major | Improve navigation and provide clearer access to notification settings |
| Leave Queue action not immediately visible | P05, with minor hesitation from P01 | Major | Make Leave Queue more prominent on the active queue screen |
| QR code purpose unclear | P01, P02, P05 | Minor | Add explanatory text beside the QR code |
| Service point discovery required minor exploration | P01, P05 | Minor | Improve service point navigation and visual hierarchy |

## Severity Rating

The following scale was used when evaluating the identified usability issues:

- **Critical** — task could not be completed at all
- **Major** — task completed but only with significant confusion or backtracking
- **Minor** — task completed but participants experienced limited friction or confusion
- **Cosmetic** — no functional impact; primarily a visual or wording suggestion

No **Critical** usability issues were identified during the testing sessions.

---

# Design Iterations Based on Testing

The usability testing results were used to identify areas that required refinement before implementation.

### Iteration 1 — Notification Preferences

**Problem identified:**  
Participants had difficulty locating notification settings.

**Change:**  
The notification settings were made more prominent and the navigation path was simplified.

**Expected improvement:**  
Users should be able to locate and configure notification preferences with fewer navigation steps.

---

### Iteration 2 — Leave Queue

**Problem identified:**  
The Leave Queue action was not sufficiently visible to all participants.

**Change:**  
The Leave Queue action was given greater visual prominence on the active queue screen while maintaining a confirmation step.

**Expected improvement:**  
Users should be able to leave a queue more easily while reducing the risk of accidental cancellation.

---

### Iteration 3 — QR Code Explanation

**Problem identified:**  
Some participants were unsure about the purpose of the QR code.

**Change:**  
A short explanatory label was added to the digital ticket.

**Expected improvement:**  
Users should understand that the QR code is presented to staff for ticket verification.

---

# Conclusion

The usability testing demonstrated that the core functionality of the Virtual Queue Management App was generally understandable to the participants. All five participants were able to complete the main queue discovery, queue joining, queue status, history, and feedback tasks.

The main areas requiring improvement were **notification settings, the visibility of the Leave Queue action, and the explanation of the QR code**.

The findings provided a basis for refining the prototype before implementation and demonstrated the importance of testing the interface with users rather than relying solely on the design team's assumptions.

The overall testing process followed the design iteration cycle:

**Prototype → Usability Testing → Identify Problems → Refine Design → Implementation**