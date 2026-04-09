# 🇮🇳 Indian General Elections Analytics (1962 - 2019)

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![HTML5](https://img.shields.io/badge/HTML5-Data%20Viz-orange)
![CSS3](https://img.shields.io/badge/CSS3-Responsive-blue)
![Plotly.js](https://img.shields.io/badge/Plotly.js-Interactive%20Charts-success)

> 🟢 **[View the Live Interactive Dashboard Here](https://rcb13.github.io/election-dashboard/)**

## 📌 Project Overview
This project is a high-performance, serverless **Single Page Application (SPA)** designed to visualize over 60 years of Indian electoral history. It allows users to explore macroscopic national trends and microscopic state-level demographic shifts across major parliamentary elections from 1962 to 2019.

## ✨ Key Features
* **Zero-Latency Filtering:** Engineered with an embedded JSON architecture, allowing instantaneous cross-filtering across States, Election Years, and Constituency Types (General, SC, ST) without backend API calls.
* **Smart Data Handling:** Implemented dynamic rendering logic to handle historical data gaps (e.g., dynamically disabling demographic charts prior to 2004 when candidate educational/professional affidavits were not mandatory).
* **Advanced Visualizations:** Utilized `Plotly.js` to render interactive spline curves (to smooth historical volatility), dynamic donut charts, and area graphs.
* **Responsive State Management:** Custom JavaScript routing cleanly swaps DOM elements between "Trend" analysis and "Demographic" analysis modes.

---

## 📊 Metrics Analyzed
The dashboard provides interactive tracking for the following key electoral metrics:
1. **Voter Turnout (%)** - Tracking democratic participation over decades.
2. **Victory Margin (%)** - Measuring the competitiveness of elections.
3. **Women Candidates (%)** - Visualizing gender representation in Indian politics.
4. **Total Candidate Explosion** - Tracking the massive spike in candidates (e.g., 1996) and subsequent regulatory corrections.
5. **Candidate Demographics** - Breakdown of Education and Professional backgrounds (Post-2004).

---

## 🖥️ UI / Visual Highlights

### The Main Trends Dashboard
> `![Trends Dashboard]](https://github.com/RCB13/election-dashboard/blob/main/front_page.png)`
> `![Trends Dashboard](https://github.com/RCB13/election-dashboard/blob/main/front_page2.png)`

### Demographic Donut Charts (Education & Profession)
> `![Demographics profession chart](https://github.com/RCB13/election-dashboard/blob/main/prof_dist.png)`
> `![Demographics education chart](https://github.com/RCB13/election-dashboard/blob/main/edu_dist.png)`
---

## 🗄️ Data Source
* **TCPD (Trivedi Centre for Political Data), Ashoka University:** The underlying dataset aggregates decades of official Election Commission of India (ECI) records.

---

## ⚙️ How to Run Locally
Because this is a serverless architecture, no local server or backend installation is required.

1. Clone this repository:
   ```bash
   git clone [https://github.com/rcb13/election-dashboard.git](https://github.com/rcb13/election-dashboard.git)
   
2.Navigate to the project folder:
Bash
cd election-dashboard

3.Simply double-click the index.html file to open it in any modern web browser.
***
### 💡 Final Steps for this Repository:
1. **Take Screenshots:** Open your live dashboard on your computer. Take one nice screenshot of the "Trends" tab, and one of the "Demographics" tab.
2. **Upload the Screenshots:** Upload those image files directly to your GitHub repository.
3. **Link them:** Just like we did for the Metro project, copy the image links and replace `path_to_trends_screenshot.png` and `path_to_demographics_screenshot.png` in the README. 

This repository is now a top-tier showcase of your front-end and data visualization abilities!
