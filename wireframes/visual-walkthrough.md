# Visual Walkthrough — DeKUT VirtualQ

*A descriptive companion to the screenshots in the design document — for readers of the final report who need to picture the interface without the images in front of them, and for anywhere a screenshot isn't practical to embed.*

## Visual Identity

The app uses a clean, deep-green and off-white color scheme throughout — a calm, institutional palette that reads as trustworthy rather than playful, fitting for an administrative tool. Primary action buttons (Login, Join Queue, Confirm) are solid green with white text; destructive or exit actions (Leave Queue, Cancel) use a visually distinct treatment so the two are never confused at a glance. Typography is simple and legible, with generous white space rather than dense, cramped screens — every screen has one clear focal element rather than competing for attention.

## The Student Journey, Screen by Screen

**Opening the app** lands on a Splash Screen: the DeKUT VirtualQ logo centered on a solid green background, with a simple tagline beneath it — "Join, Monitor & Arrive When Needed." It's the kind of screen you see for a second or two before being carried into either Login or Sign Up, depending on whether the app recognizes you.

**Login** greets returning users with a friendly "Karibu Tena!" ("Welcome back") header, then a straightforward two-field form — email/phone and password — with a solid green Login button beneath, a "Forgot Password?" link, and social sign-in options (Google, Microsoft) if the student prefers not to type credentials at all.

**Sign Up** mirrors this simplicity for first-time users: full name, email, phone, and a password field with visible strength requirements, so a first-year student isn't guessing whether their password is acceptable.

**Home Dashboard** is the app's command center. A personalized greeting ("Habari Njema, John Maina") sits at the top, immediately followed by the single most important object on the whole screen: a card showing the student's *active ticket* if they have one — queue number, service point, position, and estimated wait, all visible without a single tap. Below that sit Quick Actions (Join Queue, My Tickets, Nearby Services) and a bottom tab bar (Home, Services, Tickets, Notifications, Profile) that stays identical across every top-level screen, so navigation never has to be relearned.

**Service Points** presents a simple searchable list — Registry, Finance, Clinic, Accommodation, Student Affairs — each row showing a live queue-length badge, so a student can compare offices before choosing one. Tapping through to **Service Details** shows operating hours, the specific services offered (e.g. "Transcripts & Certificates," "Academic Records"), and a single prominent green "Join Queue" button at the bottom — nothing else competes with that action.

**Joining a queue** is a short, focused form: which service within that office, how many people (if joining on someone's behalf), and a Join Queue button. The moment it's tapped, the student is taken straight to their **Digital Ticket** — visually the boldest screen in the app. A large ticket-style card, colored to match the app's identity, displays the queue number in oversized text ("A023"), the position ("12/45"), estimated wait ("~25 min"), and — after the QR-code iteration — a short line of explanatory text confirming what the code is for, so it's not left ambiguous the way early testers found it.

**Live Queue Status** takes that same ticket format and adds movement: a "Currently Serving" indicator, the student's own position updating as it changes, a short visual progress bar filling in as the queue advances, and a small live queue-line preview showing who's a few spots ahead. It's designed so a glance — not a read — tells the student where things stand.

**Notifications** (now reachable both from the Profile area and, after the iteration, via a direct shortcut on the active ticket itself) shows a simple feed: "You've moved up to position #12," "You're approaching your turn," "You're next," each timestamped and color-coded by urgency (a red accent for time-sensitive alerts like "your ticket has been cancelled").

**Leave Queue** — now more visually prominent on the active ticket screen following the iteration — opens a deliberately simple confirmation modal: a door icon, "Are you sure you want to leave the queue?", a warning that the student will lose their current position, and two clearly separated buttons ("Yes, Leave Queue" vs. "No, Stay in Queue") so the destructive choice is never accidental.

**Service Completion** closes the loop warmly: a green checkmark, "Hongera!" ("Congratulations!"), a thank-you message, and an optional star rating before returning to the dashboard.

**Profile** and **Edit Profile** are unremarkable by design — name, student ID, contact details, a photo, and clear paths to History, Notification Preferences, and Logout — because a profile screen's job is to stay out of the way once the information is correct.

## The Staff Side

Running in parallel is a second, structurally similar app experience for service-point staff: a **Staff Dashboard** showing today's stats at a glance (active queue count, waiting, served, average wait), an **Active Queue** list they can call from, a **Verify & Serve** screen built around QR-code scanning (the same code the student was shown), and an **Analytics & Reports** view with a simple bar chart of service volume by hour. This half of the system uses the same visual language — same green identity, same clarity-first layout — so it feels like one coherent product rather than two different apps bolted together.

## How the Iterations Changed What's Visible

Three specific visual changes separate the current version from the one tested with the 5 participants:

1. **Notification Preferences** used to require navigating into Profile; a student on the active ticket screen now sees a small, direct shortcut icon leading straight there, alongside clearly labeled channel toggles (Push / SMS / In-app) that are no longer ambiguous at a glance.
2. **Leave Queue** used to sit quietly among other options; it now has stronger visual weight on the active queue screen itself — closer to the position display, where testers said they expected to find it — while keeping its confirmation step intact.
3. **The Digital Ticket's QR code** used to appear with no explanation; a short line beneath it now reads "Show this QR code at the service counter," closing the exact gap that caused 3 of 5 testers to hesitate.

