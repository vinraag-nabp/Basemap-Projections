# Basemap-Projections
Business Process: In case of a vehicle accident a person takes his/her vehicle to a repair shop and the repair shop is directed by the Isurance to buy parts at specific locations

Goal of the Project :
Basemap LCC projection to view where insurers prefer NABP more and which insurance companies gives us priorities at which locations

Data Collection:
Data retrieved from a Relational Database using Pyodbc connect
Data Attributes include
1. Invoice Line Items
2.Product Codes
3.Prouct Description
4.Product Category
5.Sales Quantity
6.Invoice Data
7.Customer Code
8.Customer Name
9.Customer Location
10.Insurance Company Name
11.Sales Representative

Data Cleanup:
Cleanup Customer locations to remove[".,;:-_=+*&#@!%^()/?<>"]
Check for insurers name to be clear 
Rename Blank data points in Insurers name to NA

Once Data Cleanup is done main script is called
