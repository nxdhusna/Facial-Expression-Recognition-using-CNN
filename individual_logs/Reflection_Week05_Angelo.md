
## Week 05 – Reflection on Cost Management

### 1. Which project phase has the highest cost and why?
**Phase 6 (Dashboard Development)** has the highest estimated cost. This is driven primarily by **Human Resource** costs rather than hardware. Developing a functional real-time prototype requires specialized Full-Stack development hours (Task 6.3 and 6.4), which are billed at a higher rate and require more hours than the automated model training process in Phase 4.

### 2. How could you reduce costs without affecting quality?
We could implement **Transfer Learning** (using a pre-trained model like VGG16) instead of training a CNN from scratch. This would significantly reduce the **GPU compute time** required in Phase 4 (Model Training), lowering cloud rental costs. Additionally, using open-source frameworks like **Streamlit** for the dashboard (Task 6.3) instead of building a custom React app would reduce developer hours.

### 3. How does resource allocation influence your schedule and overall success?
Resource allocation is the critical constraint on our schedule. For example, in **Task 2.3 (Data Cleaning)**, assigning only one Data Engineer creates a bottleneck; if this task is delayed, the AI Architect cannot begin **Phase 3 (Model Design)**. Proper allocation ensures that dependencies are met on time, preventing "idle time" where expensive resources (like Cloud GPUs) are paid for but not utilized.
