# User Journeys & Task Flows — Virtual Queue Management App
These two diagrams map every screen in the design (see `wireframes/`) into complete end-to-end flows for both the student and staff sides of the app.*

---

## 1. Full Task Flow — App Screens, Decisions & Background Processes

![User task flow diagram](user-journey-flow.png)

This diagram shows the complete task flow from launch to task completion, including decision points and error/retry paths.

- **Authentication branch:** Open App → checks if the user has an account → routes to Sign Up (with OTP verification) or Login (with password recovery via Forgot Password), looping back on failure until successful, then lands on the Home Dashboard.
- **Eight top-level sections from the dashboard:** Service Points & Services, Queue Experience, Notifications & Alerts, My Queue Actions, History, Profile, Feedback & Support, and More — each expands into its own linear sub-flow (e.g. Queue Experience: Join Queue → Get Digital Ticket → Live Queue Status → Currently Serving).
- **Staff / Service Point Flow (bottom section):** a separate flow for staff — Login → Dashboard → Active Queues → Call Next Customer → Verify & Serve → Complete Service → Queue Exceptions (skip/no-show) → Analytics & Reports.
- **Background System Processes:** shows how the Queue Management System, Real-time Updates Engine, Notification Service, Database, and Analytics Engine connect behind the user-facing flow — relevant to the NFR-1 (live status) requirement in `requirements.md`.
- All paths converge at a shared **Process End** step, representing exit or return to the dashboard.

## 2. Information Architecture & Journey Summary

![Information architecture and journey diagram](information-architecture.png)

This diagram summarizes the same structure as a navigation map plus two condensed, linear journeys:

- **Information architecture (top):** the 9 top-level sections reachable from the Mobile App root, each broken into their sub-items, plus **Global/Utility** elements (Search, Scan QR Code, Help/FAQ, Contact Support, etc.) accessible from anywhere in the app.
- **Student/User Journey Flow (bottom-left):** the condensed happy-path journey — Open App → Home Dashboard → Select Service Point → Choose Service → Join Queue → Monitor Queue → Notifications → Arrive & Get Served → Service Completion — with Leave Queue as a branch-off at the Monitor Queue stage.
- **Staff/Service Point Flow (bottom-right):** the condensed staff journey — Staff Login → Dashboard → Active Queue List → Call Next Customer → Verify & Serve → Complete Service, with Queue Exceptions and Analytics & Reports as supporting flows.

## 3. How This Maps to Requirements & Personas

These flows are the basis for the functional requirements in `requirements.md` (e.g. FR-3.1–FR-3.6 for the Queue Experience flow, FR-7.1–FR-7.7 for the staff flow) and the scenarios both personas (`personas.md`) move through — Faith's first-time, anxious journey through Sign Up → Service Point Details → Live Queue Status, and Brian's repeat, efficiency-focused journey through Join Queue → Notifications → Ticket History.
