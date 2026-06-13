# Loan Prediction System (Flask + Machine Learning)

A modern Loan Approval Prediction System built using Flask and Machine Learning. The application predicts whether a loan application is likely to be approved based on applicant information and provides confidence scores, risk analysis, downloadable reports, and application history management.

## Live Demo

🌐 Live Application: https://loan-prediction-stytem-tm.onrender.com/

## GitHub Repository

🔗 Repository: https://github.com/saifullahtanim/Loan-Prediction-System

---

## Project Overview

This project is a web-based Loan Prediction System that uses a pre-trained Machine Learning model to predict loan approval status. Users can submit loan application information through a user-friendly interface and instantly receive prediction results with confidence scores and risk assessments.

The system also includes history tracking, PDF report generation, CSV/JSON exports, and email support through Flask-Mail.

---

## Key Features

### Machine Learning Prediction

* Loan approval prediction using a trained ML model.
* Instant prediction results.
* Confidence score calculation.
* Risk level assessment.
* Key decision factor analysis.

### Application History Management

* Automatic history storage.
* Unique Application ID generation.
* View previous applications.
* Delete history records using AJAX.
* Real-time statistics update.

### Report Generation

* Download individual PDF reports.
* Export application history as CSV.
* Export application history as JSON.
* Printable prediction reports.

### Dashboard Statistics

* Total Applications.
* Approved Applications.
* Rejected Applications.
* Dynamic charts using Chart.js.

### Contact & Email Support

* Contact form integration.
* Email notification support using Flask-Mail.
* SMTP configuration support.

### User Experience

* Responsive design.
* Bootstrap-powered interface.
* Modern UI components.
* Redirect-after-post implementation.
* Duplicate submission prevention.

---

## Tech Stack

### Backend

* Python 3
* Flask
* Flask-Mail
* NumPy

### Machine Learning

* Scikit-learn
* Pickle Model Serialization

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* JavaScript
* Chart.js
* html2pdf.js

### Data Storage

* JSON-based storage
* loan_history.json

---

## Project Structure

Loan-Prediction-System/

│

├── app.py

├── requirements.txt

├── train.csv

├── TM.pkl

├── model.pkl

├── loan_history.json

│

├── templates/

│ ├── index.html

│ ├── prediction.html

│ └── pdf_template.html

│

├── static/

│ ├── css/

│ ├── js/

│ └── images/

│

├── EMAIL_SETUP.md

└── README.md

---

## Application Routes

### Home Page

GET /

Displays the landing page.

### Prediction Page

GET /predict

Displays prediction form and history.

POST /predict

Processes loan prediction requests.

### History Management

POST /history/delete/<application_id>

Deletes a specific history entry.

### PDF Report Download

GET /download_reports

Downloads prediction reports.

### History Export

GET /history/export/json

Exports history as JSON.

GET /history/export/csv

Exports history as CSV.

### Contact Form

POST /contact

Sends contact emails.

---

## Local Installation

### Clone Repository

git clone https://github.com/saifullahtanim/Loan-Prediction-System.git

cd Loan-Prediction-System

### Create Virtual Environment

python -m venv .venv

### Activate Environment

Windows:

.venv\Scripts\activate

Linux/macOS:

source .venv/bin/activate

### Install Dependencies

pip install -r requirements.txt

### Run Application

python app.py

### Open Browser

http://127.0.0.1:5000/predict

---

## Deployment

This project is successfully deployed on Render.

### Production URL

https://loan-prediction-stytem-tm.onrender.com/

### Deployment Platform

* Render
* GitHub Integration
* Automatic Deployments

---

## Testing Checklist

* Prediction generation works.
* History storage works.
* History deletion works.
* CSV export works.
* JSON export works.
* PDF report generation works.
* Contact form works.
* Charts load correctly.

---

## Future Improvements

### Planned Features

* SHAP Explainable AI Integration.
* Admin Dashboard.
* User Authentication.
* Database Integration (MySQL/PostgreSQL).
* Advanced Analytics Dashboard.
* Email Verification.
* Multi-Model Comparison.
* REST API Support.
* Docker Deployment.
* Cloud Database Integration.

---

## Author

Saifullah Tanim

Department of Computer Science and Engineering

Green University of Bangladesh

---

## License

This project is intended for educational and academic purposes.
