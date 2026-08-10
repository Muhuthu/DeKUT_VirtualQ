# Functional & Usability Requirements — Virtual Queue Management App

*Derived from the assignment brief, the two personas (`docs/personas.md`), and the current Information Architecture / high-fidelity design.*

## 1. Functional Requirements

Functional requirements describe **what the system must do**. Each is linked to the persona need it serves and the screen(s) that implement it.

### 1.1 Authentication

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-1.1 | User can create an account with name, student ID/email, and password | Faith needs a low-friction first-time setup | Sign Up |
| FR-1.2 | User can verify their account via email/phone OTP | Prevents fake accounts, builds trust | Email/Phone Verification |
| FR-1.3 | User can log in with email/phone and password | Returning use, Brian's repeat visits | Login |
| FR-1.4 | User can reset a forgotten password via OTP/reset link | Prevents lockout, account recovery | Forgot Password, Reset Password |

### 1.2 Home & Service Discovery

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-2.1 | Home Dashboard shows an overview, active ticket summary, and quick actions | Both personas need at-a-glance status | Home Dashboard |
| FR-2.2 | User can view all service points with current queue status | Faith needs to check before committing to a trip | Service Points & Services |
| FR-2.3 | User can view a service point's hours, requirements, and services offered before joining | Faith needs to avoid wasted trips | Service Point Details |

### 1.3 Queue Experience

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-3.1 | User can join a queue remotely for a selected service | Brian wants to avoid physically waiting | Join Queue |
| FR-3.2 | User receives a digital ticket with queue number and QR code after joining | Speeds up verification at the counter (Brian); gives Faith a clear artifact of "I'm in the queue" | Digital Ticket |
| FR-3.3 | User can view live queue position and estimated wait time, updating in near-real-time | Both personas need visible, trustworthy status updates | Live Queue Status |
| FR-3.4 | User can see who is currently being served and overall queue progress | Reinforces trust in the live data | Live Queue Status |
| FR-3.5 | User can leave a queue voluntarily, with a confirmation step | Prevents accidental loss of place; Brian may need to leave and rejoin | Leave Queue |
| FR-3.6 | User receives confirmation once service is completed, with optional rating | Closes the loop on the interaction | Service Completion |

### 1.4 Notifications

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-4.1 | User is notified when their queue position changes significantly | Reduces need to keep checking the app manually | Notifications |
| FR-4.2 | User is notified when their turn is approaching ("You're next") | Prevents missed turns — core anxiety for Faith | Notifications, Turn Notification |
| FR-4.3 | User can set notification preferences (push, SMS, in-app; per category) | Brian wants multi-channel redundancy | Notification Preferences |

### 1.5 History & Profile

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-5.1 | User can view a history of past queue tickets, including status (completed/cancelled) | Brian tracks repeated visits | Ticket History |
| FR-5.2 | User can view and edit their profile details | Basic account management | Profile, Edit Profile |
| FR-5.3 | User can log out | Basic account management | Profile |

### 1.6 Feedback & Support

| ID | Requirement | Persona need | Screen(s) |
|---|---|---|---|
| FR-6.1 | User can rate a completed service (1–5 stars) and submit feedback | Closes the loop, gives students a voice | Service Completion / Feedback |
| FR-6.2 | User can access Help/FAQ and Contact Support | Reduces confusion, especially for first-time users like Faith | Feedback & Support |

### 1.7 Staff-Side (Service Point Flow)

| ID | Requirement | Screen(s) |
|---|---|---|
| FR-7.1 | Staff can log in securely to a dedicated dashboard | Staff Login, Staff Dashboard |
| FR-7.2 | Staff can view the active queue list, filtered by service | Active Queue |
| FR-7.3 | Staff can call the next customer and view their ticket/details | Call Next / Customer Details |
| FR-7.4 | Staff can verify a ticket (e.g. via QR scan) and start service | Verify & Serve |
| FR-7.5 | Staff can mark service as complete, with optional notes | Complete Service |
| FR-7.6 | Staff can skip/reorder a queue entry or mark a no-show after a time limit | Queue Exceptions |
| FR-7.7 | Staff/admin can view analytics: queue volume, average wait time, peak hours | Analytics & Reports |

## 2. Non-Functional / Usability Requirements

Non-functional requirements describe **how well** the system must perform — these map directly to HCI heuristics and the assignment's mobile-usability focus.

| ID | Requirement | HCI Principle | Relevant Screens |
|---|---|---|---|
| NFR-1 | Live queue position must update within a few seconds of a real change, with a visible indicator that it's live (not stale) | Visibility of system status | Live Queue Status |
| NFR-2 | All destructive/committing actions (Leave Queue, Logout) must require explicit confirmation | Error prevention | Leave Queue, Logout |
| NFR-3 | Primary "confirm" actions and "leave/cancel" actions must use a consistent, distinguishable color pattern across all screens | Consistency & standards | All screens |
| NFR-4 | Every screen involving a wait or process (joining, verifying, completing) must show clear feedback that the system registered the action | Visibility of system status / feedback | Join Queue, Verify & Serve, Complete Service |
| NFR-5 | Navigation (bottom tab bar / IA structure) must remain identical across all top-level screens | Consistency, recognition over recall | Home, History, Profile, etc. |
| NFR-6 | First-time users must be able to understand the Digital Ticket screen's purpose without external explanation | Learnability | Digital Ticket |
| NFR-7 | All touch targets must be sized appropriately for mobile (no reliance on hover, adequate spacing) | Mobile usability / error prevention | All screens |
| NFR-8 | Users must be able to reach Help/Support from anywhere without losing their place in a flow (e.g. queue position) | User control and freedom | Global/utility elements |
| NFR-9 | Forms (Sign Up, Login, Reset Password) must validate input and show clear, specific error messages | Error prevention & recovery | Authentication screens |
| NFR-10 | Staff-side screens must allow completing a full customer interaction (call → verify → serve → complete) in as few taps as possible | Efficiency of use | Staff flow screens |

## 3. Traceability Note

This document should be revisited after usability testing — if NFR-6 (Digital Ticket comprehension) or NFR-1 (live status trust) fail during testing (see `research/03-findings.md`, Section D reactions), that's evidence to cite directly in your final report as a finding that shaped iteration.