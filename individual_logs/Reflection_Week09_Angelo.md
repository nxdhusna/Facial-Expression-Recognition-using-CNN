**Task:** PDM & Schedule Calculations

## 1. Why is identifying the critical path important for project managers?
Identifying the critical path is crucial because it reveals the specific chain of activities that have "zero slack". In our PDM calculations, I saw that while the "CNN Architecture Design" had 4 days of float, the "Data Collection" path had none. This mathematical certainty tells me exactly which tasks will delay the entire project if they slip, allowing me to prioritize monitoring those specific activities over others.

## 2. Which activity posed the highest scheduling risk?
**Activity E (Model Training)** posed the highest risk. Mathematically, it has the longest duration (6 days) and sits directly on the critical path. If our model fails to converge or the accuracy is poor, we cannot simply "make up the time" later because there is no slack. It acts as a bottleneck for the subsequent testing and integration phases.

## 3. What trade-offs are involved when crashing a project?
Crashing inevitably involves trading **resources/quality for time**. For example, to shorten the schedule, we analyzed "crashing" the training phase. The trade-off is financial (paying for expensive Cloud GPUs instead of using free local resources) or quality-based (reducing the number of training epochs, which might lower the model's final accuracy).
