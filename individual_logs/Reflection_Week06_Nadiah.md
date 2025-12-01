# Reflection Week 06

# 1. Which quality criterion do you think will be hardest to achieve?
The **Accuracy Target (> 85%)** will be the most difficult. Human emotions are subtle; the difference between "neutral" and "sad" can be very small in a photo. Ensuring the model doesn't get confused between similar emotions will require a very clean, high-quality dataset, which is hard to find for free.

# 2. Which risk poses the greatest threat to your project and why?
**R2 (Not enough face photos/Data Quality)** is the major risk. In AI projects, "garbage in equals garbage out." If our dataset is unbalanced (e.g., 5000 happy faces but only 500 sad faces), the model will fail to recognize sad faces entirely. Without good data, the code doesn't matter.

# 3. How does quality management support project success?
It helps us define what "success" actually looks like. Instead of just saying "it works," the quality checklist forces us to verify specific things—like checking if the data is balanced and if the bounding boxes appear correctly. It acts as a safety net to ensure we don't submit a broken or biased project.
