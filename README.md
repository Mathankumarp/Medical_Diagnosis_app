# Medical Diagnosis | A Machine Learning Based Web Application

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Python](https://img.shields.io/badge/Python-3.6.8-green.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Web%20Framework-red.svg)](https://flask.palletsprojects.com/)

## 🏥 About The Project

This repository contains a comprehensive machine learning-based web application designed for medical diagnosis. The application integrates multiple ML and deep learning models to predict various diseases based on user-provided medical data. Built with Flask and featuring an intuitive web interface, this tool aims to assist in preliminary medical screening while providing appointment booking and doctor communication features.

## 🎯 Problem Statement

The healthcare industry faces challenges in providing quick and accurate preliminary diagnoses. This project addresses these challenges by:

- **Reducing Human Error**: Leveraging machine learning algorithms that maintain consistent accuracy
- **Improving Accessibility**: Providing 24/7 access to preliminary medical screening
- **Supporting Healthcare Professionals**: Offering a tool for initial patient assessment
- **Enabling Early Detection**: Facilitating early identification of potential health issues

## 🔍 Why Machine Learning for Medical Diagnosis?

While humans are prone to errors and fatigue, machine learning models provide:
- **Consistent Performance**: Models don't experience fatigue or emotional bias
- **High Accuracy**: Trained on large datasets with validated accuracy metrics
- **Data-Driven Insights**: Evidence-based predictions using proven algorithms
- **Scalability**: Ability to handle multiple patients simultaneously

*Note: This system focuses on allopathic medicine due to the availability of comprehensive datasets from platforms like Kaggle and UCI Machine Learning Repository.*

## 🏗️ System Architecture

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Frontend      │    │   Backend        │    │   ML Models     │
│   (HTML/CSS/JS) │◄──►│   (Flask App)    │◄──►│   (.pkl files)  │
│                 │    │                  │    │                 │
│ • User Input    │    │ • Data Processing│    │ • Predictions   │
│ • Results       │    │ • Model Integration    │ • Disease       │
│ • Appointments  │    │ • Communication  │    │   Classification│
└─────────────────┘    └──────────────────┘    └─────────────────┘
```

## 📁 Project Structure

```
Medical_Diagnosis/
├── Python_notebooks/              # Jupyter notebooks for model development
├── trained_models/                # Serialized ML models (.pkl files)
├── static/                       # Static assets
│   ├── css/                      # Stylesheets
│   ├── js/                       # JavaScript files
│   ├── images/                   # Images and logos
│   └── fonts/                    # Font files
├── templates/                    # HTML templates
│   ├── home.html
│   ├── contact.html
│   ├── about.html
│   ├── services.html
│   └── disease_prediction/       # Disease-specific templates
│       ├── diabetes.html
│       ├── breast_cancer.html
│       ├── heart_disease.html
│       ├── kidney_disease.html
│       ├── liver_disease.html
│       ├── malaria.html
│       └── pneumonia.html
├── app.py                        # Main Flask application
├── requirements.txt              # Python dependencies
├── runtime.txt                   # Python version specification
└── README.md                     # Project documentation
```

## 🚀 Quick Start Guide

### Prerequisites
- Python 3.6.8 or higher
- pip package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/medical-diagnosis.git
   cd medical-diagnosis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python app.py
   ```
   or
   ```bash
   flask run
   ```

4. **Access the application**
   - Open your web browser
   - Navigate to `http://localhost:5000`

## 🩺 Supported Disease Predictions

The application can predict the following diseases with high accuracy:

| Disease | Model Type | Accuracy | Dataset Source |
|---------|------------|----------|----------------|
| Diabetes | Machine Learning | 98.25% | Kaggle |
| Breast Cancer | Machine Learning | 98.25% | Kaggle |
| Heart Disease | Machine Learning | 85.25% | Kaggle |
| Kidney Disease | Machine Learning | 99.00% | Kaggle |
| Liver Disease | Machine Learning | 78.00% | Kaggle |
| Malaria | Deep Learning (CNN) | 96.00% | Kaggle |
| Pneumonia | Deep Learning (CNN) | 95.00% | Kaggle |

## 💻 Technical Stack

- **Frontend**: HTML5, CSS3, Bootstrap, JavaScript
- **Backend**: Flask (Python Web Framework)
- **Machine Learning**: Scikit-learn, TensorFlow/Keras
- **Data Processing**: Pandas, NumPy
- **Model Serialization**: Pickle
- **Development Environment**: Python 3.6.8

## 📊 Features

### Core Functionality
- **Multi-Disease Prediction**: Support for 7 different diseases
- **User-Friendly Interface**: Intuitive web design with responsive layout
- **Real-Time Predictions**: Instant results upon data submission
- **High Accuracy Models**: Trained on validated medical datasets

### Additional Features
- **Appointment Booking**: Schedule consultations with healthcare professionals
- **Email Communication**: Direct communication channel with doctors
- **Responsive Design**: Compatible with desktop and mobile devices
- **Secure Data Handling**: Proper handling of sensitive medical information

## 🔗 Resources

### Datasets
- [Diabetes Dataset](https://www.kaggle.com/dataset-link)
- [Breast Cancer Dataset](https://www.kaggle.com/dataset-link)
- [Heart Disease Dataset](https://www.kaggle.com/dataset-link)
- [Kidney Disease Dataset](https://www.kaggle.com/dataset-link)
- [Liver Disease Dataset](https://www.kaggle.com/dataset-link)
- [Malaria Dataset](https://www.kaggle.com/dataset-link)
- [Pneumonia Dataset](https://www.kaggle.com/dataset-link)

### Model Development Notebooks
- [Diabetes Prediction Notebook](link-to-notebook)
- [Breast Cancer Prediction Notebook](link-to-notebook)
- [Heart Disease Prediction Notebook](link-to-notebook)
- [Kidney Disease Prediction Notebook](link-to-notebook)
- [Liver Disease Prediction Notebook](link-to-notebook)
- [Malaria Detection Notebook](link-to-notebook)
- [Pneumonia Detection Notebook](link-to-notebook)

## ⚠️ Important Disclaimers

- This application is designed for **educational and research purposes only**
- Predictions are **not a substitute for professional medical advice**
- Always consult with qualified healthcare professionals for medical decisions
- The application should be used as a **preliminary screening tool** only


## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

```
Copyright 2021 Karan Mehra | Surbhi | Navdeep Nijjar

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## 📞 Support

If you encounter any issues or have questions about the project, please:
- Open an issue on GitHub
- Contact the development team
- Check the documentation and notebooks for detailed implementation

---

⭐ **Star this repository if you found it helpful!**
