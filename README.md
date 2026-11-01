# titanic_eda
Exploratory data analysis on 'Titanic Dataset' from Kaggle. 

Assignment for CPSC 4800 given by Nasim Taba.
EDA carried out by Oluwanifesimi Olubunmi.

This EDA as of November 1, 2026 explores three hypothesis

1. If the survival rate had any association with class of passengers
2. If the survival rate had any association with gender of passengers
3. If the survival rate had any association with the age of passengers

Results of the explorations can be found in the "Results" folder.

Graphs are saved in docs for reference but can also be found in each .pdf file inside the 'Results' folder.

The dataset was sliced into different subsets for the purpose of the EDA and the survival rates for each category was calculated by dividing the number of passengers who survived in a specific category by the total number of passengers in that specific category multiplied by 100 to get the percentage i.e. (surv_women/total_num_women)*100. EDA code for each hypothesis can be found in the /src folder.

FUTURE EDA

In the nearest future, I hope to be able to figure out if there were passengers that fit into two or more of the categories with considerably higher chances of survival but did not survive. I.e. female adults with class 1 ticket (like the beautiful Kate Winslet. ||  R.I.P. Jack 😔)