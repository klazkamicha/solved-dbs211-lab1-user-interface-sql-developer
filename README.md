Download Link: https://assignmentchef.com/product/solved-dbs211-lab1-user-interface-sql-developer
<br>
The purpose of the first lab of DBS211 is to familiarize yourself with the User Interface, SQL Developer, that we will be using throughout the course to communicate with the Oracle server.  By the end of this lab you should be able to:

<ul>

 <li>Successfully establish a connection with and login to the Oracle database server using SQL Developer</li>

 <li>Run the sample database creation script</li>

 <li>Navigate SQL Developer to view the tables created, their structure and the data contained within them.</li>

</ul>

<h1>Preface:</h1>

If you have not already done so, you will need to download the sample database creation script from blackboard and run it.  These instructions are included in the W01 – Getting Started with SQL Developer document.

LAB 01 – SUBMISSION

<h2>Explore the Database</h2>

Answer the following questions in the SQL Developer Worksheet area.  Use comment blocks for answers that are not running code.

In the connections window, expand <strong>Tables.</strong>

<ul>

 <li>How many tables have been created? List the names of the created tables.</li>

</ul>




<ul>

 <li>Click on table <strong>customers</strong>. Click on the Data tab near the top of the worksheet. How many rows are there in the table <strong>customers</strong>?</li>

 <li>What SQL statement would return the same results. Write the statement in the .sql file and execute it.You will learn how to select rows and columns from a table by writing SQL select statements later in this course.</li>

 <li>How many columns does the <strong>customers</strong> table have? List the column names.</li>

 <li>What is the value of each column in the first row in table <strong>customers</strong>? Write the column name and the column data type in addition to the value.</li>

 <li>Write the number of rows and columns for the rest of the tables in your schema. Format it something like the following.</li>

</ul>

<u>Table Name</u>                   <u>Rows</u>                          <u>Columns</u>

<u>__________</u>                _____                         _______<u>__________</u>                _____                         _______




<ul>

 <li>Right Click on the <strong>orderdetails</strong> table and choose tables/count rows. How many rows does the order details table include?</li>

 <li>Write the following SQL statement in the new tab.</li>

</ul>

desc offices;

You can also write

describe offices;

What is the result of the statement execution?

<ul>

 <li>Type the following statements in, execute them, then briefly describe what the statement is doing!</li>

</ul>

SELECT * FROM employees;

SELECT * FROM customer ORDER BY ContactLastName;

<ul>

 <li>How many constraints does the <strong>products</strong> table have?</li>

 <li>Find a way to turn on line numbers in the gutter.</li>

 <li>Set the font size in the worksheet editor to a size that is best for you. (Hint: Tools/Preferences)</li>

</ul>





