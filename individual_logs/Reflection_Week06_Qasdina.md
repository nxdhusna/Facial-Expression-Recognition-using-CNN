# Reflection Week 06

# 1. Which quality criterion do you think will be hardest to achieve?
The **Performance Expectation (< 500ms per frame)** will be the hardest. Running a Deep Learning model (CNN) on a live video feed requires significant processing power. Since we are developing on standard laptops without dedicated GPUs, achieving real-time speed without "lag" will require very efficient coding and possibly reducing the image resolution.

# 2. Which risk poses the greatest threat to your project and why?
**R1 (Computer is too slow)** is the biggest threat. Deep learning models take hours or even days to train. If our hardware is too slow, every time we find a bug or want to change a parameter, we lose valuable time waiting. This could push our schedule back significantly if we don't use cloud resources like Google Colab.

# 3. How does quality management support project success?
Quality management prevents us from "over-engineering." By setting a specific target (85% accuracy), I know exactly when the model is "good enough" to stop training and start building the interface. Without these definitions, I might waste weeks trying to get 99% accuracy when it isn't strictly necessary for a prototype.
