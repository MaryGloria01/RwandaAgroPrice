#  RwandaAgroPrice — Ibiciro by'Isoko

> **Live Market Price Dashboard for Smallholder Farmers in Rwanda**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=for-the-badge)](https://marygloria01.github.io/RwandaAgroPrice/index.html)
[![HTML](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JavaScript-orange?style=for-the-badge)]()
[![University of Kigali](https://img.shields.io/badge/University%20of%20Kigali-CSC422-blue?style=for-the-badge)]()

---

##  About This Project

**RwandaAgroPrice** is a web-based market price decision support dashboard built as a group assignment for the **Distributed and Cloud Computing (CSC422)** module at the **University of Kigali**.

The system addresses a real problem faced by Rwandan smallholder farmers — **information asymmetry in agricultural markets**. Farmers often sell their produce at the nearest market without knowing that a market 10–15 km away may be paying up to 40% more for the same crop. This dashboard gives them the price comparison they need, at the moment they need it.

🔗 **Live Site:** [https://marygloria01.github.io/RwandaAgroPrice/index.html](https://marygloria01.github.io/RwandaAgroPrice/index.html)

---

##  Markets Covered

| Market | District | Province |
|---|---|---|
| Nyabugogo | Nyarugenge | Kigali City |
| Kimironko | Gasabo | Kigali City |
| Muhanga Market | Muhanga | Southern Province |
| Huye Market | Huye | Southern Province |
| Musanze Market | Musanze | Northern Province |
| Rubavu / Gisenyi | Rubavu | Western Province |
| Nyagatare Market | Nyagatare | Eastern Province |

---

##  Crops Tracked

| Kinyarwanda | English | Typical Range |
|---|---|---|
| Ibigori | Maize | 270 – 340 RWF/kg |
| Ibishyimbo | Beans | 500 – 610 RWF/kg |
| Tamato | Tomatoes | 350 – 560 RWF/kg |
| Ibirayi | Potatoes | 200 – 310 RWF/kg |
| Umuceli | Rice | 830 – 950 RWF/kg |
| Ingano | Wheat | 390 – 455 RWF/kg |

---

##  Features

- **★ Isoko rya Cyane** — "Best Market Today" recommendation that identifies the highest-paying market across all 7 locations
- **Animated bar charts** — CSS-powered price comparison bars with smooth transitions
- **Price table view** — toggle between bar chart and structured table layouts
- **Price change indicators** — ▲ / ▼ arrows showing price movement since last refresh
- **Light / Dark mode toggle** — sliding track toggle with sun and moon icons, preference saved in localStorage
- **District coverage strip** — shows all provinces covered at a glance
- **Live metrics** — market count, crop count, blended average price, best spread of the day
- **Auto-refresh** — data refreshes every 30 seconds automatically
- **Crop filter buttons** — filter to view one crop across all markets
- **Fully responsive** — works on desktop, tablet, and mobile browsers
- **Zero dependencies** — no frameworks, no libraries, no backend — pure HTML, CSS, JavaScript
- **Free hosting** — deployed on GitHub Pages at no cost

---

##  Technology Stack

| Technology | Role |
|---|---|
| HTML5 | Document structure and semantics |
| CSS3 | Styling, animations, bar chart visualisation |
| JavaScript (ES6+) | Application logic and data store |
| GitHub Pages | Free static hosting and deployment |

---

##  How to Run Locally

No installation required. Just:

```bash
git clone https://github.com/MaryGloria01/RwandaAgroPrice.git
cd RwandaAgroPrice
```

Then open `index.html` in any browser. That's it.

---

##  How to Update Prices

Prices are stored as a JavaScript object inside `index.html`. To update them weekly:

1. Open `index.html` in any text editor
2. Find the `const CROPS` array near the top of the `<script>` section
3. Edit the `base` price values for each crop and market
4. Save and commit — the live site updates automatically

No database, no server, no special software needed.

---

##  Group 5 — Team Members

| # | Name |
|---|---|
| 1 | Nwanochiri Ogochukwu GloriaMary |
| 2 | Cyizere Ishema Delice Darlene |
| 3 | Bol Alol Mayen |
| 4 | Edou Obiang Lewis |
| 5 | Buay Biel Nienkel |
| 6 | Abrahim Dixon |
| 7 | Niyonsaba Enock |

---

##  Academic Context

| Field | Detail |
|---|---|
| Institution | University of Kigali |
| School | School of Computing and Information Technology |
| Module | CSC422 — Distributed and Cloud Computing |

---

##  License

This project was created for academic purposes at the University of Kigali.  
Free to use and adapt for educational and non-commercial purposes.

---

*Ibiciro by'Isoko — Market Prices for Rwanda's Smallholder Farmers 🇷🇼*
