<div align="center">

# ✦ VANTIS AIR CARGO
## VAMSYS VA MANAGEMENT ARCHITECTURE — Fleet Intelligence Platform
### B777F Interstellar Themed Fleet Registry · 31 Frames · 18 Emblems · 3 Series

![Version](https://img.shields.io/badge/VAMSYS-v2.6.0-7c3aed?style=for-the-badge)
![Fleet](https://img.shields.io/badge/FLEET-31%20×%20B777F-22d3ee?style=for-the-badge)
![Emblems](https://img.shields.io/badge/EMBLEMS-18%20VARIANTS-f472b6?style=for-the-badge)
![Status](https://img.shields.io/badge/STATUS-OPERATIONAL-10b981?style=for-the-badge)
![Host](https://img.shields.io/badge/HOST-GITHUB%20PAGES-181717?style=for-the-badge&logo=github)
![Classification](https://img.shields.io/badge/CLASSIFICATION-INTERNAL-f59e0b?style=for-the-badge)

---

*A self-contained, single-file web application for managing the VANTIS B777F interstellar-themed cargo fleet.*
*Zero dependencies. No build step. Deploy anywhere.*

**Live Platform → `https://bluecreek206.github.io/vantis-fleet-registry/`**

</div>

---

## 📡 Overview

**VAMSYS** (VANTIS Aircraft Management System) is the internal fleet intelligence platform for **VANTIS Air Cargo's** 31-frame Boeing 777F interstellar-themed fleet. It provides a fully interactive registry, HUD-style fleet cards, and an 18-variant tail emblem codex — all delivered as a **single zero-dependency HTML file** deployable to any static host in minutes.

The platform covers all **six active fleet classes** — from the founding APAC trunk frames to the newest STRATOS expansion frames — with complete ICAO data, operational role tags, status tracking, and interstellar star-name designations. An additional **12 reserve and orbital emblems** are pre-designed for future fleet expansion through VAN090.

---

## ✨ Platform Features

| Module | Description |
|---|---|
| 🗄 **Fleet Registry** | Sortable, filterable table of all 31 B777F frames with ICAO codes, MTOW, range, roles, and live status |
| 🪪 **VAMSYS Fleet Cards** | HUD-style card grid with expandable technical specs, VAMSYS IDs, and operational tags |
| 🎖 **Emblem Codex** | 18 SVG tail emblem variants across 3 series with lore, class assignments, and animated artwork |
| 🔐 **Access Gate** | Full-screen VANTIS-branded login authentication before any fleet data is accessible |
| 🌐 **API Data Layer** | Toggle between local data and a live REST API endpoint with configurable polling interval |
| 🖨 **Print Export** | Scoped, layout-configurable print-ready fleet card output with CSS print stylesheet |
| ⬇ **HTML Export** | In-browser download of the full self-contained application file |
| ⚙ **API Config Panel** | Slide-in panel for configuring remote data source, poll interval, and API key |
| 💾 **Session Persistence** | `localStorage` retention of filters, view state, and API config across sessions |
| 🔒 **Session Auth** | `sessionStorage` login flag — re-authentication required on each new tab/session |

---

## 🛸 Fleet Registry — Current Status

```
TOTAL FRAMES : 31 × Boeing 777F
ACTIVE       : 24 frames
MAINTENANCE  :  4 frames
STANDBY      :  2 frames
IN DELIVERY  :  1 frame
```

### Fleet Classes

```
CLASS          FRAMES       REGION                  EMBLEM            ENTRY
─────────────────────────────────────────────────────────────────────────────
FOUNDING       VAN001–005   APAC Trunk              Stellar Crown     2018–19
EXPANSION I    VAN006–010   Transatlantic & MEA     Nebula Arc        2020–21
EXPANSION II   VAN011–015   E-Commerce Express      Comet Strike      2021–22
MERIDIAN       VAN016–020   Pharma & High-Value     Meridian Cross    2022–23
NOVA           VAN021–025   Perishable & Cold Chain Nova Burst        2023–24
APEX           VAN026–030   Full Freighter Global   Apex Vector       2024–25
STRATOS        VAN031       Pacific Ridge           Pulsar Ring       2026
```

### Sample Registry Entries

| Frame | Name | Reg | Class | Role | Status |
|---|---|---|---|---|---|
| VAN001 | ARCTURUS | VX-ANT001 | FOUNDING | APAC TRUNK | 🟢 ACTIVE |
| VAN009 | CAPELLA | VX-ANT009 | EXPANSION I | MEA CORE | 🟡 MAINTENANCE |
| VAN016 | ACRUX | VX-ANT016 | MERIDIAN | PHARMA COLD | 🟢 ACTIVE |
| VAN023 | TEJAT | VX-ANT023 | NOVA | PERISHABLE REG | ⚫ STANDBY |
| VAN030 | TUREIS | VX-ANT030 | APEX | FULL FREIGHTER | 🟣 IN DELIVERY |
| VAN031 | CENTAURI | VX-ANT031 | STRATOS | PACIFIC RIDGE | 🟢 ACTIVE |

---

## 🎖 Emblem Codex — 18 Variants · 3 Series

### Series I — Active Fleet (VAN001–VAN030)

| # | Emblem | Class | Frames | Design |
|---|---|---|---|---|
| 1 | **Stellar Crown** | FOUNDING | VAN001–005 | Five-star arc over the VANTIS V in gold and violet |
| 2 | **Nebula Arc** | EXPANSION I | VAN006–010 | Violet-blue nebula wisps sweeping a hemisphere arc |
| 3 | **Comet Strike** | EXPANSION II | VAN011–015 | Cyan comet with violet trailing glow — speed forward |
| 4 | **Meridian Cross** | MERIDIAN | VAN016–020 | Precision crosshair with white diamond quadrant accents |
| 5 | **Nova Burst** | NOVA | VAN021–025 | Eight-point crystalline icy burst in cyan and violet |
| 6 | **Apex Vector** | APEX | VAN026–030 | Clean white forward chevron with integrated V tip |

### Series II — Reserve (VAN031–VAN060)

| # | Emblem | Class | Reserved | Design |
|---|---|---|---|---|
| 7 | **Pulsar Ring** | STRATOS | VAN031–035 | Five concentric pulsing rings with animated cyan markers |
| 8 | **Event Horizon** | ABYSS | VAN036–040 | Black void circle with gravitational lensing arcs |
| 9 | **Solar Flare** | CORONA | VAN041–045 | Amber solar disc with violet-tipped corona prominence arcs |
| 10 | **Void Lance** | OBSIDIAN | VAN046–050 | White diamond lance with violet electrical discharge arcs |
| 11 | **Quasar Beam** | LUMINARY | VAN051–055 | Dual cyan crossbeams converging on a bright white core |
| 12 | **Dark Matter** | PHANTOM | VAN056–060 | Orbiting shards around a glowing V — **CLASSIFIED** |

### Series III — Orbital Deep Expansion (VAN061–VAN090)

| # | Emblem | Class | Reserved | Design |
|---|---|---|---|---|
| 13 | **Binary Star** | DUALITY | VAN061–065 | Two orbiting stars with animated mass-transfer stream |
| 14 | **Ion Trail** | VELOCITY | VAN066–070 | 7 stacked diagonal ion ellipses fading emerald to violet |
| 15 | **Gravity Well** | TITAN | VAN071–075 | Spacetime curvature grid warping toward a silver singularity |
| 16 | **Aurora Veil** | PRISM | VAN076–080 | Three polar ribbon curtains with shimmering aurora animation |
| 17 | **Neutron Shield** | BASTION | VAN081–085 | Triple nested hexagonal lattice with pulsing orange core |
| 18 | **Warp Gate** | NEXUS | VAN086–090 | Spinning vortex inside a fuchsia gate ring — **APEX CLASSIFIED** |

---

## 🔐 Authentication

VAMSYS includes a full-screen VANTIS-branded login gate. Default credentials:

| Field | Default Value | Where to Change |
|---|---|---|
| **Operator ID** | `VANTIS-OPS` | Search `DEFAULT_CREDENTIALS` in `index.html` |
| **Access Code** | `VX2026` | Search `DEFAULT_CREDENTIALS` in `index.html` |

> **Note:** Authentication is session-scoped via `sessionStorage`. Closing the tab requires re-login. Credentials are stored client-side — supplement with server-side auth (Cloudflare Access, Netlify Identity, or HTTP Basic Auth) for production environments handling sensitive data.

---

## 🌐 API Integration

VAMSYS supports live REST API data sources via the built-in **⚙ API CONFIG** panel.

**To configure:**
1. Click **`⚙ API CONFIG`** in the platform header (top right)
2. Switch mode to **`REMOTE API`**
3. Enter your endpoint URL and optional API key
4. Set poll interval (default: 30 seconds)
5. Click **`TEST CONNECTION`** → **`APPLY & RELOAD`**

**Expected JSON response schema:**

```json
[
  {
    "frameId": "VAN031",
    "name": "CENTAURI",
    "registration": "VX-ANT031",
    "type": "B77F",
    "class": "STRATOS",
    "mtow": "347,810 KG",
    "range": "9,045 KM",
    "role": "PACIFIC RIDGE",
    "status": "ACTIVE",
    "emblem": "PULSAR RING",
    "entryYear": 2026,
    "region": "PACIFIC",
    "vamsysId": "VMS-031-B77F-ANT"
  }
]
```

API configuration is persisted to `localStorage` and auto-applied on next page load. A **LIVE / LOCAL** status pill in the header reflects the current data source.

---

## ➕ Adding Aircraft

### Method 1 — Edit index.html Directly

1. Open `index.html` in any text editor
2. Press `Ctrl + F` → search for `VAN031` (the last frame)
3. Add a comma after the closing `}` and paste a new aircraft object:

```javascript
{
  frameId: "VAN032",
  name: "SAIPH",
  registration: "VX-ANT032",
  type: "B77F",
  class: "STRATOS",
  mtow: "347,810 KG",
  range: "9,045 KM",
  role: "ATLANTIC EXPRESS",
  status: "ACTIVE",
  emblem: "PULSAR RING",
  entryYear: 2026,
  region: "ATLANTIC",
  vamsysId: "VMS-032-B77F-ANT"
}
```

4. Update the frame count references (`31 FRAMES` → `32 FRAMES`)
5. Save and re-upload to GitHub

### Method 2 — Use the API Data Layer

Connect VAMSYS to a live JSON endpoint and add aircraft directly to your database — no HTML editing required. The platform auto-updates on the configured poll interval.

---

## 🖨 Print Export

Click **`🖨 PRINT FLEET CARDS`** in the filter bar.

| Option | Choices |
|---|---|
| **Scope** | All 31 frames / Current filter selection / Active frames only |
| **Layout** | 2 cards per page / 4 cards per page |
| **Include** | Emblem designation / Operational tags / VAMSYS ID / Full tech specs |

Print output renders on a clean white background with VANTIS header, status badges, and automatic CSS page numbering.

---

## 🚀 Deployment

### GitHub Pages (This Repository)

This file is deployed via **GitHub Pages** — no server, no build step, no cost.

```
Repository:  github.com/YOUR-USERNAME/vantis-vamsys
Branch:      main / (root)
Entry file:  index.html
Live URL:    https://YOUR-USERNAME.github.io/vantis-vamsys/
```

**To update the platform:**
1. Export the updated `VANTIS-VAMSYS-Fleet-v2.6.0.html` from inside the app using **`⬇ EXPORT HTML`**
2. Rename it to `index.html`
3. Go to this repository → **`Add file`** → **`Upload files`**
4. Upload `index.html` → **`Commit changes`**
5. Live site updates within ~30 seconds ✅

---

### Other Static Hosts

| Platform | Method |
|---|---|
| **Netlify** | Drag `index.html` into the Netlify drop zone |
| **Vercel** | `vercel --prod` or drag-and-drop via dashboard |
| **AWS S3** | Upload to bucket → enable Static Website Hosting |
| **Azure Static Web Apps** | Upload via portal or `az staticwebapp` CLI |
| **Apache / Nginx** | Copy `index.html` to your `public_html` or `www` root |
| **cPanel** | Upload via File Manager to `public_html/` |

---

## 🛠 Technical Specifications

```
Platform      :  Single-file HTML5 Web Application
Version       :  VAMSYS v2.6.0
Dependencies  :  None (zero external scripts, zero npm packages)
Fonts         :  Rajdhani · Space Mono (Google Fonts CDN)
Storage       :  localStorage (API config, filters, view state)
               :  sessionStorage (authentication session)
Data layer    :  Hardcoded JS array OR live REST API
Fleet frames  :  31 × Boeing 777F (VAN001–VAN031)
Emblems       :  18 variants across 3 series
File size     :  ~90 KB (fully self-contained, all SVG inline)
Browsers      :  Chrome 90+ · Firefox 88+ · Safari 14+ · Edge 90+
Responsive    :  1-col mobile · 2-col tablet · 3-col desktop
Print         :  @media print stylesheet included
Favicon       :  Inline SVG data URI (no external file)
```

---

## 📁 Repository Structure

```
vantis-vamsys/
│
├── index.html     ← VANTIS VAMSYS — complete self-contained application
└── README.md      ← This file
```

---

## 📋 Changelog

### v2.6.0 — 2026-06-22
- ✅ Added VAN031 CENTAURI — STRATOS class / PACIFIC RIDGE role / PULSAR RING emblem
- ✅ Expanded Emblem Codex from 12 to 18 variants (Series III added)
- ✅ Series III emblems: Binary Star · Ion Trail · Gravity Well · Aurora Veil · Neutron Shield · Warp Gate
- ✅ Added full-screen VANTIS login / access gate with shake animation
- ✅ Added ⚙ API CONFIG slide-in panel with live REST API integration and auto-polling
- ✅ Added 🖨 PRINT FLEET CARDS modal with scoped print-ready export
- ✅ Added ⬇ EXPORT HTML in-browser file download
- ✅ Added localStorage persistence for filters, view state, and API config
- ✅ Added sessionStorage authentication session management
- ✅ Added STRATOS class to filter dropdown (teal #06b6d4)
- ✅ Pulsar Ring Codex updated: 1 ACTIVE · 4 REMAINING
- ✅ NEXUS emblem — animated fuchsia border · APEX CLASSIFIED designation · lore redaction
- ✅ PHANTOM emblem — CLASSIFIED designation · lore redaction bars

### v2.5.0 — Initial Release
- ✅ VAN001–VAN030 full B777F fleet registry (30 frames)
- ✅ Three-view platform: Registry · VAMSYS Cards · Emblem Codex
- ✅ Six fleet classes with interstellar star-name designations
- ✅ Twelve SVG tail emblem variants across Series I and Series II
- ✅ Live clock, dynamic filter pills, row-click card navigation
- ✅ Violet-graphite design language with HUD-style data readouts

---

## ⚖ License & Classification

```
CLASSIFICATION  :  INTERNAL — AIRGRID INTELLIGENCE PLATFORM
OPERATOR        :  VANTIS AIR CARGO
DIVISION        :  FLEET INTELLIGENCE DIVISION
PLATFORM        :  VAMSYS v2.6.0
COMPILED        :  2026-06-22
FRAMES          :  31 × Boeing 777F
EMBLEMS         :  18 Variants · 3 Series

© 2026 VANTIS INTERSTELLAR OPERATIONS — ALL RIGHTS RESERVED
This software is proprietary to VANTIS Air Cargo.
Unauthorised distribution, reproduction, or modification is prohibited.
```

---

<div align="center">

**VAMSYS · VANTIS AIR CARGO · FLEET INTELLIGENCE DIVISION**

FLY SMART. FLY HEAVY. FLY VANTIS

*31 Frames. Three Emblem Series. One Platform.*

`https://YOUR-USERNAME.github.io/vantis-fleet-registry/`

</div>

