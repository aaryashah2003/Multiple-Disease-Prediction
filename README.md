# 🧠 Disease Prediction System
The Disease Prediction System is a web-based application designed to predict the likelihood of three major diseases: diabetes, heart disease, and Parkinson's disease. This system utilizes machine learning models trained on datasets specific to each disease, providing users with a user-friendly interface to input their data and receive a prediction result. The core features of this system include disease prediction, data visualization, and a navigation menu for easy access to different disease prediction pages.

## 🚀 Features
- **Disease Prediction**: The system can predict the likelihood of diabetes, heart disease, and Parkinson's disease based on user input data.
- **Data Visualization**: The system includes data visualization capabilities to help users understand their input data and prediction results.
- **Navigation Menu**: A sidebar navigation menu allows users to easily switch between different disease prediction pages.
- **User-Friendly Interface**: The system provides a user-friendly interface for users to input their data and receive prediction results.

## 🛠️ Tech Stack
- **Frontend**: Streamlit for creating the web-based user interface
- **Backend**: Python for loading and using machine learning models
- **Machine Learning**: scikit-learn for training and evaluating machine learning models
- **Data Manipulation**: pandas for data manipulation and analysis
- **Data Visualization**: seaborn and matplotlib for data visualization
- **Model Saving**: pickle for saving trained machine learning models
- **Numerical Computations**: numpy for numerical computations

## 📦 Installation
To install the required dependencies, run the following command:
```bash
pip install streamlit streamlit_option_menu pandas scikit-learn numpy seaborn matplotlib pickle
```
### Prerequisites
- Python 3.8 or later
- pip 20.0 or later

### Running Locally
1. Clone the repository: `git clone https://github.com/your-username/disease-prediction-system.git`
2. Navigate to the repository: `cd disease-prediction-system`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the application: `streamlit run app.py`

## 💻 Usage
1. Open a web browser and navigate to the application URL (e.g., `http://localhost:8501`)
2. Select a disease prediction page from the navigation menu
3. Input your data in the required fields
4. Click the "Predict" button to receive a prediction result

## 📂 Project Structure
```markdown
disease-prediction-system/
│
├── app.py
├── diabetes_prediction.py
├── heart_disease_prediction.py
├── parkinson_s_disease_detection.py
├── requirements.txt
├── README.md
```
