# 🪖 Kavach
### AI-Powered Parametric Insurance for Freelance Musicians, Performers & DJs

> Because losing a gig shouldn't mean losing your livelihood.

---

## The Problem

Freelance musicians, performers, and DJs in India depend entirely on booked gigs for income. A single cancellation — due to extreme weather, a venue shutdown, or a sudden civic disruption — can erase weeks of earnings.

No platform backs them. No union protects them. Traditional insurance doesn't even know they exist.

**Kavach does.**

---

## Persona & Scenarios

**Persona:** Independent musicians, performers, and DJs — primarily in Tier-1 and Tier-2 Indian cities, working weddings, college fests, corporate events, and local shows.

| Disruption | Example |
|---|---|
| Weather | Heavy rain or cyclone warning wipes out an outdoor wedding |
| Venue | Sudden closure, license issue, or last-minute cancellation |
| Civil | Curfew, bandh, or local unrest in the event zone |

### Workflow
```
Performer Onboards → Risk Profile Created → Policy Linked to Booked Gig
                              ↓
              Real-time Disruption Monitoring (Weather / Venue / Civil)
                              ↓
                  Parametric Trigger Detected
                              ↓
            Fraud Check (booking verification + location validation)
                              ↓
                        Auto Payout
```

---

## Weekly Premium Model

Premiums are structured weekly and tied to the performer's upcoming gig schedule. Pricing is dynamic — factoring in event type, city, season (e.g. wedding season = elevated risk), and earnings history. Exact tiers TBD during development.

---

## Parametric Triggers

Payouts are initiated automatically when objective conditions are met — no manual claim needed.

| Trigger Type | Example Condition |
|---|---|
| Weather | Rainfall intensity / cyclone alert on event day in event zone |
| Venue Shutdown | Verified closure or license cancellation |
| Civil Disruption | Confirmed curfew or bandh in the event area |

Exact thresholds will be calibrated during development.

---

## AI/ML Plan

- **Premium Calculation** — Dynamic model using event type, location risk, season, and performer history
- **Fraud Detection** — Booking verification cross-checked against cancellation claims + location validation
- **Risk Modeling** — Predictive scoring by city/zone and time of year to anticipate high-risk periods

Specific models and libraries TBD during implementation.

---

## Tech Stack *(Tentative)*

- **Backend:** Python, FastAPI
- **Frontend:** React.js (Web App)
- **ML:** Python-based (libraries TBD)
- **APIs:** Weather & civil disruption data (free tiers / mocks), venue data (simulated)
- **Payments:** Sandbox / mock for now

---

## Planned Features

- Performer onboarding & risk profiling
- Gig-linked policy creation with dynamic weekly pricing
- Real-time disruption monitoring & automatic claim triggering
- Fraud detection & booking verification
- Payout processing
- Analytics dashboard

---

## Out of Scope

Health insurance, instrument damage, and travel coverage are excluded. Kavach covers **loss of income from gig cancellations only.**

---

## Team

- Khrisha Sreedar
- Tanishq Ude
- Sameeksha Kurup
- Arvin Mathew Saj
- Pranauv Srinath

## Submission Links

- 🎥 Demo Video: *(link)*

---
