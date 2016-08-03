#Bank Account Project
##Due: Monday, August 8, 2016 by 8:00 AM 
[Submission Link](https://docs.google.com/forms/d/e/1FAIpQLScRhWuvH7mxDMlQv-zb_LAqi6qUTZF_xzBGGYHghqWdyp9T1g/viewform)
##Directions
Update your console application to manage a client’s bank account. For now, the application will have only one client that is hard-coded into the system.

##Tasks
###Menu Items
- [ ] View Client Information
- [ ] View Account Balance
  - [ ] Checking Account Balance
  - [ ] Reserve Account Balance
  - [ ] Savings Account Balance
- [ ] Deposit Funds
- [ ] Withdraw Funds
- [ ] Exit

###Checking Account Class
- [ ] Inherits Account base class
- [ ] Minimum 2 fields
- [ ] Minimum 2 properties
- [ ] Minimum 1 constructor

###Reserve Account Class
- [ ] Inherits Account base class
- [ ] Minimum 2 fields
- [ ] Minimum 2 properties
- [ ] Minimum 1 constructor

###Savings Account Class
- [ ] Inherits Account base class
- [ ] Minimum 2 fields
- [ ] Minimum 2 properties
- [ ] Minimum 1 constructor

###Objects
- [ ] Minimum 1 object instantiated from the Checking Account Class
- [ ] Minimum 1 object instantiated from the Reserve Account Class
- [ ] Minimum 1 object instantiated from the Savings Account Class

###Other Requirements
- [ ] Use StreamWriter to create account summary files that track transactions **for each account type (each type has its own text file)**. Files should be located in the Debug Folder and should include:
  - [ ] Name of Client
  - [ ] Client Account Number
  - [ ] Account Type (Checking, Reserve, or Savings)
  - [ ] Each transaction should be on its own line
  - [ ] Each transaction should show date and time of transaction (must use DateTime Class)
  - [ ] Each transaction should show a “+” for deposit and a “-” for withdrawal
  - [ ] Each transaction should show the transaction amount
  - [ ] Each transaction should show the new current balance after the transaction
