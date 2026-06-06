# 🎓 MPDTE BTech College Predictor 2025

An interactive, responsive, and data-driven web tool designed for engineering aspirants in Madhya Pradesh to predict their admission chances in B.Tech courses under the **Directorate of Technical Education (DTE), MP** counselling.

Live Link: [saurabh2807.github.io/College-predictor](https://saurabh2807.github.io/College-predictor/)

---

## 🚀 Key Features

- **📊 Comprehensive 2025 Cutoff Data**: Built on top of actual MPDTE 2025 counselling database containing **5,000+ data points** covering multiple counselling rounds (Round 1, Upgrade Round, Round 2, and Branch Change).
- **🎯 Highly Personalised Predictions**: Takes into account critical factors like:
  - **JEE Main Common Rank (CRL)**
  - **Category-specific Quotas** (UR, OBC, SC, ST, EWS)
  - **Domicile Status** (automatic conversion of other-state students to General category)
  - **Gender** (accommodating female-only supernumerary seats)
- **🔍 Smart Filtering & Sorting**:
  - Filter colleges by type (Government Only, Government Aided, or Private Only).
  - Search by preferred branches or specific college names instantly.
  - Sort predictions based on **Best Chances First**, **Rank Proximity** (closest to cutoff), or **College Name**.
- **🚦 Visual Admission Chance Indicators**:
  - 🟢 **Safe**: High probability of getting admission based on past trends.
  - 🟡 **Possible**: Borderline case (worth keeping in choice-filling).
  - 🔴 **Low**: Admission is highly competitive or unlikely.
- **✨ Sleek Responsive Design**: Modern UI with a neat card-based form, responsive tables, loading animations, and clear legends for mobile and desktop screens.

---

## 🛠️ Technology Stack

- **HTML5**: Standard markup structure.
- **CSS3**: Implements CSS variables, custom animations, gradients, responsive grids, media queries, and sleek hover effects.
- **JavaScript (ES6)**: Real-time client-side calculation, search filtering, and dataset parsing.

---

## 📂 Project Structure

```text
├── index.html       # Single page application containing both the prediction UI and the inline database logic.
