# 💻 Laptop Price Predictor

A machine learning project that predicts laptop prices based on various specifications using regression algorithms. This project demonstrates data preprocessing, feature engineering, model training, and evaluation techniques.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Performance](#model-performance)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 Overview

This project aims to predict the price of laptops based on their specifications such as brand, processor, RAM, storage, screen size, and other features. The model can help consumers make informed purchasing decisions and assist retailers in competitive pricing.

## ✨ Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Feature engineering and encoding
- Multiple regression model comparison
- Model evaluation with performance metrics
- Prediction on new laptop configurations

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries:**
  - pandas - Data manipulation and analysis
  - numpy - Numerical computations
  - scikit-learn - Machine learning algorithms
  - matplotlib - Data visualization
  - seaborn - Statistical visualizations
  - jupyter - Interactive development environment

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/therajbali/laptop-price-predictor.git
cd laptop-price-predictor
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook laptop-price-predictor.ipynb
```

2. Run all cells sequentially to:
   - Load and explore the dataset
   - Preprocess the data
   - Train the model
   - Evaluate performance
   - Make predictions

3. To make predictions on new data, modify the input features in the prediction section of the notebook.

## 📊 Dataset

The dataset contains information about various laptops with the following features:

- **Company** - Laptop manufacturer
- **TypeName** - Type of laptop (Notebook, Ultrabook, Gaming, etc.)
- **Inches** - Screen size
- **ScreenResolution** - Display resolution
- **CPU** - Processor details
- **RAM** - Memory size
- **Storage** - Hard drive/SSD capacity
- **GPU** - Graphics card
- **OpSys** - Operating system
- **Weight** - Laptop weight
- **Price** - Target variable (in your currency)

**Source:** [Add dataset source here if publicly available]

## 📈 Model Performance

| Model | R² Score | MAE | RMSE |
|-------|----------|-----|------|
| Linear Regression | 0.XX | XXX | XXX |
| Random Forest | 0.XX | XXX | XXX |
| Gradient Boosting | 0.XX | XXX | XXX |

*Note: Update these metrics after running your models*

### Key Findings:
- Most influential features: [Add your findings]
- Model accuracy: [Add percentage]
- Best performing algorithm: [Add result]

## 📁 Project Structure

```
laptop-price-predictor/
│
├── data/
│   └── laptop_data.csv           # Dataset
│
├── notebooks/
│   └── laptop-price-predictor.ipynb  # Main analysis notebook
│
├── models/
│   └── trained_model.pkl         # Saved model (if applicable)
│
├── images/
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   └── prediction_plot.png
│
├── README.md                     # Project documentation
├── requirements.txt              # Python dependencies
├── .gitignore                   # Git ignore file
└── LICENSE                      # License file
```

## 🔮 Future Improvements

- [ ] Deploy as a web application using Streamlit or Flask
- [ ] Add more advanced feature engineering
- [ ] Implement deep learning models
- [ ] Create an API for price predictions
- [ ] Add real-time data scraping for updated predictions
- [ ] Hyperparameter tuning using GridSearchCV
- [ ] Add cross-validation for better model evaluation

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Contact

**Raj Bali**

- GitHub: [@therajbali](https://github.com/therajbali)
- LinkedIn: [Add your LinkedIn URL]
- Email: [Add your email]

## 🙏 Acknowledgments

- Dataset source: [Credit the source]
- Inspiration from various ML projects
- Community support and resources

---

⭐ If you found this project helpful, please give it a star!

**Made with ❤️ by Raj Bali**
