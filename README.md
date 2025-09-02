This project is a Streamlit-based web application that classifies customer support tickets into predefined categories using a machine learning model. It demonstrates how to build an automated text classification pipeline with ~90% accuracy using TF-IDF
and Logistic Regression.
🚀 Features
✅ Classifies support tickets into categories like:
Login Issue
Payment Issue
App Crash
Subscription
Order Issue
Website Issue
Profile Issue
Refund Issue
Upload Issue
📊 Displays model accuracy
🧠 Uses TF-IDF + Logistic Regression
🖥️ Interactive UI built with Streamlit
📁 Sample training data viewer
📁 Project Structure
ticket_classifier/
├── app.py               # Streamlit app
├── requirements.txt     # Dependencies
├── README.md            # Project overview and instructions

🧰 Setup Instructions
Clone or unzip the project folder
Open a terminal and navigate to the folder
Install dependencies:
pip install -r requirements.txt

Run th app
streamlit run app.py


Usage
Enter a support ticket description in the text box.
Click Classify to see the predicted category.
View sample training data by expanding the section.
