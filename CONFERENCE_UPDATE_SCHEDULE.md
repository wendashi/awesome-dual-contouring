# Conference Update Schedule

This document tracks when to search for newly accepted or newly public Dual Contouring, contouring, and mesh extraction papers for this repository.
Months are approximate and should be checked against each conference's official dates page every year.

## DC / Contouring Keywords

Use these keywords when searching GitHub, arXiv, OpenReview, official programs, and project pages:

```text
dual contouring, neural dual contouring, unsigned dual contouring, occupancy-based dual contouring
contouring, surface extraction, mesh extraction, isosurface extraction, zero level set extraction
level-set extraction, UDF meshing, unsigned distance field meshing, SDF meshing, occupancy field meshing
```

Also search mechanism-level variants:

```text
QEF, quadric error function, Hermite data, edge intersection, dual grid, dual marching cubes
Voronoi Optimization, Voronoi UDF, VoroUDF, non-voxel meshing, non-grid meshing, point-based meshing
```

## Monthly Watch Schedule

| Month | Conferences to Watch | What to Do |
| --- | --- | --- |
| January | ICLR | Check OpenReview decisions and accepted/spotlight/oral tabs. Search GitHub and arXiv for ICLR + contouring keywords. |
| February | ICLR, CVPR | Do an ICLR follow-up sweep. After CVPR decisions, run the first CVPR GitHub/arXiv sweep. |
| March | CVPR, SIGGRAPH | Do a CVPR second sweep. After SIGGRAPH Technical Papers decisions, run the first SIGGRAPH sweep. |
| April | SIGGRAPH, ICML | Do a SIGGRAPH follow-up sweep. After ICML decisions, run the first ICML sweep. |
| May | CVPR, SIGGRAPH, ICML | Calibrate CVPR against virtual/proceedings pages when available. Do ICML follow-up. Check SIGGRAPH final/publication updates. |
| June | CVPR, ICCV/ECCV | Final CVPR cleanup. After ICCV or ECCV decisions, run the first ICCV/ECCV sweep. |
| July | ICCV/ECCV, SIGGRAPH, SIGGRAPH Asia | Do ICCV/ECCV follow-up. Calibrate SIGGRAPH against program/proceedings. After SIGGRAPH Asia decisions, run the first SIGGRAPH Asia sweep. |
| August | ICCV/ECCV, SIGGRAPH Asia | Do ICCV/ECCV program pre-checks. Do SIGGRAPH Asia follow-up. |
| September | ICCV/ECCV, NeurIPS | Final ICCV/ECCV cleanup when program/proceedings are available. After NeurIPS decisions, run the first NeurIPS sweep. |
| October | NeurIPS, ICCV/ECCV | Do NeurIPS follow-up. Finish ICCV/ECCV program/proceedings checks. |
| November | NeurIPS, SIGGRAPH Asia | Calibrate SIGGRAPH Asia against final program/publication. Do NeurIPS program pre-checks. |
| December | NeurIPS | Calibrate NeurIPS against final program/proceedings. Do annual dedupe, broken-link checks, and label cleanup. |

## Decision vs. Public List Timing

| Conference | Decision Month | More Complete Public List Usually Appears |
| --- | --- | --- |
| ICLR | January | Late January to February on OpenReview; program details around March-April. |
| CVPR | February | March for early public traces; May-June for virtual site/proceedings. |
| SIGGRAPH | March | May-July after conditional acceptance, revisions, and final publication updates. |
| ICML | April | Late April-May for accepted papers; June-July for program/proceedings. |
| ICCV | June | July for early public traces; September-October for program/proceedings. |
| ECCV | June | Late June-July for early public traces; August-September for program/proceedings. |
| SIGGRAPH Asia | July | August for early public traces; September-November for final program/publication. |
| NeurIPS | September | Late September-October for accepted papers; November-December for program/proceedings. |

Notes:

- ICCV and ECCV alternate years: ICCV is usually odd years; ECCV is usually even years.
- SIGGRAPH and SIGGRAPH Asia often have conditional acceptance and final revision stages, so final public lists can lag decisions by months.
- NeurIPS is the current conference name; older materials may still use NIPS.

## Search Workflow

For each active conference/month:

1. Check official source first:
   - CVPR: conference dates, virtual site, accepted papers, openaccess pages.
   - ECCV/ICCV: ECVA conference pages and official accepted/program pages.
   - SIGGRAPH/SIGGRAPH Asia: Technical Papers pages and conference schedule pages.
   - ICLR: OpenReview accepted/oral/spotlight tabs.
   - ICML/NeurIPS: official dates, accepted papers, program, proceedings pages.
2. Search GitHub:
   - `"CVPR 2026" dual contouring`
   - `CVPR2026 dual contouring`
   - `"SIGGRAPH Asia 2026" UDF meshing`
   - `"ICCV 2025" isosurface extraction`
   - Repeat with the DC / contouring keywords and mechanism-level variants above.
3. Search arXiv and project pages with the same conference + keyword combinations.
4. Compare against `README.md` to avoid duplicates.
5. Classify candidates against the current README categories:
   - `MC and DMC Marching Cubes Family`
   - `DC Single-Dual-Vertex Methods`
   - `DC Multi-Dual-Vertex Methods`
   - `Beyond DC, Non-Voxel/Grid-based`
   - `Field-Free DC-Like Structured Representations`
6. List candidates for manual review before editing the repo.
7. After approval, update `README.md`, run `git diff --check`, commit, and push.

## Candidate Review Template

Before updating the repo, list proposed additions in this format:

| Conference | Title | Authors | Links | Keywords | Notes |
| --- | --- | --- | --- | --- | --- |
| ECCV 2026 | Example Paper Title | Author A, Author B | GitHub / arXiv / official page | dual contouring, UDF meshing | Evidence that it is accepted and relevant to contouring or mesh extraction. |

Only add papers after the candidate list has been checked.

## README Update Rules

- Put new entries under the most precise existing README category.
- Prefer mechanism-based placement over venue-based placement.
- Keep the paper title directly clickable.
- Preserve each entry's compact format: title, venue/year, `input = ...`, code link if official code exists, and GitHub stars badge when applicable.
- Prefer official conference page links when available; otherwise use GitHub/project page, then arXiv.
- Add labels only when confirmed by official sources:
   - `🏅best`
   - `🏆oral`
   - `🌟highlight`
- Keep weakly related reconstruction or generation papers out of the README unless the contouring / mesh extraction mechanism is central.
- If a paper only uses SDF/UDF/occupancy as an upstream representation but does not contribute to meshing, contouring, or a plausible DC replacement, list it as a weak candidate and do not add it unless manually approved.

## Suggested Automation Policy

A monthly automation is enough for this repository, with extra manual sweeps during active decision windows:

- Run once per month, preferably on the 1st.
- Detect the current month.
- Use the monthly schedule above to choose which conferences to scan.
- Produce a candidate list only.
- Do not edit files automatically unless explicitly instructed in that run.

During active decision windows, add follow-up sweeps:

- Decision week: first scan.
- Four weeks later: second scan.
- Two to four weeks before the conference: final program/proceedings calibration.
