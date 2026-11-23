# Neopolis - Smart City Web Platform

A modern, responsive civic-tech web portal for the intelligent metropolis of **Neopolis**, built exclusively using pure **HTML5** and **CSS3** (`index.html` and `styles.css`) with zero external JavaScript dependencies.

🔗 **Live Demo (GitHub Pages)**: [https://balamanidharyella-afk.github.io/smart-city-website/](https://balamanidharyella-afk.github.io/smart-city-website/)  
📦 **GitHub Repository**: [https://github.com/balamanidharyella-afk/smart-city-website](https://github.com/balamanidharyella-afk/smart-city-website)

---

## 🌆 Overview & Vision

Neopolis represents next-generation urban living powered by autonomous infrastructure, 100% clean energy microgrids, real-time IoT environmental telemetry, and zero-latency civic digital governance for 2.45 million connected residents.

---

## 🚀 Key Sections & Architecture

### 1. **Live Civic Announcement Ticker**
- Real-time notification strip displaying transit network status, Air Quality Index (AQI 14 &bull; Pristine), and microgrid telemetry.

### 2. **Navigation Bar**
- Sticky glassmorphic header with backdrop blur.
- High-visibility **Emergency 911** fast-dial shortcut.
- Pure CSS mobile hamburger drawer (no JS required, utilizing the accessible checkbox hack).

### 3. **Hero Section**
- Futuristic cyber-grid backdrop with glowing radial light orbs.
- Real-time civic search input with quick-query recommendation pills (Metro Pass, EV Hyperchargers, Emergency Dispatch).
- Direct call-to-action buttons for Public Services, Emergency Assistance, and Key Landmarks.

### 4. **City Statistics Dashboard**
- Dashboard metrics bar with real-time indicators:
  - **86.4% Renewable Grid Energy** (Solar, tidal microgrids & solid-state storage)
  - **99.2% Public 6G & Wi-Fi Mesh** (Low-latency municipal connectivity)
  - **44.5% Urban Green Canopy** (Biophilic forests, sponge city bioswales)
  - **2.45M Connected Citizens** (Active digital IDs, 99.4% satisfaction)
- Secondary telemetry bar: AQI, Average Commute Times, Water Purity, and EV Charger status.

### 5. **Public Services Grid**
- Responsive CSS Grid featuring high-detail civic service cards with inline SVG iconography:
  - **Autonomous Smart Transportation** (Maglev, autonomous EV shuttles, contactless ticketing)
  - **Connected Healthcare & Trauma Care** (ICU telemetry, 4.2-min dispatch, drone defibrillators)
  - **Digital Education & Future Labs** (STEM campuses, open quantum computing labs)
  - **Autonomous Eco-Utilities & Water** (Pneumatic waste sorting, greywater reclamation)
  - **100% Digital Civic Permits & Registry** (Instant AI building approvals, open treasury)
  - **Intelligent Public Safety & Alerts** (Seismic early warning, 2,800 smart beacon poles)

### 6. **Important Locations & Civic Landmarks**
- Visual showcase of municipal headquarters, tech corridors, transit terminals, and biospheres:
  - Neopolis Civic Tower & Municipal Forum (District 1)
  - Quantum Horizon Cyberpark (District 4)
  - Grand Multimodal Maglev Terminal (District 3)
  - Biophilic Botanical Biosphere (District 2)
  - Apex Central Medical Complex (District 1)
  - Lumina Civic Arts & Holographic Pavilion (District 5)
- Includes district tags, public operating hours, and physical addresses.

### 7. **Emergency Command & Citizen Dispatch**
- High-contrast, high-visibility emergency section with glowing warning pulse ring.
- One-touch direct dialing cards with `tel:` protocols:
  - **Police & Security Dispatch**: `911 / 100`
  - **Emergency Medical & Trauma**: `108 / 911`
  - **Fire & Rescue Service**: `101 / 911`
  - **Disaster & Crisis Helpline**: `112 / 1077`
- **Citizen Quick Safety Protocols & Action Guides**:
  1. Seismic & Structural Tremors (Drop, Cover, Hold)
  2. Severe Storm & Flash Surge (Automated flood gates)
  3. Automated AED & First Aid (150m proximity array)
  4. Municipal Digital Safe Zones (72h+ microgrid islanding)

### 8. **Civic Portals Fast-Access**
- Instant gateway chips for Transit Passes, Smart Meter Power Bills, Building Permits, Participatory Budgeting, and Hospital Bed Triage.

### 9. **Civic Footer**
- Municipal headquarters contact info, official citizen inquiry email, 311 hotline.
- Weekly Citizen Dispatch newsletter signup form.
- Organized columns for Portals, Governance, and Open Data Transparency.
- WCAG 2.1 AAA accessibility statement and smooth "Back to top" link.

---

## 🎨 Design System & Color Palette

| Token | Hex / Value | Purpose |
|---|---|---|
| `--bg-base` | `#070e1e` | Deep Space Navy Background |
| `--bg-surface` | `#0d172e` | Dark Surface Panels |
| `--bg-card` | `rgba(14, 25, 52, 0.75)` | Glassmorphic Card Surfaces |
| `--cyan-primary` | `#00f0ff` | Futuristic Accent & Key Highlights |
| `--sky-primary` | `#38bdf8` | Secondary Sky Blue Accent |
| `--green-eco` | `#10b981` | Sustainability & Status Badges |
| `--red-emergency`| `#ef4444` | High-Alert Hotlines & Emergency Accents |
| `--text-primary` | `#f8fafc` | Crisp Heading & Body Text |
| `--text-secondary`| `#94a3b8` | Supporting Descriptions & Subtitles |

---

## 📱 Responsiveness & Accessibility

- **Layout**: CSS Grid (`repeat(auto-fit, minmax(...))` and explicit breakpoints) + CSS Flexbox.
- **Breakpoints**:
  - `> 1024px`: Desktop multi-column layouts (3-4 columns).
  - `769px - 1024px`: Tablet layout (2 columns).
  - `≤ 768px`: Mobile layout (single-column stack, mobile hamburger navigation drawer).
  - `≤ 480px`: Compact mobile optimizations.
- **Accessibility**:
  - Skip-to-content accessible link.
  - Semantic HTML5 structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`).
  - WCAG AAA contrast ratio compliance.
  - Native `:focus-visible` ring indicators.
  - Respects `@media (prefers-reduced-motion: reduce)` for users sensitive to motion.

---

## 💻 How to View Locally

Simply open `index.html` in any modern web browser:
```bash
# On Windows
start index.html

# Or via Python local server
python -m http.server 8080
# Open http://localhost:8080 in your browser
```

---

## 📄 License
Released under the MIT License for open civic-tech development.
