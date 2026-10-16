# srtm_fsm_site

Public front end for the SRTM finite-state-machine prototype: a JCOP FSM on WinCC OA for the SRTM boards on the
LAr signal processors, University of Arizona ATLAS group.

Open `index.html` (or the GitHub Pages site). It shows the planned software as a flowchart, each component's file,
the milestones and their status, and the progress log. Updated 16 Oct 2026.

This repository holds only the generated page. The code, tests and records are in a private repository; this page is
rebuilt from it by `tools/build_public.py`, which removes internal details and refuses to publish if any remain.
