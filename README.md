# Pharmacy
Database Integrator job 2
-----------------------------

SURVEY
A chain of pharmacies asks us to computerize the operations of their business. As a result of his survey, we obtain the following information:
The pharmacy sells medicines and perfumery products.
Some clients have social work and others are private.
Surname, name, ID, address (street, number, town, province), work if you have one (name of the social work and affiliate number)
Of the employees it is required to know the last name, name, DNI, CUIL, address (street, number, town, province) and social work to which it contributes (name of the social work and affiliate number).
For each product, it is required to know if it is a medicine or perfumery product, a description, the laboratory that produces it, a numerical code and the price.
For each sale, the following is recorded: date, ticket number, total sale, method of payment (cash, card or debit), products sold with their quantities, unit and total price; employee who served the customer and the employee who made the cashier.
From each branch it is known which employees belong to it, the address (street, number, town, province) and which of the employees is in charge of it. The ticket number is issued with a point of sale different for each branch (the point of sale is identified with the first four numbers of the tax receipt, eg: 0001-00001234 is a point of sale 1)

REQUIRED REPORTS
The client wants the system to provide the following information through queries made to the database
MongoDB data:
1. Detail and total sales for the entire chain and by branch, between dates.
2. Detail and total sales for the entire chain and by branch, by social or private projects between dates.
3. Detail and total collection for the entire chain and by branch, by means of payment and between dates.
4. Detail and totals of product sales, total of the chain and by branch, between dates, differentiated between pharmacy and perfumery.
5. Ranking of product sales, total for the chain and by branch, between dates, by amount.
6. Ranking of product sales, total for the chain and by branch, between dates, by quantity sold.
7. Ranking of customers by purchases, total of the chain and by branch, between dates, by amount.
8. Ranking of customers by purchases, total of the chain and by branch, between dates, by quantity sold.

Then modify those 8 points by the following:
The customer wants the system to provide the following information through queries
made to the MongoDB database:
1. A report with two results, on the one hand the total amount of sales of the entire complete chain (all branches) and on the other hand the amounts of sales grouped by
branch offices. All of this must occur between two dates passed as parameters (date from and date until).
2. A report with the amounts of sales grouped by obras sociales and also consider the private ones (without social work) as one more group. All this must happen between two dates passed as parameters (date from and date to).
3. A report with two results, on the one hand the total collection of the entire chain complete (all branches) and on the other hand the collection grouped by branches. All this must occur between two dates passed as parameters (date from and date to).
4. A report with the amounts of sales grouped by type of product (pharmacy / perfumery). All of this must occur between two dates passed as parameters (date from and date to).
5. Ranking of amount sold, grouped by product and by branch.
6. Ranking of quantity of products sold, grouped by product and by branch.
7. Ranking of purchases grouped by customer for the entire chain. (I want to see the clients that they bought the most in the entire chain, they were able to buy in more than one branch).
8. Ranking of purchases grouped by customer and by branch. (I want to see how they bought the intra-branch customers).
