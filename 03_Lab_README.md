# 03_Lab

Lab 3 - Hybrid Cars
Background

Hybrid cars usually have higher initial costs but lower fuel costs than non-hybrid cars. Some car buyers might prefer to spend more up front in order to save gas whereas others might worry only about the total cost of owning the car over some period of time. To help a car buyer make such a decision, write a program to compute both the gas consumed and the total cost of owning a car for 5 years. A user could then run your program for two potential car purchases and compare the results based on fuel consumption or total cost.
Requirements
Part 1 - User Input (20 points)

Prompt the user for the following input in the following order. All numeric values should be doubles.

    The estimated miles driven per year
    The estimated price of a gallon of gas during the 5 years of ownership
    The initial cost of a hybrid car
    The efficiency of the hybrid car in miles per gallon
    The estimated resale value (a dollar amount) for a hybrid after 5 years
    The initial cost of a non-hybrid car
    The efficiency of the non-hybrid car in miles per gallon
    The estimated resale value (a dollar amount) for a non-hybrid after 5 years
    The user's buying criterion, either minimized gas consumption or minimized total cost. Assume the user will enter either "Gas" or "Total" to indicate their preference.

Make sure that you prompt in this order.
Part 2 - Error checking (15 points)

You may assume that the input will be numeric but you must verify that all numeric inputs are positive. Remember that zero is not positive. You will need to check each number individually. If the user has attempted to give a non-positive value, output a message that only positive numbers are valid and reprompt for the needed input. You may assume that the second value will be numeric and positive. The buying criterion must be either "Gas" or "Total".
Part 3 - Output Costs (15 points)

For both cars, your program should correctly output the following:

    A label indicating whether the car is Hybrid or Non-Hybrid
    The estimated total gallons of fuel consumed over 5 years
    The estimated total cost of owning the car for 5 years (fuel cost + depreciation in car value)
    Both the gallons and the cost must be printed out with two decimal places to the right of the period, that is, "5678.90", not "5678.9".

Part 4 - Helping with the Decision (25 points)

Having computed the total gas consumption and the total cost for each car, you can now use the user's preference for lower gas consumption or lower total cost, and make a recommendation. Print out a message of the form "** The HYBRID Car is better than the NON-HYBRID Car when "Total" is the user's primary objective."; obviously indicating the correct car for the user's preference.

When printing the message identifying the preferred car, select the message using a single if-else pair, that is, exactly one if part and exactly one else part. Use a boolean expression (using boolean operators such as and's && and or's ||) to select the message. If you are not sure how to do this, you might start with multiple if-statements and then start looking for parts that are the same, then try to add and's and or's to make it just one if-else statement.
Implementation

If the cars are equally good with respect to the user's criteria, you can select either car as best. You do not have to have special code to handle this case.
Items Graded by the TA's Inspection (25 points)

    The TA will check for your adherence to the Style guidelines.
    The TA will check part 4 to assure that you are using just one if-statement with and's and or's. (5 point deduction if missing)

Notes

The test cases start with just the input part, so you can start there and then build your solution step by part. Also, you can submit your code as many times as you like.
Sample Run
Sample Input

15000
-4.35
4.35
28000
46.5
16000
0
24000
28.5
12000
Total

Sample Output

Please enter the following:

The estimated miles driven per year: 
The estimated price of a gallon of gas during the 5 years of ownership: 
I'm sorry, you must enter a value bigger than zero. Please try again. Please enter:
The estimated price of a gallon of gas during the 5 years of ownership: 
The initial cost of a hybrid car: 
The efficiency of the hybrid car in miles per gallon: 
The estimated resale value (a dollar amount) for a hybrid after 5 years: 
The initial cost of a non-hybrid car: 
I'm sorry, you must enter a value bigger than zero. Please try again. Please enter:
The initial cost of a non-hybrid car: 
The efficiency of the non-hybrid car in miles per gallon: 
The estimated resale value (a dollar amount) for a non-hybrid after 5 years: 
The user's buying criterion, either minimized gas consumption or total cost (enter Gas or Total): 
For the Hybrid Car:

The total gallons of fuel consumed over 5 years: 1612.90
The total cost of owning the car for 5 years: 19016.13

For the NON-Hybrid Car:

The total gallons of fuel consumed over 5 years: 2631.58
The total cost of owning the car for 5 years: 23447.37

** The HYBRID Car is better than the NON-HYBRID Car when "Total" is the user's primary objective.
