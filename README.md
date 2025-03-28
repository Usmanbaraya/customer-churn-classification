# Customer Churn Classification

## 📌 Project Overview
Customer churn is a critical issue for businesses, as retaining customers is often more cost-effective than acquiring new ones. This project aims to predict customer churn using machine learning techniques. By analyzing customer behavior and various factors, the model helps businesses take proactive measures to retain customers.

## 📂 Repository Structure
```
📦 customer-churn-classification
├── 📁 data/                 # Dataset and preprocessed data files
├── 📁 models/               # Saved machine learning models
├── 📁 encoders/             # Encoders for categorical variables
├── 📄 app.py                # Main application file for inference
├── 📄 model_training.ipynb   # Jupyter notebook for training models
├── 📄 prediction.ipynb       # Notebook for testing and making predictions
├── 📄 requirements.txt       # Dependencies and packages
└── 📄 README.md              # Project documentation
```

## 🔧 Installation
To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Usmanbaraya/customer-churn-classification.git
   cd customer-churn-classification
   ```

2. **Set up a virtual environment (optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Dataset
This project uses a dataset containing customer information, transaction history, and service usage data. The dataset includes features such as:
- **Customer ID**
- **Tenure** (Length of stay with the company)
- **Monthly charges**
- **Total charges**
- **Contract type** (Month-to-month, one year, two years)
- **Payment method**
- **Churn label** (Yes/No - target variable)

## 🚀 Usage
### Training the Model
To train the machine learning model, run:
```bash
jupyter notebook
```
Open `model_training.ipynb` and execute the cells.

### Making Predictions
To make predictions using a trained model:
1. Run the `app.py` script:
   ```bash
   python app.py
   ```
2. Use the `prediction.ipynb` notebook to test the model with new data.

## 📈 Model Details
The project employs various machine learning models, such as:
- **Logistic Regression**
- **Random Forest**
- **XGBoost**

The best-performing model is selected based on evaluation metrics like:
- **Accuracy**
- **Precision & Recall**
- **F1-score**
- **ROC-AUC Score**

## 📊 Results
The trained model provides valuable insights, including:
- Important features affecting churn
- Probability scores for each customer
- Performance comparison of different models

## 🤝 Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
🌟 **If you find this project useful, don't forget to star the repository!** ⭐

