# fusion-igni
Nuclear Fusion Ignition Prediction Model

**🚀 Machine Learning in Nuclear Fusion Research: Predicting Ignition! 🔥**

🔹 **Project Overview**:
In this project, we explored a **classification problem** using machine learning to predict **ignition success** in a **simulated nuclear fusion experiment dataset**. The dataset contains **100,000 experiments**, each with multiple critical parameters such as **fuel density, temperature, energy input, and neutron yield**. Understanding these factors is crucial for advancing sustainable **carbon-free energy solutions**.

🔹 **Dataset & Features**:
We conducted **feature selection** based on **Variance Inflation Factor (VIF) and Mutual Information** to reduce multicollinearity and select the most important predictors. Our final selected features:

✔ **Target Composition**  
✔ **Magnetic Field Configuration**  
✔ **Instabilities**  
✔ **Beam Symmetry**  
✔ **Leakage**  
✔ **Injection Energy**  

🔹 **Model Selection & Performance**:
We trained and evaluated three different models:
1️⃣ **Random Forest** – **Accuracy: 68.8%**
2️⃣ **K-Nearest Neighbors (KNN)** – **Accuracy: 63.5%**
3️⃣ **Neural Network (MLP)** – **Accuracy: 69.9%** (Best Performing Model 🎯)

📊 **MLP Model Performance**:
- Precision: **69%**  
- Recall: **70%**  
- F1-score: **69%**  
- Tuned the **hidden layers, activation function, and optimizer** to enhance performance.

🔹 **Deployment & Visualization**:
✅ **Animated the model’s test predictions** to visually analyze the classification performance.  
✅ **Deployed the best model** to Kaggle for further validation.  

🔹 **Key Takeaways**:
📌 Feature selection played a significant role in improving model efficiency.  
📌 Neural networks outperformed traditional methods in classifying fusion ignition events.  
📌 This research could accelerate fusion technology by predicting successful ignition conditions.

💡 **Next Steps**:
- Explore more **deep learning architectures**.
- Implement **explainable AI (XAI)** to understand model decisions better.
- Collaborate with **fusion energy researchers** to refine predictive modeling.

