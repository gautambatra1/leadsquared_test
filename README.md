# leadsquared_test
GAUTAM BATRA
17BIT0291
gautambatra000@gmail.com
JOB ROLE-Reports Developer
Q1-Write a query to print the number of employees per department in the organization
Select department,count(*) from employee group by department;
Q2-Write an SQL query to find the name of the top-level manager of each department
Select first_name,last_name from employee where employee_id=(select manager,department from employee group by department);
Q3-Write a query to find the total incentive received by a given employee in a given month.
select SUM(incentive_amount) from employee,incentives where employee.employee_id=incentives.employee_ref_id and employee.first_name='GIVEN NAME';
Q4-Write a query to find the month where employees got maximum incentive
select incentive_date from incentives where incentive_amount in(select MAX(incentive_amount) from incentives);



SECTION 2
Q5-You have two sand timers, which can show 4 minutes and 7 minutes respectively. Use both the sand timers (at a time or one after other or any other combination)and measure a time of 9 minutes.
At 0 minutes: Start both hourglasses at the same time.
At 4 minutes: 4 minutes hourglass runs out and flip it. 7 minutes hourglass is left with 3 minutes
At 7 minutes: 4 minutes hourglass is left with 1 minute. 7 minutes hourglass runs out and flip it.
At 8 minutes: 4 minutes hourglass runs out and 7 is filled with 6 minutes and 1 minute on the other side. Flip it as the sand is left with 1 minute.
At 9 minutes: 7 minutes hourglass becomes empty from above side
Q6-
Ans6- 1/3
Q7- 
Ans 7-In the given excerpt the credit of the business increase by 10% is solely given to the advertisement which according to me might not be true as there are other factors which are also responsible for the increase in business like a customer recommending the cafe to his/her friend .Increase in the business activities in nearby areas,increse in the customer satisfaction index of the cafe etc. 
In conclusion I believe that the advertisement might have benefitted te cafe but it is not solely responsible for the increase in cafe's business.

