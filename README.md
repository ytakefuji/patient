# patient
This is under review.

Patients need to know effects of medication and exercise for alleviating diseases. 
Biomarkers are used to monitor the status of diseases.

phope.py (Patient for Hospital Observation and Predicting Effects of medication and exercise)
is a universal biomarker prediction tool that can be used for evaluating the performance and predicting values of biomarkers in the next hospital visit.

To run phope.py, type python phope.py in the terminal.

phope is a PyPI application. phope allows users to run on Windows, MacOS, and Linux operating systems as long as Python is installed on the system.

data.csv is a data file composed of five determinants such as "day" (tested date), "hgb" of hbA1c value (biomarker for diabetes), "ntbnp" of NT-proBNP value (biomarker for heart failure), "degree1" (polynomial regression for hbA1c), and "degree2" (polynomial regression for NT-proBNP).

Based on data.csv with state-of-the-art technology, phope.py can calculate and predict values of biomarkers for the next visit.

Predicting biomarker values allows patients to know the progress and trends of improvement in their diseases. 

Predictive values are hopes of patients.

#How to install phope
$ pip install phope

#How to run phope
$ phope

