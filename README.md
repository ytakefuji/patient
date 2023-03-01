# patient
This is under review.

Patients need to know effects of medication and exercise for alleviating diseases. 
Biomarkers are used to monitor the status of individual diseases.

phope.py (Patient for Hospital Observation and Predicting Effects of medication and exercise)
with five determinants such as "day" (tested date), "hgb" of hbA1c value (biomarker for diabetes), "ntbnp" of NT-proBNP value (biomarker for heart failure), "degree1" (polynomial regression for hbA1c), and "degree2" (polynomial regression for NT-proBNP) is a universal biomarker prediction tool that can be used for evaluating the performance and predicting values of biomarkers in the next hospital visit.

To run phope.py after creating a data.csv, type python phope.py in the terminal.
The following table is an example of data.csv. 
2023/4/10 is the date of the next hospital visit.

# An example of data.csv for phope.py
<img src="https://github.com/ytakefuji/patient/raw/main/datacsv.png" height=120 width=480>

In phope.py, you can change Python codes for your use.

phope is a PyPI universal biomarker prediction tool with data.csv. 
phope allows users to run on Windows, MacOS, and Linux operating systems 
as long as Python is installed on the system. 
phope can set left vertical axis and right vertical axis of two biomakers with data.csv.

data.csv for phope is a data file composed of seven determinants such as "day" (tested date), "hbA1c" value (biomarker for diabetes), "NT-proBNP" value (biomarker for heart failure), "degree1" (polynomial regression for hbA1c), "degree2" (polynomial regression for NT-proBNP), the left vertical-axis range (low and high), and the right vertical-axis range (low and high).

The data.csv file must be created by the patient or physician before running the program as shown in the following table.

# An example of data.csv for phope
<img src="https://github.com/ytakefuji/patient/raw/main/fig.png" height=120 width=480>

phope allows users to modify two biomarker's names such as hbA1c and NT-proBNP in data.csv.

Five determinant names such as "day", "degree1", "degree2", 
"y1" and "y2" should not be changed in data.csv.

This example shows two biomarkers such as hbA1c and NT-proBNP. 

phope can predict any two biomakers simultaneously with the second and third columns in data.csv.

Columns 4 (degree1) and 5 (degree2) show the degree of polynomial regression for the first and second biomarkers, respectively.

Columns 6 (y1) and 7 (y2) set the range of vertical axis for the first and second biomarkers, respectively. The range of y1 is from 5 to 9 and that of y2 is from 0 to 450.

Based on data.csv with state-of-the-art technology using linear polynomial regressions, phope or phope.py can calculate and predict values of biomarkers for the next hospital visit.

R2-squared value can identify the best polynomial regression model. The higher the R2-squared, the better the prediction accuracy.

Predicting biomarker values allows patients to know the progress and trends of improvement in their diseases. 

Predictive values are hopes of patients.

An image png file will be automatically generated by phope or phope.py

# How to install phope
If you receive an error message in installation, Python may not be installed properly.

$ pip install phope

# How to run phope
Make sure that data.csv file is the same directory for running phope.

$ phope

