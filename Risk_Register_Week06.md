# Risk Register (Week 06)

# 1. Risk Table
| Risk ID | Description | Category | Likelihood (1-5) | Impact (1-5) | Score (L x I) | Response |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **R1** | *Computer is too slow:* Training the AI model takes too long on a regular laptop. | Resource | 4 | 4 | **16** | **Transfer:** Use Cloud GPUs (Budgeted). |
| **R2** | *Not enough face photos:* We might not find 10,000 quality images or they lack variety. | Technical | 3 | 5 | **15** | **Mitigate:** Use data augmentation. |
| **R3** | *Video lag:* The AI takes too long (>500ms) to process video frames. | Technical | 3 | 4 | **12** | **Mitigate:** Resize images/frame skip. |
| **R4** | *Coding errors:* Debugging Python errors takes longer than planned. | Schedule | 3 | 3 | **9** | **Accept:** Prioritize core features first. |
| **R5** | *Team availability:* A member gets sick or is busy with other assignments. | Stakeholder | 2 | 4 | **8** | **Transfer:** Reassign tasks immediately. |
| **R6** | *Budget Overrun:* Cloud GPU training hours exceed the estimated 24 hours. | Cost | 2 | 4 | **8** | **Mitigate:** Monitor usage strict limits. |

# 2. Top Priority Risks (Mitigation Plans)
*Based on the highest scores above:*

**1. R1 – Computer is too slow (Score: 16)**
- *Mitigation:* Switch from local laptop training to **Paid Cloud GPUs (AWS/Colab Pro)**. We have allocated **RM 120** in the Week 05 budget to cover this resource if the free tier is insufficient.
- *Owner:* Angelo
- *Tentative Date:* Week 07

**2. R2 – Not enough face photos (Score: 15)**
- *Mitigation:* If we cannot find 10,000 images, we will apply data augmentation (random rotations, lighting changes, flipping) to multiply our existing dataset.
- *Owner:* Qasdina
- *Tentative Date:* Week 06

**3. R3 – Video lag (Score: 12)**
- *Mitigation:* Implement a frame-skipping algorithm (process every 3rd frame) or reduce input resolution (e.g., to 640x480) to improve speed.
- *Owner:* Nadiah
- *Tentative Date:* Week 09 (Testing Phase)

# Integration Notes
- **Budget Link:** R1 and R6 are directly linked to the "Model Training" budget in Week 05.
- **Schedule Link:** Delays in R4 (Coding) will impact the "Dashboard Development" milestone.
- **Quality Link:** R2 (Data) is mitigated by the "Quality Check 3" (Dataset Size) in the Project Plan.
