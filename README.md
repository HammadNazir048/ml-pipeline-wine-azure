# 🍷 ml-pipeline-wine-azure

This project demonstrates how to build a **Machine Learning pipeline using Azure ML Designer** to predict **wine quality** based on physicochemical properties. It leverages a **drag-and-drop low-code approach** to create, train, evaluate, and deploy ML models—all within the Azure ML Studio interface.

---


---

## 🧪 Dataset

We used the [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) from the UCI Machine Learning Repository, which contains physicochemical tests of red/white variants of Portuguese "Vinho Verde" wine.


## 🚀 Key Features

- Built using **Azure ML Designer** (drag-and-drop interface)
- Covers **data ingestion**, **data cleaning**, **feature normalization**
- Trains models like **Decision Tree**, **Logistic Regression**, etc.
- Evaluates performance with **accuracy**, **confusion matrix**
- Deploys as a **real-time web service** for predictions

---

## 🧰 Tools & Technologies

- **Azure Machine Learning Studio**
- Azure ML Designer (Low-code ML interface)
- Classification Models: Decision Tree, Logistic Regression
- Dataset: Wine Quality (CSV)
- JSON config for reproducibility

---

## 📊 Model Pipeline Overview

The ML pipeline includes the following components:

1. **Data Import** – Load the dataset from local or cloud storage
2. **Data Preprocessing** – Handle missing values, normalize features
3. **Model Training** – Apply classification algorithms
4. **Model Evaluation** – Compare model metrics
5. **Web Service Deployment** – Publish the best model as a REST API

---

## 🖼️ Screenshots (Optional)

> Add screenshots of your Azure ML Designer pipeline for visual clarity.

---

## 🧠 Author

**Muhammad Hammad Nazir**  
- GitHub: [@HammadNazir048](https://github.com/HammadNazir048)  
- LinkedIn: [linkedin.com/in/hammadnazir048](https://linkedin.com/in/hammadnazir048)  

---

## 📌 How to Reproduce

> If you’re uploading your `config.json` or pipeline export:

1. Open [Azure ML Studio](https://ml.azure.com/)
2. Create a new pipeline in ML Designer
3. Upload and use your dataset
4. Use the configuration in `config.json` (optional)
5. Drag and connect modules as per the pipeline logic
6. Run the pipeline and deploy the model

---

## 📄 License

This project is open source under the [MIT License](LICENSE).


