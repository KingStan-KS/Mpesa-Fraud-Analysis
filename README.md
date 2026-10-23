# Mpesa-Fraud-Analysis
Project Title: Financial Anomaly Detection & Risk Profiling Dashboard (M-Pesa)
Role: Data Analyst
Tools Used: Microsoft Excel (PivotTables, Data Modeling, Time-Series Analysis, Interactive Dashboards)
Dataset: 120,000+ Mobile Money Transaction Logs
Executive Summary:
Designed and built a corporate-level security dashboard to analyze over 120,000 mobile money transactions. The objective was to identify fraudulent behaviors, map temporal drift (time-based attacks), and isolate high-risk payment channels to provide actionable intelligence for risk management teams.
Technical Architecture:
Data Pipeline: Successfully ingested and processed a massive 120,000-row CSV file bypassing legacy system limitations via Pivot Caches.
System Design: Implemented an industry-standard Frontend/Backend split. All raw data and calculation grids are isolated in the backend, feeding into a clean, interactive frontend command center called the Executive Dashboard.
Dynamic Interactivity: Engineered a master Slicer network that allows stakeholders to instantly filter all visual metrics by geographic region.
Key Business Insights Discovered:
Financial Vulnerability (Channel Risk): Identified that the Till channel is the primary route exploited for maximum financial extraction, significantly outpacing direct Peer-to-Peer (P2P) and Paybill routes.
Temporal Drift (Time-Series Spikes): Discovered a critical operational vulnerability at exactly 21:00 (9:00 PM), indicating that attackers exploit reduced evening customer service staffing hours to delay account freezing.
Victim Profiling (Account Draining): Analyzed post-transaction account balances, proving that fraudulent actors systematically drain compromised accounts to near-zero balances immediately upon access.
