Download Link: https://assignmentchef.com/product/solved-sql-statements-to-grant-the-following-privileges
<br>
<strong>An owner of a relational database (ADMIN) created</strong> <strong>the following relations:</strong>

<strong>STUDENT</strong> = (ID, NAME, TOTAL_CREDIT, DEP_NUMBER)

<strong>INSTRUCTOR</strong> = (ID, NAME, SALARY, DEP_NUMBER)

<strong>COURSES</strong> = (COURS_ID, TITLE, DEP_NUMBER, CREDITS)

<strong>DEPARTMENT</strong> = (DEP_NUMBER, BUILDING, BUDGET)

<strong>The ADMIN user wants to pass privileges to other accounts X, Y and Z. Write the correct SQL statements to grant the following privileges.</strong>

1-Account <strong>X</strong> can retrieve or modify any relation except <strong>COURSES</strong> and can pass any of these privileges to other accounts.

2- Account <strong>Y</strong> can retrieve all the attributes of <strong>STUDENT</strong> and <strong>COURSES</strong> except <strong>TOTAL_CREDIT</strong>, <strong>DEP_NUMBER</strong> for both relations. <strong>[2 marks]</strong>

3- Account <strong>Z</strong> can retrieve any attribute of <strong>INSTRUCTOR</strong> but only for those whom working on the IT (DEP_NUMBER=2). <strong>[1 mark]</strong>