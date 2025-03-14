<h1 align="center"> 🚨 AI-powered phishing detection system 🚨 </h1>

##  ⚙️ About the Project 

🔍 Detect phishing emails using AI! This system utilizes Natural Language Processing (NLP) and Machine Learning to identify phishing emails based on text content and URLs.

## 🚀 Features

- ✅ Detects phishing emails using Naïve Bayes Classifier
- ✅ Cleans and processes email text using NLTK Stopwords
- ✅ Extracts and analyzes URLs within emails
- ✅ Supports custom training with uploaded datasets
- ✅ Interactive Streamlit UI for real-time phishing detection

## 🧑‍💻 Technologies Used

- **Python** 🐍
- **Streamlit** 🌐
- **scikit-learn** 🤖
- **pandas** 📊
- **nltk** 🧠
- **Requests** 🌍
- **BeautifulSoup** 🍲

## 🎯 Installation & Setup

1. Clone the repository
   
   ```bash
   git clone https://github.com/Imaad00/AI-Powered-Phishing-Detection.git
   cd AI-Powered-Phishing-Detection

2. Install Dependencies
   Create and activate a virtual environment, then install required packages:
   ```bash
   python -m venv venv
   source venv/bin/activate   # For macOS/Linux
   venv\Scripts\activate      # For Windows

   pip install -r requirements.txt

3. Run the App
   Start the Streamlit app to launch the phishing detection system:
   ```bash
   streamlit run phishing_detection.py

4. Upload Dataset for Training (Optional)
   Upload a CSV file with columns email_body (content of the email) and label (1 for phishing, 0 for safe) to train the model.

🔍 How to Use

- **Training the Model**: Upload a CSV file containing emails labeled as phishing or safe.
- **Prediction**: Enter the body of an email, and the system will classify it as phishing or safe.

Example Email to Test:

- **Phishing Email**:
  
  ```bash
  URGENT: Your PayPal account has been restricted. Verify your details here: http://scamlink.com

- **Safe Email**:

  ```bash
  Great job on the presentation today! Looking forward to working on the next steps.

5. Check Prediction
   Click Check Phishing to see the prediction results for the email you entered.

## 📊 Results

The system will display whether the email is a phishing attempt or safe based on its body content and URL features.


## 🌐 Connect with Me 

- 📧 [Email](imaadsharieff266@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/mohammed-imaad-sharieff-08891a238/)
