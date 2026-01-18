
## Week 05 – Reflection on Cost Management

### 1. Which project phase has the highest cost and why?
**Phase 8 (Report & Presentation) has the highest estimated cost (RM 1,600). This was surprising, as we initially assumed technical phases would be more expensive. However, the final documentation and delivery (Tasks 8.3.1 and 8.4.1) require all three team members to work simultaneously for final reviews and asset compilation. This "all-hands-on-deck" approach triples the hourly labor cost compared to development phases where members work individually.

### 2. How could you reduce costs without affecting quality?
We could implement **Transfer Learning** (using a pre-trained model like VGG16) instead of training a CNN from scratch. This would significantly reduce the **GPU compute time** required in Phase 4 (Model Training), lowering cloud rental costs. Additionally, using open-source frameworks like **Streamlit** for the dashboard (Task 6.3) instead of building a custom React app would reduce developer hours.

### 3. How does resource allocation influence your schedule and overall success?
Resource allocation is the critical constraint on our schedule. For example, in **Task 2.3 (Data Cleaning)**, assigning only one Data Engineer creates a bottleneck; if this task is delayed, the AI Architect cannot begin **Phase 3 (Model Design)**. Proper allocation ensures that dependencies are met on time, preventing "idle time" where expensive resources (like Cloud GPUs) are paid for but not utilized.
