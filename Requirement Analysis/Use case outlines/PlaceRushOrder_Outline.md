# USE CASE "Place a rush order" Outline
> ISD.ICT.20232-20210451-Nguyen_Trong_Huy

## I. Description
When doing the delivering process. Customer can request to place a rush order.

## II. Actor
### 1. Primary actor
Customer

## III. Flow of events
### 1. Basic flow
Step 1: Customer opts for requesting the rush order.

Step 2: The software checks whether the delivery address supports this service and if any products are eligible.

Step 3: In cases where both the products and delivery address support rush order delivery, the software requests additional rush order delivery information from the customer.

Step 4: Customer completes the rush order delivery information then move to payment process. 

### 2. Alternative flow
Step 2.1: If no products are eligible or the delivery address doesn't support rush order delivery, the software prompts the customer.

- Step 2.1.1: The customer must change the delivery information or change the delivery method.  

