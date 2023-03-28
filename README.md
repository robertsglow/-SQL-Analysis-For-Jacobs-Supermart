# **Jacobs-Supermart**

![](Image_front-2.png)

**Introduction:**
This is an SQL Analysis for an imaginary Supermart Store, showing the Names,Departments,Salaries,State of each workers in the Store.
Areas covered in the analysis includes DDL,DML,TCL,TQL(of course because i did a lot of **SELECTING**:see_no_evil:) You will definitely find more query languages along the line in this project:yum:


_Disclaimer_ This project is done to improve my skills and to show that to a fault,i can use all these query languages appropraitely.The names,values are imaginary.Lets jump right in :boom:

Lets create the **Database** that will house our queries

Database                                               |Result
:------------------------------------------------------|:------------------------------------------------------
![](new_1.png)                                                  |![](next_.png)

There we have it:smiley: Make sure you select the Database you just created,so that when you create your table it automatically houses it in that Database

Now, let us create a table.The table will be hosted in our Database

![](2.png)

Looks like our table will be empty:weary:Lets populate it

![](3_(2).png)

Lets select all we populated to see the Before and After magic

Before                                           |After
:-------------------------------------------------|:-----------------------------------------------------------
![](Select_new.png)                                             |![](4.png)


Lets do some basic calculations
- average
- minimum
- count

![](5.png)

The result:

![](6_(2).png)

Lets update the salary of one of the Employee:shushing_face:
Update Query                                                 | Updated
:----------------------------------------------------------|:---------------------------------------------
![](7_(2).png)                                             |![](8.png)

Lets update some of our Employee names:
Before                                                     | After
:--------------------------------------------------------|:--------------------------------------
![](9.png)                                               |![](10-(2).png)

We want to modify our table and, add another column to the existing table.

Before                                          | After
:-------------------------------------------|:-------------------------------------
![](alter-column_.png)                                        |![](12.png)

Oh Oh:unamused: Empty rows again.Lets populate

Before Population                               | After Population
:-----------------------------------------------|:------------------------------------------
![](13-(2).png)                                           |![](14.png)

Yaay!

We can **SELECT** functions, we may want to call out some columns without returning the entire table. See here:point_down:

![](15_NEW.png)

We want to use the group by statement now

We can see the statement and Output below

Query                                   |Result
:---------------------------------------|:---------------------------------------
![](16.png)                                    |![](17.png)

We want to use the ORDER BY command to sort our query in asc order

![](orders-.png)

The next on the line now is to add more values to our existing table after which,we will drop the salary column. The output is below

Populating table                           | Alter Query
:------------------------------------------|:----------------------------------
![](20-(2).png)                               |![](21.png)

The SELECT statement is used to call our table, it then returns our entire column excluding the Salary column which we already dropped

![](new_0.png)

Next on the list: We want to create another table which will house our Employee_payment_details
![](22.png)

lets populate :tired_face:

![](23.png)

Now that it has been effected,lets view our tables together! Yes, we can view tables together using the SELECT command.see here:point_down:
Before                                     | After
:------------------------------------------|:-------------------------------------------
![](24-(2).png)                            |![](24next.png)

We want to add more rows to our table,but different banks from default bank

![](25.png)

We want to use the SELECT command along with the WHERE clause to run some Queries.
Before                                    |After
:-----------------------------------------|:------------------------------------------
![](26.png)                                     |![](27.png)

Lets use the comparison operator to run Queries in our Employee_payment_detais table.Below is a snippet of what the before and after query looks like.
Before                                  |After
:------------------------------------------|:------------------------------------------
![](29_(3).png)                                      |![](29_(4).png)

Oops! looks like our time is far spent :open_mouth: Lets look at the range operator before we conclude.

![](30-(2).png)

![](30-3.png)

Thank you for staying tuned. In the concluding part, we will be joining our tables and creating views:yawning_face:
