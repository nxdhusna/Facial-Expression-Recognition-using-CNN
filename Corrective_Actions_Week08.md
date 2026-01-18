# Week 08 - Corrective Actions

Based on the Progress Tracking Report showing delays in the Model Training phase (WBS 4.3.1), the following corrective actions are being implemented immediately to bring the project back on track.

## 1. Resource Reallocation (Response to Risk R1)
* **Issue:** Local hardware is too slow, causing Task 4.3.1 to lag behind schedule.
* **Corrective Action:** Move the training environment from local hardware to **Google Colab Pro** to utilize high-performance cloud GPUs.
* **Budget Impact:** This utilizes the **RM 120 Hardware Reserve** allocated in the Week 05 Cost Plan.
* **Responsibility:** Nadiah (Task Owner)
* **Status:** In Progress

## 2. Schedule Crashing (Fast-Tracking)
* **Issue:** The delay in training impacts the downstream dashboard integration.
* **Corrective Action:** We will "de-couple" the dashboard tasks. Qasdina will begin **Task 6.3.1 (Coding UI)** immediately using placeholder data, rather than waiting for the model to finish. This allows development to proceed in parallel with training.
* **Responsibility:** Qasdina
* **Status:** Scheduled

## 3. Scope Refinement (Contingency Plan)
* **Issue:** Potential for further delays if training accuracy does not converge.
* **Corrective Action:** If the cloud training takes longer than 24 hours, we will reduce the number of training epochs from **100 to 50**, provided the validation accuracy remains above our quality target of 75% (Acceptance Criteria).
* **Responsibility:** Angelo (AI Architect)
* **Status:** Pending Review
