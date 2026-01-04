# Cost & Resource Plan - Week 05

## Part 2 – Identify Resources

| WBS ID | Task | Resource Type | Resource Name | Quantity / Hours | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1.0** | **Requirement Gathering** | | | | |
| 1.1 | Project Kick-off | Human | Project Manager | 2 hrs | Initial team meeting & scope alignment. |
| 1.2 | User Needs Analysis | Human | Business Analyst | 4 hrs | Defining emotion categories needed. |
| 1.3 | Final Requirements Document | Software | MS Word | - | Documenting the agreed scope. |
| **2.0** | **Data Collection** | | | | |
| 2.1 | Data Source ID | Human | Data Scientist | 3 hrs | Identifying datasets (CK+, FER-2013). |
| 2.2 | Data Acquisition | Software | Python Scripts | - | Downloading/scraping images. |
| 2.3 | Data Cleaning & Preprocessing | Human | Data Engineer | 6 hrs | Resizing and grayscale conversion code. |
| 2.4 | Data Augmentation | Hardware | Local GPU | 4 hrs | Generating rotated/flipped images. |
| **3.0** | **Model Design** | | | | |
| 3.1 | Architecture Selection | Human | AI Architect | 3 hrs | Choosing CNN model structure. |
| 3.2 | Environment Setup | Software | Anaconda / TensorFlow | - | Installing libraries and dependencies. |
| 3.3 | Initial Model Codebase | Human | AI Engineer | 5 hrs | Writing the skeleton Python code. |
| **4.0** | **Model Training** | | | | |
| 4.1 | Parameter Tuning | Human | AI Engineer | 4 hrs | Adjusting learning rates/epochs. |
| 4.2 | Initial Training Run | Hardware | Cloud GPU (AWS/Colab) | 2 hrs | Testing pipeline on small data. |
| 4.3 | Full Training & Optimization | Hardware | Cloud GPU (High-end) | 12 hrs | Full training cycle. |
| **5.0** | **Model Evaluation** | | | | |
| 5.1 | Test Data Preparation | Human | Data Scientist | 2 hrs | Segregating the validation set. |
| 5.2 | Performance Metrics Calc | Software | Scikit-Learn | - | Generating Confusion Matrix. |
| 5.3 | Error Analysis | Human | Data Scientist | 4 hrs | Analyzing false positives. |
| **6.0** | **Dashboard Development** | | | | |
| 6.1 | UI/UX Design | Human | UI Designer | 3 hrs | Designing the webcam interface. |
| 6.2 | Back-End Integration | Human | Back-End Dev | 6 hrs | Connecting model to API. |
| 6.3 | Front-End Implementation | Software | Streamlit / React | - | Building the user interface. |
| **7.0** | **Testing & Validation** | | | | |
| 7.1 | Unit Testing | Human | QA Tester | 4 hrs | Testing individual modules. |
| 7.3 | User Acceptance Testing (UAT)| Human | Beta Users | 5 users | Live testing with real faces. |
| **8.0** | **Report & Presentation** | | | | |
| 8.1 | Final Report Drafting | Human | Project Team | 8 hrs | Writing final documentation. |
| 8.2 | Presentation Preparation | Software | PowerPoint | - | Creating slide deck. |

<br>

## Part 3 – Summarize Costs

| Task (Selected High-Cost Items) | Hours | Rate (RM/hr) | Total Cost (RM) |
| :--- | :--- | :--- | :--- |
| Project Kick-off (PM) | 2 | 30 | 60 |
| Data Cleaning & Preprocessing | 6 | 25 | 150 |
| Initial Model Codebase | 5 | 35 | 175 |
| Full Training & Optimization (Cloud GPU) | 12 | 10 | 120 |
| Back-End Integration | 6 | 30 | 180 |
| Final Report Drafting | 8 | 20 | 160 |
| **Total (Selected Tasks Only)** | **--** | **--** | **845** |

<br>

## Part 4 – Project Budget Overview

| Cost Category | Example Items | Subtotal (RM) |
| :--- | :--- | :--- |
| **Human Resources** | Project Manager, AI Engineers, QA Testers (Labor) | 1,850 |
| **Hardware / Cloud** | Cloud GPU rental (AWS/Colab), Storage | 250 |
| **Software / Licenses** | Hosting fees, paid datasets (if any) | 100 |
| **Communication / Misc** | Printing, contingency buffer | 150 |
| **Total Estimated Budget** | | **2,350** |
