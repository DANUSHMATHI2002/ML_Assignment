# **Multilayer Perceptron (MLP) - Machine Learning Tutorial**

## **📌 Project Overview**
This repository contains a complete tutorial on **Multilayer Perceptrons (MLPs)**, including:  
✅ **Theoretical Explanation** of MLPs and their components.  
✅ **Mathematical Formulations** such as forward propagation, activation functions, and backpropagation.  
✅ **Python Implementation** using **TensorFlow & Keras**.  
✅ **Dataset Analysis** using the **Wine Quality Dataset**.  
✅ **Model Training, Evaluation & Visualization**.  

This tutorial is designed to help students and professionals understand **how MLPs work** and **how to implement them effectively**.  

---  

## **📂 Repository Contents**  

### **1️⃣ Documentation**  
- 📄 **`ML_Transcript.pdf`** → Full transcript of the tutorial video.  
- 🎥 **`ML_Tutorial.mp4`** → Tutorial video covering MLPs.  

### **2️⃣ Code Files**  
- 📌 **`ML_assignment.ipynb`** → Jupyter Notebook with full Python implementation.  

### **3️⃣ Other Files**  
- 📄 **`requirements.txt`** → List of required Python packages.  
- 📌 **`LICENSE`** → Project license file.  

---  

## **🔧 Installation & Setup**  

Follow these steps to set up and run the project on your local machine:  

### **📌 Step 1: Clone the Repository**  
```bash
git clone https://github.com/your-username/ML_Assignment.git
cd ML_Assignment
```

### **📌 Step 2: Install Dependencies**  
Ensure you have **Python 3.7+** installed. Then, install required libraries:  
```bash
pip install -r requirements.txt
```  
If `requirements.txt` is missing, manually install dependencies:  
```bash
pip install tensorflow pandas numpy matplotlib scikit-learn jupyter
```  

### **📌 Step 3: Run the Jupyter Notebook**  
```bash
jupyter notebook ML_assignment.ipynb
```  

---  

## **📊 Dataset Details**  
We use the **Wine Quality Dataset** from the UCI Machine Learning Repository.  

- **Features:** Acidity, sugar content, alcohol content, etc.  
- **Target:** Wine quality ratings (1-10 scale).  
- **Objective:** Train an MLP model to predict wine quality based on its chemical properties.  

---  

## **🚀 Model Architecture**  
- **Input Layer:** Takes in the preprocessed features.  
- **Hidden Layers:** Two hidden layers with **ReLU activation**.  
- **Output Layer:** Predicts a continuous value (wine quality score).  
- **Optimizer:** **Adam**  
- **Loss Function:** **Mean Squared Error (MSE)**  

---  

## **🖥️ Running the Code**  
After running the script, you will see:  
✅ **Training progress** with loss & accuracy metrics.  
✅ **Graphs showing model performance over epochs.**  
✅ **Predictions on new wine samples.**  

---  

## **📈 Results & Performance**  
After training for **200 epochs**, our MLP model achieves:  

- **Mean Absolute Error (MAE):** **0.4821**  
- **R² Score:** **0.4523**  

---  

## **⚖️ Ethical AI Considerations**  
- **Bias Handling:** The dataset is balanced to ensure fair predictions.  
- **Accessibility:** The visuals are color-blind friendly, and the report supports screen readers.  
- **Transparency:** All code and datasets are open-source.  

---  

## **📝 License**  
This project is licensed under the **MIT License** - you are free to use, modify, and share it.  

---  

## **📩 Contact & Contributions**  
👨‍💻 **Author:** DANUSHMATHI PATHMANABAN  
📧 **Email:** [danushmathip@gmail.com](mailto:danushmathip@gmail.com)  

Feel free to contribute, raise issues, or reach out with questions! 🚀  
