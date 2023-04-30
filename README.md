# Blockchain-Bank
We have created a BANK on the blockchain based on the ICP chain . The project has functionalities like check balance , Withdraw ,  Deposit  and even has a Compound Interest function.


This file explains the features and functionalities of a Bank created on blockchain on the Internet Computer (ICP) chain with Motoko and JavaScript. The bank application allows users to perform basic banking operations such as deposit, withdrawal, check balance, and compound interest.

Prerequisites:
Before proceeding, ensure you have a basic understanding of blockchain technology, Internet Computer, and Motoko programming language.

Features:

Deposit:
The deposit function allows the user to deposit a specified amount into their bank account. The deposit function receives two parameters: the account number and the amount to be deposited. Upon successful deposit, the balance in the user's account is updated.
Withdrawal:
The withdrawal function allows the user to withdraw a specified amount from their bank account. The withdrawal function receives two parameters: the account number and the amount to be withdrawn. If the user has sufficient funds in their account, the amount is deducted from their account balance, and the user can collect the cash. However, if the user does not have sufficient funds, the withdrawal transaction is rejected.
Check balance:
The check balance function allows the user to check their account balance. The check balance function receives one parameter: the account number. The function returns the current balance in the user's account.
Compound interest:
The compound interest function allows the user to earn interest on their account balance. The interest rate is set by the bank, and the interest is calculated and added to the user's account balance annually. The compound interest function receives one parameter: the account number. The function calculates the interest and adds it to the user's account balance.
How to use:

Deposit:
To deposit money into your account, call the deposit function with your account number and the amount you wish to deposit.
Example: deposit(123456, 1000)

Withdrawal:
To withdraw money from your account, call the withdrawal function with your account number and the amount you wish to withdraw.
Example: withdrawal(123456, 500)

Check balance:
To check your account balance, call the check balance function with your account number.
Example: check_balance(123456)

Compound interest:
To earn interest on your account balance, call the compound interest function with your account number.
Example: compound_interest(123456)

Conclusion:
This bank application on blockchain on ICP chain with Motoko and JavaScript allows users to perform basic banking operations such as deposit, withdrawal, check balance, and compound interest. The application provides a secure and transparent way of performing banking operations using blockchain technology.

<img width="1280" alt="Screenshot 2023-04-26 at 2 53 10 PM" src="https://user-images.githubusercontent.com/121884963/235369341-4bfec50c-8054-4a2e-ad33-a86b045dc413.png">

Thankyou - Yash Shah
