# Project-ComputerStore
This project is a web application that builds on HTML, CSS and JavaScript. 
The application has three main sections: the bank, work, and laptops.

The Bank:

Balance: Shows the amount available for the user to buy a laptop. The number format feature in JavaScript should be used.
Outstanding Loan: (Only visible after taking a loan): Shows the outstanding loan value. This should be reduced as the loan is paid back.
Get a loan: Allows the user to get a loan from the bank. When the button is clicked, a prompt popup box appears that allows the user to enter an amount. 

Constraints on the Get a loan button include:
The user cannot get a loan more than double of their bank balance.
The user cannot get more than one bank loan before repaying the last loan.
The user may not have two loans at once. The initial loan should be paid back in full.

Work:

Pay: Shows the user's current salary amount. This money is not part of their bank balance.
Bank Button: Transfers money from the user's pay/salary balance to their bank balance. 
Constraints on the Bank button include:
If the user has an outstanding loan, 10% of their salary must first be deducted and transferred to the outstanding loan amount.
The remaining balance may be transferred to the user's bank account.
Work button: Increases the user's pay balance by 100 on each click.
Repay Loan button: Allows the user to repay their loan. Upon clicking this button, the full value of their current pay amount 
should go towards the outstanding loan, and not their bank account. Any remaining funds may be transferred to the user's bank account.

Laptops:

Laptop selection area: Allows the user to select a laptop from a list of available computers. 
The feature list of the selected laptop should be displayed here. Changing a laptop should update the user 
interface with the information for that selected laptop.
Info section: Displays the image, name, description, and price of the laptop. 
It also includes a "Buy Now" button that allows the user to purchase the selected laptop. 
If the user does not have enough money in their bank balance, a message should appear indicating that
they cannot afford the laptop. If they have sufficient funds, the amount should be deducted from their 
bank balance and a message should indicate that they are now the owner of the new laptop.
The data for the laptops will be provided to you via a RESTful API that returns JSON data. 
The endpoint for the API is: https://hickory-quilled-actress.glitch.me/computers

Link:
