# Practical_tasks/ Each branch presents a corresponding solution to each practical.
# Assignment for Practical Task #5

You need to write two classes, MovablePoint and MovableCircle, that implement the Movable interface based on the classes developed in Practical Task #4.

# Assignment for Practical Task #6

1. Add the previously developed Rectangle class to the project. If it doesn't exist, create it. Based on it, write a new class,
MovableRectangle (a moving rectangle). Your class must implement the Movable interface.
2. The rectangle can also be represented as two moving MovablePoints (representing the upper-left and lower-right points) implementing the Movable interface.
3. Ensure that the two points have the same speed (you need to add a method that checks whether the points are moving at the same speed).

# Assignment for Practical Exercise #7

1. Create an abstract class describing tableware (Dish). Using inheritance, implement different types of tableware, each with its own properties and methods. Test the classes.
2. Create an abstract class describing dogs (Dog). Using inheritance, implement different dog breeds. Test the classes.

# Assignment for Practical Exercise #8

1. Create an abstract class describing furniture. Using inheritance, implement different types of furniture. Implement a furniture store class (FurnitureShop), implement a furniture catalog with the ability to purchase. Create a console interface.

# Assignments for Practical Exercises #9 and #10

1. Create an Employee class defining an employee. Required fields: Last Name, First Name, Fixed Salary, and Position (see step 2).
2. Create an EmployeePosition interface defining the position. Define the String getJobTitle() method, which returns the job title, and the double calcSalary() method, which returns the employee's salary based on their fixed base salary.
3. Create classes that define employee positions. All of them must implement the EmployeePosition interface.

- Manager — The salary consists of a fixed portion and a bonus of 5% of the company's earnings. Generate a random amount of earnings between 115,000 and 140,000 rubles.
- TopManager — The salary consists of a fixed portion and a bonus of 150% of the salary if the income of employees below this rank exceeds 10 million rubles.
- Operator — The salary consists of a fixed portion only.

4. Create a Company class that contains employees and implements the following methods:

- Hire a single employee – hire(),
- Hire a list of employees – hireAll(),
- Fire an employee – fire(),
- Get company income – getIncome().

Choose the arguments and return values ​​for the methods based on the logic of your application.

Create two methods that return a list of the specified length (count). They should contain employees sorted by salary, ascending and descending:
- List<Employee> getTopSalaryStaff(int count),
- List<Employee> getLowestSalaryStaff(int count).

Choose the arguments and return values ​​for the methods based on the salary calculation logic.

## To demonstrate and test your classes:

1. Create a company and hire 180 Operators, 80 Managers, and 10 TopManagers.

2. Print a list of the 10-15 highest salaries in the company.
3. Print a list of the 30 lowest salaries in the company.
4. Fire 50% of the employees.
5. Print a list of the 10-15 highest salaries in the company.
6. Print a list of the 30 lowest salaries in the company. Examples of Salary List Output: List of five salaries in descending order:
- 230,000 rubles
- 178,000 rubles
- 165,870 rubles
- 123,000 rubles
- 117,900 rubles

## Recommendations:
- You can create different company instances with their own list of employees and income.
- To retrieve company data within the job class, store a reference to Company and pass the Company object using a constructor or setter.
- Please note that methods for obtaining salary lists may receive count values ​​that exceed the number of employees in the company, or that are negative.
