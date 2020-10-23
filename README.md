# School_District_Analysis



Maria and I work for city school district. We collects all the necessary information from school sites and state resources enter it to our system and analyze it.Those anlysis help the board to make sound decisions on how to spend budget most efficient way.
Recently school board has notifed us that there might be academic dishonesty: specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We were given the following tasks to complete;

	1-replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact
	2-repeat the school district analysis for all schools
	3-write up a report to describe how these changes affected the overall analysis
	

In order to accomplish task 1 and 2 we have used open-source distribution software called Anaconda and one of its products, Jupyter Notebook and Pandas programming library. 
Using Jupyter Notebook and the Pandas library, we read raw data from CSV files, inspected, and cleaned them, performed mathematical calculations and completed the following code

[PyCitySchools_Challange_starter_code](https://github.com/4renginy/School_District_Analysis/blob/main/PyCitySchools_Challenge_starter_code.ipynb) running this code gave us the following:<br>
<br>
-After replacing the grades with NAN for Reading and Math results, 461 number of student accounts affected by this change.<br>
	Total Student count for the average calculations went down to 38,709<br>
-Changing the grades to NAN reqired the passing math, passing reading and passing overall scored to be recalutaed.They are as below;<br>
<br>
	District Counts Before<br>
    <br>
    ![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/module_dist_summary.PNG)<br>
    <br>
    District Counts After<br>
	<br>
    ![](https://github.com/4renginy/School_District_Analysis/blob/main/Resources/Challange_Dist_Summary.PNG)
	
	
Looking at those pictures Overall passing percentage went down from 65.2 % to 64.9% which is .3 % downgrade.
-Next we rerun all the analysis for the district and each school as requested.
	
-Although there is .3 % drop on the overall passing percentage Thomas High School kept its second place as high performing school.

-Created the following spending bins
"<$584", "$585-629", "$630-644", "$645-675" and Thomas High Schol was in a 630-644 bin. There was no change to the change before and after calculations.
-Running the calculations for the type of the school 
Charter Schools seemed to be more sucessful despide the drop on 0.5 % on Overall passing percentage.
-
 
