#  ml-pipeline-wine-azure

This project demonstrates how to build a **Machine Learning pipeline using Azure ML Designer** to predict **wine quality** based on physicochemical properties. It leverages a **drag-and-drop low-code approach** to create, train, evaluate, and deploy ML models—all within the Azure ML Studio interface.

##  Dataset

We used the [Wine Quality Dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset) from the Kaggle, which includes the results of physicochemical tests on Portuguese "Vinho Verde" red and white wine variants. The dataset is designed for classification tasks to predict wine quality scores based on chemical composition.


##  Key Features

- Built using **Azure ML Designer** (drag-and-drop interface)
- Covers **data ingestion**, **data cleaning**, **feature normalization**
- Trains models like **Decision Tree**, **Logistic Regression**, etc.
- Evaluates performance with **accuracy**, **confusion matrix**
- Deploys as a **real-time web service** for predictions


##  Tools & Technologies

- **Azure Machine Learning Studio**
- Azure ML Designer (Low-code ML interface)
- Classification Models: Decision Tree, Logistic Regression
- Dataset: Wine Quality (CSV)
- JSON config for reproducibility


##  Model Pipeline Overview

The ML pipeline includes the following components:

1. **Data Import** – Load the dataset from local or cloud storage
2. **Data Preprocessing** – Handle missing values, normalize features
3. **Model Training** – Apply classification algorithms
4. **Model Evaluation** – Compare model metrics
5. **Web Service Deployment** – Publish the best model as a REST API

---

##  Snapshots 
![image](https://github.com/user-attachments/assets/f050e53f-26f2-44cf-9b49-895591855514)
![image](https://github.com/user-attachments/assets/caa60259-b973-48d1-a80a-2c45793b0ed5)
![image](https://github.com/user-attachments/assets/63e80153-2452-450d-ba87-7812d12299a1)
![image](https://github.com/user-attachments/assets/d1f5c6b4-ba80-4f3a-b20d-513fe8e606b7)
![image](https://github.com/user-attachments/assets/6506e84a-2ea4-4fa1-aa5a-788b9cbcad8a)

---

##  Author

**Muhammad Hammad Nazir**  
- GitHub: [@HammadNazir048](https://github.com/HammadNazir048)  
- LinkedIn: [linkedin.com/in/hammadnazir048](https://linkedin.com/in/hammadnazir048)  

---

##  How to Reproduce

> If you’re uploading your `config.json` or pipeline export:

1. Open [Azure ML Studio](https://ml.azure.com/)
2. Create a new pipeline in ML Designer
3. Upload and use your dataset
4. Use the configuration in `config.json` (optional)
5. Drag and connect modules as per the pipeline logic
6. Run the pipeline and deploy the model

---
