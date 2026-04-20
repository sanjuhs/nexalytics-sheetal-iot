# Nexalytics DTX — Client Website

A single-page marketing website for **Nexalytics DTX** ("Think Digital"), a Singapore-based technology solutions company delivering AI/ML, Cybersecurity, IoT Customisation, Voice Analysis, and Industrial Robotics solutions across industries.

## Overview

This project is a responsive, modern single-page website built with vanilla HTML, CSS, and JavaScript — no frameworks or build tools required. It serves as the client-facing landing page and technology showcase for Nexalytics DTX.

## Sections

| Section | Description |
|---|---|
| **Hero** | Lightweight landing with prominent branding and call-to-action |
| **About** | Company overview, NDTX philosophy on customer well-being, vision & mission |
| **Why Us** | Four pillars — industry expertise, proven case studies, scalable security, innovation |
| **Solutions** | Core offerings including IoT, AI Vision, Digital Transformation, and accelerators |
| **Technology Hub** | Detailed tabbed interface covering AI/ML, Cybersecurity, IoT, Voice Analysis, and Industrial Robotics with case studies |
| **Industries** | Sectors served — semiconductors, healthcare, banking, electronics, energy, telecom, logistics |
| **Management Team** | Leadership and advisory overview |
| **Partners** | Ecosystem partners across cloud, IoT, AI, and security |
| **Contact** | Call-to-action linking to the main Nexalytics DTX website |

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, Grid, Flexbox, animations, responsive breakpoints (1024px, 768px, 480px)
- **JavaScript** — Intersection Observer for scroll animations, tab navigation for Technology Hub, smooth scrolling, mobile hamburger menu
- **Google Fonts** — DM Sans + Outfit

## Project Structure

```
nexalytics-sheetal-iot-client/
├── index.html                  # Main single-page website
├── README.md                   # This file
├── backup-versions/            # Historical backups
│   ├── index-apr16.html
│   └── index-apr20.html
└── newpics/                    # Brand assets and graphics
    ├── customer-painpoints-ai-workflow.png
    ├── customer-painpoints-chart.png
    ├── identifying-and-resolving-nexalytics.png
    ├── rectangle-highres-logo.png
    ├── square-higres-logo.png
    └── uncover-customer-insigths.png
```

## Running Locally

No build step required. Open `index.html` in any modern browser:

```bash
# macOS
open index.html

# Or use a local server for best results
npx serve .
```

## Browser Support

Tested for modern browsers (Chrome, Firefox, Safari, Edge). Fully responsive across desktop, tablet, and mobile viewports.

## Key Design Decisions

- **Lighter hero design** instead of all-navy to align with the overall site aesthetic
- **Prominent logo** using high-resolution brand assets in the navbar and hero
- **Customer pain points** graphics from the client integrated into the Solutions section
- **Technology Hub** with interactive tabs for each technology vertical (AI/ML, Cybersecurity, IoT, Voice, Robotics)
- **Mobile-first responsive** layout with breakpoints at 1024px, 768px, and 480px

## License

Proprietary — Nexalytics DTX. All rights reserved.
