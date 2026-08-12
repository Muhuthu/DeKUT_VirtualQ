# Virtual Queue Management Mobile App (DeKUT VirtualQ)

A mobile application prototype that lets university students and staff join, track, and manage virtual queues at campus service points — the registry, finance office, clinic, and accommodation office without having to physically stand in line.

This project was designed for the **Human–Computer Interaction (HCI)** module group term assignment, using **Figma** for wireframing/prototyping and **GitHub** for collaboration, documentation, and submission.

> **Note on tooling:** The assignment brief specifies Balsamiq as the default tool. Our group  chose  to use Figma instead .

> **Status:** 🚧 In progress — wireframe screens are built; user research, personas, and usability testing are still pending. See [Project Status](#project-status) below.

---

## Table of Contents

- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Target Users](#target-users)
- [Main Features](#main-features)
- [HCI Focus](#hci-focus)
- [Team Members](#team-members)
- [Repository Structure](#repository-structure)
- [Prototype](#prototype)
- [Project Status](#project-status)
- [How to View the Prototype](#how-to-view-the-prototype)

---

## Problem Statement

Students at university service points like registry, finance, clinic, and accommodation offices ,routinely lose significant time standing in physical queues with no visibility into their position, expected wait time, or whether the office is even open. This creates wasted time, overcrowding at service points, and anxiety around missing one's turn. There is currently no simple mobile way for a student to join a queue remotely, track their position in real time, and be notified when it's nearly their turn.

## Objectives

- Allow students to browse live queue status across multiple campus service points before deciding where/when to go.
- Let students join a queue remotely instead of waiting in person.
- Provide real-time visibility of queue position and estimated wait time (Nielsen's *visibility of system status* heuristic).
- Notify students when their turn is approaching so they can arrive just in time.
- Give students an easy way to leave a queue or confirm service completion.
- Maintain a history of past queue visits for reference.

## Target Users

- **University students** who regularly use registry, finance, clinic, or accommodation services and want to avoid long physical waits.
- **First-time / first-year students** unfamiliar with how queueing at these offices works and who need clear, low-friction onboarding.
- **Frequent users** (e.g., final-year students handling clearance, fees, or repeated clinic visits) who prioritize speed and want minimal steps to rejoin a queue.



## Main Features

- **Live service point dashboard** — browse all service points with current queue length and estimated wait, at a glance.
- **Join a queue remotely** — select a service point, review details, and confirm joining without being physically present.
- **Real-time queue position tracking** — see live position updates and progress as the queue moves.
- **Turn notifications** — in-app/push alert when a student is nearly at the front of the queue.
- **Leave queue / confirm service completion** — exit a queue early or check in once served.
- **Queue history** — view a record of past visits, wait times, and outcomes.
- **Account & notification management** — manage profile details and alert preferences (push, SMS, in-app).

## HCI Focus

This project emphasizes:

- **Visibility of system status** — the queue position screen and live-update states (screens 8–10) are deliberately split into distinct states to make position changes and system feedback obvious to the user.
- **User feedback** — confirmation screens, toasts, and banners for key actions (joining, leaving, arriving).
- **Consistency** — a shared bottom tab bar and consistent color coding for "confirm" vs "leave/cancel" actions across all screens.
- **Error prevention** — explicit confirm/cancel steps before joining or leaving a queue.
- **Mobile-first navigation** — built and evaluated specifically for a smartphone context (touch targets, mobile device frame sizes), not adapted from a desktop layout.

## Team Members

| Name | Registration Number |
|---|---|
| Margaret Njeri | C025-01-0624/2023 |
| Joe Mburu | C025-01-0626/2023 |
| Diana Chepkorir | C025-01-0652/2023 |
| William Macharia | C025-01-0616/2023 |
| Neema Kimutai | C025-01-0669/2023 |
| Peter Wanyoike | C025-01-0826/2022 |
| Faith Chebet | C025-01-0663/2023 |
| Daisy Jeruto | C025-01-0653/2023 |
| Ian Muhuthu | C025-01-0646/2023 |

**GitHub Repository:** `[text](https://github.com/Muhuthu/DeKUT_VirtualQ.git)`

## Repository Structure

```
Dekut_VitualQ/
├── design/                 # Figma wireframe screens, grouped by flow
│   ├── authentication/     # Login, Sign-Up
│   ├── Home/                # Home / Dashboard
│   ├── Onboarding/         # Splash Screen, Onboarding Tutorial
│   ├── profile/            # Profile / Account, Notification Settings, Queue History
│   ├── queue/               # Service Point Detail, Confirm Join, Leave Queue Confirmation
│   └── queue-tracking/     # Queue Position/Ticket, Live Update State, Turn Notification,
│                            # Service Completion / Check-In
├── docs/                   # Requirements, personas, user journeys, task flows, reports
├── research/                # User research instruments and summarized findings
├── wireframes/              # Exported Figma screenshots / prototype documentation
├── usability-testing/       # Test tasks, participant summaries, findings
├── iterations/               # Evidence of design changes made after usability feedback
├── final/                    # Final prototype exports, presentation, final report
└── README.md
```

> Screen numbering and full navigation map (all 16 screens, what each contains, and how they link) are documented in `docs/Virtual_Queue_App_Screen_Map.docx`.

## Prototype

The Figma prototype currently consists of **16 linked mobile and staff-dashboard screens** (well beyond the 12-screen minimum), organized around a 9-section Information Architecture: Authentication, Home Dashboard, Service Points & Services, Queue Experience, Notifications & Alerts, History, Profile, Feedback & Support, and More — plus a parallel Staff/Service Point flow (login, active queue, call next, verify & serve, complete service, exceptions, analytics).
 
Full system flow, IA structure, and screen-by-screen detail are documented in `docs/` (system flowchart, IA diagram, and `requirements.md`).
 
Three complete user scenarios are supported end-to-end through the linked screens, covering joining a queue, tracking live position, leaving early, and completing service.



## How to View the Prototype

1. Open the Figma file link: `(https://www.figma.com/design/gc7v0azzDMVOoUiILQ1zK8/DeKUT-VirtualQ---Interactive-Prototype?node-id=0-1&t=Kh1ouPY7iIXVN0bj-1)`
2. Switch to **Present** mode and start from screen **1 – Splash Screen**; use the linked hotspots to click through the flows.
3. To follow a specific scenario, see the step-by-step walkthroughs in `docs/Virtual_Queue_App_Screen_Map.docx`, Section 4.
4. Static exports/screenshots of each screen are also available in `wireframes/` for quick review without opening Figma.

---

*This README will be updated as research, personas, usability testing, and iteration evidence are added throughout the project.*
