# CS777_TermPaper
Demonstration of SystemDS
- Environment setup
  This program is run on google collab. This requires accessing the website at
  https://colab.research.google.com/
  and uploading the code directly. The coad includes a pip command to add the necessary
  library to run. Adding the dataset to collab directly works best instead of referencing a local cop.y
  Select the file icon on the left side of the screen to add the file directly.
- How to run the code
  Add the dataset file to the collab session. Right click the file in collab to get the collab pathway, copy and paste
  this over the existing text string on line 10.
  The execution button in the shape of a play button. the top left corner should be selected.
- Results of running the code with data
  The code will ouput an indecipherable matrix object.
- Detailed explaination of the dataset and results
  The dataset consists of 10,000 entries, and includes 26 variables. These are descriptive information of NYC
  restaurants and their results in food safety inspections. The code runs a linear regression
  against the geographical lattitude of the restaurant against their rating in food safety. The idea was to determine
  if the geographical location of a restaurant had an association with their food safety.
  Interpretting the proprietary matrices internally used in systemds was not completed. 
