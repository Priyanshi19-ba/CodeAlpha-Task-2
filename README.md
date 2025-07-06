# CodeAlpha-Task-2
**Name: Priyanshi Bansal**
Company:CodeAlpha 
Student ID: CA/JU1/14308 
Duration: 10 June 2025 to 10 July 2025
Domain : Python Programmig 
Overview of the project
**Project:Stock Portfolio Tracker**
![image alt](https://github.com/Priyanshi19-ba/CodeAlpha-Task-2/blob/bbf98be2e6d9f05c121f6017af6812f4bb8b585f/Screenshot%202025-07-06%20182027.png)

**Objective:**
The objective of this project is to create a simple stock portfolio tracker where the user can input stock names and quantities they own. The program uses a predefined dictionary of stock prices to calculate and display the user’s total investment value. Optionally, the result can be saved to a text or CSV file. This project helps in practicing key programming concepts such as dictionaries, user input/output, basic arithmetic operations, and file handling.

**Key Activities:**
1.Defining Stock Prices
A hardcoded dictionary (stock_prices) is used to store stock symbols and their respective prices.
2.Initializing Variables
total_investment is set to 0 to keep track of the total investment value.
investment_details is an empty list to store details of each stock purchase.
3.Displaying Available Stocks
The program prints the list of available stock symbols for the user’s reference.
4.User Input Loop
The program repeatedly prompts the user to enter a stock symbol and quantity until the user types 'done'.
Input is converted to uppercase to ensure consistency.
5.Stock Symbol Validation
The program checks if the entered stock symbol exists in the stock_prices dictionary.
If not, it prompts the user to try again.
6.Quantity Input and Validation
The program asks for the quantity of the selected stock.
It uses a try-except block to handle invalid (non-integer) inputs.
7.Calculating Investment Value
For each valid entry, the value is calculated as price * quantity.
This value is added to the total_investment.
8.Storing Investment Details
Each stock’s symbol, quantity, price, and calculated value are stored in the investment_details list for later display and optional saving.
9.Displaying Investment Summary
After the user is done entering stocks, the program prints a summary showing each stock’s details and the total investment value.
10.Optional File Saving
The program asks the user if they want to save the results.
If yes, it prompts for a filename and writes the investment details and total value to the specified file (either .txt or .csv).

**Technologies Used:**
1.Python Programming Language:
The entire application is written in Python, which is widely used for scripting and financial calculations.
2.Python Standard Library:
Dictionaries: Used to store and access hardcoded stock prices efficiently.
Input/Output Functions: input() for user input and print() for displaying information in the console.
File Handling: The built-in open() function is used to write investment results to a .txt or .csv file if the user chooses to save their data.
3.Basic Programming Concepts:
Variables and Lists: To keep track of total investment and details of each stock entry.
Loops and Conditionals: while loops and if-else statements manage user interaction and program flow.
Error Handling: try-except blocks ensure robust handling of invalid user input.

**Key Insights:**
1.Manual Portfolio Tracking:
The project demonstrates how users can manually track their investments by entering stock symbols and quantities, reflecting a hands-on approach to portfolio management.
2.Use of Hardcoded Prices:
By using a predefined dictionary for stock prices, the project ensures consistency and simplicity, making it easy to understand how investment values are calculated.
3.Real-Time Calculation:
The program instantly calculates and displays the total investment value based on user input, giving immediate feedback on portfolio worth.
4.Data Validation and Error Handling:
The code includes checks for valid stock symbols and numeric input, which helps prevent errors and ensures the accuracy of the investment summary.
5.Optional Data Persistence:
The ability to save results in a .txt or .csv file introduces basic data persistence, allowing users to keep a record of their portfolio for future reference.
6.Foundation for Diversification and Analysis:
While the project is basic, it introduces the concept of tracking multiple assets, which is essential for understanding diversification—a key principle in portfolio management to reduce risk and improve stability over time.
7.User-Friendly Console Interaction:
The project uses straightforward console input and output, making it accessible to beginners and easy to operate without advanced tools or interfaces.
