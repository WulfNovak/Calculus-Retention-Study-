# Calculus Retention Study
In this repository we recreate a calculus retention study. This includes data cleaning, variable creation, data visualization, a mixed effects logistic regression model, and some very simple interactive graphs. The intended audience for this report  

**Where to start:** Under the following file description section I have the files listed in the order you should visit them

**File Description:**
1. *Original Calc Retention Study*
  * This is the original study and writeup. The data used and tables created in the following files were reproduced to match the tables found in this paper. Instructions from this paper were used to assure accurately cleaned data, and a mixed-effects logistic regression model was created under the same specifications as the paper, however, the bayesian portion was not recreated. 
  
2. *Replicated Data Cleaning and Tables*
  * This features the long data cleaning process, which includes aggregating select variables into a switch/persist variable and Principal Component Analysis. Tables S1, S5, S6, S7, and S8 from the original study are created from scratch. The tables were modified visually from the paper useing kablextra and are arguably more clear and easy to read. The code used for the data cleaning, specifically coding the switcher/persistor variable, is inefficient. My professor offered suggestions on how to make the code more efficient, and these suggestions are implemented in the '3. *Calc Model and Results*' file.   
  
3. *Calc Model and Results*
  * This is a report for my professor displaying the model used, a few graphs with interpretation provided, and all of the code used to generate the graphs. Interactive versions of these graphs were created but are not included in this repository.  

**Additional Files:** CalcData.csv is the data used in this project, and CalcData README is the variable description for the CalcData
