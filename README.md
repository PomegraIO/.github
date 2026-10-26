# PomegraIO/.github

Org-wide defaults for every PomegraIO repo without its own: issue forms (Bug, Feature, Task, Epic) and the PR template.

## How we work

- **Board:** [Pomegra](https://github.com/orgs/PomegraIO/projects/1) - every issue and PR across the org.
- **Issue -> PR:** each code change starts as an issue in the repo it changes; the branch is `<issue>-<slug>` and the PR says `Closes #<issue>`. Hotfixes and tiny ad-hoc changes may go straight to `main`.
- **Epics:** issue type Epic, the work split into sub-issues (they can live in other repos).
- **Board fields:** Status (Backlog, Todo, In progress, In review, Blocked, Done), Priority (P0 now, P1 this cycle, P2 next, P3 someday), Area, Owner (Valera / Hermes / Claude), Size, Iteration (2 weeks), Target date (epics).
- **Labels:** `area:*` mirrors the Area field; `sev:*`, `kind:*`, `status:*`, `who:*`, `triage` belong to the security triage automation in Pomekube; `demo` marks mock issues.
