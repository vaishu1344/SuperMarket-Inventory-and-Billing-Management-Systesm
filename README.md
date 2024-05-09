
1.	Introduction

1.1	Project Profile:

Managing inventory is an important part of business administration. If you have excess inventory, money is being wasted (which is referred to as underutilization.). If you don’t have enough, it delays deliveries. Neither one is good scenario.
An Inventory Management System tracks inventory availability at all points of your supply chain – from purchasing, to production, and finally sales to consumers. An Inventory Management System is important for with large amount of inventory in order to keep it at optional levels. When you have clear visibility into your inventory, you know when to order, where to store it, and when you need to stop selling.
In our system, the Super Admin manages the other Admins.  Super Admin can add, update or delete Admins details. Admin manages the categories, products, customers and can view order of particular customer. 
Our System generates the bill of product purchased by customer in the PDF form with products details for good customer services. 
1.2	 Company Profile:

Project Name:	Supermarket Inventory Management System
Company Name:	Parivar Supermarket
Company Address:	Nashik Road, Opposite Rajendra Honda, Ganesh Nagar, Sangamner, Maharashtra 422605
Email Id:	parivarsupermarket@gmail.com

Contact No.:	9822172986

1.3	 Proposed System

•	 An Inventory Management System provides 2 login interphases. One for Super Admin and another for Admin. Where Super Admin manages the details of other Admins and Admin manages the details of categories, products, customers and can also view the order of customers.
•	It generates the bill for products purchased by the customers of good customer services.
•	In our system reminders appears when stock is out of stock or bill have any double entry of single product for minimizing the errors in the billing system.
•	Admin can manage order and generates the bill for purchased product with the product quantity and product details.
1.4	 Objectives of System

1. To avoid both overstocking and understocking of inventory.
2. To maintain the availability of the materials whenever and wherever required in enough quantity.
3.	To maintain minimum working capital as required for operational and sales activities.
4.	To keep material cost under control as they contribute to reducing the cost of production.
5.	To eliminate duplication in ordering stocks.
6.	To ensure the quantity of goods at reasonable prices.
7.	To supply the required material continuously.
8.	To maintain a systematic record of inventory.

2.	Literature Survey

2.1 Existing System

•	The existing system of supermarket inventory involved manual processes such as inventory management, billing, sales, and customer relationship management. These processes were time-consuming, error-prone, and required a lot of manual labor.
•	According to Store wise, supermarkets used to rely on manual cash registers and paper-based inventory management systems. The inventory management system involved manually counting the stock and updating the records.
•	 The billing process was also manual, and the cashier had to calculate the total bill manually. The customer relationship management was limited to the store manager’s ability to remember customers’ preferences and offer personalized service.








2.2 Feasibility Study

This software has been tested for various feasibility criterions from various point of views.
1)	Economic Feasibility:
The system is estimated to be economically affordable. The benefits include increase efficiency, effectiveness, and the better performance. Comparing the cost and benefits the system is found to be economically feasible.

2)	Technical Feasibility:
Development of the system requires tools like:
	Jframe
	NetBeans software
	Mysql Database
	JDK, etc

3)	Operational Feasibility:
The system provides better solution to the libraries by adding the typical requirement and necessities. The solution provided by his system will be acceptable to ultimate solution for the stock management.









3.7 Data Design:
	Admin:
Field Name	Data Type	Size	Constraint
Email	Varchar	20	Not null
Pass	Int	--	Not null
Role	Varchar	10	Not null

	AppUser:
Field Name	Data Type	Size	Constraint
appuser_pk	Int	--	Primary Key
Name	Varchar	10	Not null
mobileNo	Int	--	Not null
Email	Varchar	20	Not null
Password	Varchar	8	Not null
Address	Varchar	20	Not null
Status	Varchar	10	Not null

	Customer:
Field Name	Data Type	Size	Constraint
custId	Int	--	Primary Key
Name	Varchar	10	Not null
mobNo	Int	--	Not null
Email	Varchar	20	Not null



	Category:
Field Name	Data Type	Size	Constraint
cId	Int	--	Primary Key
Cname	Varchar	10	Not null
	Product:
Field Name	Data Type	Size	Constraint
pId	Int	--	Not null
Name	Varchar	10	Not null
Quantity	Int	--	Not null
Price	Varchar	10	Not null
description	Varchar	20	Not null
cId	Int	--	Not null
	Order:
Field Name	Data Type	Size	Constraint
orderId	Int	--	Primary Key
custId	Int	--	Not null
orderDate	Int	--	Not null
billId	Int	--	Not null
Total	Int	--	Not null
	Bill:
Field Name	Data Type	Size	Constraint
BillId	int	--	Primary Key
orderId	int	--	Not null
Total	Int	--	Not null

3.8 Data Dictionary:
Field Name	Data Type	Size	Constraint
Email	varchar	20	Not null
Pass	int	--	Not null
Role	varchar	5	Not null
appuser_pk	int	--	Not null
Name	varchar	20	Not null
mobileNo	int	--	Not null
Email	varchar	20	Not null
Password	varchar	10	Not null
Address	varchar	20	Not null
Status	varchar	20	Not null
CustId	int	--	Primary Key
Name	varchar	10	Not null
mobNo	int	--	Not null
Email	varchar	20	Not null
cId	int	--	Primary Key
Cname	varchar	10	Not null
PId	int	--	Not null
Name	varchar	20	Not null
Quantity	int	--	Not null
Price	varchar	10	Not null
description	varchar	20	Not null
orderId	int	--	Primary Key
orderDate	int	--	Not null
BillId	int	--	Primary Key
Total	int	--	Not null


4.	Hardware and Software Requirement
4.1 Hardware Requirement:

•	Processor – Intel i5 or more
•	Processor Speed – 1.4 GHz
•	RAM – 4 GB or more
•	Hard Disk – 500 GB or more
•	Monitor – Dell
4.2 Software Requirement:

•	Operating System – Windows 11
•	JFrame
•	Mysql Database
•	NetBeansIDE
•	JDK

 
5.	Advantages and limitations
5.1 Advantages of System:
•	The system reduces much of human efforts in calculating bill especially for huge products.
•	Saves money and resources of organization excludes of use of paper or sheets in making bill.
•	Saves time on calculation.
•	It provides accuracy and faultlessness in billing calculations.
•	 It generates the receipt of customer’s purchase in the PDF form.
•	Improve resource uses.
•	AppUser can keep track of stock of products without going anywhere by reviewing it on product details.

5.2 Limitations of System:
•	Requires large database.
•	GUI is not good so the operators get bored by watching screen.

 

6.	Future Enhancement

1.	This System does not provide the any operator friendly GUI, in future we can add interesting operator friendly GUI.
2.	Barcode scanning techniques will be added for billing of products.
3.	Billing receipt will be provided by email or SMS to Customer.
4.	Allow customers to earn points or rewards for their purchases and redeem them for discounts or free products.
 
	
7.	Bibliography
This refers to the books/websites which were through for completion of this project report.
•	Reference Books:
	Software Testing Book , Core Java Book, Advance Java Book – Nirali Prakashan
	Software Analysis and Design - Scan
•	Collect some code from online website like
	www.google.com
	www.w3school.com
	www.stackoverflow.com 
•	Guidance from project teacher.


