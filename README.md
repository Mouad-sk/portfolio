# Cybersecurity Engineer & SOC Analyst Portfolio

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Live Site](https://img.shields.io/badge/Live_Site-00e5ff?style=for-the-badge&logo=githubpages&logoColor=black)](https://mouad-sk.github.io/portfolio/)

>  **Live Portfolio:** [mouad-sk.github.io/portfolio](https://mouad-sk.github.io/portfolio/)

A modern, high-performance personal portfolio for a Final-Year IT Security Engineering Student and SOC Analyst. Designed with a **SOC Command Center / High-Tech Cyber-Dark** aesthetic, complete with real-time bilingual capabilities, ambient particles, interactive terminals, and animated UI micro-interactions.

---

##  Key Features

### 1.  SOC Command Center Aesthetic
- **Midnight Obsidian Dark Theme:** Deep palette (`#090c12`) tailored for cybersecurity and SOC profiles.
- **Electric Cyan & Emerald Accents:** High-contrast glowing highlights (`#00e5ff`, `#10b981`) paired with sleek dark glass cards.
- **Typography:** Modern pairing using **Space Grotesk** for headings, **Outfit** for body text, and **JetBrains Mono** for cyber telemetry and code.

### 2.  Real-Time Bilingual Toggle (EN / FR)
- Instant, client-side language switching between **English (EN 🇬🇧)** and **French (FR 🇫🇷)** without page reloads.
- Seamless translation across all sections, project details, badges, and form placeholders.
- Automatic persistence using `localStorage`.

### 3.  Dynamic Navigation with Sliding Glow Indicator
- **Sliding Indicator Line:** A fluid, physics-based cyan glowing bar (`cubic-bezier(0.22, 1, 0.36, 1)`) that tracks the active navigation tab.
- **Integrated Scrollspy:** Automatically glides underneath the relevant section as the user scrolls.
- **Magnetic Hover Preview:** Interactively tracks hover states and gracefully returns to the current active section on mouse leave.
- **Mobile Responsive:** Seamlessly transforms into a vertical accent highlight inside the collapsed mobile menu.

### 4.  Ambient Particle Canvas Engine
- Lightweight 2D canvas particle simulation rendering subtle, gentle falling celestial snow dust.
- Features soft sinusoidal swaying, delicate opacity modulation, and multi-resolution responsive canvas resizing.

### 5.  Interactive Cyber Terminal Widget
- Simulated SOC terminal output featuring real-time telemetry, mock security tool verification commands (`./verify_pipeline.sh`), and dynamic system stats.


---

##  Technologies & Stack

| Technology | Purpose |
|:---|:---|
| **HTML5** | Semantic structure, accessibility (ARIA), and SEO meta tags |
| **Vanilla CSS3** | Custom design system, CSS Grid/Flexbox, custom properties, animations |
| **Vanilla JavaScript (ES6+)** | State management, bilingual switching, canvas physics, DOM manipulation |
| **Canvas 2D API** | Ambient drifting particle system |
| **Bootstrap 5.3.2** | Responsive grid system, collapse navigation, and accessible modals |
| **Font Awesome 6.5.1** | Vector UI iconography |
| **Google Fonts** | Space Grotesk, Outfit, and JetBrains Mono |

---

##  Repository Structure

```text
portfolio/
├── assets/
│   └── cv/                      # Downloadable PDF CVs (EN & FR)
│       ├── CV_SAKHI_MOUAD_EN.pdf
│       └── CV_SAKHI_MOUAD_FR.pdf
├── index.html                   # Core single-page application & style architecture
└── README.md                    # Project documentation
```

---

## Getting Started

### Local Preview
No build tools, bundlers, or package managers required. Opens directly in any modern browser:

1. Clone the repository:
   ```bash
   git clone https://github.com/Mouad-sk/portfolio.git
   ```
2. Navigate to the project directory:
   ```bash
   cd portfolio
   ```
3. Open `index.html` in your browser (or use VS Code Live Server).

---

##  License
This project is open-source and available under the [MIT License](LICENSE).
