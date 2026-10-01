# ChungaAlert

A flood and drought early-warning system that distributes verified alerts to pastoralist communities in Kenya's arid and semi-arid lands via SMS.

## Problem

Pastoralist communities in Kenya's ASALs face recurring flood and drought events, but existing early-warning data (from KMD, NDMA, WRA) rarely reaches the people most at risk in a timely, verified, and locally actionable form.

## What ChungaAlert does

- Ingests rainfall, river-level, and drought-classification data from KMD and NDMA
- Applies threshold-based logic to classify flood/drought risk
- Routes every alert through a human verification step (local chief / NDMA county officer) before dispatch
- Sends verified alerts to registered community contacts via SMS (Africa's Talking)
- Provides an admin dashboard for alert history, subscriber management, and affected-zone monitoring

## Team & Roles

| Name | Role |
|---|---|
| Crystal Kanana | Project Manager & Data Engineer |
| Donell Bikketi | Backend Engineer (Core Logic) & Security Architect |
| Gloria Kendi | Backend Engineer (Integrations) |
| Emmanuel Douglas | Frontend Engineer |
| Andrew Kigondu | QA Engineer & Technical Writer |

## Tech Stack

> To be filled in as decisions are finalized.

- Backend: TBD
- Frontend: TBD
- Database: TBD
- SMS Gateway: Africa's Talking
- Data Sources: Kenya Meteorological Department (KMD), National Drought Management Authority (NDMA)

## Getting Started

```bash
git clone <repo-url>
cd chungaalert
# setup instructions to be added once the stack is finalized
```

## Branching Strategy

`main` is protected — no direct pushes. All work happens on a personal branch and merges via Pull Request with at least one reviewer's approval.

**Branch naming convention:** `<your-name>/<role>`

Examples:
- `crystal/ProjectManagement`

Keep the description short, lowercase, and hyphenated. Open a new branch per feature/task rather than reusing one long-lived personal branch.

## Contributing

1. Pull the latest `main` before starting new work.
2. Create your branch using the naming convention above.
3. Commit with clear, descriptive messages.
4. Open a Pull Request into `main` and request a review from a teammate.
5. Do not merge your own PR.

## License

> To be determined.
