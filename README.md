# Promotion-Budget-Allocation-using-Linear-Maximization-Model

Promotion Allocation: Allocate advertising budget across programs
Process: Estimate total promotion budget. identify goal of promotion efforts. Calculate
contribution delivered by each promotion vehicle (email, SEO, PPC, social, etc.). Execute
promotion allocation model. 

## Background 

You are the marketing manager for a fine dining restaurant in San Francisco, Acme Restaurant(fictitious). Acme’s top entrees include:
 Dish A: Braised Alaskan wild salmon with rice pilaf and grilled asparagus
 Dish B: Grass-fed organic beef tenderloin with baked potato and sautéed mushrooms in Cabernet sauce
 Dish C: Vegetable melee, with red and green peppers, organic beets and artichoke hearts, over a bed of spinach, served with a spicy balsamic vinaigrette

You use three promotion tools to drive business to Acme. The first tool is Facebook (F) to promote discussion of local restaurants in the community. The second tool is Groupon (G) to increase trial rate of new customers. The third tool is Yelp (Y) to show customer ratings.

After analyzing historic sales and promotion data, you assemble the data shown in Table 1.
You gain a certain number of viewers per each campaign, and the viewers are provided by
the promotion vehicle analytics. Each campaign costs a certain amount, and the cost is
provided by the monthly bill for services. You face a maximum allowable monthly budget.
Due to limited capacity (ability to produce) of the promotion service you use, you cannot
create more than a certain number of new campaigns per month.

![image](https://user-images.githubusercontent.com/113878059/228691973-9b0a4042-3c4d-46e5-84fc-7c491030c8d8.png)

## Data analysis model

The promotion allocation model uses linear optimization to calculate the optimum allocation of budget across promotion vehicles. It is an example of a normative model. The model takes an objective function and constraint equations as inputs, and delivers the maximized objective and other information as outputs.

The linear optimization process entails four steps. In the first step, we calculate the vehicle contribution, which is the amount of results generated per use of the vehicle. For example, we could estimate the number of impressions, or views, delivered by each ad. In the next two steps, we express our promotion objective and constraints in equation form. We cover how to do that in the next slides. We then execute the model.

We start by discussing promotion constraints. First is budget. Almost every organization faces a limited budget, such as a certain amount of money that can be spent each month on promotion. Next, we face legal constraints, such as legal regulations that cover that jurisdiction. Third, we often face contractual constraints, such as specific limits placed on us due to performance contracts with external agencies. And fourth, we must observe company policies.

To run the optimization model, we follow a three step process. We set up the model in a specific format, we execute the model using Microsoft Excel's Solver function, and then interpret the results. We will cover each step.




