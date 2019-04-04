# Calculus Retention Study
In this repository we recreate a calculus retention study. This includes data cleaning, variable creation, data visualization, a mixed effects logistic regression model, and some very simple interactive graphs. 

**Where to start:** Under the following file description section I have the files listed in the order you should visit them.

**File Description:**
1. Original Calc Retention Study
  * This is the original study and writeup. The data used and tables created in the following files were found in this paper. Instructions from this paper were used to assure accurately clean the data, and a mixed-effects logistic regression model was created under the same specifications as the paper, however, the bayesian portion was not recreated.   
2. Replicated Data Cleaning and Tables
  * This features the long data cleaning process and tables S1, S5, S6, S7, and S8. The tables were modified visually from the paper useing kablextra and are arguably more clear and easy to read. The code used for the data cleaning, specifically coding the switcher/persistor variable, is inefficient. My professor offered suggestions on how to make the code more efficient, and these suggestions are implemented in the next file.  
3. Calc Model and Results
  * This includes the model from the study and tables featuring the results. More efficient code is used to create the switcher/persistor variable. 

**Additional Files:** CalcData.csv is the data used in this project, and 
