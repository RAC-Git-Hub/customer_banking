# customer_banking# Module 3 Challenge - customer_banking
## The Challenge
This project involves the creation of a customer banking system that will allow
the end user to calculate and track balance and earned interest in their
savings and cd accounts. The user will be first promtped to enter their starting
balance for their savings account, then enter the interst rate for savings
account, then to provide the sesied maturity period to calculate the earned
interest. This system will return the customer's updated balance and earned
interest for the given maturity period with values calculated to the two
decimla places and the thousandths. The above process will be repeated for
customer's cd account.
## Getting Started
Before starting this assignment, make sure the user has a GitHub account, and 
also VS Code or similar IDE that can run Python 3.10 installed on the user's
computer. Then take the following steps:
>*   Create a new repository for this project called "customer_banking" 
>    **Do not add this homework assignment to an existing repository.**
>*   Clone the new repository to your computer.
>*   Inside your local Git repository, add the starter file "menu.py" from the
>    file downloads.
>*   Push the changes GitHub or GitLab.
In the above steps, the starter file "menu.py" appears to be a typo. Per the
course downloads, the four project starter files are: "Account.py", 
"savings_account.py", "cd_account.py", and "customer_banking.py".  
>## Challenge Instructions
>The starter files consist of the following files: "Accounts.py",
>"savings_account.py", "cd_account.py", and "customer_banking.py". The
>"Accounts.py" file contains the Account class with methods to set the balance
>and interest.
>
>In the "savings_account.py" file, you will import the Account class and create
>a create_savings_account function that will create a savings account instance,
>calculate the interest earned based on user input, update the account balance
>with the earned interest, and return the updated balance and interest earned.
>
>In the "cd_account.py" file, you will import the Account class and create a
>create_cd_account function that will create a CD account instance, calculate
>the interest earned based on user input, update the account balance with the
>earned interest, and return the updated balance and interest earned.
>
>In the "customer_banking.py" file, you will import the create_savings_account
>and create_cd_account functions, then create a main function that prompts the
>user to enter the savings and CD account details, call the corresponding
>functions to calculate the interest earned and update the balances, and display
>the results.
>### Create the Savings Account Function
>Open the "savings_account.py" file, and do the following:
>1. Imports the Account class from the "Accounts.py" file.
>2. In the create_savings_account function do the following:
>   - Create an instance of the Account class and pass in the balance and
>     interest parameters.
>   - Calculate interest earned.
>   - Update the savings account balance by adding the interest earned.
>   - Pass the updated balance to the set balance method using the instance of
>     the Account class.
>   - Pass the interest earned to the set interest method using the instance of
>     the Account class.
>   - Return the updated balance and interest earned.
>### Create the CD Account Function
>Open the "cd_account.py" file, and do the following:
>1. Import the Account class from the "Accounts.py" file.
>2. In the create_cd_account function, do the following:
>   - Create an instance of the Account class and pass in the parameters.
>   - Calculate interest earned.
>   - Update the savings account balance by adding the interest earned
>   - Pass the updated balance to the set balance method using the instance of
>     the Account class.
>   - Pass the interest earned to the set interest method using the instance of
>     the Account class.
>   - Return the updated balance and interest earned.
>### Create the Main Function
>Open the "customer_banking.py" file, and do the following:
>1. Import the create_cd_account and create_savings_account functions from the
>   appropriate files.
>2. In the main function, do the following:
>   - Prompt the user to set the savings balance, interest rate, and months for
>     the savings account.
>   - Call the create_cd_account function and pass in the variables from the
>     user.
>   - Print out the interest earned and updated savings account balance with
>     interest earned for the given months.
>   - Prompt the user to set the CD balance, interest rate, and months for the
>     CD account.
>   - Call the create_cd_account function and pass the variables to the function
>     used to prompt the user from the user.
>   - Print out the interest earned and updated CD account balance with interest
>     earned for the given months.
>   - Call the main function.
A sample of the output after calling the main function can be seen in the image
immediately following:
![Module-3-Challenge-sample-output]
(C:\Users\rac06\OneDrive\Desktop\Git\Module_3_Challenge\customer_banking\
Module-3-Challenge-sample-output.png)
## Sources
The starter codes were obtained in November 2023 from the instructional staff of
the OSU AI Bootcamp and were generated by edX Boot Camps LLC.
## Collaborators
Although this project was done individually, the skillset used to complete this 
assignment is a culmination of knowledge learned in the classroom setting which
includes lecture materials, example programming from instructors, interactive
dialogue in group settings among fellow students, independent internet research,
and some general programming guidance from sources such as CoPilot and ChatGPT. 