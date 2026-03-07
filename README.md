# Thanadol — Personal & Academic Website

A single-page portfolio and academic CV for **Thanadol Sutantiwanichkul**, PhD student in Biotechnology (DDLS) at KTH Royal Institute of Technology / SciLifeLab.

## Live site

**https://thanadol-git.github.io**

---

## What’s on the website

- **Personal information** — Contact details, address, LinkedIn, GitHub  
- **Education** — KTH, Mahidol University, Mahidol Wittayanusorn School  
- **Teaching** — Courses (CB2030, CB2080, CB2110)  
- **Current positions** — Swedish Proteomics Early Career Scientist (core member), DDLS Student Council (co-chair)  
- **Scholarship** — SciLifeLab-EMBL, SISS, IJRA, SIM-Premier, JSTP, and others  
- **Experience** — PRIDE/EMBL-EBI, Human Protein Atlas, A05 diagnostics, SciLifeLab, KI, BIOTEC, ECDD, Sussex, XLAB, etc.  
- **Publication** — Papers with direct links to DOIs  
- **Conference** — BMB Thailand, GYSS, TBRN, Benzon Symposium, and others  
- **Activity** — EMBL-EBI exchange, summer schools, FEBS course, YTSA, ISSF, and more  
- **Map** — Interactive world map of conference and activity locations (Leaflet)  
- **SciLifeLab** — Embedded Google Map for SciLifeLab  

The page includes a **Download CV** button that opens a print-friendly view of the main sections (excluding the maps).

## Tech

- Single **HTML** file with embedded **CSS** and **JavaScript**  
- [Leaflet](https://leafletjs.com/) for the world map  
- Google Maps embed for SciLifeLab  
- No build step; open `index.html` in a browser or use any static file server  

## Run locally

```bash
# Option 1: open in browser
xdg-open index.html   # Linux

# Option 2: local server (e.g. Python)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## Repository

- **GitHub:** [thanadol-git/thanadol-git.github.io](https://github.com/thanadol-git/thanadol-git.github.io)  
- **Hosting:** GitHub Pages (site served from the default branch).
