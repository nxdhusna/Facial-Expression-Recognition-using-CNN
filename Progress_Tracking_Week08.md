# Week 08 - Progress Tracking & Performance Analysis

## Project Baseline Summary
*Based on Week 03 Schedule and Week 05 Cost Plan:*
- **Project Name:** Facial Expression Recognition using CNN
- **Planned Duration:** 32 Days (Oct 07 – Nov 08)
- **Planned Budget:** **RM 6,840** (Labor + RM 120 Hardware Reserve)
- **Key Milestones:**
    1. Requirement Sign-off (WBS 1.3.1)
    2. Data Augmentation Complete (WBS 2.4.1)
    3. Model Training Completion (WBS 4.3.1)
    4. Prototype Deployment (WBS 6.4.1)

## Progress Tracking (Midway through Execution)
*Status Date: October 28 (Week 07)*

| WBS ID | Task Name | Planned % | Actual % | Status |
| :--- | :--- | :--- | :--- | :--- |
| 2.4.1 | Apply transformations (augmentation) | 100% | 100% | **Completed** |
| 3.3.1 | Develop initial model code | 100% | 100% | **Completed** |
| 4.1.1 | Define hyperparameters | 100% | 100% | **Completed** |
| 4.3.1 | **Train model on full dataset** | 100% | **65%** | **🔴 BEHIND** |
| 4.3.2 | Monitor loss and accuracy | 100% | 50% | **🔴 BEHIND** |
| 5.2.1 | Calculate performance metrics | 40% | 0% | **🔴 BLOCKED** |

## Performance Analysis
1. **Largest Deviation:**
   Task 4.3.1 (Model Training) shows the largest deviation. It was scheduled to complete by **Oct 17**, but is currently stalled at 65% completion due to hardware throughput issues.

2. **Possible Causes:**
   The training process is taking significantly longer than the estimated 3 days. We initially attempted to use standard "Free Tier" resources to save costs, but they are struggling with the 10,000+ augmented images, leading to timeouts and slow epoch completion.

3. **Relation to Risks:**
   This issue is a realization of **Risk R1 (Computer is too slow)** from our Risk Register. We identified that local/free hardware might bottleneck the schedule, and that risk has now occurred. We must now trigger the mitigation plan (using the paid budget).
