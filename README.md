# SafeMailAI

SafeMailAI is a powerful email classification tool that leverages NLP and machine learning to protect your inbox from spam. With an intuitive interface built on Streamlit, it accurately identifies and filters spam, ensuring a secure and clutter-free email experience.


## Features

- **Email Classification**: Enter an email and classify it as either Spam or Not Spam.
- **Model Performance**: View accuracy, confusion matrix, and classification report on the dataset.
- **User-Friendly Interface**: The result is displayed with a colored background to clearly indicate whether an email is Spam (red) or Not Spam (green).

## Installation

### 1. Clone the Repository


Installation
To get started with the spam email classification project, follow the steps below to clone the repository and set up the project environment.

1. Clone the Repository
First, clone the repository to your local machine by using the following command in your terminal or command prompt:


git clone https://github.com/yourusername/spam-email-classification.git
Replace yourusername with your actual GitHub username.

This will create a local copy of the repository on your machine. Once cloned, navigate to the project directory:


cd spam-email-classification
2. Install Required Dependencies
After cloning the repository, you need to install the necessary libraries and dependencies. It is recommended to use a virtual environment to avoid conflicts with other projects.

Using venv (Python Virtual Environment)
Create a virtual environment (if you don’t have one already):


python -m venv venv
Activate the virtual environment:

On Windows:

venv\Scripts\activate
On macOS/Linux:

source venv/bin/activate
Install the dependencies listed in the requirements.txt file:

pip install -r requirements.txt
This will install all necessary libraries like scikit-learn, pandas, nltk, matplotlib, etc., required for the project.

3. Run the Project
Once all dependencies are installed, you can run the project.

Train the Model: To train the spam classification model, run the following Python script:


python train_model.py
Classify New Emails: To classify new emails, use the provided script or modify the dataset to input emails for classification:

python classify_email.py
This will run the machine learning model and display the predicted results for your email.



```bash
git clone https://github.com/your-username/spam-email-classifier.git
cd spam-email-classifier
