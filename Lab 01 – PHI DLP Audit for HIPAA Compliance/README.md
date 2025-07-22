# 🧪 Lab 01 – PHI DLP Audit for HIPAA Compliance

## 📚 Table of Contents
- [📌 Overview](#-overview)
- [🎯 Objectives](#-objectives)
- [🧠 Key Concepts Reinforced](#-key-concepts-reinforced)
- [🧰 Lab Environment & Tools](#-lab-environment--tools)
- [🔧 Tasks Performed](#-tasks-performed)
- [📈 Outcome Summary](#-outcome-summary)
- [🏢 Business Relevance](#-business-relevance)
- [🖼️ Screenshots](#-screenshots)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 📌 Overview

In this lab, I acted as a Compliance Analyst for a healthcare organization tasked with auditing the exposure of Protected Health Information (PHI) under HIPAA. I used Microsoft Purview to identify, monitor, and alert on sensitive PHI content uploaded to OneDrive and SharePoint, using built-in detectors and a custom DLP policy.

---

## 🎯 Objectives

- Upload simulated PHI files to OneDrive or SharePoint.
- Enable and understand built-in PHI detectors in Microsoft Purview.
- Create a DLP policy to audit PHI exposure.
- Generate and review alert activity in the Purview compliance portal.

---

## 🧠 Key Concepts Reinforced

| Concept                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| PHI (Protected Health Info)   | Regulated health data under HIPAA such as SSNs, diagnoses, and records.    |
| Sensitive Info Types (SITs)   | Built-in Microsoft classifiers that detect regulated data patterns.         |
| DLP Policy                    | Data Loss Prevention rule enforcing policy actions on sensitive content.    |
| Audit-Only Mode               | Allows visibility into policy matches without restricting user activity.    |
| Microsoft Purview             | Compliance portal for Microsoft 365 that enables data governance and DLP.  |

---

## 🧰 Lab Environment & Tools

- Microsoft 365 E5 Tenant (Trial)
- Microsoft Purview Compliance Portal  
- OneDrive or SharePoint (test site)
- Admin privileges (Global or Compliance Admin)

---

## 🔧 Tasks Performed

1. **Uploaded a test file** to OneDrive with simulated PHI including:
   - Patient Name, SSN, Medical Record Number, Diagnosis Code, Health Plan ID

2. **Verified built-in PHI detectors** in Microsoft Purview:
   - Located and reviewed `Protected Health Information (PHI)` SIT

3. **Created a custom DLP policy** named `PHI Monitoring – HIPAA Compliance`:
   - Targeted OneDrive and SharePoint
   - Set to audit only
   - Monitored PHI content with medium confidence, single occurrence

4. **Triggered policy detection** by opening the file and validating alert visibility:
   - Viewed logs in DLP Alerts and Activity Explorer

---

## 📈 Outcome Summary

By the end of this lab, I successfully simulated HIPAA compliance auditing by using Microsoft Purview to monitor the upload and handling of PHI. Alerts were triggered as expected using built-in detectors, and the policy remained in audit-only mode for visibility without disruption.

---

## 🏢 Business Relevance

This lab reflects real-world compliance needs for healthcare organizations subject to HIPAA. By simulating PHI detection and policy auditing, it demonstrates how Microsoft Purview can proactively identify data exposure risks and support regulatory requirements.

---

## 🖼️ Screenshots

| Filename                     | 📸 Description                             | URL Placeholder                                 |
|-----------------------------|--------------------------------------------|--------------------------------------------------|
| `phi_test_upload.png`       | Uploaded PHI file to OneDrive              | `[Link to Raw Image]()`                          |
| `purview_phi_sit.png`       | PHI sensitive info type in Purview         | `[Link to Raw Image]()`                          |
| `dlp_policy_creation.png`   | DLP policy setup for PHI monitoring        | `[Link to Raw Image]()`                          |
| `dlp_alert_triggered.png`   | DLP alert log showing matched PHI content  | `[Link to Raw Image]()`                          |

---

## 🙏 Acknowledgments

Thanks to the Microsoft Purview team and documentation. This lab was conceptualized and executed independently using Microsoft 365 E5 and AI-assisted planning via ChatGPT.

