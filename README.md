## Overview  
The **Integrated Disease Prediction & E-Appointment Scheduler** is a web-based application that leverages machine learning to predict diseases using the Naïve Bayes algorithm. It simplifies the healthcare process by allowing users to book appointments through an e-scheduler.  

---

## Technologies Used  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Django, Python  
- **Database:** SQLite  
- **Machine Learning Algorithm:** Naïve Bayes Classifier  
- **Version Control:** Git  

---

## Features  
- **Accurate Disease Prediction** using user-input symptoms.  
- **E-Appointment Scheduler** to book healthcare appointments online.  
- **Admin Panel** for managing patient records and appointments.  
- **Interactive UI** for seamless navigation.  

---

## Installation and Setup  

Install Dependencies
Ensure Python is installed, then run:

pip install -r requirements.txt
Apply Database Migrations

python manage.py migrate
Start the Server

python manage.py runserver
Access the Application
Open a browser and navigate to:
http://127.0.0.1:8000/

Usage
Login or Register: Create a new account or log in.
Predict Disease: Input symptoms to receive a prediction.
Book Appointment: Schedule an appointment based on the prediction.
Admin Panel Access: Manage patient data and appointments (admin only).
  
