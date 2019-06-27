# KCSNB

This appliation predicts any variable in any categorical dataset for given values of predictor variables.
If a dataset contains 4 variables, then any variable can be predicted based on the values of the other three variables given by the user. 
The user can upload their own datasets and select what variable they want to predict.
A handsontable is provided to enter the predictor values and also accuracy of the prediction is also shown.
   
Follow the instruction sbelow to use the application in RStudio in your own computer
   
   install.packages("devtools")  \n
   library("devtools")
   devtools::install_github("Chaithanya07/KCSNBShiny")
   library("KCSNBShiny")
   KCSNBSiny()
