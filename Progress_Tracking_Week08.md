# Week 08 - Progress Tracking & Performance Analysis

## Project Baseline Summary
- **Project Name:** Facial Expression Recognition using CNN
- **Planned Duration:** 35.5 Days
- **Planned Budget:** $0 (Utilizing Open Source Tools & Google Colab)
- **Key Milestones:**
    1. Requirement Sign-off (WBS 1.3.1)
    2. Data Augmentation Complete (WBS 2.4.1)
    3. Model Training Completion (WBS 4.3.1)
    4. Prototype Deployment (WBS 6.4.1)

## Progress Tracking (Midway through Execution)
| WBS ID | Task Name | Planned % | Actual % | Status |
| :--- | :--- | :--- | :--- | :--- |
| 2.4.1 | Apply transformations (augmentation) | 100% | 100% | Completed |
| 3.3.1 | Develop initial model code | 100% | 100% | Completed |
| 4.1.1 | Define hyperparameters | 100% | 100% | Completed |
| 4.3.1 | Train model on full dataset | 100% | 65% | **Behind** |
| 4.3.2 | Monitor loss and accuracy | 100% | 50% | **Behind** |
| 5.2.1 | Calculate performance metrics | 40% | 0% | **Behind** |

## Performance Analysis
1. **Largest Deviation:** Task 4.3.1 (Model Training). We are currently at 65% completion, whereas we should have finished the training phase by the end of this week.
2. **Possible Causes:** The training process is taking significantly longer than the estimated 3 days. The local GPU resources are struggling with the 10,000+ augmented images, leading to system crashes and slow epoch completion.
3. **Relation to Risks:** This issue is directly related to **Risk R1 (Computer is too slow)** and **Risk R3 (Video Lag/Processing speed)** identified in our Risk Register.
