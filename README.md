# FPM Agency OS

The instructions and tools that Claude and FPM's agents run: skill files, the priority tool and, later, the AI front end that connects ClickUp, the Client Hub and reporting.

## Where the master copy of each thing lives

| What | Master copy |
|---|---|
| Processes, SOPs and rules the team reads | Google Drive |
| Templates (docs, sheets, Canva) | Google Drive |
| Skill files, the priority tool, agent code | This repo |

Do not copy process docs or templates into this repo. Link to the Drive doc instead. Keeping the same thing in two places by hand is how documents drift apart. (Dan, Nov 10, 2026.)

The Claude Project "FPM Agency OS & Client Management" reads the team's process docs straight from Google Drive. It does not need this repo for that.

Scope is process and fulfillment. Client fees, payments and cost of delivery are in scope. Company cash flow, the CEO dashboard and the owners' partnership matters are not.

## How it is organized

| Folder | What goes in it |
|---|---|
| `skills` | One folder per Claude skill: its SKILL.md and any files it needs. Each skill links to the Drive docs it follows instead of repeating them. |
| `tools` | Code for the priority tool and, later, the AI front end |
| `archive` | Replaced versions, each pointing to what replaced it |

## Rules for this repo

1. Doc proposes changes and Dan approves them. Nothing goes into `main` without Dan's approval. Mark anything not yet approved as proposed.
2. When an approved process changes in Drive, check every skill that uses it and update the skill if needed. Note the check in Doc's change log.
3. Keep skill files short. Link to the process in Drive rather than copying it.
4. Write in plain English. No em dashes in anything the team reads.
5. Replaced files move to `archive`. They are not deleted.

## Where the team's docs are

Doc's Drive folder, "FPM Priority Operational Project", starting with "00 Start Here".
