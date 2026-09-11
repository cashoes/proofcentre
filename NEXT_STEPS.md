# PROOF Centre Website — Session Handover & Next Steps

**Date:** September 10, 2026  
**Repository Branch:** `main` (Clean, up to date)  
**Local Preview:** `http://localhost:1313/` (`hugo server -D`)

---

## 🚀 What We Accomplished Today

1. **Capabilities Sub-Hero Band**:
   * Consolidated into a 4-column horizontal strip beneath the manifesto.
   * Linked each pillar to the 4 PROOF logo colors:
     * **Biomarker Discovery & Development:** `#b3d335` (Lime Green)
     * **Multi-Omic Integration & ML:** `#6dcff5` (Sky Blue)
     * **Clinical Cohorts & Biobanking:** `#044694` (Royal Navy)
     * **Translational & Assay Strategy:** `#fecb07` (Golden Yellow)
   * Dots aligned flush to the left margin with synchronized baselines.

2. **Spacing & Visual Hierarchy**:
   * Removed hairline dividers above capabilities, "Hosted By", and "Featured Publications" for a lighter editorial feel.
   * Balanced vertical cadence between the manifesto, capabilities grid, `[ Explore Research ↓ ]` button (`pt-12 sm:pt-16`), and the `Hosted By` institutional trust lockup (`mt-16 sm:mt-20 md:mt-24`).

3. **Core Research Areas**:
   * Renamed section to **Core Research Areas**.
   * Updated section subtitle in `content/_index.md`: *"Heart transplantation, pulmonary disease, infection & immunity, and computational systems biology."*
   * Cleaned up the 4 area cards: removed the surrounding card boxes (`bg-primary/5`) so icons sit directly to the left of each title as clean, modern glyphs.

4. **Publications Portfolio & Color Harmony**:
   * Subtitle updated to: *"Translational discoveries, clinical biomarker validations, and computational frameworks."*
   * Re-used the **4 PROOF capabilities colors** across:
     * **Portfolio distribution bar chart**:
       * `#044694` — PROOF-Led Original Research
       * `#6dcff5` — Collaborative Original Research
       * `#fecb07` — Editorial & Commentary
       * `#b3d335` — Reviews & Other
     * **Filter chip legend dots**: Mapped 1-to-1 to the bar segments.
     * **Table row tag badges**: Styled `Original Research`, `Editorial & Commentary`, and `Review` with matching brand tones.

5. **HEARTBiT European Heart Journal Citation Fix**:
   * Corrected author ordering to the official manuscript author list:
     > `Shannon CP, Assadian S, Rajasekaran A, Yang C, Espín E, Lam L, Balshaw R, Seidman MA, Lai CK, Ross HJ, Hyden MP, Chih SSY, Toma M, McManus BM, Ng RT, Tebbutt SJ.`
   * Display byline: `Shannon CP, Assadian S, Rajasekaran A, et al.`
   * Synchronized across `data/research.yml`, `data/publications.yml`, and both `.ris` bibliographic files (`proof_centre_publications.ris` and `static/data/proof_centre_publications.ris`).

6. **Full-Page Exports on Desktop**:
   * High-resolution retina full-height screenshot: `PROOF-Centre-Website-FullPage.png`
   * Single continuous unpaginated PDF: `PROOF-Centre-Website-SinglePage.pdf`
   * Printable multi-page PDF: `PROOF-Centre-Website.pdf`

---

## 📋 Punchlist to Pick Up Next Session

- [ ] **1. Team Bios (`data/team.yml`)**:
  * Add full accordion bios (`bio:`, `original_bio:`) for:
    * **Dr. Scott Tebbutt** (CEO & CSO)
    * **Casey Shannon** (Director of Data Science)
    * **Sara Assadian** (Director of Clinical Research)
  * *(Current status: all 3 have clean 1-sentence `mini_bio` summaries active on the cards).*

- [ ] **2. Team Headshots (`static/images/headshots/`)**:
  * Currently only `estefania.jpg` is present.
  * Collect and drop in photos for:
    * `scott.jpg`
    * `casey.jpg`
    * `sara.jpg`
    * `chengliang.jpg`
    * `abhinav.jpg`
  * Link filenames in `data/team.yml` under `image: "images/headshots/<name>.jpg"`.

- [ ] **3. Core Research Areas Final Polish**:
  * Confirm wording of the 4 pillar descriptions and section subtitle if any further refinements are desired.

---

## 🛠 Quick Start on Home Desktop

Since this repository is inside your OneDrive directory (`.../OneDrive-Personal/Proof/projects/scratch/website`), the changes will sync automatically to your home computer.

1. Open terminal in this project directory.
2. Start the Hugo preview server:
   ```bash
   hugo server -D
   ```
3. Open `http://localhost:1313/` in your browser.
