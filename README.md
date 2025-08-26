# LMDA: Enhancing Lateral Movement and Data Access Identification on Windows Systems

**LMDA** introduces two new Velociraptor artifacts:
- **LM (Lateral Movement)**
- **DA (Data Access)**

These artifacts streamline analysis by aggregating key forensic data from multiple artifacts and presenting data in a normalized format.

---

## 🚧 Challenges faced while investigating Lateral Movement and Data Access
- Manual and time-consuming analysis
- Limited insights from Windows Event Logs
- Fragmented forensic data sources

---

## 🧭 LM Artifact
The LM artifact aggregates and categorizes accesses to identify lateral movement.

### Features:
- Categorizes inbound vs. outbound access
- Integrated visualization via Jupyter notebooks
  - Comes with Jupyter notebook used for creating Lateral Movement triage visuals
- Integrated visualization via Grafana
  - Comes with custom server side Velociraptor artifact for ingesting results and creating visuals in Grafana

---

## 📂 DA Artifact: Data Access & Exfiltration Analysis
The DA artifact compiles user activity data to build structured timelines for data access and potential exfiltration.

### Features:
- Combines data from various artifacts in a normalized format
- Results are catered toward Excel reporting tempate used for stakeholder communication
- Highlights sensitive file interactions

---

### 📊 Reporting
An Excel-based reporting template is included to simplify stakeholder communication.

#### Highlights:
- Flags access to sensitive files (e.g., HR, Legal, Payroll)
- Easy-to-read summaries for non-technical audiences

---

## Copyright

Copyright 2025, Stroz Friedberg, A LevelBlue Company. LMDA is licensed under the Apache License, Version 2.0.
