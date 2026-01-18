# Project Scope Document

**Project Title:** SKIPZ - Facial Expression Recognition using CNN

## 1. Project Objectives
The primary goal of this project is to develop a Convolutional Neural Network (CNN) model that accurately identifies human facial expressions.
* **Data Collection:** Collect and preprocess a dataset of at least **10,000 labeled facial images** (e.g., from FER-2013) with augmentation.
* **Model Accuracy:** Develop and train a CNN model to classify emotions with a target accuracy of **80%** or higher.
* **Real-Time Performance:** Ensure the prototype system can classify an image within **500 milliseconds** to demonstrate real-time capability.
* **Ethical Compliance:** Ensure all data handling respects privacy standards and is used solely for academic research.

## 2. Key Deliverables
| Deliverable | Description |
| :--- | :--- |
| **Curated Dataset** | A cleaned, labeled, and augmented dataset of facial expressions (Rotated, brightened, normalized). |
| **Trained Model** | The final serialized model file (`.h5` or `.pkl`) optimized for emotion classification. |
| **Prototype Application** | A Python-based desktop application (using OpenCV) that takes an image/webcam feed and displays the predicted emotion. |
| **Project Report** | A comprehensive document detailing the methodology, confusion matrix analysis, and final performance metrics (Precision, Recall, F1-Score). |

## 3. Stakeholders
| Stakeholder | Role | Responsibility |
| :--- | :--- | :--- |
| **Dr. Farhan Khan** | Project Supervisor | Provides academic guidance, approves milestones, and evaluates final deliverables. |
| **SKIPZ Team** | Project Team | Responsible for data collection, model training, interface development, and testing. |
| **University Lab Admin** | Infrastructure Provider | Provides access to GPU resources and ensures network security compliance. |
| **End Users** | Testing Group | Students or staff who will test the prototype to verify usability and responsiveness. |

## 4. Tools & Integration
* **Project Management:** Microsoft Project / Excel (Scheduling), Microsoft Planner (Task Tracking).
* **Version Control:** GitHub (Code repository and documentation storage).
* **Collaboration:** Microsoft Teams (Daily stand-ups, file sharing, and peer reviews).
* **Development Stack:** Python, TensorFlow/Keras, OpenCV.
