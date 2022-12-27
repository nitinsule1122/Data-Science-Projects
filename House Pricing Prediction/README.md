Below list of task are covered in project
1. Read the Data
2. Drop unnecessary columns(Columns with no statitical importance)
3. Missing Data treatment
4. Exploratory Data Analysis <br>
	4.1 Check for Skew in X columns<br>
	4.2 Remove skew<br>
	4.3 Correlation<br>
	4.4 Drop cols from X having very minute or no correlation<br><br>
5. Preprocessing	<br>
	5.1 Standardization of con columns<br>
	5.2 OHE of categorical columns<br><br>
6. Divide data in training & testing set(Random state: 31)
7. Create a backward elemination OLS model
8. Remove unncessary columns on the basis of pval
9. Create a Linear Regression model on the basis of selected columns.
10. Find training | testing error --> Overfitting or not
11. Check for colinearity and multicolinearity
12. Ridge, Lasso
13. Create a Tuning grid
14. GrisearchCv model to find best penalty value for Ridge | Lasso
15. Using the best value, create a Ridge | Lasso Model 
16. Check for overfitting.
