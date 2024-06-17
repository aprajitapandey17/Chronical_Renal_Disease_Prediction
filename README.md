# Chronical_Renal_Disease_Prediction
Technological development, including machine learning, has a huge impact on health through an effective analysis of various chronic diseases for more accurate diagnosis and successful treatment. Kidney disease is a major chronic disease associated with aging, hypertension, and diabetes, affecting people 60 and over. Its major cause is the malfunctioning of the kidney in disposing toxins from the blood. This study analyzes chronic kidney disease using machine learning techniques based on a chronic kidney disease(CKD).
Given 24 health related attributes taken in 2-month period of 400 patients, using the information of the 158 patients with complete records to predict the outcome(i.e. whether one has chronic kidney disease of the remaining 242 patients(with missing values in their records).
# Data Set Information:
We use following representation to collect the dataset
 age - age 
 bp - blood pressure
 sg - specific gravity 
 al - albumin
 su - sugar
 rbc - red blood cells
 pc - pus cell
 pcc - pus cell chumps
 ba - bacteria
 bgr - blood glucose random
 bu - blood urea 
 sc - serum creatinine 
 sod - sodium 
 pot - potassium
 hemo - hemoglobin
 pcv - packed cell volume 
 wc - white blood cell count 
 rc - red blood cell count 
 htm - hypertension
 dm - diabetes mellitus 
 cad - coronary artery disease 
 appet - appetite
 pe - pedal edema 
 ane - anemia
 class - class

# Conclusion 
The ML algorithm used for training the model is Decision Tree Classifier with grid searchCV and applying hyper parameter tuning resulting with the best estimated parameter 
with the resultant F1 score - 98.9 %
The other ML algorithm used is an ensemble of logistic regression , SVM , KNN , Random Forest and Decision Tree Classifier that is resulted with F1 score - 98.9 %
