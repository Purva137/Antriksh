# Antriksh

A web experience built to document India's space programme the way it deserves — not as a government portal, but as something that makes you *feel* what ISRO has actually accomplished.

Every mission documented. Every rocket dissected. Every scientist remembered by name. Forty-one satellites tracked live overhead. The full history of ISRO — from a borrowed coconut tree antenna in Thumba to a soft landing on the Moon's south pole — laid out the way it deserves to be told.

**Live site →** https://purva137.github.io/Antriksh

---

## What's Inside

| Section | Description |
|---|---|
| **Eyes on Earth** | 41 NASA & ISRO satellites rendered live in 3D using real TLE orbital data. Toggle NASA GIBS and ISRO MOSDAC imagery layers. |
| **Missions** | 30+ missions documented in depth — Chandrayaan, Mangalyaan, Gaganyaan, NavIC, Aditya-L1, and more. |
| **Timeline** | Sixty years of ISRO's journey, event by event — from 1963 to 2035. |
| **Rockets** | PSLV, GSLV, LVM3, SSLV, RLV — full technical specs, stage diagrams, and 3D viewers. |
| **Heroes** | Scientists and leaders who built India's space programme. |
| **ISRO-pedia** | Orbital mechanics, rocket propulsion, space careers — explained simply. |
| **ISS Live** | Real-time International Space Station tracker with live telemetry. |
| **Space Applications** | How ISRO satellites affect 1.4 billion people every day — agriculture, weather, navigation, disaster response. |
| **Launch Services** | ISRO's commercial launch record — 34 countries, 400+ foreign satellites. |

---

## Built With

- **Three.js** — 3D WebGL rendering, Earth, satellites, orbital trails
- **Satellite.js** — SGP4 propagator for real-time orbital mechanics
- **NASA GIBS WMS** — Live Earth imagery layers
- **ISRO MOSDAC WMS** — Ocean, rainfall, and atmospheric layers
- **CelesTrak TLE** — Live two-line element sets for all satellites
- **GSAP + ScrollTrigger** — Scroll animations
- Vanilla JS / HTML / CSS — no frameworks, no build tools

---

## Run Locally

Just open `index.html` in a browser — or use any static server:

```bash
npx serve .
```

---

*Built by Purva Patel*
