

# Research Findings — User Questionnaire (SAMPLE)

## Response Log

| # | Year | Service point(s) used most | Typical wait | Biggest frustration | Would use app? | Notification preference |
|---|---|---|---|---|---|---|
| 1 | First year | Registry | 30–60 min | Not knowing how much longer, standing the whole time | Yes, definitely | Push notification |
| 2 | Final year | Finance | 10–30 min | Coming back multiple times when office was "closed for lunch" | Yes, definitely | More than one (push + SMS) |
| 3 | Second year | Clinic | Over an hour | Long wait while sick, no seating available | Maybe, depends how it works | In-app only |
| 4 | Third year | Accommodation | 30–60 min | Queue moving slowly with no explanation | Maybe, depends how it works | Push notification |
| 5 | Final year | Finance, Registry | 10–30 min | Having to physically hold a spot, can't leave to grab food | Yes, definitely | SMS |

## Notable Open-Ended Quotes (illustrative)

- "I once waited two hours only to be told I needed a form from another office — a queue app could at least tell me that before I show up."
- "I'd trust it if I could actually see the line moving, not just a static number that doesn't change for 20 minutes."
- "Losing my place because I stepped away is my biggest fear — I want to be able to leave and come back without starting over."

## Patterns & Themes (illustrative)

- **Biggest pain points:** uncertainty about wait time; being physically tied to the queue with no ability to leave
- **Trust concerns:** students want visible, frequently-updating position — a static or slow-updating number reduces trust
- **Notification preferences:** push notifications most commonly preferred, often combined with a second channel (SMS/in-app) as backup
- **Behavior around leaving a queue early:** students want a simple leave option but fear losing their place permanently if they step away briefly
- **Divisive/unexpected:** in-app-only vs push split roughly by how often students check their phone during the day

## Implications for Design (illustrative)

| Finding | Design implication | Already addressed by |
|---|---|---|
| Students distrust static-feeling wait numbers | Position must visibly update in near-real-time | Screens 8–9 (Queue Position, Live Update State) |
| Fear of losing place if stepping away | Consider a "temporarily away" state, not just Leave/Stay | Not yet addressed — potential design gap to raise in Chapter/Discussion |
| Multi-channel notification preference | Notification Settings should allow multiple channels at once | Screen 14 (Notification Settings) already supports toggles for Push/SMS/In-app |

## Input for Personas (illustrative)

- Responses #1 and #3 (first/second year, anxious about uncertainty, unfamiliar with office processes) → support a **first-year, anxious-about-queues** persona.
- Responses #2 and #5 (final year, frequent user, wants speed and multitasking ability) → support a **final-year, frequent/efficiency-focused** persona.