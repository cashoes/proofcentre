# PROOF Centre Website — Session Handover & Next Steps

**Date:** September 11, 2026  
**Repository Branch:** `main` (Clean, up to date)  
**Local Preview:** `http://localhost:1313/` (`hugo server -D`)

---

## 🚀 What We Accomplished Today

1. **Footer Hosting Affiliation**:
   * Synchronized the institutional co-hosting line across `content/_index.md` and `layouts/index.html`:
     > *"Biomarkers for the Prevention of Organ Failure.<br>Co-hosted by Providence Research, the Centre for Heart Lung Innovation, and the University of British Columbia at St. Paul's Hospital, Vancouver, Canada."*

2. **Full Team Headshots Completed & Verified (`static/images/headshots/`)**:
   * All 6 team members have custom-processed, high-resolution headshots with uniform optical scale (~60% circle fill) and generous headroom (no curl/crown clipping):
     * **Dr. Scott Tebbutt** (`scott.jpg`): Sourced from uploaded photo, scaled to ~60% with seamless stone wall and ivy background extension.
     * **Casey Shannon** (`casey.jpg`): Clean, centered, balanced framing.
     * **Sara Assadian** (`sara.jpg`): Balanced circular portrait.
     * **Dr. Chengliang Yang** (`chengliang.png`): Balanced circular portrait.
     * **Dr. Abhinav Checkervarty** (`abhinav.png`): Foliage/sky extended seamlessly.
     * **Estefanía Espín** (`estefania.jpg`): Balanced circular portrait.

3. **Team Bios (`data/team.yml`)**:
   * Added full accordion bios (`bio:`) and preserved historical source bios (`original_bio:`) for all 6 members.
   * **Multi-Paragraph Rhythm**: Refactored `layouts/index.html` to render bios via `markdownify` with `space-y-3` spacing, breaking dense text into two readable, balanced paragraphs across all members.
   * **Casey Shannon**:
     * Updated `mini_bio` to establish active leadership: *"Leads computational biology and data science at the PROOF Centre, developing multi-omic pipelines to translate complex molecular data into non-invasive clinical biomarkers."*
     * Updated full `bio` to a grounded, humble academic narrative highlighting his computational lead role on HEARTBiT, open-source methods (DIABLO, enumerateblood), and international consortia (EPIC, IMPACC).
   * **Length Balance**: All bios now sit between 80 and 133 words in a uniform 2-paragraph rhythm.

4. **Updated Desktop Exports**:
   * Re-generated and saved to Desktop:
     * `PROOF-Centre-Website-FullPage.png` (Retina full-page render)
     * `PROOF-Centre-Website-SinglePage.pdf` (Continuous single-page PDF)
     * `PROOF-Centre-Website.pdf` (Standard paginated PDF)

---

## 📋 What Remains / Potential Next Steps

1. **ORCID iDs (`data/team.yml`)**:
   * The team layout contains built-in support for clickable green ORCID badges.
   * Currently, `orcid: ""` is empty for all 6 members. If desired, we can look up and populate their official ORCID iDs.

2. **Intellectual Property Section (`data/patents.yml`)**:
   * Currently lists 4 key patents (Heart transplant rejection EP/US/PCT, and COPD exacerbation US).
   * Review if any additional issued patents or active applications should be added.

3. **Publications & Research Areas Final Review**:
   * Review the 4 Core Research Areas descriptions (`data/research.yml`) and featured publications to confirm they fully reflect current grant priorities.

4. **Production Deployment & Domain Readiness**:
   * Verify production build settings (`baseURL`, minify).
   * Review meta/OpenGraph tags for social sharing.
   * Review deployment options (GitHub Pages, Netlify, Cloudflare Pages, or institutional hosting).
