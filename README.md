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
<img width="811" height="486" alt="image" src="https://github.com/user-attachments/assets/f39783bd-fdb6-4e42-95c5-1a31fb249ddf" />
<img width="809" height="470" alt="image" src="https://github.com/user-attachments/assets/c70e965a-6964-4087-b0ab-8fa7a3f3dd55" />
<img width="818" height="511" alt="image" src="https://github.com/user-attachments/assets/5723f06c-257a-4ee0-b888-0000aff8082a" />
<img width="806" height="529" alt="image" src="https://github.com/user-attachments/assets/c0d531bd-1151-4919-9910-3b1f255cef01" />
<img width="815" height="550" alt="image" src="https://github.com/user-attachments/assets/f7f0cf8e-bac9-4870-83f8-344b58f53ab8" />
<img width="813" height="508" alt="image" src="https://github.com/user-attachments/assets/57520a31-d667-4313-b990-ce7764b32023" />
<img width="814" height="461" alt="image" src="https://github.com/user-attachments/assets/00e892f9-f02a-4a47-abf2-416c66851c29" />
<img width="813" height="444" alt="image" src="https://github.com/user-attachments/assets/1508920d-1b01-41fd-b1bf-828d5290f76f" />
<img width="808" height="462" alt="image" src="https://github.com/user-attachments/assets/636bc42c-e8f1-4713-b68e-81690ab073ab" />
<img width="815" height="444" alt="image" src="https://github.com/user-attachments/assets/fd394182-29f5-4243-bdb0-b0b48979025a" />
<img width="816" height="462" alt="image" src="https://github.com/user-attachments/assets/dab3c27b-5427-422e-91ed-86492898150c" />
<img width="818" height="520" alt="image" src="https://github.com/user-attachments/assets/2e379dcb-5071-4e86-816f-61da4cabaddf" />
<img width="814" height="537" alt="image" src="https://github.com/user-attachments/assets/0d5955dd-08f1-47b3-8803-f2cbe1e45f16" />
<img width="815" height="450" alt="image" src="https://github.com/user-attachments/assets/2da99df5-b324-4e27-b689-4deee834e5d2" />
<img width="814" height="473" alt="image" src="https://github.com/user-attachments/assets/12158c47-48b3-4f9e-b386-1e586c1b95c7" />
<img width="826" height="493" alt="image" src="https://github.com/user-attachments/assets/e8c232cc-b3f4-484e-a24f-623a862e6cb2" />
<img width="811" height="524" alt="image" src="https://github.com/user-attachments/assets/e4a97968-fb98-491f-82ff-e7b27fb566da" />
<img width="821" height="557" alt="image" src="https://github.com/user-attachments/assets/d3b0b8a6-e122-446d-b846-2ed7986cf1cc" />
<img width="760" height="566" alt="image" src="https://github.com/user-attachments/assets/8257d60d-f2d8-4c88-9dc5-8133778aace0" />
<img width="762" height="439" alt="image" src="https://github.com/user-attachments/assets/b00a2f53-9d1d-47e7-8c18-ed7ac4376cbb" />
<img width="762" height="521" alt="image" src="https://github.com/user-attachments/assets/5a2da384-eac0-4b82-b5a7-6d072c66bf5e" />
<img width="763" height="579" alt="image" src="https://github.com/user-attachments/assets/21f2b24d-74bf-4dac-9d03-2b0d1f80663d" />

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

**Rajbali**

- GitHub: [@therajbali](https://github.com/therajbali)
- LinkedIn: https://www.linkedin.com/in/therajbali/
- Email: rajbaliofficial@gmail.com

## 🙏 Acknowledgments

- Dataset source: Flipkart GRiD | Software Development Challenge
- Inspiration from various ML projects
- Community support and resources

---

⭐ If you found this project helpful, please give it a star!

**Made with ❤️ by Rajbali**
