# 📊 Cyber Threat Analytics Platform with Incident Visualization System 

## 🚀 Project Overview

This project was completed as part of our internship with **Infosys Springboard Virtual Internship 7.0**.

**Advanced Threat Incident Analytics Framework** is an interactive cybersecurity analytics dashboard designed to replace slow, error-prone manual review of network and threat-detection logs with fast, visual, data-driven triage. The project uses **Microsoft Power BI, Power Query, and DAX** to transform 6 million raw network-traffic and security-event log rows into a clean, risk-enriched dataset and a 7-page interactive dashboard delivering meaningful insights and an easy-to-understand user experience for both security analysts and non-technical stakeholders.

The project demonstrates how **data analytics and business intelligence** can be used to solve real-world Security Operations Centre (SOC) problems by providing data-driven insights, interactive visualizations, and meaningful analysis of traffic patterns, protocol usage, and network origins — narrowing the gap between threat detection and prevention.

## 🗂️ Project Files

Here's an overview of the files in this repository:

- **Team_Members_PPT/** – Individual PPT slides for each team member
- **Cyber Threat Analytics Platform with Incident Visualization System Group 1.pbit** – Main Power BI template file
- **Team A-Group PPT.pptx** – Group presentation slides
- **Internship_Project_Report.docx** – Internship completion / milestone report
- **LICENSE** – License file
- **README.md** – This overview file

## 🚀 Key Features

**📊 KPI Scorecards:**
At-a-glance headline metrics — Total Log Events, % Traffic Blocked, and Total Data Transferred — for instant situational awareness.

**🔍 Traffic & Protocol Analysis:**
Daily traffic trend (area/line chart) and a protocol breakdown (donut chart) reveal allowed vs. blocked traffic across 7 network protocols over time.

**🧠 Severity & Threat Intelligence:**
Engineered Severity_score and Urgency_Flag DAX measures classify incidents by Malicious, Suspicious, and Benign response outcomes.

**⚙️ Source & Destination Network Mapping:**
Geographic/subnet-level mapping traces attack origins and pinpoints the most-targeted internal machines for rapid forensic isolation.

**📈 Executive Risk Gauge:**
A composite risk score and detection-vs-prevention trend gives leadership a single, decision-ready view of the organization's security posture.

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**: Core platform for interactive dashboard development
- **Power Query (M Language)**: 12-step ETL pipeline for data cleaning, formatting, and enrichment
- **DAX (Data Analysis Expressions)**: Calculated columns and measures (Severity Score, Urgency Flag, Malicious Allowed Rate %)
- **Kaggle Dataset — "Cybersecurity Threat Detection Logs"**: 6,000,000 raw rows, refined to 1,495,242 network log events (Jan–Mar 2024)
- **GitHub / GitLab**: Version control and repository management
- **Microsoft Teams**: Team collaboration and communication

## 📊 Project Workflow

1. **Data Collection** – Sourced the 6-million-row raw "Cybersecurity Threat Detection Logs" dataset from Kaggle.
2. **Data Cleaning & Preprocessing** – Ran a rigorous 12-step Power Query ETL pipeline across three phases (Scale Optimization, Chronology & Text Format, Enrichment & Finalization) to clean, de-duplicate, and optimize the data.
3. **Data Analysis** – Built table relationships, indexing, and DAX measures such as Severity_score, Urgency_Flag, and Malicious Allowed Rate %.
4. **Visualization / Development** – Designed a 7-page interactive Power BI dashboard with KPI cards, trend charts, donut/treemap visuals, and network maps.
5. **Insights & Interpretation** – Cross-filtered protocols, severity levels, and network origins to surface actionable security intelligence for SOC decision-making.

## 🎯 Objectives

- To replace slow, error-prone manual log review with a visual-first analytics framework.
- To engineer a clean, risk-ready dataset from 6 million raw network log rows.
- To build an interactive, multi-page Power BI dashboard covering traffic, protocols, severity, and network origins.
- To provide a data-driven basis for closing the gap between threat detection and prevention.
- To demonstrate the practical application of business intelligence and data analytics in cybersecurity operations.

## 👥 Team Learnings & Outcomes

Through this project, our team strengthened both technical and soft skills.

### 🔧 Technical Skills
- Power Query (M language) data transformation
- DAX measures and calculated columns for KPI and risk-scoring logic
- Multi-page Power BI dashboard design
- Feature engineering for risk-based analytics (severity scoring, urgency flagging)
- Data modeling and relationship design in Power BI

### 💡 Soft Skills
- Problem-solving and analytical thinking
- Effective team collaboration
- Communication and presentation skills
- Time management
- Data-driven decision making

This internship-based project helped bridge academic learning with real-world industry experience, providing practical exposure to cybersecurity analytics and business intelligence.

## 📈 Future Enhancements

- Integrate drill-through pages for full incident history per source IP.
- Add real geolocation mapping instead of subnet-based grouping.
- Implement near-real-time log streaming instead of a static extract.
- Deploy the project as a web application / cloud-hosted dashboard.
- Add ML-based anomaly-detection scoring to complement the rule-based Severity_score.

## 🏁 Conclusion

The **Advanced Threat Incident Analytics Framework** project demonstrates how business intelligence and data analytics can be effectively used to address the cybersecurity "data overload" problem faced by modern Security Operations Centres.

By leveraging Power BI, Power Query, and DAX, the project transformed 1.5 million raw network logs into a fully functional, 7-page interactive dashboard — revealing a 49.89% critical breach rate, protocol-specific exfiltration risks, and disproportionate threat origins — and demonstrates the practical application of industry-oriented analytics concepts learned during the internship.

## 💬 Contributors

- Hemanth M
- Darsh Dwived
- Harini T
- Srinidhi
- Akshay Jaiswal

**Year:** 2026

## 📌 Notes

- This project was developed as part of the **Infosys Springboard Virtual Internship 7.0**.
- All data/resources used in this project are intended for educational and demonstration purposes.
- The project is developed as an internship-based academic/industry-oriented project.
