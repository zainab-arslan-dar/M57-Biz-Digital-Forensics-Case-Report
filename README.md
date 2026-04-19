#  M57.biz Digital Forensics Case Report

##  Overview
This repository presents a **digital forensics investigation** of the M57.biz case scenario.  
The analysis focuses on identifying suspicious user activity, reconstructing a timeline of events, and examining host-based artifacts to determine potential data exfiltration.

---

##  Objectives
- Reconstruct a **forensic timeline** of system activity  
- Identify **evidence of file access, execution, and transfer**  
- Analyze key artifacts to support findings  
- Produce an **evidence-based incident report**

---

##  Methodology
The investigation followed a structured **DFIR (Digital Forensics & Incident Response)** approach:

1. **Evidence Acquisition & Examination**  
2. **Artifact Analysis**  
3. **Timeline Reconstruction**  
4. **Correlation of Events**  
5. **Reporting & Conclusion**

---

##  Key Artifacts Analyzed
- **LNK (Shortcut) Files** – Evidence of file access and user interaction  
- **Prefetch Files** – Application execution history  
- **File System Metadata** – Timestamps and file activity  
- **User Activity Traces** – Recent files and system usage patterns  

---

##  Timeline Highlights
- Detection of suspicious shortcut (`m57biz.LNK`) activity  
- Correlation with **application execution (EXCEL.EXE)**  
- Events indicating **staging behavior prior to data movement**  
- Timeline suggests **intentional user-driven actions**

---

##  Tools & Techniques
- Autopsy (Digital Forensics Platform)
- FTK Imager  
- Manual artifact analysis  
- Timeline reconstruction techniques  
- Evidence correlation and validation  

---

##  Full Report
The complete forensic report is available below:

 **[View Full Case Report (PDF)](./RedTeam_M57.biz_CW2.pdf)**


---

##  Key Findings
- Evidence of **file access and staging activity** prior to exfiltration  
- Strong correlation between **shortcut creation and application execution**  
- Indicators suggest **deliberate user involvement** rather than automated processes  

---

##  Skills Demonstrated
- Digital Forensics Investigation  
- Timeline Analysis  
- Artifact Analysis (LNK, Prefetch)  
- Incident Reporting  
- Critical Thinking & Evidence Correlation  

---

##  Author
**Zainab Arslan Dar**  
BSc (Hons) Cybersecurity & Digital Forensics  
Middlesex University Dubai
