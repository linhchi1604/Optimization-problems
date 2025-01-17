# Optimization problems
These are assignments from the course at my university about operations analytics. Three optimization problems presented are: (1) Aggregate Planning, (2) Capaciated Lot Sizing with multiple Products, and (3) Line Balancing.


# 1. Aggregate Planning
The FlowHigh AG, worldwide leader in the production of positive displacements rotary pumps, produces three main products: lope pumps, gear pumps and vane pumps. A forecast for each product has been made for the upcoming six months and the demand has to be fulfilled (no back-orders are allowed).

The factory has period specific technical capacity (c) and workforce capacity (n) (can be extended by overtime, which is limited to o time units per period).

In order to produce one unit of product k, b units of technical capacity and a units of workforce capacity are needed. The coefficients of the workforce capacity are a=(0.5, 1.0, 0.8) and the coefficients of the technical capacity are b=(1.0, 0.5, 0.8), the initial inventory level of product group 1 is 20 units.

The demand and capacity data is given in the following table:

![image](https://github.com/user-attachments/assets/2e670141-9ef9-4951-a513-5aeac5ebd550)

The goal is to find the optimal production quantity for all product groups and all periods. If the production quantity and the demand are not equivalent, then inventory level either raises or decreases. The cost per period of one unit in stock  is l=(8, 4.5, 6), while overtime costs are u=10 per period (costs are expressed in hundreds of €). All other costs do not have an influence on the structure of the optimal production plan.


# 2. Capacitated Lot Sizing with multiple Products
The Capacitated Lot Sizing Model with multiple Products has many applications in many industries including the production of fruit-based beverages. One of the features of the production of fruit-based beverages is the need for a setup process when a production resource e.g., a tank switches from one product to the next. A dataset with real demand is given in the file "lotsizing.xlsx".

Part a: Find the optimal solution

Part b: Carry out a sensitivity analysis to show the impact of the inventory holding costs on the total costs. Assume that the same inventory costs apply to all products. Visualize the results of the sensitivity test.


# 3. Line Balancing
Work on the line balancing problem for Stars Hollow's blanket production. All input data, except for the demand D, is already entered in the Jupyter notebook. The goal is to minimize the number of workstations.

Part a: Find the optimal objective value when demand D = 32 blankets.

Part b: Analyze the maximum demand for which the optimal solution from (a) remains feasible. Begin with D=32. Increment demand by 1 in each iteration, solving the model until the number of required stations increases.

Part c: Consider the situation where the total demand, D, is stochastic and follows an uniform distribution between 25 and 55. Generate a sample of size 100 from the distribution of D. Subsequently, calculate and print the mean and the coefficient of variation of the sampled data.
