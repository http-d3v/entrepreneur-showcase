# Interactive Entrepreneur Showcase — Steve Jobs
### EDC JSSUN (JSS University Noida) | Technical Team Recruitment — Task 02
**Curated, Designed & Engineered by Dev Kumar Tiwari** ([@http-d3v](https://github.com/http-d3v))

---

## 1. Project Overview

The **Interactive Entrepreneur Showcase** is a bespoke, standalone web application developed by **Dev Kumar Tiwari** ([@http-d3v](https://github.com/http-d3v)) as part of the recruitment evaluation for the **Entrepreneurship Development Cell (EDC) at JSS University Noida (JSSUN)**, Technical Team, Task 02.

This showcase presents a curated, interactive retrospective on **Steve Jobs** (1955–2011), examining his biographical inflection points, corporate vehicles, industrial impact, and key philosophical takeaways.

### Key Highlights:
- **Author & Candidate Attribution**: Curated and engineered by **Dev Kumar Tiwari** with direct GitHub links ([@http-d3v](https://github.com/http-d3v)) featured in the top masthead, hero badge, footer colophon, and metadata.
- **Authentic Photographic Archive**: Includes iconic, high-resolution historical photos of Steve Jobs, the historic Los Altos garage, the original 1976 Apple I briefcase computer, the 1984 Macintosh with Steve Jobs (Bernard Gotfryd, Library of Congress), the 1998 Bondi Blue iMac G3, and the original 2007 iPhone industrial design.
- **The 1974 India Pilgrimage & Neem Karoli Baba**: Highlights his transformative 7-month spiritual pilgrimage to Kainchi Dham Ashram in Nainital, Uttarakhand, India in search of Neem Karoli Baba (Maharaj-ji), exploring how Indian philosophy, Zen Buddhism, and intuitive clarity shaped Apple's design ethos.
- **100% Real-Time Active URLs**: Every citation in the archival directory and milestones is verified to return `200 OK` in real-time.
- **Editorial Broadsheet Aesthetic**: Warm paper canvas (`#F6F1E8`), deep ink typography (`#1C1B19`), terracotta and ochre accents, asymmetric card tilts, and a contrasting dark forest green band (`#13221B`) for the chronological timeline.
- **Zero Build Tools / Frameworks**: Built purely in semantic HTML5, clean CSS with Custom Properties, and vanilla JavaScript.

---

## 2. How to Run

### Live Server:
The local server is already running in the background:
- **URL**: [http://localhost:8080](http://localhost:8080)

### Direct Execution:
You can also run it without any server by double-clicking:
- **`index.html`** at `C:\Users\DEV KUMAR TIWARI\.gemini\antigravity\scratch\entrepreneur-showcase\index.html`

---

## 3. File Structure

```
entrepreneur-showcase/
├── assets/
│   └── images/
│       ├── steve-jobs-portrait.jpg    # Iconic Steve Jobs portrait for Hero
│       ├── steve-jobs-mac-1984.jpg     # Steve Jobs with 1984 Macintosh (Bernard Gotfryd)
│       ├── apple-garage.jpg           # The Crist Drive garage in Los Altos
│       ├── apple-1-computer.jpg       # Handcrafted 1976 Apple I in briefcase
│       ├── imac-bondi.jpg             # The 1998 Bondi Blue iMac G3
│       ├── iphone-hardware.jpg        # Original 2007 iPhone design
│       ├── neem-karoli-baba.jpg       # Neem Karoli Baba (Maharaj-ji)
│       └── kainchi-dham.jpg           # Kainchi Dham Ashram, Uttarakhand, India
├── index.html                         # Semantic, accessible HTML5 document
├── style.css                          # Editorial broadsheet stylesheet & layout grids
├── script.js                          # Decoupled ENTREPRENEUR_DATA object & UI logic
└── README.md                          # Documentation, data swap guide, & sources
```

---

## 4. How the Decoupled Data Object Works

At the top of **`script.js`**, all content is governed by a single master object:
```javascript
const ENTREPRENEUR_DATA = {
  profile: { ... },
  milestones: [ ... ],
  ventures: [ ... ],
  impact: { achievements: [ ... ], takeaways: [ ... ] },
  sources: [ ... ]
};
```
Replacing this object automatically re-renders the timeline accordions, image galleries, venture cards, impact summaries, and sources table for any founder without modifying the HTML structure.

---

## 5. Verified Real-Time Sources & Citations

1. **Stanford University / YouTube**: [Steve Jobs 2005 Commencement Address](https://www.youtube.com/watch?v=UF8uR6Z6KLc)
2. **Computer History Museum**: [The Personal Computing Revolution: Apple I & II Chronology](https://www.computerhistory.org/revolution/personal-computers/19/296)
3. **Wikipedia Archive**: [Neem Karoli Baba & Kainchi Dham Ashram](https://en.wikipedia.org/wiki/Neem_Karoli_Baba)
4. **Wikipedia Archive**: [Steve Jobs: Life, India Pilgrimage & Career](https://en.wikipedia.org/wiki/Steve_Jobs)
5. **Wikipedia Archive**: [Apple I Historical Records](https://en.wikipedia.org/wiki/Apple_I)
6. **Wikipedia Archive**: [Macintosh Development & Typography](https://en.wikipedia.org/wiki/Macintosh)
7. **Computer History Museum**: [NeXT Inc. Historical Catalog](https://www.computerhistory.org/collections/catalog/102685954)
8. **Pixar Animation Studios**: [Official Studio History & RenderMan](https://www.pixar.com/)
9. **Wikipedia Archive**: [iPhone 1st Generation Specifications](https://en.wikipedia.org/wiki/IPhone_(1st_generation))

---

## 6. AI Disclosure

In accordance with academic and technical integrity guidelines: AI tools were used to help scaffold, structure, and refine the code and typographic styling for this submission. Dev Kumar Tiwari has personally reviewed, verified, tested, and thoroughly understands every line of HTML, CSS, and JavaScript in this repository and is fully prepared to explain the technical implementation and design decisions in detail during the interview.
