
The dataset is used for this competition is synthetic but based on a real dataset (in this case, the actual Titanic data!) and generated using a CTGAN. The statistical properties of this dataset are very similar to the original Titanic dataset.
https://www.kaggle.com/c/tabular-playground-series-apr-2021/data

**Data Dictionary**

| Variable | Definition | Key |
|----------|------------|-----|
| survival |	Survival |	0 = No, 1 = Yes |
| pclass |	Ticket class |	1 = 1st, 2 = 2nd, 3 = 3rd |
| sex |	Sex	|  |
| Age |	Age in years |  |
| sibsp |	# of siblings / spouses aboard the Titanic |  |	
| parch |	# of parents / children aboard the Titanic |  |	
| ticket |	Ticket number	|  |
| fare |	Passenger fare |  |	
| cabin |	Cabin number  |  |
| embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton  |

**Variable Notes**

**pclass**: A proxy for socio-economic status (SES)  
1st = Upper  
2nd = Middle  
3rd = Lower  

**age**: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**sibsp**: The dataset defines family relations in this way...  
Sibling = brother, sister, stepbrother, stepsister  
Spouse = husband, wife (mistresses and fiancés were ignored)  

**parch**: The dataset defines family relations in this way...  
Parent = mother, father  
Child = daughter, son, stepdaughter, stepson  
Some children travelled only with a nanny, therefore parch=0 for them.