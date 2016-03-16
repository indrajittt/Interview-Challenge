#Software Engineer – Backend / Frontend challenge 
##Welcome
Welcome to the AKJ technical challenge! If you are someone who is looking to be a part of the next big company, you are here at the right place. You will be a part of a sharp, motivated and world class team working on the most ground breaking technology. 

##Basics 
The rules of this challenge are simple –

•	Your code should be commented

•	We at AKJ, take code organization quite seriously, so please do ensure your source files are organized when you submit

•	Please complete the code in your local repository and email a patch file / the link to info.theakjgroup@gmail.com

•	Please note that you will also be judged on the elegance of your code, level of abstraction and technical skills presented in the implementation. For more details, refer to the Judging Criteria section below.

##The Challenge
###What You’ll need to build:
You will need to build a sandbox for our users which lets them play around with sample stocks they might use to construct the portfolio. What they choose is not reflected in their actual choice on our production system, but you should still let them get a good sense of what would have happened had they actually chosen the stocks.

Requirements:

•	Portal login functionality – user should be able to login / logout of the interface.

•	Once logged in he should be able to select from a stocks list (provided in file Stocks List.xlsx) 

•	Backend algorithm will return some weights (use some dummy weights for now) for this portfolio. You are encouraged to build your own heuristics for weights.

•	Historical performance charts of the chosen portfolio vs individual stocks will be displayed in a time series (user selected time range) which will change depending upon the portfolio user selects.
An example of a historical performance graph is provided below- charts should be highly intuitive and interactive making the user experience a smooth one. 
 
•	Store user history. The user should be able to see his previous selections and also visualize the previously generating graphs/charts for those selections. You can further enhance this feature by comparing the different stocks you looked at.

##What you are encouraged to use
1.	Django
2.	ReactJS
3.	PostgreSQL

##Judging Criteria
•	What you have produced will determine your final outcome

•	Responsive and creative design, appropriateness of error messages, etc. 

•	Historical graph should have low latency with large number of data points

