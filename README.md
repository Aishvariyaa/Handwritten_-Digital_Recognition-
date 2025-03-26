Here’s the **Git-based format** for your **Handwritten Digit Recognition** project using SVM on the MNIST dataset. 🚀  

---

## ✍️ Handwritten Digit Recognition (MNIST)  

### 📌 Overview  
This project builds a **Handwritten Digit Classifier** using **Support Vector Machine (SVM)** trained on the **MNIST dataset** for multi-class classification. 🖊️🔢  

### 🔍 Key Steps  
✅ **Dataset Loading & Preprocessing**  
   - Loaded the **MNIST dataset** 🗂️  
   - Normalized pixel values (0-255 ➝ 0-1) 📊  
   - Reshaped data for SVM training  

✅ **Model Training (SVM)**  
   - Used **Scikit-Learn’s SVM (Support Vector Machine)**  
   - Optimized hyperparameters using **GridSearchCV**  

✅ **Model Evaluation**  
   - **Accuracy, Precision, Recall, F1-score**  
   - **Confusion Matrix & Classification Report**  

### 📂 Project Structure  
```
Handwritten-Digit-Recognition/
│── README.md  # Documentation  
│── digit_recognition.ipynb  # Jupyter Notebook (Model Training & Evaluation)  
│── mnist_data/  # MNIST Dataset (Downloaded via TensorFlow/Keras)  
│── predictions.csv  # Model Predictions  
```  

### 🔗 Dataset  
📌 **Dataset Source:** [MNIST Handwritten Digits Dataset](http://yann.lecun.com/exdb/mnist/)  

### 🔧 Technologies Used  
🔹 Python  
🔹 NumPy & Pandas (Data Handling)  
🔹 Scikit-learn (SVM & Model Evaluation)  
🔹 Matplotlib & Seaborn (Data Visualization)  

### 📜 How to Run the Project?  
#### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Aishvariyaa/Handwritten-Digit-Recognition.git
cd Handwritten-Digit-Recognition
```  

#### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```  

#### 3️⃣ Run the Jupyter Notebook  
```bash
jupyter notebook digit_recognition.ipynb
```  

### 📈 Model Performance  
📌 **SVM Model Results on MNIST:**  
- **Accuracy:**- 0.9404


📌 **KNN Model Result on MNIST**
- **Accuracy:**-  0.9688


📌 **Confusion Matrix**  
<img width="360" alt="{53F5862F-72A3-463E-A549-11E0435FFB63}" src="https://github.com/user-attachments/assets/cff818ca-9bf1-462a-89c6-370dd9049cd8" />


### 📌 Next Steps  
🔹 Experiment with **CNNs (Convolutional Neural Networks)** for improved accuracy.  
🔹 Convert the model into a **real-time digit recognition app** using Flask or Streamlit.  

