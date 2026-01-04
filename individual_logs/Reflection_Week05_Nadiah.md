## Week 05 – Reflection on Cost Management

### 1. Which project phase has the highest cost and why?
**Phase 2 (Data Collection & Preparation)** represents a significant hidden cost in terms of labor hours. Although it doesn't require expensive hardware, the process of cleaning, labeling, and augmenting thousands of facial images (Task 2.3 & 2.4) is labor-intensive. In AI projects, data preparation often consumes 60-80% of the team's total effort, making it the most expensive phase in terms of "man-hours."

### 2. How could you reduce costs without affecting quality?
We could automate the **Data Augmentation** process (Task 2.4) using Python scripts (e.g., Keras ImageDataGenerator) rather than manual sorting. Furthermore, verifying our data quality on a small "sample batch" before running the full training cycle would prevent wasting GPU resources on bad data ("Garbage In, Garbage Out").

### 3. How does resource allocation influence your schedule and overall success?
Resource allocation dictates the **Critical Path** of the project. If we under-allocate resources to critical tasks like **Integration (Task 6.2)**, the entire project delivery is delayed regardless of how fast the model was trained. Successful allocation ensures that high-priority tasks have sufficient coverage to absorb unexpected delays without derailing the final deadline.
