# Promotion-Budget-Allocation-using-Linear-Maximization-Model

## Background 

Exciting news! A new fine dining restaurant has opened its doors to the public in San Francisco, and its top entrees include:
- Dish A: Braised Alaskan wild salmon with rice pilaf and grilled asparagus

![image](https://github.com/apoorvadudani/Promotion-Budget-Allocation-using-Linear-Maximization-Model/assets/113878059/13d7d395-3ad5-4283-979a-7b20d68752ac)

- Dish B: Grass-fed organic beef tenderloin with baked potato and sautéed mushrooms in Cabernet sauce

![image](https://github.com/apoorvadudani/Promotion-Budget-Allocation-using-Linear-Maximization-Model/assets/113878059/916f4780-45b9-4110-9179-494783bede73)

- Dish C: Vegetable melee, with red and green peppers, organic beets and artichoke hearts, over a bed of spinach, served with a spicy balsamic vinaigrette

![image](https://github.com/apoorvadudani/Promotion-Budget-Allocation-using-Linear-Maximization-Model/assets/113878059/ba269b24-adea-4a96-a4e8-f4798e0eeddc)

I use three promotion vehicles to drive business to Acme. The first tool is Facebook (F) to promote discussion of local restaurants in the community. The second tool is Groupon (G) to increase trial rate of new customers. The third tool is Yelp (Y) to show customer ratings.

After analyzing historic sales and promotion data, I assemble the data in the table shown below. I gain a certain number of viewers per each campaign, and the viewers are provided by the promotion vehicle analytics. Each campaign costs a certain amount, and the cost is provided by the monthly bill for services. 

I face some promotion constraints, or conditions that limit the number of solutions to problems while executing promotion campaigns for the restaurant. Firstly, there is a maximum allowable budget that can be spent each month on promotions. Secondly, due to limited capacity (ability to produce) of the promotion service I use, I cannot create more than a certain number of new campaigns per month.

The promotion objective is to maximize audience exposure.

![image](https://user-images.githubusercontent.com/113878059/228691973-9b0a4042-3c4d-46e5-84fc-7c491030c8d8.png)

## Data analysis model

In promotion budget allocation, we aim to maximize the effectiveness of our promotional efforts (our promotional objectives) for a given budget (our promotion constraint). 

The promotion allocation model uses linear optimization to calculate the optimum allocation of budget across different promotion vehicles. Once the goals of the promotional campaign are identified and promotional constraints are defined, we then calculate the vehicle contribution, which is the amount of results generated per use of the vehicle. Then, the model takes an objective function and constraint equations as inputs, and delivers the maximized objective and other information as outputs upon execution.

Considering that we have all of this prerequisite data available, linear optimization model for promotion allocation is the best method to follow through with.

## Developing the objective equation

*Z = 30 * F + 30 * G + 40 * Y*

The equation applies the following variables:
- Z = Our objective, in this case the total number of audience impressions from all promotion vehicles.
- F = Quantity of Facebook campaigns to run, given that each direct marketing campaign results in 30 viewers per advertisement. 
- G = Quantity of Groupon campaigns to run, with 30 viewers per campaign.  
- Y = Quantity of Yelp campaigns to run, with 40 viewers per campaign

## Develop relevant constraints equation

*B = 30 * F + 40* G + 60 * Y*
B < 2000
F < 30
G < 20
Y < 10

The equation applies the following variables:
B = Our monthly budget
F = Quantity of Facebook campaigns, which cost $30 each to run.
G = Quantity of Groupon campaigns, which cost $20 each to run.
Y = Quantity of Yelp campaigns, which cost $10 each to run.
≤ = Inequality sign, indicating that we may not exceed our maximum budget.

## Executing the model

## Analysis and Insight

Findings
1.The condition is not optimum. Y faces a surplus of capacity. 

2. The data in the case suggests that Facebook is a more cost-effective method for gaining impressions. Its cost-effectiveness does not necessarily indicate the ability to increase sales, or even the ability to drive traffic to the restaurant. 

3. Facebook and Groupon target different consumer behaviors. Facebook users can be more motivated by the ongoing conversations they have with other users. By comparison, Groupon users tend to focus more on one-time savings, such as a 50% savings to get them to try a restaurant the first time. (Magda, 2017)

3. Foursquare is generally provided to businesses at no cost, while Groupon charges its customers (companies) for the use of the service. Groupon’s charge could be a deterrent to its use. (Business Insider, 2017)

4. Facebook Places, Facebook’s location-based social media advertising platform, could assist with local promotion efforts.


Conclusions: 
The mix of promotion vehicles has its strengths. 
The current use of the mix of vehicles can be improved.

Recommendations:
The extra capacity of Y should be redistributed elsewhere.

References

1. Magda, George. (2017). “Success using Foursquare vs. Groupon for Dealerships Today.” georgemagda.com. http://www.georgemagda.com/2011/08/success-using-foursquare-vs-grupon-for.html

2. Business Insider. (2017) “BII Report: Why Location-based Services Like Groupon Now and Foursquare Are Going to Be Big Businesses.” businessinsider.com..http://www.businessinsider.com/special-report-why-location-based-services-like-groupon-now-and-foursquare-are-going-to-be-big-businesses-2012-7
