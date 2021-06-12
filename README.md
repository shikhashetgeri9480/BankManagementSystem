# BankManagementSystem
This project is focused on customer account services in bank, so it is named “Bank Management System”. 

bank Management System is based on a concept to generate and maintain daily payment transactions with the customer’s account. Before stepping into the main system a user has to pass through login system to get access, then only he/she can use all the features of the system which includes Adding, Removing, Updating and viewing records, withdraw and deposit cash feature, check details of existing customers.

Talking about the features of Bank Management System, while entering customer’s record he/she has to provide the current date, account number, name, date of birth, age, address, phone number, the amount deposited while creating an account and select account type. Under this, there are five types of account, Saving, Current, Fixed(for 1 year), Fixed(for 2 years), Fixed(for 3 years). But while updating customer’s information from existing account, he/she can only change address and phone number. There are two methods to check a user’s account in detail i.e by Account number or by Account name. The other listing record displays customer’s name with an Account number, address and contact detail.
Transaction through a bank is either done by Depositing or Withdrawing amounts. So here the user can use both of the features easily. Whenever a user wants to withdraw or deposit some amount of money he/she has to provide Amount then the system automatically maintain his/her Transaction record with total bank balance. And another thing is that while checking a customer’s account in detail the system will display a bank interest information. This system calculates interest per month and displays to the user.
Overall, with this project, you can perform banking activities like in a REAL bank. 

Bank management mini project in C is a console application without graphics. It is compiled in Code: Blocks with gcc compiler.

Functions used in Bank Management System: 
The source code for Customer Account Bank Management System is relatively easy to understand. We have divided this C mini project into many functions, most of which are related to different banking activities.
Listed below are some of the more important functions:-
1.	menu () – 
This function displays the menu or welcome screen to perform different banking

2.	new_acc () – 
This function creates a new customer account. It asks for some personal and banking details of the customer such as name, date of birth, citizenship number, address and phone number. You can enter the amount to deposit and choose one type of deposit account – saving, current, fixed for 1 year, fixed for 2 years or fixed for 3 years.

3.	view list () – 
With this function, you can view the customer’s banking information such as account number, name, address and phone number provided while creating the account.


4.	edit () – 
This function has been used for changing the address and phone number of a particular customer account.

5.	transact () –
With this function, you can deposit and withdraw money to and from a particular customer account.

6.	erase () – 
This function is for deleting a customer account.


7.	see () – 
This function shows account number, name, date of birth, citizenship number, age, address, phone number, type of account, amount deposited and date of deposit. It also displays the amount of interest corresponding to a particular account type.

In this bank management system project in C, file handling has been used for almost all functions. File has been used to store data related to new account, transaction, editing of account information and viewing of account information. we haven’t used file handling for the menu, interest calculation and password.

