# USE CASE "Place an order" Outline
> ISD.ICT.20232-20210451-Nguyen_Trong_Huy

## I. Description
After completing their cart, customers can request to place an order, then pay the order. All the goods, after that, can be delivered.

## II. Actor
### 1. Primary actor
Customer
### 2. Secondary actor
Product manager

## III. Flow of events
### 1. Basic flow
Step 1: After reviewing the cart, customer requests to place an order of their selected cart. 

Step 2: AIMS checks if the quantity is sufficient for the order, then notifies to the customers.

Step 3: Customers request the valid order, moves to the next part, completing the delivery information.

Step 4: The software asks customer the delivery information. At the same time, AIMS calculates the delivery fee then save the invoice.

Step 5: Then AIMS allows customers to pay for the order.

Step 6: Customers have to pay for the order (Call to USE CASE "Pay the order").

### 2. Alternative flow
Step 2.1: If the products is not sufficient in the inventory.

- Step 2.1.1: AIMS asks the customer to update the products in their cart.

- Step 2.1.2: Customer requests to place the order again.

Step 4.1: Customer can request to place an rush order. (Call to USE CASE "Place a rush order").

Step 4.2: AIMS specifies any information of customers is invalid.

- Step 4.2.1: Customer have to input the blank field or complete the invalid field.


