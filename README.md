# Laptop Price Prediction

A machine learning model that predicts laptop prices based on specifications such as RAM, storage, processor, GPU, and more.  
All steps — from data preprocessing to model evaluation — are implemented in a single, well-documented Google Colab notebook.

---

## 📁 Repository Structure
The repository has two directories: 
-->**Data** : (which includes the data that has been used for training the model)
-->**Notebooks** : (which includes all the pre processing , feature engineering and model building scripts bundled into a single notebook trained in a google colab environment.)

## 📊 Dataset Description

The dataset includes the following fields:

- **Brand**
- **Processor**
- **RAM (Size & Type)**
- **Storage (HDD/SSD)**
- **GPU**
- **Operating System**
- **Display Size/Type**
- **Price (Target Variable)**
- **TypeName**

✅ Format: CSV  
✅ Source: Curated from real e-commerce listings  
✅ Target: `Price` (in INR or USD)

---

## 🧠 Model Highlights

- Performed exploratory data analysis and cleaning
- Feature engineering for structured attributes
- Trained regression models like Linear Regression, Random Forest, or XGBoost
- Evaluated using metrics like:
  - R² (coefficient of determination)
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)

---

## 🚀 Getting Started

1. **Clone this repository:**

```bash
git clone https://github.com/your-username/laptop-price-prediction.git
cd laptop-price-prediction

