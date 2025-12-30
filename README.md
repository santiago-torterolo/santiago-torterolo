# Hi there, I'm Santiago Torterolo 👋
### Fraud Prevention & Risk Analyst | Fintech Specialist

I specialize in detecting financial crime patterns, optimizing risk rules, and protecting payment ecosystems. Currently based in Germany 🇩🇪.

- 🔭 **I'm currently working on:** End-to-End AML Transaction Monitoring Engine with Hybrid Detection (SQL Rules + Machine Learning).
- 💼 **Professional Background:** 4+ years at Mercado Libre & Ingeniarte minimizing fraud loss.
- 🛠 **Tech Stack:**
    - **Analysis:** Python (Pandas, NumPy, NetworkX), SQL (Advanced Window Functions, CTEs).
    - **Databases:** DuckDB, Athena, BigQuery, SQLite.
    - **Machine Learning:** XGBoost, Scikit-learn (Isolation Forest), SHAP (Explainability).
    - **APIs & Dashboards:** Flask, Streamlit, Tableau, Looker.
    - **Risk:** AML Compliance, Device Fingerprinting, Rule Backtesting, Anomaly Detection, Behavioral Analytics.
    - **ATO / Auth Security:** Session risk scoring, Login anomaly detection, MFA strategy, Velocity & bot signals.

---

#### 📂 Featured Portfolio Projects
These projects simulate real-world fraud scenarios using public datasets, demonstrating end-to-end risk analysis.

| Project | Type | Tech |
| :--- | :--- | :--- |
| [**AML Transaction Monitoring Engine**](https://github.com/santiago-torterolo/aml-transaction-monitoring-engine) | Production-Ready Detection System | Python, DuckDB, SQL, scikit-learn, Flask, Streamlit |
| [**ATO Risk Profiler**](https://github.com/santiago-torterolo/ATO-Risk-Profiler) | Account Takeover Risk & Behavioral Profiling | Python, Pandas, scikit-learn, Anomaly Detection, Device/Session Signals |
| [**Blockchain Fraud Prevention**](https://github.com/santiago-torterolo/blockchain-fraud-prevention) | Crypto Transaction Analysis | Python, XGBoost, NetworkX, Web3.py, Solidity |
| [**KYC EU Compliance**](https://github.com/santiago-torterolo/kyc-eu-compliance) | Regulatory Compliance & Automation | Python, eKYC, GDPR, AMLD6 |
| [**The AML Network Hunter**](https://github.com/santiago-torterolo/Fraud-Prevention-Portfolio/tree/main/01_Money_Laundering_Investigation) | Forensic Analysis | Python, NetworkX, Pandas |
| [**Athena Fraud Engine**](https://github.com/santiago-torterolo/Athena-Fraud-Detection) | ML & Behavioral Analysis | Python, XGBoost, SHAP, Streamlit |
| [**SQL Rule Optimizer**](https://github.com/santiago-torterolo/Fraud-Prevention-Portfolio/tree/main/02_SQL_Fraud_Audit) | Audit & Operations | SQL (SQLite), PaySim Dataset |
| [**Fintech Risk Dashboard**](https://github.com/santiago-torterolo/Fraud-Prevention-Portfolio/tree/main/03_Executive_Risk_Dashboard) | Executive Reporting | Tableau Public |

---

#### 🎯 Project Highlights

**AML Transaction Monitoring Engine** processes 6.3M transactions using:
- 4 SQL-based fraud typology rules (Structuring, Velocity Abuse, Round Amounts, Beneficiary Rotation)
- Isolation Forest ML algorithm for unsupervised anomaly detection
- REST API for system integration (5 endpoints)
- Interactive Streamlit dashboard for investigators
- Achieves industry-optimal 0.0175% alert rate

**ATO Risk Profiler** focuses on account takeover risk using behavioral + session signals:
- Feature engineering on login/activity patterns (time-of-day, velocity, geo changes, device changes)
- Unsupervised profiling to spot deviations vs. normal customer behavior
- Risk scoring approach designed for step-up authentication / investigation queues
- Investigator-friendly outputs (reason codes / contributing signals) for faster triage

**Blockchain Fraud Prevention** detects illicit crypto transactions through:
- Graph-based wallet clustering using NetworkX to trace fund flows across DeFi protocols
- XGBoost classifier trained on Bitcoin transaction patterns identifying mixer services and scam wallets
- Smart contract integration via Web3.py for real-time on-chain fraud flagging
- Anomaly detection algorithms spotting suspicious velocity patterns and phishing campaigns
- Chainalysis-style transaction scoring assigning risk levels to wallets and addresses

**KYC EU Compliance** automates customer verification under European regulations:
- eKYC document validation and identity verification workflows
- GDPR-compliant data handling and privacy-by-design architecture
- AMLD6 risk scoring and PEP/sanctions screening integration
- Reduces manual review time by 70% while maintaining compliance standards

**The AML Network Hunter** uncovers money laundering rings through:
- Graph-based network analysis using NetworkX (500+ suspicious nodes)
- Community detection algorithms to identify coordinated mule accounts
- Visual forensic reports linking shell companies to beneficial owners
- Pattern recognition for layering and integration schemes

**Athena Fraud Engine** combines ML and behavioral analytics:
- XGBoost classifier with 92% precision on synthetic fraud datasets
- SHAP explainability for transparent risk decisions
- Real-time scoring API processing 10K transactions/hour
- Behavioral features: device fingerprinting, velocity checks, session anomalies

**SQL Rule Optimizer** audits and tunes fraud detection logic:
- Backtesting framework for 15+ production rules on PaySim dataset
- False positive rate reduction from 12% to 3.5% through parameter tuning
- Performance benchmarking: query execution time optimization (45% faster)
- A/B test simulation for rule rollout impact analysis

**Fintech Risk Dashboard** delivers executive-level visibility:
- Real-time KPIs: fraud loss rate, approval rate, alert volume trends
- Geo-heatmaps showing high-risk regions and merchant categories
- Cohort analysis for chargeback patterns by payment method
- Tableau Public interactive version for stakeholder sharing

---

[linkedin-badge]: https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white&link=https://linkedin.com/in/santiago-torterolo-5u
[![LinkedIn][linkedin-badge]](https://linkedin.com/in/santiago-torterolo-5u)
