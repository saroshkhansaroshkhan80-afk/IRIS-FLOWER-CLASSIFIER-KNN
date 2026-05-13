# Iris Flower Classifier - KNN

A machine learning project implementing the K-Nearest Neighbors (KNN) algorithm to classify iris flowers based on their physical characteristics. The project includes a web interface built with Flask for interactive predictions.

## 🎯 Project Overview

This project demonstrates:
- **Machine Learning**: KNN classification algorithm implementation
- **Data Preprocessing**: Data cleaning and feature scaling
- **Web Application**: User-friendly Flask interface for predictions
- **Data Analysis**: Iris dataset exploration and visualization

## 📊 Dataset

The project uses the famous **Iris Dataset** containing 150 samples with 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

**Target Classes**: 3 Iris species (Setosa, Versicolor, Virginica)

## 🔧 Tech Stack

- **Python 3.x**
- **scikit-learn**: Machine Learning library
- **pandas**: Data manipulation
- **numpy**: Numerical computing
- **Flask**: Web framework
- **matplotlib**: Data visualization
- **Jupyter**: Interactive development (optional)

## 📦 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/IRIS-FLOWER-CLASSIFIER-KNN.git
   cd IRIS-FLOWER-CLASSIFIER-KNN
   ```

2. **Create Virtual Environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   # or
   source venv/bin/activate  # On macOS/Linux
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

### Running the Web Application

```bash
python app.py
```

The application will be available at `http://localhost:5000`

### Using the Classifier

1. Open your browser and navigate to the application
2. Enter Iris flower measurements (Sepal Length, Sepal Width, Petal Length, Petal Width)
3. Click "Predict" to get the classification result
4. View confidence scores and predictions

## 📁 Project Structure

```
IRIS-FLOWER-CLASSIFIER-KNN/
│
├── app.py                  # Flask web application
├── model.py               # KNN model implementation
├── preprocess.py          # Data preprocessing functions
├── IRIS.csv              # Dataset
├── requirements.txt       # Python dependencies
│
├── models/               # Trained model artifacts
├── static/               # CSS, JavaScript, images
├── templates/            # HTML templates
│   ├── index.html       # Home page
│   └── result.html      # Prediction results page
│
└── README.md             # This file
```

## 🎓 Model Details

- **Algorithm**: K-Nearest Neighbors (KNN)
- **Distance Metric**: Euclidean distance
- **Feature Scaling**: StandardScaler for normalization
- **Train-Test Split**: 80-20 split

## 📈 Performance

The KNN classifier achieves high accuracy on the Iris dataset with proper hyperparameter tuning and feature scaling.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Fork the repository
- Create a feature branch (`git checkout -b feature/AmazingFeature`)
- Commit your changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

[Your Name]  
GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)

## 📞 Contact

Feel free to reach out for questions or suggestions!

---

## 🙏 Acknowledgments

- Iris dataset from UCI Machine Learning Repository
- scikit-learn documentation and tutorials
- Flask documentation for web framework guidance

## 📚 Resources

- [scikit-learn Documentation](https://scikit-learn.org/)
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
