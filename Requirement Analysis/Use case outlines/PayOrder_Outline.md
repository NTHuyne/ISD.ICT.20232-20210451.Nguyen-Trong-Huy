# USE CASE "Pay the order" Outline
> ISD.ICT.20232-20210451-Nguyen_Trong_Huy

## I. Description
After finishing the delivery information completion part, customer then move to pay the order part to finish the "Place an order" operation.

## II. Actor
### 1. Primary actor
Customer
### 2. Secondary actor
VNPay

## III. Flow of events
### 1. Basic flow
Step 1: Customer selects the payment method provided by VNPay.

Step 2: VNPay open the selected payment method.

Step 3: Customer provides the imformation offered by VNPay.

Step 4: VNPay completes the transaction process.

Step 5: Software displays the transaction details and send the transaction information and invoice to customers' email. The order is now in the pending process state.
### 2. Alternative flow
Step 1.1: Customer turns back or exit the payment process.