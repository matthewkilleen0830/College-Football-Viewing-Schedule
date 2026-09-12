# Road to the CFP: College Football Broadcast Dashboard 🏈

An interactive, single-page web dashboard designed to simplify your weekly college football viewing experience each week. Built with **HTML5, CSS3, JavaScript (ES6+), Bootstrap 5**, and **Plotly.js**, this dashboard provides a sleek, dark-mode visual grid of all broadcast and streaming kickoff schedules with real-time dynamic filtering.

![Road to the CFP Dashboard Banner](headerBanner.png)

---

## 🚀 Live Demo

Check out the live interactive application hosted on GitHub Pages:
👉 **[https://matthewkilleen0830.github.io/College-Football-Viewing-Schedule/](https://matthewkilleen0830.github.io/College-Football-Viewing-Schedule/)**

---

## ✨ Features & Functionality

* **Dual Schedule Visualizations**:
  * **National Broadcast Networks**: Visual timeline tracking major linear networks (e.g., ABC, CBS, FOX, ESPN, SEC Network, Big Ten Network).
  * **Streaming Providers**: Dedicated schedule tracking for digital-only streams (e.g., ESPN+, Peacock, Paramount+, B1G+).
* **Interactive Slicers & Adaptive Filters**:
  * **Day / Date Selection**: Instant focus on specific game days.
  * **AP Top 25 Toggle**: One-click filter to highlight high-stakes ranked matchups.
  * **Kickoff Time Slicer**: Dynamic multi-select filter adapting to available kickoff slots for selected days.
  * **Conference Slicer**: Multi-select conference filter (SEC, Big Ten, Big 12, ACC, etc.) that adaptively updates based on active date, time, and ranking constraints.
* **Art Deco Dark Theme**:
  * Clean, polished, custom CSS UI tailored for late-night viewing.
  * Custom team color branding and high-contrast timeline bars for seamless visual scanning.
* **Full Analytics Integration**:
  * Integrated **Google Analytics 4 (GA4)** for tracking real-time user activity, slicer interactions, and device metrics.
  * Configured with dual IPv4 & IPv6 internal traffic exclusion rules to keep development metrics clean.
* **SEO & Social Share Ready**:
  * Fully equipped with **Open Graph** and **Twitter Card** metadata for rich media link previews across iMessage, X, LinkedIn, and Discord.
  * Embedded **Schema.org (JSON-LD)** structured data for enhanced search engine indexing.

---

## 🛠️ Tech Stack & Libraries

| Category | Technology / Library |
| :--- | :--- |
| **Frontend Framework** | HTML5, Modern CSS3, JavaScript (Vanilla ES6+) |
| **UI Layout** | Bootstrap 5.3 |
| **Data Visualization** | Plotly.js |
| **Hosting & Deployment**| GitHub Pages |
| **Analytics** | Google Analytics 4 (gtag.js) |
| **Typography & Assets**| Google Fonts, Custom SVG Icons |

---

## 📁 Repository Structure

```text
├── index.html          # Main HTML entry point with layout & SEO metadata
├── styles.css          # Custom Art Deco dark-theme styling & responsive rules
├── script.js          # Dynamic data fetching, filter logic, and Plotly chart rendering
├── headerBanner.png    # Dashboard header banner and Open Graph preview image
├── favicon.png         # Browser favicon icon
└── README.md           # Project documentation
