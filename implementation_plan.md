# Implementation Plan: Proyecto_11_RappiPlus Repository

## Goal
Create a polished GitHub repository for the **Proyecto_11_RappiPlus** analytics project. The repository will contain all source assets, a premium‑styled `README.md` with embedded dashboard images, detailed DAX explanations, and removal of the raw Git command block.

## Repository Location
`d:/Anty_Gravity_Proyectos/SNIPER_CORE/Proyectos_GitHub/Proyecto_11_RappiPlus`

## Folder Structure
```
Proyecto_11_RappiPlus/
├─ data/                # CSV files (catalog_clean.csv, marketing_clean.csv, orders_clean.csv)
├─ notebooks/           # Jupyter notebook (David German_revisado.ipynb)
├─ src/dax/             # Individual .dax files split from dax.txt
├─ docs/images/         # Dashboard screenshots (G1.png, G2.png, gmejorado*.png)
├─ pbix/                # Power BI project file (Proyecto_Final_Mejorado.pbix)
├─ docs/                # PDF pipeline guide (pipeline_antigravity_end_to_end_base.pdf)
└─ README.md
```

## Tasks
1. **Create repository directory** – ensure the target folder exists.
2. **Copy source assets** from `d:/Nuevos documentos/Triple_10/Sprint_12/Archivos limpios` into the corresponding folders.
3. **Split DAX file**: read `dax.txt` and create separate `.dax` files (one per measure) in `src/dax/`.
4. **Generate premium README**:
   - Project overview and objectives.
   - Cohort analysis insights (use the cohort matrix image `G2.png`).
   - Funnel and retention analysis description.
   - Embed dashboard screenshots with markdown image tags.
   - Explain each DAX measure with code fences.
   - Remove the previously added raw Git commands block.
   - Add SEO meta tags (title, description) as HTML comments.
5. **Initialize Git repository** (no need for the command block in README).
6. **Commit all files** with a meaningful message.
7. **Push to remote** using the provided GitHub PAT if the user wishes (prompt later).
8. **Verification** – open the README locally to confirm images render, DAX files are present, and no Git block remains.

## Verification Plan
- Run `git status` to ensure all files are tracked.
- Open `README.md` in a markdown preview to check image rendering.
- Spot‑check a few `.dax` files for correct content.
- Ensure line‑endings are consistent (CRLF for Windows).

## Open Questions
- Do you want the repository created under the GitHub organization/account `DataAnalist-DavidGRamos` with name `Proyecto_11_RappiPlus` now, or only the local structure?
- Any custom naming for the DAX files, or should we use the measure names extracted from `dax.txt`?

---
*Implementation plan saved at `d:/Anty_Gravity_Proyectos/SNIPER_CORE/Proyectos_GitHub/Proyecto_11_RappiPlus/implementation_plan.md`*
