# Project Progress Tracking (Week 08)

## 1. Project Baseline Summary
*Based on Week 03 Schedule and Week 05 Cost Plan:*
* **Planned Duration:** 32 Days (Oct 07 – Nov 08)
* **Planned Budget:** RM 6,840
* **Key Milestones:**
    * Data Collection Complete: Oct 08
    * Model Training Complete: Oct 17
    * Dashboard Prototype Ready: Oct 30
    * Final Presentation: Nov 08

## 2. Progress Tracking Table (Status as of Oct 28)
*Scenario: We are currently in Week 06/07 execution phase.*

| WBS ID | Task Name | Planned % | Actual % | Status |
| :--- | :--- | :--- | :--- | :--- |
| 1.3.1 | Stakeholder Sign-off | 100% | 100% | **Completed** |
| 2.3.1 | Filter low-quality images | 100% | 100% | **Completed (Late)** |
| 3.1.1 | CNN Architecture Selection | 100% | 100% | **Completed** |
| 4.3.1 | **Train the model (Full)** | 100% | **65%** | **🔴 BEHIND SCHEDULE** |
| 5.2.1 | Calculate Metrics | 100% | **0%** | **🔴 BLOCKED** |
| 6.1.1 | Create Dashboard Mockups | 50% | 80% | **🟢 AHEAD** |

## 3. Performance Analysis
**1. Largest Deviation:**
The **Model Training (Task 4.3.1)** is significantly behind schedule. It was scheduled to finish on Oct 17, but as of Oct 28, it is only 65% complete. This has blocked Task 5.0 (Evaluation).

**2. Root Causes:**
* **Technical Issue (Risk R1):** The initial training attempts on local laptops failed due to memory errors, causing a 3-day delay before we switched to Cloud GPUs.
* **Data Quality (Risk R2):** The "Filtering Images" task (2.3.1) took 3 days instead of the planned 2 days because the FER-2013 dataset had many mislabeled images that required manual cleaning.

**3. Impact Category:**
* **Schedule:** Critical Path is delayed by roughly 1 week.
* **Cost:** No budget overrun yet (we haven't spent the extra GPU money yet), but labor hours for Nadiah are higher than planned.
