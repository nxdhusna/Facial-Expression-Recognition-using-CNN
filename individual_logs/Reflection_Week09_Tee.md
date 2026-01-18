**Task:** Schedule Crashing & Optimization

## 1. Why is identifying the critical path important for project managers?
It is impossible to effectively shorten a project without knowing the critical path. As I learned during the crashing analysis, shortening a non-critical task (like "UI Development") is a waste of money because it doesn't change the project end date. Identifying the critical path ensures that any extra budget spent on crashing actually results in an earlier finish.

## 2. Which activity posed the highest scheduling risk?
**Activity F (Hyperparameter Tuning)** is a high risk. While we estimated 3 days, this is an iterative process that is hard to predict. Unlike coding (which has a definition of done), tuning can go on forever if we aren't satisfied with the metrics. Since it is on the critical path, an endless tuning loop would destroy our schedule.

## 3. What trade-offs are involved when crashing a project?
The primary trade-off is **Cost vs. Schedule**. In my analysis, reducing the project duration by 3 days required us to "buy" time by renting a Cloud GPU for the training phase. We had to decide if finishing early was worth the extra financial cost. Additionally, crashing can lead to team burnout if the method used is "overtime" rather than better tools.
