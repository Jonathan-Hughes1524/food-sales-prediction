 Food-Sales-Prediction
  Using Machine Learning to make future sales predictions
  
Author: Jonathan Hughes

Business problem:
Forcasting future sales of outlet stores based on informational data gathered by the stores. 

Data:
That dat used can be found in the link. 
C:\Users\jhugh\OneDrive\Desktop\Coding Dojo\sales_predictions (1).csv
This data provides outlet sizes, year established and tier of outlets. Along with that it provides the data on the items being sold with relevent data to use on each item.

Methods:
  * The first methods that I used were data cleaning.
  * I checked the data for duplicates and deleted those.
  *Also checked for any missing data and made a decision on what to do with missing data. 
  * After that visualizations were made to represent the data.
  * Then used preprocessing to prepare the data to be used in Machine Learning.
  * After preprocessing ran the data through a Linear Regression and Decision Tree. 
  * Evaluated the models with MAE, MSE, RMSE and R^2 metrics to determine best model.
  
  Results:
  Outlet Sale
  ![image](https://user-images.githubusercontent.com/108833661/186662710-1f5db3cf-1242-4f1f-9349-7ac53a80232a.png)
  
  Heatmap Correlation 
  ![image](https://user-images.githubusercontent.com/108833661/186662990-61275010-64f5-4f70-a42f-b4dfe79c3559.png)

Model:
The final model was a linear regression. This method was able to produce a 67% of the data to be used to show the sales prediction. This gave us the best error out of the two models and allows us to predict the sales of outlet stores. 

Recommendations:
My recommendation is that the item mrp has the biggest correlation with the sales. The outlet size doesn't necessarily correlate to bigger sales. Focus more on the itmes you are selling rather then the size of the store. 

Lmitiations & Next Steps:
I have only begun my machine learning and I am working on the next steps of this. I plan on learning new methods and returning to this project to further the data and come up with more solutions on how to predict sales. 

For futher information:
For any additional questions, please contact jhughes1542@gmail.com
