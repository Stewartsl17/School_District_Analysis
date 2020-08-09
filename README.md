# School_District_Analysis

# Project Overview 

Maria, the chief Data Scientist for a school district, has asked for our help analyzing data in order to showcase school performance which will be used by the School Board to make changes to the budget. In particular, she wanted us, using Jupyter Notebooks, to find out the following: 

  * The top 5 and bottom 5 performing schools based on the overall passing rate
  * The average math score for each grade level from each school
  * The average reading score for each grade level from each school
  * The scores by school spending per student, by school size, and by school type

Along with those metrics, she wanted to see a school summary and a district summary to overall trends. After submitting these metrics, the School Board has notified Maria that there are altered grades for Thomas High School and has additionally tasked us with removing their ninth grade math and reading scores and to assess what changes that has made to the data set. 

# Resources

* Data Source: [schools_completes.csv](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/students_complete.csv), [students_complete.csv](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/students_complete.csv)
* Software: Jupyter Notebook

# Results

## Effect on District Summary

Overall, the effect on the district summary is very minimal. The largest changes that we can observe here are the reductions in the overall passing percentage, as well as, the passing math and reading percentages by about 1% each. The changes make sense since we didn't affect much on the overall district level. Below is the newest district summary. <br>

* Table: District Summary
![](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/District%20Summary.png)

## Effect on School Summary

Similarly, we can see minimal change in the school overall averages. There are actually slightly positive changes to the data set, which could be due to better score averages amongst the other three grades. These shifts are about 1% as well. Below is the newest school summary with Thomas High School as the third to last school. <br>

* Table: School Summary
![](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/School%20Summary.png)

However, the largest changes for Thomas High School come in the form of overall school perfomance. In the school summary above, we can see that the overall passing percentages for Thomas High School have plummetted. 

* % Passing Math: 93% --> 67%
* % Passing Reading: 97% --> 70% 
* % Overall Passing: 91% --> 65% 

Moreover, these changes in the passing percentages for Thomas High School has shifted them from being a top 5 school (was number 2) to be the eighth ranked school in our dataset. The new top 5 perfoming school can be seen in the image below. 

* Table: Top 5 Schools Summary
![](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/Top%205%20Schools.png)

## Additional School Effects By Grade

### Math and Reading Scores By Grade

The only change to the math and reading scores by grade was the replacment of the scores for Thomas High School. Below are the updated math and reading scores by grade. 

* Table: Reading Scores By Grade <br>
![](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/Reading%20Scores%20By%20Grade.png)

* Table: Math Scores By Grade <br>
![](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/Math%20Scores%20By%20Grade.png)

### Scores by School Spending 

Changing the ninth grade scores has shifted some of the numbers when looking at scores by school spending. Below is the updated image of school spending by scores.

* Table: Scores By School Spending <br>
![](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/Scores%20By%20School%20Spending.png)

In the third spending bin, $630-$644 , we can observe some changes from the original dataset. These shifts are: 

* % Passing Math: 73% --> 67%
* % Passing Reading: 84% --> 77% 
* % Overall Passing: 63% --> 56% 

### Scores by School Size

Changing the ninth grade scores has shifted some of the numbers when looking at scores by school size. Below is the updated image of school size by scores.

* Table: Scores By School Size <br>
![](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/Scores%20By%20School%20Size.png)

In the second size bin, Medium (1000-2000), we can observe some changes from the original dataset. These shifts are: 

* % Passing Math: 94% --> 88%
* % Passing Reading: 97% --> 91% 
* % Overall Passing: 91% --> 85% 

### Scores by School Type

Changing the ninth grade scores has shifted some of the numbers when looking at scores by school type. Below is the updated image of school type by scores.

* Table: Scores By School Type <br>
![](https://github.com/Stewartsl17/School_District_Analysis/blob/master/Resources/Scores%20By%20School%20Type%20.png)

In the Charter school row, we can observe some changes from the original data set. These shifts are: 

* % Passing Math: 94% --> 88%
* % Passing Reading: 97% --> 91% 
* % Overall Passing: 91% --> 85% 
