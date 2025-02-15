
## **Breast Cancer Classification using Machine Learning**  

### **Overview**  
Breast cancer is one of the most common cancers among women worldwide. Early detection and accurate classification of tumors as **malignant** or **benign** are crucial for effective treatment and improved survival rates. This project applies **machine learning algorithms** to classify breast cancer tumors and compare their performance.  

### **Problem Statement**  
The goal of this project is to develop and evaluate **Decision Tree, Random Forest, Support Vector Machine (SVM), Kernel SVM, and Naïve Bayes** models to determine which algorithm provides the most accurate classification of breast cancer tumors.  

### **Dataset**  
- **Dataset Name:** Breast Cancer Wisconsin (Diagnostic) Dataset  
- **Total Instances:** 569  
- **Features:** 30 numerical attributes describing cell nuclei characteristics  
- **Target Variable:**  
  - 'M' (Malignant)  
  - 'B' (Benign)  

### **Key Features in the Dataset**  
- **ID:** Unique identifier for each patient  
- **Diagnosis:** Malignant (M) or Benign (B)  
- **Feature Examples:**  
  - `Radius_mean`: Mean of distances from center to perimeter points  
  - `Texture_mean`: Standard deviation of gray-scale values  
  - `Perimeter_mean`: Mean tumor perimeter size  
  - `Area_mean`: Mean tumor area  
  - `Smoothness_mean`: Local variation in radius lengths  

### **Technologies & Libraries Used**  
- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib & Seaborn (for visualization)  

### **Machine Learning Models Used**  
1. **Decision Tree**  
2. **Random Forest**  
3. **Support Vector Machine (SVM)**  
4. **Kernel SVM**  
5. **Naïve Bayes**  

### **Model Performance Comparison**  
Each model was trained and tested, and their accuracy was compared to identify the most effective classifier.  

| Model          | Accuracy (%) |  
|---------------|-------------|  
| Decision Tree | XX.XX%      |  
| Random Forest | XX.XX%      |  
| SVM           | XX.XX%      |  
| Kernel SVM    | XX.XX%      |  
| Naïve Bayes   | XX.XX%      |  

### **Results & Insights**  
- The **Random Forest model** provided the highest accuracy due to its ensemble learning approach.  
- **SVM and Kernel SVM** performed well, particularly in handling complex decision boundaries.  
- **Naïve Bayes** was the fastest but had lower accuracy compared to other models.  

### **How to Run the Project**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```  
2. Install required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the Jupyter Notebook or Python script to train and evaluate models.  

### **Conclusion**  
This project provides insights into the effectiveness of different machine learning models in classifying breast cancer tumors. The **Random Forest algorithm** showed the best performance in terms of accuracy, making it a suitable choice for real-world applications in medical diagnosis.  

### **Future Improvements**  
- Fine-tuning hyperparameters for improved accuracy  
- Implementing deep learning models for better classification performance  
- Deploying the model as a web application for easy accessibility  
