#  Machine Learning & Generative AI Solutions  

![image](https://github.com/user-attachments/assets/3e7d06c7-d853-406d-aa9c-bde1ae502a10)


## 📌 Overview  
This project consists of two key phases:  
1. **Phase 1: ML Model Optimization & Explainability** – Improving predictive model performance and interpretability.  
2. **Phase 2: AI-Powered Personalized Marketing Email System** – Implementing an LLM-based email generation system.  

Each phase contributes to ABC Corp Ltd’s **data-driven decision-making and AI-powered automation** for enhanced business operations.

---

## 📖 **Phase 1: ML Model Optimization & Explainability**  

### 🔍 **Objective**  
Optimize and interpret ML models for **predicting customer behavior** using **feature engineering, hyperparameter tuning, and SHAP-based explainability.**  

### 📊 **Key Steps & Results**  

1. **Baseline Model Evaluation**  
   - Models tested: **Linear Regression & Random Forest**  
   - Metrics (before tuning):  
     - **Linear Regression:** MAE = 21.14, RMSE = 23.85  
     - **Random Forest:** MAE = 22.28, RMSE = 25.48  

2. **Hyperparameter Tuning & Optimization**  
   - Tuned models: **Random Forest, Ridge, Lasso**  
   - Best hyperparameters identified:  
     - **RF:** `max_depth=3`, `n_estimators=50`  
     - **Ridge:** `alpha=100`  
     - **Lasso:** `alpha=10`  
   - Metrics (after tuning):  
     - **Optimized RF:** MAE = 21.67, RMSE = 24.44  
     - **Optimized Ridge:** MAE = 21.18, RMSE = 23.87  
     - **Optimized Lasso:** MAE = 21.36, RMSE = 24.00  

3. **Model Explainability with SHAP**  
   - **SHAP Summary Plot:** Highlights **feature importance and impact** on predictions.  
   - **SHAP Force Plot:** Visualizes individual prediction influence.  
   - **Feature Importance Plot:** Identifies **top influential features** in **Random Forest.**  

🔹 **Conclusion:** The optimized **Ridge Regression** model performed best with **reduced error metrics**, and SHAP analysis provided transparency in decision-making.

---

## 📖 **Phase 2: AI-Powered Personalized Marketing Email System**  

### 🎯 **Objective**  
Implement an **LLM-based system** to generate **personalized marketing emails** for customers using **few-shot learning & chain-of-thought prompting.**  

### 🏢 **About ABC Corp Ltd**  
- **Industry**: Leading E-commerce chain  
- **Website**: [ABCcorp.com](https://ABCcorp.com)  
- **Social Media**: `@abccorp4all`  
- **Customer Support**: 📞 12345684  

### 🤖 **System Implementation**  
1. **Pre-trained LLM**: `deepseek-r1-distill-llama-70b` via **Groq API**  
2. **Personalization Factors**:
   - Customer **name & last purchase history**  
   - **Preferred product category**  
   - **Exclusive discounts & promotional offers**  
3. **Few-Shot Learning Approach**:
   - Providing the LLM with **realistic email examples**  
   - Ensuring **brand consistency & promotional effectiveness**  
4. **Chain-of-Thought Prompting**:
   - Improving logical flow and structured email generation  

### 🔬 **Additional Exploration: AI Email Agent with PhiData**  
- Implemented an **AI-driven email agent** using **PhiData framework** for:  
  - **Automated email structuring**  
  - **Customer segmentation**  
  - **Message optimization**  

---

## 🚀 **Next Steps**  
✅ **Phase 1**: Deploy the **best ML model** analytics pipeline.  
✅ **Phase 2**: **Refine & A/B Test** AI-generated emails for increased conversion rates.  
🔜 **Phase 3**: Develop a **UI for email automation & marketing campaign execution.**  

---

### **📌 Summary**  
This project successfully integrates **ML model optimization** and **Generative AI**  **predictive analytics & marketing automation.** 🚀  
