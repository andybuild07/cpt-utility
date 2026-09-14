# cpt-utility

### 🎯 Project Charter

**The Mission**
Support the City of Cape Town’s Open Data Initiative by democratizing access to public municipal datasets, fostering operational transparency, civic innovation, and data-driven economic growth.

**The Architecture**
An end-to-end ELT Medallion Lakehouse pipeline on Databricks that ingests, cleans, and structures public municipal records into:
* **8 Silver Datasets:** Cleaned, deduplicated, and governed via Delta Live Tables (DLT) expectation rules.
* **Gold Galaxy Schema:** 6 enriched, conformed dimensions sharing 8 multi-fact tables tailored for complex municipal metrics.

**The Impact**
Eliminates manual data preparation bottlenecks and removes technical friction for analysts and city stakeholders, delivering high-performance, low-latency DirectQuery reporting in Power BI or Tableu.

### 📂 Ingested Open Data Datasets (City of Cape Town)

**Finance & Revenue Protection**
* **Municipal Arrears by Sub-council** (`2021–2026`) — Sub-council level debt and arrear tracking.
* **Municipal Arrears by Suburb & Service Type** (`2025–2026`) — Granular suburb debt broken down by service category.
* **Suburb-Level Electricity Billing** (`2021–2026`) — Spatial electricity consumption and revenue metrics.
* **Suburb-Level Water Billing** (`2021–2026`) — Spatial water usage and billing records.

**Operations & Service Delivery**
* **Municipal Service Requests** (`2023–2026`) — Citizen C3 service request logging, status, and resolution timelines.

**Grid & Energy Infrastructure**
* **Main Substations Load Profiles** (`2022–2024`) — Electrical substation load telemetry and capacity metrics.

**Water Resources & Climate**
* **Cape Town Dam Levels** (`2000–2026`) — Long-term historical water storage levels and capacity percentages.

