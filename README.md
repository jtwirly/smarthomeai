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

#### Results:
Neural Network:

<img width="826" alt="Screen Shot 2025-03-10 at 1 48 48 PM" src="https://github.com/user-attachments/assets/f3f48032-8d18-48b3-8a1c-8e72877aa07f" />

<img width="134" alt="Screen Shot 2025-03-10 at 1 49 01 PM" src="https://github.com/user-attachments/assets/a815ac3f-f20d-4b32-84e7-5511088b85d7" />

LSTM:

<img width="827" alt="Screen Shot 2025-03-10 at 1 49 22 PM" src="https://github.com/user-attachments/assets/e53c614a-e0f3-4bf3-a249-dfa18b30a376" />

<img width="73" alt="Screen Shot 2025-03-10 at 1 49 30 PM" src="https://github.com/user-attachments/assets/a37c8715-06dd-4818-b957-0c710f6095e1" />

