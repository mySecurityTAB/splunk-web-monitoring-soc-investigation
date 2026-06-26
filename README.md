# 🛡️ Splunk Web Monitoring & SOC Investigation

> Enterprise SIEM Portfolio Project demonstrating operational monitoring, business analytics, security investigation, dashboard development, and incident response using Splunk Enterprise.

---

## 📖 Project Overview

This project demonstrates the deployment and use of **Splunk Enterprise** as a Security Information and Event Management (SIEM) platform for monitoring and analysing simulated Apache web server logs.

Using a realistic business scenario based on **ButterByte Biscuits Ltd**, the project showcases how machine data can be transformed into actionable operational, business, and security insights through the use of Search Processing Language (SPL), dashboards, and structured investigation techniques.

The project demonstrates how a Junior SOC Analyst can use Splunk Enterprise to transform raw machine data into operational, business, and security intelligence through structured investigation and dashboard-driven analysis.

---
# 🎯 Business Scenario

ButterByte Biscuits Ltd is a fictional online retailer used to simulate a realistic enterprise environment. Recently, the organisation experienced increasing customer complaints relating to website availability, failed purchases, and inconsistent user experience. At the same time, the IT department observed a rise in web server errors and unusual request patterns that required further investigation.

Management required a solution capable of collecting and analysing machine-generated data to answer several key business questions:

- Is the website operating normally?
- Which browsers and operating systems are most commonly used?
- How many customer purchases are failing?
- What is the estimated financial impact of failed purchases?
- Is there evidence of suspicious or potentially malicious web activity?

To address these challenges, Splunk Enterprise was deployed as the central Security Information and Event Management (SIEM) platform. Simulated Apache access logs were generated using Python and ingested into Splunk, where Search Processing Language (SPL) was used to analyse operational, business, and security events through interactive dashboards.

Rather than focusing solely on cybersecurity, this project demonstrates how a single dataset can provide valuable insights for multiple stakeholders, including IT Operations, DevOps engineers, Business Analysts, Security Operations Centre (SOC) analysts, and Executive Management.
# 🎯 Project Objectives

The objectives of this project were to:

- Deploy Splunk Enterprise on Ubuntu Linux.
- Generate realistic Apache-style web server logs using Python.
- Configure Splunk data inputs to ingest machine-generated logs.
- Perform operational monitoring using Search Processing Language (SPL).
- Develop dashboards for different business stakeholders.
- Investigate suspicious web activity using log analysis techniques.
- Estimate business impact from failed customer purchases.
- Document findings using structured SOC investigation practices.
- Present technical results in a professional GitHub portfolio.
# 💼 Skills Demonstrated

Throughout this project, the following technical and analytical skills were demonstrated:

### Security Information and Event Management (SIEM)

- Splunk Enterprise deployment
- Data onboarding
- Search Processing Language (SPL)
- Dashboard development
- Log analysis

### Security Operations

- Security event investigation
- Threat hunting
- Incident response documentation
- Evidence-based analysis
- SOC workflow

### DevOps & IT Operations

- Website monitoring
- Browser and operating system analysis
- HTTP status monitoring
- Service health monitoring

### Business Analytics

- Failed transaction analysis
- Business KPI reporting
- Estimated revenue impact
- Executive dashboard development

### Technical Skills

- Ubuntu Linux
- Python
- Apache Access Logs
- Git
- GitHub
- Visual Studio Code

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Splunk Enterprise | Log collection, analysis, dashboards, and security monitoring |
| Ubuntu Linux | Operating system hosting Splunk Enterprise |
| Python | Generation of simulated Apache web logs |
| Apache Access Logs | Source dataset used throughout the project |
| Search Processing Language (SPL) | Query language for searching and analysing machine data |
| Git | Version control |
| GitHub | Source code and documentation management |
| Visual Studio Code | Project documentation and Markdown editing |

# 🏗️ Solution Architecture

The project simulates a real-world Security Information and Event Management (SIEM) environment in which machine-generated Apache web server logs are collected, indexed, analysed, and visualised using Splunk Enterprise.

The solution consists of five primary components:

1. **Python Log Generator** – Generates realistic Apache-style web server logs.
2. **Apache Access Log Dataset** – Stores simulated HTTP requests.
3. **Splunk Enterprise** – Collects, indexes, and analyses log data.
4. **Interactive Dashboards** – Present operational, business, DevOps, and security insights.
5. **SOC Investigation Process** – Uses SPL searches to investigate suspicious behaviour and document findings.

The overall architecture is illustrated below.

> ![Splunk Solution Architecture](architecture/splunk_architecture.png)
**Figure 1.** High-level solution architecture illustrating the end-to-end workflow from simulated Apache log generation through Splunk data ingestion, SPL analysis, dashboard development, and SOC decision-making.

# 🔄 Data Pipeline

The project follows a structured data pipeline that transforms raw machine data into actionable operational and security intelligence.

1. Python generates simulated Apache web server logs.
2. Log files are written to the Ubuntu filesystem.
3. Splunk monitors the log directory.
4. Events are indexed into the `main` index.
5. Search Processing Language (SPL) queries analyse the indexed events.
6. Interactive dashboards visualise the results.
7. SOC analysts investigate suspicious activity and document findings.

> *![Data Pipeline](architecture/data_flow.png)

**Figure 2.** ![Data Pipeline](architecture/data_flow.png) End-to-end data pipeline illustrating how simulated Apache web server logs are generated, monitored, indexed, transformed into searchable events, and analysed using Splunk Enterprise dashboards.

# ⚙️ Project Workflow

The project follows a structured monitoring and investigation workflow similar to that used within a Security Operations Centre (SOC).

1. Generate simulated web server logs.
2. Configure Splunk data inputs.
3. Onboard Apache log data.
4. Validate field extraction.
5. Develop dashboards for different stakeholders.
6. Perform operational monitoring.
7. Conduct business analytics.
8. Investigate suspicious web activity.
9. Document findings.
10. Present executive-level summaries.

> *## SOC Investigation Workflow

![SOC Workflow](architecture/soc_workflow.png)

**Figure 3.** Security Operations Centre (SOC) investigation workflow illustrating the structured process followed by analysts when investigating suspicious activity, assessing risk, collecting evidence, escalating incidents, and reporting findings.*

