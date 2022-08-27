# Heart-Disease-Prediction
The definition of classifying is categorizing something or someone into a certain group or system based on certain characteristics. Here we are classifying whether or not an individual is having a heart disease or not on the basis of given data.

We have a binary classification problem (a sample can only be one of the two things) with us. In this problem to identify whether or not an individual is having a heart disease or not we will be using number of different features (pieces of information) i.e. clinical data/parameters about a patient, example age, chest pain type, fasting blood sugar, etc.


## Data Used
The original data came from the Cleveland database from UCI Machine Learning Repository.
Howevever, I downloaded it in a formatted way from Kaggle. The original database contains 76 attributes, but here only 14 attributes will be used. Attributes (also called features) are the variables what we'll use to predict our target variable. Attributes and features are also referred to as independent variables and a target variable can be referred to as a dependent variable. Here the independent variables are a patients different medical attributes and the dependent variable is whether or not they have heart disease.


## Heart Disease Data Dictionary
Data dictionary describes what we are dealing with. We can't possibly know each and everything about our data so this is where we may have to do our research or ask a subject matter expert (someone who knows about the data) for more.
These are the features/attributes we will be using to predict our target variable (heart disease or no heart disease).

1. age - Age in years
2. sex - (1 = male; 0 = female)
3. cp - Chest Pain Type
    - 0: Typical angina: chest pain related decrease blood supply to the heart.
    - 1: Atypical angina: chest pain not related to heart.
    - 2: Non-anginal pain: typically esophageal spasms (non heart related).
    - 3: Asymptomatic: chest pain not showing signs of disease.
4. trestbps - Resting blood pressure (in mm Hg on admission to the hospital).
    Anything above 130-140 is typically cause for concern.
5. chol - Serum Cholestoral in mg/dl
    - serum = LDL + HDL + .2 * triglycerides
    - Above 200 is cause for concern
6. fbs - (Fasting Blood Sugar > 120 mg/dl) (1 = true; 0 = false)
    - '>126' mg/dL signals diabetes
7. restecg - resting electrocardiographic results
    - 0: Nothing to note
    - 1: ST-T Wave abnormality
         - Can range from mild symptoms to severe problems.
         - Signals non-normal heart beat.
    - 2: Possible or definite left ventricular hypertrophy
         - Enlarged heart's main pumping chamber
8. thalach - Maximum heart rate achieved.
9. exang - Exercise induced angina (1 = yes; 0 = no)
10.oldpeak - ST depression induced by exercise relative to rest
    - Looks at stress of heart during excercise.
    - Unhealthy heart will stress more.
11.slope - the slope of the peak exercise ST segment
    - 0: Upsloping: Better heart rate with excercise (uncommon).
    - 1: Flatsloping: Minimal change (typical healthy heart).
    - 2: Downslopins: Signs of unhealthy heart.
12.ca - Number of major vessels (0-3) colored by flourosopy.
    - Colored vessel means the doctor can see the blood passing through.
    - The more blood movement the better (no clots).
13.thal - thalium stress result
    - 1,3: normal
    - 6: Fixed defect: used to be defect but now it's okay.
    - 7: Reversable defect: No proper blood movement when excercising.
14.target - Have disease or not (1=yes, 0=no) (= the predicted attribute)
