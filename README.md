# University Course : Web Development, Semester 1, 2023-2024. Team size : 3.
## Acknowledgement : This is parts of the back-end of the full package MagicPost : End-to-end delivery software.
## This repo contains the parts that I made out of the most contributions to the project.

## Description :
+ MagicPost is a company operating in the courier services sector.
+ Senders with items to dispatch bring their goods to the nearest branch for shipment.
+ The items are then taken to the warehouse associated with the sender's branch and subsequently transferred to the warehouse corresponding to the recipient's branch.

## The functional requirements for each user type are as follows:

### Functions for Company Leadership

Manage the system of branches and warehouses.
Manage the accounts of branch and warehouse managers, with each branch or warehouse having its own manager's account.
Provide nationwide statistics on sent and received items, categorized by each branch or warehouse.

### Functions for Branch Managers

Grant accounts to transaction officers at the branch.
Provide statistics on sent and received items at the branch.

### Functions for Transaction Officers at Branches

Record items to be sent by customers (senders), generate courier receipts, and hand them to customers (refer to Figure 1 in the appendix for reference).
Create shipment orders to be sent to the warehouse every time before dispatching items to the warehouse.
Confirm (orders for) items returning from the warehouse.
Generate shipment orders for items to be sent to recipients.
Confirm items delivered to recipients.
Confirm items undeliverable to recipients and return them to the branch.
Provide statistics on successfully delivered items, unsuccessful deliveries, and items returned to the branch.

### Functions for Warehouse Managers

Manage employee accounts at the warehouse.
Provide statistics on incoming and outgoing items.

### Functions for Employees at Warehouses

Confirm (orders for) items coming from branches for dispatch.
Create shipment orders for items to be sent to the destination warehouse (corresponding to the destination branch, i.e., the branch responsible for the region where the recipient's address is located).
Confirm (orders for) items received from other warehouses.
Create shipment orders for items to be sent to the destination branch.
### Functions for Customers

Check the status and progress of the delivery of their dispatched items.

