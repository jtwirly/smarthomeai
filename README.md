### **Project Description: Smart Home AI (Jupyter Notebook)**
This project is a **Jupyter Notebook-based implementation** that focuses on **energy usage prediction and optimization** using machine learning techniques. 

#### **Key Components:**
- **Data Preprocessing**: Loads and cleans energy consumption data for modeling.
- **Feature Engineering**: Extracts key features relevant to predicting energy demand.
- **Model Training**: Implements **Neural Networks (NNs) and LSTMs** to forecast energy consumption.
- **Evaluation**: Compares model performance using **Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score**.
- **Visualization**: Generates plots comparing actual vs. predicted energy usage.

#### **Technologies Used:**
- Python
- TensorFlow / Keras
- Pandas / NumPy
- Matplotlib / Seaborn
- Scikit-learn

### **Dataset Reference for the Smart Home AI Project**
This project uses the **UCI Electric Power Consumption Dataset**, which is hosted on Kaggle.

#### **📌 Dataset Link:**
[UCI Electric Power Consumption Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set)

#### **📜 Dataset:**
The dataset is imported using `kagglehub`:
```python
import kagglehub

# Download latest version
path = kagglehub.dataset_download("uciml/electric-power-consumption-data-set")

print("Path to dataset files:", path)
```
This command **automatically downloads** the latest version of the dataset and stores it locally for further processing.

#### **Potential Applications:**
- **Smart Home Energy Management**
- **Dynamic Appliance Control**
- **Grid Load Forecasting**
- **Optimized Renewable Energy Use**
