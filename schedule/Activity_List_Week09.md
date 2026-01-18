#  Activity List & Dependencies

| Activity ID | Activity Name | Duration (Days) | Predecessor(s) | Logic/Notes |
| :---: | :--- | :---: | :---: | :--- |
| **A** | Define Project Scope & Dataset | 2 | — | Starts the project |
| **B** | Data Collection (Images) | 3 | A | Need scope (A) before collecting |
| **C** | Data Preprocessing | 4 | B | Need raw data (B) to preprocess |
| **D** | Design CNN Architecture | 3 | A | Can start designing once scope (A) is known |
| **E** | Model Training | 6 | C, D | Needs processed data (C) AND architecture (D) |
| **F** | Model Testing & Validation | 3 | E | Must train (E) before testing |
| **G** | Develop User Interface (UI) | 5 | D | Can start UI once design (D) is known |
| **H** | System Integration | 2 | F, G | Combines tested model (F) and UI (G) |
| **I** | Final Report & Documentation | 4 | H | Final step after system is ready |
