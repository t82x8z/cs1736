java c
CS/ECE/ISyE 524
Introduction to Optimization
Spring 2022
524 Midterm Exam
1. [10 points total] Short-Answer Questions.
a) [1 point] Given two points x and y, we define w as
w = (1 − α)x + αy
for α ∈ R. Circle the correct answer(s):
• w is called a convex combination.
• w defines a line.
b) [1 point] Consider the function f and any two points x and y in the domain of f. If f satisfies f((1 − α)x + αy) ≤ (1 − α)f(x) + αf(y) for all points x, y and 0 ≤ α ≤ 1, then we have that...
(circle the correct answer(s))
• f(x) is a convex function.
• f(x) is a concave function.
c) [3 points] You try to solve a linear maximization problem using Clp, and the solver returns ”unbounded”. Circle the correct answer(s):
• Something went wrong inside the solver.
• The feasible space is empty.
• You may be able to obtain a (finite) optimal solution by changing the objective function.
• You might have forgotten to add a constraint.
• The dual problem is infeasible.
• The problem is non-convex.
2. [17 points] Linear Programming and Duality. Consider the following linear program:
min 2x1 + 2x2
x1,x2
subject to 2x1 + 5x2 ≥ 10,
2x1 + x2 ≥ 4,
x1 ≤ 7,
x1, x2 ≥ 0.
(a) [5 points] Solve this linear problem graphically. Make sure to indicate the direction of the objective function, the optimal solution and the feasible region.
(b) [2 points] What is the value of x1 and x2 at optimality?
(c) [5 points] Write down the dual of this linear program. (Use λ1, λ2, λ3 to denote the the variables in the dual.)
(d) [5 points] Use complementary slackness to find the optimal solution of the dual problem.
3. [16 pts] Modeling
Imagine that you are organizing a summer camp for high-school students. The summer camp will host 100 students and has 10 possible activities to choose from (where each activity has a capacity of 10 students). The summer camp lasts 5 days and each student will participate in one activity per day. In the final stages of organization, you are matching the students with the a代 写CS/ECE/ISyE 524 Introduction to Optimization Spring 2022 Midterm Exam
代做程序编程语言ctivities.
Each participating student is asked to fill in a form. to indicate 5 activities which they are most interested in. They are asked to rank those 5 activities from 1 to 5, with 1 indicating highest interest and 5 indicating lowest interest. Since some activities are more popular than others, students may not be able to participate in all 5 activities of their choice.
Your goal is to assign students to the activities, while trying to ensure that the students get to partic-ipate in the activities that they are most interested in. If they cannot participate in the activities they had indicated interest in, they will be assigned to other activities
a) [5 points] Make a sketch which visualizes this problem as a minimum-cost network flow problem on a graph. What do the nodes in the graph represent? What do the edges represent? What does the cost of each edge represent? (You do not have to draw all the nodes of the graph, it is sufficient to make a sketch that indicates the different types of nodes and the edges between them).
b) [2 points] What values would you assign for activities that students had not chosen as their top five activities? Explain why.
c) [7 points] Formulate the problem as a linear program which matches students with activities, considering the preferences of the students.
What are your decision variables? What is the objective function? What are the constraints?
Make sure to include explanation in words, as well as the mathematical model. Define all problem parameters.
d) [2 points] The optimization problem you created above could potentially lead to a solution where some students get to participate in all their favorite activities, while other students do not get any of their choices fulfilled. This could be perceived as unfair. Can you suggest a change to the objective function that would guarantee a more fair assignment across different students? Please explain both the change that you make, and why you believe it will lead to a more fair solution.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
