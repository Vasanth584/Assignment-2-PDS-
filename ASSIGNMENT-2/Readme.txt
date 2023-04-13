Python is used to Analyse & visualize

I considered whole data as population for our analysis.

This Dataset Contains data of 768 patients. In this data there are 8 attributes (Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age) and 1 response variable (Outcome). The response variable, Outcome, has binary value (1 indicating the outcome is diabetes and 0 means no diabetes).

Firstly i cleaned the data

  A) I took 25 random sample observations and find mean of (glucose, population) and max of (glucose, population) and made dictionaries then Created a line      Plot and pie chart for visual representation of comparison.
 
 
  B) Same as A, took 25 sample observations and find 98th percentile of(BMI, population) and made dictionary then Created a line plot and pie chart for          visual representation of comparison.

  C) Using bootstrap (replace= True), created 500 samples (of 150 observation each) from the population and found the mean, standard deviation and              percentile of (BloodPressure, population) and made dictionaries then created line plot and pie chart for this comparison.

Results Folder is Having all the visualized outputs.
