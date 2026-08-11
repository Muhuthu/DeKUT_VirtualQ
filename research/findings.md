# Research Findings — User Questionnaire

*Real responses from 5 university students, collected via the written questionnaire in `02-questionnaire.md`.*

## Response Log

| # | Year | Service Point(s) Used Most | Typical Wait | Biggest Frustration | Would Use App? | Notification Preference |
|---|------|----------------------------|--------------|---------------------|----------------|--------------------------|
| 1 | First Year | Registry | 30–60 min | Not knowing how long the queue would take and having to remain at the office | Yes, definitely | Push notification |
| 2 | Final Year | Finance | 10–30 min | Spending time waiting when the office was temporarily unavailable | Yes, definitely | Push + SMS |
| 3 | Second Year | Clinic | Over 1 hour | Long waiting time and uncertainty about when they would be served | Yes, if reliable | In-app notification |
| 4 | Third Year | Accommodation | 30–60 min | Slow-moving queue with limited information about progress | Yes, if easy to use | Push notification |
| 5 | Final Year | Finance and Registry | 10–30 min | Having to remain physically in the queue and being unable to use the waiting time productively | Yes, definitely | SMS |

## Key Participant Responses

- Participants expressed frustration with **not knowing how long they would have to wait** before receiving a service.
- Students reported that remaining physically present in a queue made it difficult to use their time for other activities.
- Participants valued the ability to know **whether a service point was busy before travelling there**.
- Participants indicated that notifications would be useful because they would reduce the need to continuously monitor their position in the queue.
- Some participants preferred more than one notification channel, particularly SMS and push notifications.

## Notable Quotes

> "Sometimes you don't know how long the queue will take, so you just have to stay there and wait."

> "It would be useful to know whether the office is busy before going there."

> "If I could join the queue and receive a notification when my turn is close, I could use that time to do other things."

> "The queue can move very slowly, and sometimes you don't know whether it is actually moving or not."

> "I would prefer getting an SMS because I may not always have the application open."

## Patterns & Themes

**1. Uncertainty about waiting time** — the most consistent issue across responses. Students knew they had to wait but had limited information about position or progress. Supports: current queue position, estimated wait, number ahead, regularly updated status.

**2. Physical presence during waiting** — students, especially those with classes/assignments, found it inconvenient to remain physically present. Directly supports the core premise of a virtual/remote queue.

**3. Need for progress visibility, not just a number** — a static queue number isn't enough; users need confidence the app reflects real movement. Supports: live position, progress indication, visible change over time.

**4. Notification preferences vary:**

| Notification Type | Participants | Observation |
|---|---|---|
| Push | P1, P4 | Preferred for immediate updates |
| SMS | P5 | Preferred as reliable fallback when app isn't open |
| Push + SMS | P2 | Wanted multiple channels for reliability |
| In-app | P3 | Preferred keeping it within the app |

Supports configurable, multi-channel notification preferences rather than one fixed channel.

**5. Productive use of waiting time** — especially later-year students wanted to leave the physical queue area while still tracking their position remotely. Supports: digital tickets, live tracking, turn notifications, estimated wait.

## Implications for Design

| Research Finding | Design Implication | System Feature |
|---|---|---|
| Uncertainty about queue duration | Clear, regularly updated queue info | Queue Position / Live Queue Status |
| Want to know if a service point is busy before travelling | Show service-point info pre-join | Service Point Details |
| Physical waiting is inconvenient | Allow remote queue joining | Join Queue |
| Concerned about missing their turn | Turn-approaching notifications | Notification System |
| Notification preferences differ | Multi-channel, configurable notifications | Notification Preferences |
| Want to review previous visits | Persistent visit record | Ticket History |
| Need a simple way to stop waiting | Clear cancellation with confirmation | Leave Queue |

All of the above were **already present in the existing design** prior to this research being run — the findings function as validation of assumptions made during system design, rather than surfacing entirely new requirements. This is worth stating plainly in the final report rather than implying the research drove the design chronologically.

## Input for Personas

**First-year students (P1, P3)** emphasized: understanding how service points work, knowing conditions before arriving, clear wait-time information, turn notifications, and a simple/understandable interface. → Supports the **anxious first-year persona** (guidance, clarity, reassurance).

**Final-year students (P2, P5)** emphasized: saving time, remote queue joining, avoiding physical waiting, timely notifications, productive use of waiting time, and access to visit history. → Supports the **efficiency-focused final-year persona** (speed, flexibility, convenience).

## Research Conclusion

Findings indicate students' core challenges are uncertainty about waiting time, lack of queue visibility, and the requirement to remain physically present. These findings support the Virtual Queue Management App's existing feature set: viewing service-point info pre-visit, checking queue conditions, joining remotely, receiving a digital ticket, monitoring progress live, receiving turn notifications, reviewing history, and giving post-service feedback.# Research Findings — User Questionnaire

*Real responses from 5 university students, collected via the written questionnaire in `02-questionnaire.md`.*

## Response Log

| # | Year | Service Point(s) Used Most | Typical Wait | Biggest Frustration | Would Use App? | Notification Preference |
|---|------|----------------------------|--------------|---------------------|----------------|--------------------------|
| 1 | First Year | Registry | 30–60 min | Not knowing how long the queue would take and having to remain at the office | Yes, definitely | Push notification |
| 2 | Final Year | Finance | 10–30 min | Spending time waiting when the office was temporarily unavailable | Yes, definitely | Push + SMS |
| 3 | Second Year | Clinic | Over 1 hour | Long waiting time and uncertainty about when they would be served | Yes, if reliable | In-app notification |
| 4 | Third Year | Accommodation | 30–60 min | Slow-moving queue with limited information about progress | Yes, if easy to use | Push notification |
| 5 | Final Year | Finance and Registry | 10–30 min | Having to remain physically in the queue and being unable to use the waiting time productively | Yes, definitely | SMS |

## Key Participant Responses

- Participants expressed frustration with **not knowing how long they would have to wait** before receiving a service.
- Students reported that remaining physically present in a queue made it difficult to use their time for other activities.
- Participants valued the ability to know **whether a service point was busy before travelling there**.
- Participants indicated that notifications would be useful because they would reduce the need to continuously monitor their position in the queue.
- Some participants preferred more than one notification channel, particularly SMS and push notifications.

## Notable Quotes

> "Sometimes you don't know how long the queue will take, so you just have to stay there and wait."

> "It would be useful to know whether the office is busy before going there."

> "If I could join the queue and receive a notification when my turn is close, I could use that time to do other things."

> "The queue can move very slowly, and sometimes you don't know whether it is actually moving or not."

> "I would prefer getting an SMS because I may not always have the application open."

## Patterns & Themes

**1. Uncertainty about waiting time** — the most consistent issue across responses. Students knew they had to wait but had limited information about position or progress. Supports: current queue position, estimated wait, number ahead, regularly updated status.

**2. Physical presence during waiting** — students, especially those with classes/assignments, found it inconvenient to remain physically present. Directly supports the core premise of a virtual/remote queue.

**3. Need for progress visibility, not just a number** — a static queue number isn't enough; users need confidence the app reflects real movement. Supports: live position, progress indication, visible change over time.

**4. Notification preferences vary:**

| Notification Type | Participants | Observation |
|---|---|---|
| Push | P1, P4 | Preferred for immediate updates |
| SMS | P5 | Preferred as reliable fallback when app isn't open |
| Push + SMS | P2 | Wanted multiple channels for reliability |
| In-app | P3 | Preferred keeping it within the app |

Supports configurable, multi-channel notification preferences rather than one fixed channel.

**5. Productive use of waiting time** — especially later-year students wanted to leave the physical queue area while still tracking their position remotely. Supports: digital tickets, live tracking, turn notifications, estimated wait.

## Implications for Design

| Research Finding | Design Implication | System Feature |
|---|---|---|
| Uncertainty about queue duration | Clear, regularly updated queue info | Queue Position / Live Queue Status |
| Want to know if a service point is busy before travelling | Show service-point info pre-join | Service Point Details |
| Physical waiting is inconvenient | Allow remote queue joining | Join Queue |
| Concerned about missing their turn | Turn-approaching notifications | Notification System |
| Notification preferences differ | Multi-channel, configurable notifications | Notification Preferences |
| Want to review previous visits | Persistent visit record | Ticket History |
| Need a simple way to stop waiting | Clear cancellation with confirmation | Leave Queue |

All of the above were **already present in the existing design** prior to this research being run — the findings function as validation of assumptions made during system design, rather than surfacing entirely new requirements. This is worth stating plainly in the final report rather than implying the research drove the design chronologically.

## Input for Personas

**First-year students (P1, P3)** emphasized: understanding how service points work, knowing conditions before arriving, clear wait-time information, turn notifications, and a simple/understandable interface. → Supports the **anxious first-year persona** (guidance, clarity, reassurance).

**Final-year students (P2, P5)** emphasized: saving time, remote queue joining, avoiding physical waiting, timely notifications, productive use of waiting time, and access to visit history. → Supports the **efficiency-focused final-year persona** (speed, flexibility, convenience).

## Research Conclusion

Findings indicate students' core challenges are uncertainty about waiting time, lack of queue visibility, and the requirement to remain physically present. These findings support the Virtual Queue Management App's existing feature set: viewing service-point info pre-visit, checking queue conditions, joining remotely, receiving a digital ticket, monitoring progress live, receiving turn notifications, reviewing history, and giving post-service feedback.