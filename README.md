# 🔐 Azure Sentinel SIEM Lab – Cybersecurity Portfolio

Welcome to my hands-on cybersecurity lab using **Microsoft Sentinel**.

This project simulates a brute-force attack scenario, collects and analyzes Windows Event Logs, builds custom visualizations in Workbooks, and sets up alert rules for security operations.

---

## 🎯 Objectives

* Build a functional SIEM using Azure Sentinel
* Collect logs from a Windows VM (Event ID 4624, 4625, 4740, etc.)
* Detect failed and successful logins
* Create alert rules for brute-force attacks
* Visualize incidents in professional dashboards
* Document detection and response steps

---

## 🧱 Lab Architecture

✅ Azure Virtual Machine (Windows 11)
✅ Microsoft Sentinel + Log Analytics Workspace
✅ Data Collection Rules (DCR)
✅ KQL Queries and Alert Rules
✅ Workbooks for Visualization
✅ Simulated Brute-Force Attack

---

## 📁 Project Structure

```
/initial
   ├── create_VM.png
   └── RDP_VM.png

/analytics
   ├── logsAnalytics-Query.png
   └── Analytics-Rule-BruteForce.png

/incidents
   └── Incident-Details-Summary.png

/workbook
   ├── Log-Analytics-Workspace.png
   ├── Create-Workbook.png
   ├── Workbook-Resource-Settings.png
   ├── Workbook-FailedLogins-Chart.png
   └── Workbook-SuccessfulLogins-Chart-and-Incidents-Grid.png

/automation
   └── Automation-Rule.png
```

---

## 📊 Key Visuals

* Number of failed/successful logins (KQL)
* Account lockouts by time
* Alert breakdown by severity
* Active incidents table
* Custom dashboards using Grid Layout

---

## 🛠️ Tools & Technologies

* Azure Portal
* Microsoft Sentinel
* Log Analytics (KQL)
* Azure Monitor Agent
* PowerShell / RDP for simulation
* GitHub for documentation

---

## 📸 Screenshots

All screenshots from the lab setup and visualizations are stored in the structured folders above for clarity and traceability.

---

## 🚧 Project Status

🔄 Currently in progress
🗕️ Week 3 of 6 – Setting up alert rules and preparing to simulate brute-force attack

---

## 👤 Contact

**Melissa Jahani**
📧 [melissajahani@gmail.com](mailto:melissajahani@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/melissajahani)
🔗 [GitHub](https://github.com/melissajoon)

---

> This lab demonstrates real-world SIEM setup and detection logic. It is part of my cybersecurity portfolio for entry-level **Security Analyst** or **SOC Analyst** positions.

📆 *Feel free to fork or reach out for collaboration!*
