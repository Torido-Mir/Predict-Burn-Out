# Predict-Burn-Out
* I am interested in predicting the values for burn rate using either or both of the independent variables (features) 
* About the data set:
        Features:  
        Resource Allocation (RA): The amount of resource allocated to the employee to work, ie. number of working hours.
        On a scale of 1 to 10, strictly integers.
   
        Mental Fatigue Score (MS): The level of fatigue mentally the employee is facing.
        On a scale of 1 to 10,  float datatype, where 0.0 means no fatigue and 10.0 means complete fatigue.
  
        Target: 
        Burn Rate (BR): The value we need to predict for each employee telling the rate of burn out while working.
        On a scale of 0 to 1,float datatype 

* Objectives:
I am interested in predicting the values for burn rate using either or both of the independent variables (features) 

* Why does this matter ? 
It helps employers prevent foreseeable burn out, boost overall productivity and efficiency, and consequently save money for their companies.
Specifically, burnout can lead to a range of costs for employers, including:
+ Decreased Productivity: Burn out could hinder creativity and innovation within an organization. 
+ Employee Turnover: Employees experiencing burnout may leave the organization, resulting in recruitment and training costs for new hires.
+ Impact on Company Culture: Burnout can have a negative impact on the overall company culture and employee morale.

* Methodology:
The data set comes with train.csv (for training) and test.csv (for testing). For methods 1 and 2 and their variants, I make 2 models. 

I train the first model with the entire train.csv and then test it with test.csv. 
I train the second model with 70% of train.csv and test it with the other 30% of the set. 

This is because test.csv does not come with target values (burn rate) and it makes it impossible to validate the results using some common methods such as cross-validation 
