# cpt-utility

### 🎯 Project Charter

**The Mission**
Support the City of Cape Town’s Open Data Initiative by democratizing access to public municipal datasets, fostering operational transparency, civic innovation, and data-driven economic growth.

**The Architecture**
An end-to-end ELT Medallion Lakehouse pipeline on Databricks that ingests, cleans, and structures public municipal records into:
* **8 Silver Datasets:** Cleaned, deduplicated, and governed via Delta Live Tables (DLT) expectation rules.
* **Gold Galaxy Schema:** 6 enriched, conformed dimensions sharing 8 multi-fact tables tailored for complex municipal metrics.

**The Impact**
Eliminates manual data preparation bottlenecks and removes technical friction for analysts and city stakeholders, delivering high-performance, low-latency DirectQuery reporting in Power BI.

