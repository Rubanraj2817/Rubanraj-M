# Auto Ticket Classification Using ServiceNow

**Tamil Nadu Skill Development Corporation (TNSDC) – Naan Mudhalvan Scheme**

---

### 👥 Team Details

* **Project Title:** Auto Ticket Classification Using ServiceNow
* **Institution:** Government Arts and Science Collage,Srivilliputhur.
* **Department:** Bsc Computer Science
* **ServiceNow Instance ID:** dev421607

| S.No | Student Name | Role | Register / Roll Number |
|:---:|:---|:---|:---:|
| 1 | Rubanraj M | Team Leader | C4S44038 |
| 2 | Pandeeswaran M | Team Member | C4S44035 |
| 3 | Harikrishnan | Team Member | C4S44028 |
| 4 | Kaleeswaran R | Team Member | C4S44031 |

---

## 📌 Project Abstract
Incident Management is a core component of IT Service Management (ITSM). In organizations, handling numerous support tickets manually leads to response delays and inaccurate routing. 

This project implements **Automated Ticket Classification and Routing** in ServiceNow. Based on incoming incident attributes such as keywords in the short description, the system dynamically triages tickets and assigns them to the appropriate resolver groups without human intervention.

---

## ⚙️ Technology Stack
* **Platform:** ServiceNow Personal Developer Instance (dev421607)
* **Modules:** Incident Management, System Policy Rules
* **Key Components:** Assignment Rules, Condition Builders

---

## 🛠️ Implementation Steps

1. **Assignment Rule Configuration:**
   * Navigated to `System Policy > Rules > Assignment`.
   * Created a routing rule targeting the `incident` table.
   * Defined condition: `Short description contains VPN`.
2. **Automated Group Assignment:**
   * Configured the rule to automatically route matches to the `Network` assignment group.
3. **Execution & Verification:**
   * Created a test incident record with Short description `VPN Connection Issue`.
   * Validated that the incident automatically assigned to the Network team upon submission.

---

## 🎯 Conclusion
The project successfully automates ticket categorization and routing, significantly reducing Mean Time to Resolution (MTTR) and eliminating human error in ticket triage.
