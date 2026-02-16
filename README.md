# 👋 Hi there, I'm Dalbert (Dalbee)

**Software Engineer | Industrial Data Architect | GxP & DevOps Specialist**

I build high-integrity, distributed systems that bridge the gap between complex data and real-world operations. My expertise lies in designing **scalable data pipelines** and **mission-critical HMIs** for high-stakes industries like Biotech, Energy, and Aerospace.

---

### 🚀 Core Focus & Expertise
* **Industrial Data Engineering:** Architecting Medallion-style Lakehouses for multi-million row telemetry.
* **Mission-Critical Systems:** Expertise in GxP-compliant software, 21 CFR Part 11 integrity, and high-availability DevOps.
* **Distributed Architectures:** Specialized in "Triad" microservice patterns (.NET, Python, React).
* **Domain Interest:** Exploring the intersection of Data Engineering and GNSS/CubeSat ground segments.

---

### 🛠️ Strategic Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | **C# (.NET 10)**, **Python (FastAPI/PySpark)**, TypeScript, SQL, SAS |
| **Data Engineering** | **Databricks**, **dbt**, **Microsoft Fabric (OneLake)**, Medallion Architecture, Delta Lake, Spark |
| **Cloud & DevOps** | **Azure**, Docker, GitHub Actions, CI/CD, Infrastructure as Code |
| **Visualization & HMI**| **Power BI (DAX/DirectLake)**, **React**, Recharts, GxP-compliant UI/UX |

---

### 🧪 Featured Production-Scale Projects

#### 🧬 [Bioprocess Insight Platform (BIP)](https://github.com/Dalbee/bioprocess-insights-platform)
**Industrial Digital Twin & GxP-Compliant HMI**
* **Architecture:** Engineered a **Decoupled Triad Architecture** (React HMI ↔ Python SCADA Engine ↔ .NET 10 Compliance Service) to bridge historical data with live operational compliance.
* **Innovation:** Integrated a physics-based Digital Twin linking Impeller RPM to Oxygen Transfer and predictive temperature modeling via moving-window linear regression.
* **Compliance:** Built a dedicated **.NET microservice** for immutable audit trails (**21 CFR Part 11**) and a React-based HMI featuring deterministic pulsing alarms.



#### ⚡ [District Energy Intelligence Platform](https://github.com/Dalbee/energy-analytics-fabric-bi)
**Enterprise Data Engineering & Power BI Analytics (Microsoft Fabric)**
* **Business Impact:** Identified **€4.9M in potential cost recovery** (81,744 MWh efficiency risk) through advanced **Power BI (DAX)** and Star-Schema modeling.
* **Scale:** Implemented a full **Medallion Architecture** (Bronze/Silver/Gold) on OneLake using **PySpark** to process and transform millions of rows of operational telemetry.
* **Visualization:** Developed executive-level **Power BI dashboards** utilizing calculation groups and DirectLake mode to track production vs. demand with sub-second interactivity.
* **Governance:** Established a "Single Source of Truth" by computing KPIs upstream in Spark, secured via RLS/OLS, and automated through Fabric CI/CD pipelines.

#### 📦 [Nexus: Supply Chain Intelligence Lakehouse](https://github.com/Dalbee/nexus-supply-chain-ops)
**End-to-End Medallion Pipeline (dbt + Databricks + Power BI)**
* **Architecture:** Engineered a **Medallion Pipeline** (Bronze → Silver → Gold) in Databricks to refactor nested shipment telemetry into an optimized **Star Schema**.
* **Engineering:** Leveraged **dbt-databricks** to implement MD5 surrogate keys and "Inferred Dimensions," ensuring 100% referential integrity for complex Fact-to-Dimension joins.
* **Analytics Layer:** Developed an integrated **Power BI Dashboard** utilizing the Star Schema to enable sub-second "Drill Down" from executive logistics KPIs to granular `order-item` details.
* **Quality & CI/CD:** Hardened the pipeline with **dbt 2.0 relationship tests** and automated schema validation to eliminate "Blank" slicer values and row-inflation in downstream reports.


#### 🤖 [OrangeHRM Test Factory](https://github.com/Dalbee/OrangeHRM)
**Quality Engineering & DevOps Automation**
* **Stability:** Developed a comprehensive automated testing suite designed for high-frequency deployment environments, ensuring system reliability through rigorous validation.
* **Automation:** Focused on building robust frameworks and CI/CD integration to minimize regression risks in production-aligned scenarios.

---

---

### 🤝 Let's Connect & Collaborate

I’m always looking to bridge the gap between complex industrial data and actionable intelligence. Whether you want to talk **IIoT architecture** or **piano sonatas**, let’s chat!

* **Architecture Deep-Dives:** Ask me about **Digital Twins**, **Medallion Lakehouses (Fabric/Databricks)**, or maintaining **GxP integrity** in automated pipelines.
* **Aerospace & GNSS:** I am actively seeking collaborations on GNSS signal processing and CubeSat ground segment telemetry.
* **Professional Hubs:** * [LinkedIn](https://www.linkedin.com/in/dalbertonyebuchi/) — For industry networking and architecture discussions.
    * [Twitter/X](https://twitter.com/DalbertZim) — For tech updates and real-time insights.

---

### ⚡ Fun Fact
I balance the logic of data with the rhythm of music—I love **cycling**, **urban hiking**, **singing**, **leading choral groups** and **playing the piano**. Whether in a data pipeline or a piano sonata, "timing" is everything!