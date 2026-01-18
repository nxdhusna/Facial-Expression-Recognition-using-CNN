# Corrective Actions Plan (Week 08)

To recover the schedule delay identified in the Progress Tracking report, the following actions will be taken immediately.

## Action 1: Resource Reallocation (Crashing)
* **Issue:** Model Training is stalled at 65%.
* **Action:** We will immediately utilize the **RM 120 Cloud GPU budget** (Week 05 Plan) to rent a high-performance instance (e.g., AWS p3.2xlarge or Colab Pro+) instead of relying on the free tier.
* **Resource Impact:** This increases hardware cost but reduces training time from 24 hours to ~8 hours.
* **Owner:** Nadiah
* **Status:** In Progress.

## Action 2: Schedule Fast-Tracking
* **Issue:** Dashboard Development (Phase 6) is blocked waiting for the model.
* **Action:** We will decouple the Dashboard task from the Model task. Qasdina will begin **Task 6.3.1 (Coding UI)** immediately using a "dummy" random-number generator as a placeholder for the AI predictions.
* **Benefit:** This allows the Interface to be 90% finished while the Model is still training. Once the model is ready, we only need to swap the placeholder for the real file.
* **Owner:** Qasdina
* **Status:** Scheduled for tomorrow.
