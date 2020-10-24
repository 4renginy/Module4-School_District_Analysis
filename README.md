# School_District_Analysis



## Background

Maria and I work for city school district. We collects all the necessary information from school sites and state resources enter it to our system and analyze it.Those anlysis help the board to make sound decisions on how to spend budget most efficient way.
Recently school board has notifed us that there might be academic dishonesty: specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We were given the following tasks to complete;

	1-Replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact
	2-Repeat the school district analysis for all schools
	3-Write up a report to describe how these changes affected the overall analysis
	
## Process and Results
In order to accomplish task 1 and task 2 we have used open-source distribution software called Anaconda and one of its products, Jupyter Notebook and Pandas programming library. 
Using Jupyter Notebook and the Pandas library, we read raw data from CSV files, inspected, and cleaned them, performed mathematical calculations and completed the following code

[PyCitySchools_Challange_starter_code](https://github.com/4renginy/School_District_Analysis/blob/main/PyCitySchools_Challenge_starter_code.ipynb) running this code gave us the following:<br>
<br>
-Replacing the grades with NAN for Reading and Math results affected 461 rows. By this change total Student count for the average calculations went down to 38,709, using the new total student number we have calculated the new math and readign scores. Results are shown below<br>

<br>
District Counts Before<br>

![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/module_dist_summary.PNG)

District Counts After<br>

![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/Challange_Dist_Summary.PNG)

Looking at these pictures, reading, math, and overall passing results went down for the district. Overall passing percentage went down from 65.2 % to 64.9% which is .3 % downgrade.<br>

Next we rerun all the analysis for the district and each school as requested. Following pictures show that Thomas High School's rating for math, reading and overall passing percentages have dropped,there are no changes to other schools.<br>
*Following figure shows the Average Math, Average REading, Avearge overall Passing, Spending per student and school sizes;<br>
<br>
Before Thomas High School Recalculations<br>

![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/Module_categorized.png)

After Thomas High School Recalculations<br>

![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/Challange_Categorized.PNG)


	
_________________________Before___________After________

Passing_Reading%.........97.3088.........97.1873     
Passing_Math%............93.2721.........93.1856     
Passing_Overall%.........90.9480.........90.6303     

<br>
*Although there is .3 % drop on the overall passing percentage Thomas High School kept its second place as high performing school.<br>
<br>
Each School Top 5 Before,<br>

![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/Module_first_five.PNG)
<br>
Each School Top 5 After<br>

![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/Challange_top5.PNG)

<br>
*Per student spending for Thomas High School was for has remained the same as $ 638, however overall passing rate for the spendng bucket dropped from 62.8576% to  62.7782 %.<br>

*Running the calculations for the type of the school showed despite the 0.5 %drop on THS success rate Charter Schools have better success rating than the district schools.<br>
 Before the change;<br>
 <br>
![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/Module_success_by_type.PNG)

<br>
After the change;<br>
<br>

![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/Module_success_by_type.PNG)

Overall the math, reading and overall passing rates and passing rate for the ($ 638) buckets have been dropped for both district and Thomas High School but it was not significant so THS kept its second place among most successful schools and medium size schools. Most affect was on per grade calculations for math, reading and overall success. 
