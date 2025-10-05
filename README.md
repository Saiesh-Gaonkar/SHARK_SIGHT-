# SharkSight: Predicting Human-Shark Encounter Risk (Prototype)

## 🌊 Project Overview

**SharkSight** is a rapid-deployment web application prototype designed to predict and visualize areas of **Potential Human-Shark Encounter Risk ($R_{E}$)** for coastal users.

For this initial prototype, we have successfully developed and hosted the **Front-End Application** and created a fully functional **Machine Learning Model** in a Google Colab notebook. The live application currently displays the risk using **dummy data** (pre-generated risk values) to demonstrate the core user experience and visualization.

The core goal is to showcase how a simple, rapidly trained **Logistic Regression Model** (trained on NASA Earth Data) can be translated into **actionable, intuitive intelligence** via a clear risk heatmap and a **Risk Status** (LOW, MODERATE, HIGH) dial.

---

## ✨ Key Features

* **Risk Heatmap:** An interactive map (Leaflet.js/Next.js) overlaying predicted risk levels, showing "Red Zones" (high risk) for immediate action.
* **Actionable Risk Status:** A clear, user-friendly risk dial indicating **LOW, MODERATE, or HIGH** risk for a user-defined area.
* **Rapid ML Pipeline:** A simple, fast-training **Logistic Regression Model** created in a Colab environment, ready for production deployment.
* **NASA Data Focus:** The model is trained using oceanographic features derived from **NASA Earth Data** (e.g., GIBS).

---

## 🛠️ Technical Stack (Prototype)

| Component | Technology | Role in Project | Status |
| :--- | :--- | :--- | :--- |
| **Frontend/Map** | Next.js, Leaflet.js, shadcn.io | Builds the interactive map UI, the central Risk Status Dial, and the heatmap visualization. | **Hosted & Live** |
| **Data Source** | Local JSON/CSV | Provides **pre-generated Human-Shark Interaction (

research article: https://www.frontiersin.org/journals/marine-science/articles/10.3389/fmars.2018.00025/full

shark data: https://zenodo.org/records/5575189

nasa satellite data: https://oceandata.sci.gsfc.nasa.gov/l3/order/ to download modis data


