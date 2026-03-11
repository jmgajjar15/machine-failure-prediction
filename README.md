Machine Failure Prediction System
Project Description
The Machine Failure Prediction System is a machine learning–based application designed to predict whether a machine is likely to fail based on various sensor inputs. The system analyzes operational parameters such as temperature, air quality, footfall, ultrasonic sensor values, and other machine metrics to determine the likelihood of machine failure.

This project helps industries monitor machine conditions and take preventive actions before actual failures occur, thereby reducing downtime and maintenance costs. The model is deployed using Streamlit, providing an interactive web interface where users can input sensor values and instantly receive predictions.

Features
Predicts machine failure using machine learning

Interactive web interface built with Streamlit

Real-time prediction based on sensor data

Easy-to-use input system for machine parameters

Helps in predictive maintenance and monitoring

Technologies Used
Python

Machine Learning

Pandas

Scikit-learn

Joblib

Streamlit

Input Parameters
The model uses the following machine sensor parameters:

Footfall

Temp Mode

Air Quality (AQ)

Ultrasonic Sensor (USS)

Current Sensor (CS)

VOC Level

Rotational Position (RP)

Input Pressure (IP)

Temperature

Installation
Clone the repository:
git clone https://github.com/Vishal2930-Data-analyst/Machine-Failure-Prediction.git
Install dependencies:
pip install -r requirements.txt
Run the Streamlit app:
streamlit run app.py
Output
The system predicts whether:

Machine is Working Normally

Machine Failure is Likely

Applications
Predictive maintenance in industries

Monitoring machine health

Reducing operational downtime

Improving equipment reliability
