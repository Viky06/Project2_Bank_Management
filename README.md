# Project2_Bank_Management
All the banks operating in India are controlled by the RBI. RBI has set a well defined guideline (e.g. minimum interest rate, minimum balance allowed, maximum withdrawal limit etc) which all banks must follow. For example, suppose RBI has set the minimum interest rate applicable to a savings bank account to be 4% annually; however, banks are free to use 4% interest rate or to set any rates above it.

Write a JAVA program to implement bank functionality in the above scenario and demonstrate the OOPs concepts and explain how it is actually satisfying that concept.

Note:

Create a console application for the banking management system.
Create few classes namely Customer, Account, RBI (Base Class) and few derived classes (SBI, ICICI, PNB etc). Assume and implement required member variables and functions in each class.
In every Bank there should be at least 2 types of account saving and current.
Saving should give simple interest and Current should provide compound interest on deposited amount.
In the current account the interest is compounded twice a year (on half yearly its compounded).
For Every type of account at least 2 users will be there.
On the running of the application it should ask which bank we want to access.
Then what type of account you have.
And then for which user account we want to access.
Minimum amount for saving account is 2000/- and for current account is 5000/-
And we can calculate the interest for any given time and total amount as well.
Interest rates for saving will be 5% annually and for current it will be 8% annually.
Before calculating interest it should ask the user for how many years you want to calculate it.
Write code to calculate both types of interests as well for any of the users.
For total amount on Simple Interest:

A = P(1 + rt)

Where:

A = final Amount

P = initial Principal balance

r = annual interest rate

t = time (in years)

So, Total Interest = (A - P)

For total amount on Compound Interest:

𝐴 = 𝑃(1 + 𝑟

𝑛

)

𝑛𝑡

A = final Amount

P = initial Principal balance

r = annual interest rate

t = time (in years)

n = number of times interest is compounded per year

Sample Input

Sample Output

Want to open an account?

yes/No

If yes, Insert name, type of

account and date of birth, in

which bank you want

Account has been opened and account

no is: 123

Want to print mini statement

If yes, save it in .txt file somewhere

Calculate interest

If yes, calculate and print

Hint:

Class Customer

{

//Personal Details ...

// Few functions ...

}

Class Account

{

// Account Detail ...

// Few functions ...

}

Class RBI

{

Customer c; //hasA relationship

Account a; //hasA relationship

..

Public double GetInterestRate() { }

Public double GetWithdrawalLimit() { }

}

Class SBI: public RBI

{

//Use RBI functionality or define own functionality.

}

Class ICICI: public RBI

{

//Use RBI functionality or define own functionality.

}
