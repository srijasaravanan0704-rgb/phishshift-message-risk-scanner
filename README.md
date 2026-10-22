# PhishShift – Message Risk Scanner

## About the Project
PhishShift is a machine learning project designed to identify potentially suspicious or phishing messages using text classification.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Flask

## Project Files
- `Untitled12.ipynb` – Google Colab notebook containing the project code.
- `logistic_regression_model.pkl` – Trained Logistic Regression model.
- `tfidf_vectorizer.pkl` – Saved TF-IDF vectorizer.
- `requirements.txt` – Python dependencies.
- `ML-07_PhishShift_Message_Risk_Scanner_View_Only.pdf` – Project reference document.

## How It Works
1. The message text is converted into numerical features using TF-IDF.
2. The trained Logistic Regression model analyzes the features.
3. The application returns a risk prediction and risk score.

## Important Note
This project is an educational prototype. Its predictions are not a guarantee that a message is safe or malicious. Model performance depends on the training data.

## Running the Notebook
1. Open `Untitled12.ipynb` in Google Colab.
2. Install the required dependencies.
3. Run the notebook cells in order.

## Future Improvements
- Train and evaluate the model using a larger, realistic dataset.
- Improve phishing detection accuracy.
- Develop a user-friendly interface.
