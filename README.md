# Handwritten Digits Recognition using Machine Learning and CNN

## Project Overview
This project recognizes handwritten digits (0–9) using the MNIST dataset. It compares multiple machine learning and deep learning models and provides a Streamlit web application for digit prediction from uploaded images.

## Dataset
- **Dataset:** MNIST handwritten digits
- **Training images:** 60,000
- **Testing images:** 10,000
- **Image size:** 28 × 28 pixels
- **Classes:** Digits 0–9

## Models Compared
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- Artificial Neural Network (ANN/MLP)
- Convolutional Neural Network (CNN)

## Results

| Model | Test Accuracy |
|---|---:|
| CNN | 99.16% |
| SVM | 96.87% |
| ANN/MLP | 95.49% |
| Random Forest | 95.44% |
| KNN | 94.96% |

*Note: The CNN was trained on all 60,000 training images, while traditional machine learning models used a stratified sample of 12,000 images.*

## Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy and Pandas
- Streamlit
- Matplotlib and Seaborn

## Project Structure
```text
PRCP-1002-Handwritten-Digits-Recognition/
├── app.py
├── requirements.txt
├── README.md
├── mnist_model_comparison.csv
├── PRCP-1002_Handwritten_Digits_Recognition.ipynb
├── models/
│   └── mnist_cnn_best.keras
└── reports/
    └── project_report.md
```

## Run the Application Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/PRCP-1002-Handwritten-Digits-Recognition.git
   ```
2. Open the project folder:
   ```bash
   cd PRCP-1002-Handwritten-Digits-Recognition
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Project Highlights
- Compared five machine learning and deep learning approaches.
- Evaluated performance using classification metrics.
- Saved the trained CNN model for reuse.
- Built a Streamlit application for handwritten digit prediction.

## Future Improvements
- Improve predictions for images with varied handwriting styles.
- Test the application with more real-world handwritten images.
- Deploy the application online.

## Author
**Amruta Satish Kanhe**

GitHub: https://github.com/Amrutasatishkanhe

## Disclaimer
This project is developed for educational and machine learning practice purposes.
