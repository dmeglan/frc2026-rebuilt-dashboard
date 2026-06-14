# FRC 2026 REBUILT — Robot Study Dashboard

A ranked, searchable catalog of FRC 2026 *REBUILT* teams that publicly released robot
CAD, technical binders, or code — enriched with Statbotics EPA, archetype, vision system,
a documentation-confidence rating, and curated study picks.

**Live site:** https://USERNAME.github.io/frc2026-rebuilt-dashboard/

- `index.html` — the dashboard (auto-switches desktop/mobile), with an **Updated …** banner
  and an expandable **What's changed** changelog.
- `deep-dive.html` / `deep-dive.pdf` — top-teams deep-dive (subsystem cards + lessons).

The site is rebuilt and republished automatically twice a week by a scheduled task that
scans Chief Delphi for new 2026 CAD/documentation releases and adds qualifying teams.
Only these three built files are tracked here; the build pipeline lives in the local
project folder (`pipeline/`).
