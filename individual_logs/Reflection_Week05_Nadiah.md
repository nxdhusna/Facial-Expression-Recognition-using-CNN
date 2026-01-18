## Week 05 – Reflection on Cost Management

### 1. Which project phase has the highest cost and why?
**Phase 4 (Model Training) is the most expensive technical phase (RM 1,240). Unlike other phases which rely solely on human labor, this phase incurs a "double cost": it requires the longest single labor duration (24 hours for monitoring training, Task 4.3.1) plus the project's only direct hardware expense (Cloud GPU rental). While Phase 8 is higher in total due to team size, Phase 4 is the most resource-intensive individual activity.

### 2. How could you reduce costs without affecting quality?
We could automate the **Data Augmentation** process (Task 2.4) using Python scripts (e.g., Keras ImageDataGenerator) rather than manual sorting. Furthermore, verifying our data quality on a small "sample batch" before running the full training cycle would prevent wasting GPU resources on bad data ("Garbage In, Garbage Out").

### 3. How does resource allocation influence your schedule and overall success?
Resource allocation dictates the **Critical Path** of the project. If we under-allocate resources to critical tasks like **Integration (Task 6.2)**, the entire project delivery is delayed regardless of how fast the model was trained. Successful allocation ensures that high-priority tasks have sufficient coverage to absorb unexpected delays without derailing the final deadline.
