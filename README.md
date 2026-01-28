# AI-Powered-Urban-Heat-Island-Detection-for-Sustainable-City-Planning-Cottbus-
AI + Satellite Data to map Urban Heat Islands in Cottbus and guide climate-smart urban planning.
 AI-Powered Urban Heat Island Detection – Cottbus, Germany

 Project Title
**GeoAI for Urban Heat Risk Assessment in Cottbus (2023–2025)**

Project Overview

This rapid research project (10 hours) combines **Artificial Intelligence** and **Environmental Resource Management** to identify **Urban Heat Island (UHI)** risk zones in **Cottbus, Germany**. Using satellite imagery from 2023 and 2025, we applied a pretrained **U-Net** deep learning model to detect vegetation loss and climate vulnerability patterns.

> 🔗 Goal: Empower sustainable urban planning using AI-powered geospatial analysis.

---

Team Roles

| Name                     | Role                                | Background                          |
|--------------------------|-------------------------------------|-------------------------------------|
| Abdul Samad Mazari       | AI Developer & Geospatial Analyst   | Master's in Artificial Intelligence |
| Farhana Ejaz             | Environmental Strategist            | Bachelor's in Environmental Resources Management |

---

 Tools & Technologies

- Python (Google Colab)
- U-Net (PyTorch, pretrained)
- Satellite imagery (.png)
- PIL, OpenCV, Matplotlib
- NDVI preprocessing
- Geospatial comparison (2023 vs 2025)
- Optional: QGIS, PowerPoint/Photoshop for map overlay

---

Input Images

- Satellite images of Cottbus from 2023 and 2025
- Format: `.png`, visually aligned
- Resolution adjusted for model input

<p align="center">
  <img src="images/2023_satellite.png" width="45%" />
  <img src="images/2025_satellite.png" width="45%" />
</p>

---

##  Step-by-Step Process

# Step 1: Preprocessing

- Resized satellite images for U-Net input
- Normalized and aligned image shapes
- Extracted NDVI-based vegetation contrast between years

# Step 2: AI Prediction using U-Net

- Used a pretrained U-Net model for semantic segmentation
- Output: `risk_mask.png` showing vegetation loss & UHI-prone zones

# Step 3: Environmental Analysis (Farhana's Work)

- Interpreted AI output to identify neighborhoods with high UHI risk
- Cross-checked low NDVI areas with real Cottbus map
- Assessed missing green infrastructure

# Step 4: Policy & Sustainability Mapping

- Proposed 5 localized interventions:
  - Green roofs
  -  Urban street tree corridors
  -  Community gardens
  -  Permeable pavements
  -  Vertical gardens in dense areas
- Mapped these ideas to EU Green Deal and German Stadtentwicklungskonzept

---

#  Results Snapshot

<p align="center">
  <img src="images/uhi_risk_map.png" width="70%" />
</p>

**Insights:**
- Eastern districts show significant vegetation decline.
- Vulnerable zones coincide with high building density.
- Tree loss between 2023 and 2025 suggests urban sprawl without mitigation.

---

##  Real-World Application

This project demonstrates:
- How AI can support **climate-resilient city planning**
- How environmental science can **guide model interpretation**
- A practical case for **GeoAI and interdisciplinary teamwork**



