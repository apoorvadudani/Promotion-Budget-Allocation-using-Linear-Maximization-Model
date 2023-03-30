# Promotion-Budget-Allocation-using-Linear-Maximization-Model

## Background 

I are the marketing manager for a new fine dining restaurant in San Francisco, Acme Restaurant(fictitious). Acme’s top entrees include:
 Dish A: Braised Alaskan wild salmon with rice pilaf and grilled asparagus
 Dish B: Grass-fed organic beef tenderloin with baked potato and sautéed mushrooms in Cabernet sauce
 Dish C: Vegetable melee, with red and green peppers, organic beets and artichoke hearts, over a bed of spinach, served with a spicy balsamic vinaigrette

I use three promotion tools to drive business to Acme. The first tool is Facebook (F) to promote discussion of local restaurants in the community. The second tool is Groupon (G) to increase trial rate of new customers. The third tool is Yelp (Y) to show customer ratings.

After analyzing historic sales and promotion data, I assemble the data shown below. I gain a certain number of viewers per each campaign, and the viewers are provided by the promotion vehicle analytics. Each campaign costs a certain amount, and the cost is provided by the monthly bill for services. I face a maximum allowable monthly budget. Due to limited capacity (ability to produce) of the promotion service I use, I cannot create more than a certain number of new campaigns per month.

![image](https://user-images.githubusercontent.com/113878059/228691973-9b0a4042-3c4d-46e5-84fc-7c491030c8d8.png)

## Data analysis model

In promotion budget allocation, we aim to maximize the effectiveness of our promotional efforts (our objective) for a given budget (our promotion constraint). 

Promotion constraints refer to conditions that limit the number of solutions to problems while executing promotion campaigns. Here are some constraints that most organizations typically face:

- A limited budget, such as a certain amount of money that can be spent each month on promotions. 
- Legal constraints, such as legal regulations that cover that jurisdiction. 
- Contractual constraints, such as specific limits placed on us due to performance contracts with external agencies. 
- Company policies and internal regulations


The promotion allocation model uses linear optimization to calculate the optimum allocation of budget across different promotion vehicles. It is an example of a normative model. The model takes an objective function and constraint equations as inputs, and delivers the maximized objective and other information as outputs.

The linear optimization process entails four steps. In the first step, we calculate the vehicle contribution, which is the amount of results generated per use of the vehicle. For example, we could estimate the number of impressions, or views, delivered by each ad. In the next two steps, we express our promotion objective and constraints in equation form. We cover how to do that in the next slides. We then execute the model.

## Constraints

We start by discussing 

We will demonstrate the process using an example. In the example, we promote our goods and services using three different promotion vehicles--direct marketing, pay per click, and social media. In direct marketing, we send emails directly to individuals we think will be interested in our offerings. In pay per click, we work with Google and other search engines to display ads for our offerings when users search for relevant topics. In social media, we insert paid ads on various social media platforms, such as Facebook and LinkedIn. We examine the performance of previous campaigns and discover that our direct marketing campaigns result in 30 viewers per ad, and that they cost $30 to develop and send. Similarly, pay-per-click delivers 30 viewers per ad and costs $40, and social media results in 40 viewers per ad and costs $60. Our current personnel count and contracts with outside advertising agencies gives us the capacity to create 30 direct marketing campaigns, as well as 20 pay-per-click and 10 social media campaigns per month. 

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
![image](https://user-images.githubusercontent.com/113878059/228693909-569470a3-9a16-4d9c-814d-2f998eb848cc.png)
