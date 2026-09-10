# Stalwart Engineering & Contracting

A modern, high-performance static website for **Stalwart Engineering & Contracting (Pty) Ltd** — delivering multidisciplinary electrical, mechanical, solar, ICT, plumbing, and plant contracting solutions across South Africa.

Built with clean, vanilla HTML5, CSS3, and JavaScript (ES6+). Zero dependencies, zero build steps, and zero compilation required.

---

## 🌟 Key Features & Pages

- **Header & Navigation**: Dynamic responsive navigation (`Home` → `About us` → `Services` → `Projects` → `Contact us`) injected via `main.js`.
- **Home Page (`index.html`)**:
  - Hero video background with brand identity tags and grading credentials.
  - 36-image continuous smooth-scrolling solution carousel (`180s` glide).
  - 6 multidisciplinary service cards overview.
  - Trusted client delivery grid featuring Eskom, Public Works, Legal Aid SA, SAPS, City of Joburg, Department of Defence, and Gauteng Education.
  - Interactive site diagnostic hub tab system for fault location, preventative maintenance, site reliability, and compliance.
  - Projects, compliance & insights showcase section.
  - 10-column interactive image wall.
- **Services Page (`services.html`)**:
  - 4 Focus Pillars: *Locate Critical Faults*, *Preventative Maintenance*, *Scale Site Reliability*, and *Compliance & Handover*.
  - 9 detailed service categories with full bullet points, Cloudinary cover imagery, and direct quote request CTAs:
    1. `01 — electrical`: Electrical Engineering, Contracting & Maintenance
    2. `02 — renewable`: Renewable Energy & Solar
    3. `03 — ict`: ICT, Networking & Fibre Infrastructure
    4. `04 — cctv`: CCTV, Security & Site Systems
    5. `05 — mechanical`: Mechanical, Auto Electrical Services
    6. `06 — plumbing`: Plumbing
    7. `07 — plant`: Plant, Equipment & Support Services
    8. `08 — supply`: Supply & Delivery
    9. `09 — meter`: Meter Reading
  - Certified & Compliant banner (CIDB 10246207, ECA, CSD, B-BBEE).
- **About Page (`about.html`)**:
  - Company overview, mission, vision, and core values (*Reliability*, *Loyalty*, *Hard Work*, *Integrity*).
  - 100% Black-Owned & Directed capacity panel.
  - Office locations across Gauteng (Clayville & Dawn Park) and Limpopo (Louis Trichardt).
- **Projects Page (`projects.html`)**:
  - Categorized project filtering (All, Electrical, Solar, ICT & CCTV).
  - Accordion detail expansion for project descriptions.
- **Contact Page (`contact.html`)**:
  - Interactive quote request form generating formatted mailto requests.
  - Direct call and email actions, office addresses, and response time commitments.

---

## 🚀 Running Locally

Because the project is built with pure web standards, no `npm install` or build step is needed:

1. Clone or download this repository.
2. Open `index.html` directly in any web browser, OR serve with any local HTTP server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node (npx)
   npx serve .
   ```

---

## 📁 File Structure

```text
stalwart-site/
├── index.html        # Home page
├── about.html        # About us page
├── services.html     # Services page
├── projects.html     # Projects page
├── contact.html      # Contact us page
├── styles.css        # Central stylesheet & responsive layout rules
├── main.js          # Shared scripts, dynamic header/footer, carousel & tabs
├── public/
│   ├── clients/      # Client brand logos (Eskom, SAPS, Dept of Defence, etc.)
│   ├── favicon.svg   # Favicon icon
│   └── icons.svg     # SVG icon set
└── README.md         # Project documentation
```

---

## 📄 License & Ownership

© Stalwart Engineering & Contracting (Pty) Ltd since 2020. All rights reserved.
- **Reg**: 2020/543427/07
- **CIDB**: 10246207 (PE 1GB, 2EB, 1EP, 1SO, 2ME)
- **CSD**: MAAA0954115
- **ECA & PIRB Certified**

