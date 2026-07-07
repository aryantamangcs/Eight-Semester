
## Understanding the context

***Linear programming is one of the tools of operations research.***

Normally, there are two approaches which we use for decision making. They are:
- Quantitative Analysis
- Qualitative Analysis

#### Quantitative Analysis is based on measurable data. We use mathematical techniques during this analysis.

#### Qualitative Analysis is based on experiences, behaviors, perceptions. For example, Interviewing people , Open Ended surveys etc.

## Main Goal of Linear Programming Problem

***The main goal of linear programming problem is to maximize profit, revenue and minimize cost and loss.***

## Applications of Linear Programming.

Linear programming is used whenever someone wants to use limited resources in the best possible way.

#### 1. Production Planning (Manufacturing)

Question:

> How many units of each product should be produced to maximize profit?

Example:  
A factory produces:

- Shoes
- Bags

Constraints:

- Labor hours
- Machine time
- Raw materials

Objective:  
→ Maximize profit

LP decides:

- Produce 300 shoes
- Produce 150 bags

instead of guessing.

#### 2. Resource Allocation

Question:

> How should resources be distributed efficiently?

Resources:

- Budget
- Workers
- Machines
- Time

Example:  
A company has $100,000 and must allocate among:

- Marketing
- Development
- Infrastructure

Goal:  
→ Maximum return.

#### 3. Transportation Problems

Question:

> How do we move goods at minimum cost?

Example:  
Warehouses → Stores

Constraints:

- Supply available
- Demand required
- Shipping capacity

Objective:  
→ Minimize transportation cost.

Applications:

- Amazon logistics
- Food delivery
- Supply chains

#### 4. Diet / Nutrition Problems

Question:

> What combination of foods gives required nutrition at minimum cost?

Example:  
Need:

- 2500 calories
- Protein target
- Vitamin requirements

Objective:  
→ Minimize food expense.

This was actually one of the earliest LP applications.

#### 5. Workforce Scheduling

Question:

> How many employees should work each shift?

Example:  
Hospital scheduling.

Constraints:

- Labor laws
- Employee availability
- Demand

Objective:  
→ Minimize cost while maintaining service.


## Structure of Linear Programming Problem

- Decision Variable (Things that are under control of LPP)
- Objective function (The mathematical linear relationship or main objective of making decisions)
- Constraints and Conditions (Restrictions imposed on the available resources)


## Assumptions of Linear Programming Problem

- Linearity (Objective functions and constraints must be linear)
- Proportionality (Profit, Loss, Revenue must be proportional).
- Non-Negativity (All the variables in the linear programming model are either zero or greater than zero).

## Linear Programming Formulation

Read the book page number 14 or ask 


***Now I assume you know somewhat about Linear Programming Problem

## Methods for Solving LPP

Different methods are used to solve LPP. However, we are going to discuss only two methods:

- Graphical method
- Simplex method


#### 1. Graphical Method

Video to watch
https://www.youtube.com/watch?v=2EvC1v1FI2k

**Terminologies to remember**

**Feasible Region**: The common region which satisfies all the constraints is called feasible region.

**Feasible Solution**: Every point inside the feasible region is called feasible solution.

**Optimal Solution**: The best solution obtained in LPP.

< and > makes huge difference. Normally < means towards the origin and > means away from the origin.

***Unbounded solution*** -> If there exists a lot of feasible solutions for maximum then it is called unbounded solution

If you have two lines, the intersection point is simply the point that satisfies both equations at the same time.

#### 2. Simplex Method

Okay so cool, we have graphical method, we can solve the linear programming problem using graphical method. so why do we need simplex method?. And why do examiners keep asking about simplex method to solve the linear programming problem?

Well

***As you must have noticed, In graphical method, we have only used two decision variables. only x1 and x2. If you haven't realize it, go through the graphical method problem once again.***

***Graphical method cannot solve a linear programming problem if there are more than two decision variables in the problem. And in real life, it is definitely not limited to only two of them. To solve LPP with two or more than two decision variables, there are two ways of solving them. They are***

- Algebraic method
- Simplex method

Simplex method is the modified form of algebraic method of solving LPP.

Hence, we will focus more on simplex method.
The only thing that you need to remember about simplex method is 

It is an iterative procedure to get the optimum solution of the problem.
It starts with basic initial solution and gradually moves towards the best optimum solution.

#### Why Simplex method is superior over the other methods?

- It can solve two or more than two decision variables problems.
- It always moves towards the optimum solution.


SImplex method tutorial
https://www.youtube.com/watch?v=FYqg62rYxhs


From the above tutorial. Here are some of my takedowns:

- The most important step is to find key column . Key column (more negative number)
- After finding key column, we find ratio. Ration = RHS/key column (RHS is also known as constant)
- After than we find the key row.  which is exact opposite of key column (small positive) (Remember opposite of more is small and negative is postitve)
- After we find the key row and key column, We find the key element (THe most important thing)
- We try to make key element 1 after that, and every element above and below key element 0
- Then we iterate to next table and try to find key column (more negative). If there is no negative, then we found the optimum solution and then the answer.



