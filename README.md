# WOASS
## Work Order Application for Sports Shops
### An 18 Week project in ASP.NET MVC Core for MSSA

David Chui | Jan 19 2021

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Work Order Application for Sport Shops (WOASS)

##### Introduction

WOASS is an application aimed to **facilitate the workflow** of technicians at sport shops, and to give customers a convenient solution to get their gear worked on. Currently, many shops still use carbon transfer paper to track work orders and give customer receipts. I’ve seen shops lose the work order; consequently, losing the customer’s information, and spending time bringing different snowboards based on a vague description until the right one is brought out. I’ve lost my receipt and was unable to contact the technician to check if my board would be ready to pick up by the end of dinner to save a trip in the morning. These problems can be averted with a web application; furthermore, many productivity, work management, and **customer service advantages** can be unlocked. 

I envision an application that organizes, sorts, and stores various different work orders based on an existing menu of service items that customers, technicians, and managers can use. The input parameters in the database might include:
+ Customer information (Name, Phone, email)
+ Type and Description of gear. (Ski/Snowboard, Brand, Size)
+ Checkbox list of work to be done.
+ Material Costs (if applicable)
+ Priority and Deadline 
+ Notes
+ Payment Status

##### Manager Accounts

	Shop managers have access to accounts that can edit service items and prices, and view data analytics about technicians and orders, and add and remove Technician accounts. They can gain greater insight over employee productivity and customer service. They can also assign work orders and manage employees remotely easier.

##### Technician Accounts

	Technicians have access to accounts which can create, view, and edit work orders. They can sort work orders based on priority and deadlines. Work orders can be transferred seamlessly since each tech can access notes stored on a database online.

##### Customer Accounts

	Customers have access to accounts which can view and draft work orders. Draft work orders have to be approved by a technician before being tasked to work. This allows the customer to preview the price and expedite their service at the shop. Customers of the shop can create their own accounts.
	
---

[Database Diagram](WOASS%20Entity%20Relationship%20Diagram%20(2).pdf)
