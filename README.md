# -Customers-and-Products-Analysis-Using-SQL

The goal of this project is to analyze data from a sales records database for scale model cars and extract information for decision-making.

Question 1: Which products should we order more of or less of?

Question 2: How should we tailor marketing and communication strategies to customer behaviors?

Question 3: How much can we spend on acquiring new customers?

![Customer table](https://github.com/user-attachments/assets/767513f8-be3d-4f73-9469-c8aaefd466e3)


**Question 1: Which Products Should We Order More of or Less of?**

To optimize supply and enhance customer experience, we analyzed two key performance indicators:

Low Stock Rate:
This is calculated as:
Sum of quantity ordered / Quantity in stock
Products with the highest low-stock rate are those that are either already out of stock or will soon be. We selected the top 10 such products.

Product Performance:
The total sales revenue per product. Products that sell more generate higher revenue.

Priority Products for Restocking = High product performance + Low stock
These are products selling fast and are about to go out of stock.

_**Findings:**__

The highest-performing products were scale models of Classic Indian Cars, including:

Ambassador Mark II

Premier Padmini

Maruti 800

Hindustan Contessa

Tata Sierra

These are low in stock and sell frequently.

 **_Action:_**
Focus on restocking classic Indian car models immediately.

 **Question 2: How Should We Match Marketing and Communication Strategies to Customer Behavior?**
 
We aimed to categorize customers to personalize communication:

VIP Customers: Highest profit generators.

Least Engaged Customers: Lowest contributors to revenue.

We combined product and customer data and ranked customers by total purchase value.

__**Top 5 VIP Customers:**_
_
Rajesh Kumar – ₹9,85,000

Meena Patel – ₹9,20,000

Aamir Sheikh – ₹8,75,000

Priya Verma – ₹8,65,000

Vikram Singh – ₹8,40,000

🌱 Least Engaged Customers:

Nikhil Dey – ₹23,000

Anita Joshi – ₹21,500

Farhan Siddiqui – ₹18,200

Deepika Reddy – ₹15,000

Ramesh Naidu – ₹12,300

 **Strategy:**

VIPs: Target with loyalty programs, early-access sales, and premium offers.

Low engagement: Offer discount vouchers or personalized email campaigns.

_ **Question 3: How Much Can We Spend on Acquiring New Customers?**_

Customer Growth:

Our analysis showed a steady decline in new customer acquisition since 2009. The last recorded new customer joined in September 2010.

**📌 Conclusion:**

We must invest in new customer acquisition.

 **Customer Lifetime Value (LTV):**

Average customer generates: ₹32,500

If we acquire 10 new customers, expected revenue = ₹3,25,000

 **Marketing Budget Recommendation:**
 
We can afford to spend up to ₹10,000 per customer on acquisition (keeping margins and overhead in mind), giving a potential budget of ₹1,00,000 for 10 new customers.
