## Week 05 – Reflection on Cost Management

### 1. Which project phase has the highest cost and why?
**Phase 4 (Model Training)** carries the highest *variable* cost risk. While the base estimate is moderate, this phase relies on Cloud GPU instances (AWS/Colab Pro). If the model suffers from **Risk R2 (Accuracy Miss)**, we will be forced to run multiple retraining iterations, which causes the cloud costs to scale linearly with every failure, making it the most volatile financial phase.

### 2. How could you reduce costs without affecting quality?
We can utilize **Cloud Spot Instances** for our training runs (Task 4.3). Spot instances are often 70-90% cheaper than on-demand instances. To maintain quality and safety, we would implement frequent **Model Checkpoints**, ensuring that if the instance is reclaimed by the provider, we do not lose our training progress.

### 3. How does resource allocation influence your schedule and overall success?
Effective resource allocation minimizes **context switching**. By dedicating a specific team member (e.g., Angelo) solely to **Hyperparameter Tuning (Task 4.1)**, they can maintain deep focus. If resources are spread too thin across multiple phases (e.g., asking the AI Engineer to also do UI Design), the quality of the model drops, and the schedule slips due to cognitive load and task switching.
