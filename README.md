# RoomScanner: Customer Portal

Customer Portal is one of the two subsystems of RoomScanner, a travel accommodation booking platform built for EEET2582/ISYS3461 (Software Architecture). Customers use it to search for rooms, book and pay, buy Premium membership, follow regional events, and rate the providers they stayed with.

The partner subsystem is [Provider Portal](https://github.com/RoomScanner/ProviderPortal). The two teams share an API contract repository in the RoomScanner organization.

## Team

GitHub contribution stats are graded per person, so every member's full name is mapped to their GitHub username here (TW-E01).

| Full name | GitHub username | Role |
| --- | --- | --- |
| _Member 1_ | _username_ | TBD |
| _Member 2_ | _username_ | TBD |
| _Member 3_ | _username_ | TBD |
| _Member 4_ | _username_ | TBD |
| _Member 5_ | _username_ | TBD |

## Key dates

| What | Due |
| --- | --- |
| Project Charter | Before Milestone 1 |
| API contract for Milestone 1 | Fri 20 Nov 2026, 18:00 |
| Milestone 1: design report, data model, C4 diagrams | Fri 4 Dec 2026, 18:00 |
| API contract for Milestone 2 | Fri 1 Jan 2027, 18:00 (confirm with lecturer, it's a public holiday) |
| Milestone 2: implementation and deployment | Wed 13 Jan 2027, 18:00 |
| Peer review | Within 48 h after each milestone deadline |

The API contract is due by 18:00 on Friday of week N-2 for a submission in week N (TW-S06).

## Repository layout

```
.
├── frontend/              # React app (added once the stack is chosen)
├── backend/               # Backend service(s) (added once the architecture is chosen)
├── docs/
│   ├── charter/           # Project Charter
│   ├── design/
│   │   ├── data-model/    # ERD and data model notes
│   │   └── c4/            # Container and component diagrams
│   ├── api/               # Notes on what we provide/consume (the contract itself lives in the shared repo)
│   ├── meetings/
│   │   ├── standups/      # Two stand-ups per week minimum (TW-S04)
│   │   └── sprint-reviews/
│   └── contribution/      # Contribution declarations and GitHub stats
└── .github/               # Issue and PR templates
```

## How we work

See [CONTRIBUTING.md](CONTRIBUTING.md) for the board stages, branch and commit rules, review process and Definition of Done.
