*An Online Food Delivery System in Rails for home makers*

**Here's what the app is supposed to do**

The website allows users to sign up and pay for a subscription to a weekly delivery of meals. A shopping cart is used to allow users to choose meals from a menu for each day of the week.
The home cook will be selling thier own food, not other restaurants food.

Users choose how many days they want meals for, then choose the meals. 

These are the steps we want to create:

1. People sign up for the account first (i.e. name and email)
2. They then are shown a pre-selected menu to choose from and then they can also choose to customize the menu
3 Users will decide how many meals to order and the delivery days.
4. At the end of this selection, we ask them for their credit card info and delivery address.

We will also require a backend system where we can manage the orders and also manage the register. 

**Purpose:**

Empower and provide viable income options to people who are homemakers. 
Show the passion of cooking and delivering yummy, healthy & Fresh food. 
Provide homemade food to the students/bachelors staying away from home for education .
Benefit for home-makers and the student.

**App WorkFlow:**

Home-cook and the customer register in the app.(store in the database managed by HASURA )
The home-cook will provide food menu for the whole week including below details:
   Breakfast/Lunch/Dinner menu (stored in the database managed by HASURA )
   Price per meal(stored in the database managed by HASURA )
Customer can choose to subscribe on the weekly basis according to below criteria:
   Price
   Ratings of the Cook
   Breakfast/Lunch/Dinner menu
Customer will select :
   The no. of weeks he wants to subscribe (stored in the database managed by HASURA )
   Time of delivery(stored in the database managed by HASURA )

Choose to Pay the amount and select the Payment option
Money will deduct from the Bank account and transferred to the
SETU virtual bank account
SETU will split the amount as defined in the API and transfer to the individual's bank account (Cook,Courier Person,Company).
Payment cleared message notification will be sent to the individuals.
Receipt sent from Biller to the user.


**API USAGE:**

 Hasura API for  storing data (menu etc.) in the database along with the backend functionality 

SETU API for doing the payment to the billers .

Main focused areas:

We mainly aim to provide the tasty and healthy food.

This is a customized app where customer can give his taste areas like mentioning what to exclude from the recipie(sugar, refined oil)

No usage of plastic for the food delivery. Food is packed in a hygienic steel container to avoid health issues. 


