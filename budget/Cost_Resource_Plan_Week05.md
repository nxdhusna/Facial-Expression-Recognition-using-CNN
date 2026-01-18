# Cost & Resource Plan - Week 05

## Identify Resources (Aligned with WBS)

| WBS ID | Task Name | Resource Type | Resource Assigned | Duration (Hours) | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1.0** | **Requirement Gathering** | | | | |
| 1.1.1 | Schedule Kick-Off Meeting | Human | Nadiah | 4 | Initial team alignment meeting. |
| 1.1.2 | Define Initial Scope | Human | Angelo | 4 | Documenting high-level boundaries. |
| 1.2.1 | Document functional requirements | Human | Qasdina | 4 | Listing key system functions. |
| 1.2.2 | Document non-functional requirements | Human | Angelo | 4 | defining performance constraints. |
| 1.3.1 | Obtain Stakeholder Sign-off | Human | Angelo | 8 | Formal approval process with supervisor. |
| **2.0** | **Data Collection** | | | | |
| 2.1.1 | Identify public datasets | Human | Qasdina | 8 | Researching FER-2013/CK+ datasets. |
| 2.2.1 | Download/Extract raw data | Human | Nadiah | 8 | Securely downloading image files. |
| 2.3.1 | Filter low-quality images | Human | Qasdina | 16 | Manual inspection and cleaning of data. |
| 2.3.2 | Resize and normalize images | Human | Angelo | 8 | Preprocessing script creation. |
| 2.4.1 | Apply transformations | Human | Angelo | 8 | Data augmentation (rotation, flipping). |
| 2.5.1 | Finalize version control dataset | Human | Qasdina | 8 | Committing final dataset to repo. |
| **3.0** | **Model Design** | | | | |
| 3.1.1 | Research CNN architectures | Human | Angelo | 8 | Selecting VGG/ResNet baseline structure. |
| 3.1.2 | Define layer structure | Human | Angelo | 8 | Finalizing specific layer details. |
| 3.2.1 | Set up ML environment | Human | Nadiah | 4 | Installing TensorFlow, Keras, and libraries. |
| 3.2.2 | Secure compute resources | Human | Nadiah | 4 | Verifying GPU access. |
| 3.3.1 | Develop initial model code | Human | Qasdina | 8 | Writing Python code for the architecture. |
| **4.0** | **Model Training** | | | | |
| 4.1.1 | Define hyperparameters | Human | Angelo | 8 | Determining learning rate and batch size. |
| 4.2.1 | Execute initial training run | Human | Qasdina | 8 | Testing pipeline on small subset. |
| 4.3.1 | Train the model (Labor) | Human | Nadiah | 24 | Monitoring the training process and logs. |
| 4.3.1 | Train the model (Compute) | Hardware | Cloud GPU | 24 | GPU Instance rental cost for deep learning. |
| 4.3.2 | Monitor loss/accuracy metrics | Human | Qasdina | 8 | Checking for overfitting/underfitting. |
| 4.4.1 | Save best-performing model | Human | Angelo | 8 | Saving the .h5 model file. |
| **5.0** | **Model Evaluation** | | | | |
| 5.1.1 | Prepare unseen test dataset | Human | Qasdina | 4 | separating final test data. |
| 5.2.1 | Calculate performance metrics | Human | Angelo | 8 | Generating Confusion Matrix and F1 Scores. |
| 5.3.1 | Analyze misclassified images | Human | Nadiah | 8 | Identifying error patterns. |
| 5.4.1 | Document final performance | Human | Angelo | 4 | Writing evaluation summary. |
| **6.0** | **Dashboard Development** | | | | |
| 6.1.1 | Create mockups | Human | Nadiah | 8 | Designing UI wireframes. |
| 6.2.1 | Integrate model with app | Human | Angelo | 8 | Building backend prediction logic. |
| 6.3.1 | Code user interface elements | Human | Qasdina | 8 | Implementing Streamlit frontend. |
| 6.4.1 | Finalize deployable package | Human | Nadiah | 8 | Preparing executable/container. |
| **7.0** | **Testing & Validation** | | | | |
| 7.1.1 | Test individual components | Human | Qasdina | 8 | Unit testing core modules. |
| 7.2.1 | Test end-to-end speed | Human | Angelo | 8 | Measuring latency (< 500ms). |
| 7.3.1 | Conduct UAT | Human | Qasdina | 8 | Running prototype with non-team users. |
| 7.4.1 | Record test results | Human | Nadiah | 8 | Documenting final test findings. |
| **8.0** | **Report & Presentation** | | | | |
| 8.1.1 | Document methodology | Human | Angelo | 24 | Writing final report chapters. |
| 8.2.1 | Design slides | Human | Qasdina | 8 | Creating presentation deck. |
| 8.3.1 | Conduct team review | Human | All Team (3) | 8 | Final quality check meeting. |
| 8.4.1 | Deliver final project assets | Human | All Team (3) | 8 | Finalizing deliverables for submission. |

<br>

## Summarize Costs (Full Detailed Breakdown)

| Task Name | Resource | Hours | Rate (RM/hr) | Total Cost (RM) |
| :--- | :--- | :--- | :--- | :--- |
| Schedule Kick-Off Meeting | Nadiah | 4 | 20 | 80 |
| Define Initial Scope | Angelo | 4 | 20 | 80 |
| Document functional requirements | Qasdina | 4 | 20 | 80 |
| Document non-functional requirements | Angelo | 4 | 20 | 80 |
| Obtain Stakeholder Sign-off | Angelo | 8 | 20 | 160 |
| Identify public datasets | Qasdina | 8 | 20 | 160 |
| Download/Extract raw data | Nadiah | 8 | 20 | 160 |
| Filter low-quality images | Qasdina | 16 | 20 | 320 |
| Resize and normalize images | Angelo | 8 | 20 | 160 |
| Apply transformations | Angelo | 8 | 20 | 160 |
| Finalize version control dataset | Qasdina | 8 | 20 | 160 |
| Research CNN architectures | Angelo | 8 | 20 | 160 |
| Define layer structure | Angelo | 8 | 20 | 160 |
| Set up ML environment | Nadiah | 4 | 20 | 80 |
| Secure compute resources | Nadiah | 4 | 20 | 80 |
| Develop initial model code | Qasdina | 8 | 20 | 160 |
| Define hyperparameters | Angelo | 8 | 20 | 160 |
| Execute initial training run | Qasdina | 8 | 20 | 160 |
| **Train the model (Labor)** | Nadiah | 24 | 20 | 480 |
| **Train the model (GPU Compute)** | Cloud GPU | 24 | 5 | 120 |
| Monitor loss/accuracy metrics | Qasdina | 8 | 20 | 160 |
| Save best-performing model | Angelo | 8 | 20 | 160 |
| Prepare unseen test dataset | Qasdina | 4 | 20 | 80 |
| Calculate performance metrics | Angelo | 8 | 20 | 160 |
| Analyze misclassified images | Nadiah | 8 | 20 | 160 |
| Document final performance | Angelo | 4 | 20 | 80 |
| Create mockups | Nadiah | 8 | 20 | 160 |
| Integrate model with app | Angelo | 8 | 20 | 160 |
| Code user interface elements | Qasdina | 8 | 20 | 160 |
| Finalize deployable package | Nadiah | 8 | 20 | 160 |
| Test individual components | Qasdina | 8 | 20 | 160 |
| Test end-to-end speed | Angelo | 8 | 20 | 160 |
| Conduct UAT | Qasdina | 8 | 20 | 160 |
| Record test results | Nadiah | 8 | 20 | 160 |
| Document methodology | Angelo | 24 | 20 | 480 |
| Design slides | Qasdina | 8 | 20 | 160 |
| Conduct team review | All Team (3) | 8 | 60 (20x3) | 480 |
| Deliver final project assets | All Team (3) | 8 | 60 (20x3) | 480 |
| **TOTAL PROJECT COST** | | | | **7,120** |

<br>

## Project Budget Overview

| Cost Category | Description | Subtotal (RM) |
| :--- | :--- | :--- |
| **Human Resources** | 3 Team Members (Design, Dev, Testing, Documentation) | 7,000 |
| **Hardware / Cloud** | Cloud GPU Rental (24 hours @ RM 5/hr) | 120 |
| **Software / Licenses** | Open Source Tools (GitHub, Python, Teams) | 0 |
| **TOTAL ESTIMATED BUDGET** | | **7,120** |

<br>

## Integration Notes
- **Schedule Alignment:** The costs above are directly derived from the "Duration" and "Resources" columns in the Week 03 Project Schedule.
- **Budget Driver:** Human labor is the primary cost driver (98% of budget), reflecting the academic nature of the project where software tools are typically free/open-source.
- **Risk Reserve:** The "Model Training" phase carries the highest financial risk; if training exceeds the estimated 24 hours, GPU costs will rise, potentially impacting the hardware budget.
