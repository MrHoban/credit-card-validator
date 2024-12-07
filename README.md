# credit-card-validator
Codecademy assignment


In This Assignment, We are a Clerk who checks if credit cards are valid. The company that you work for suspects that credit card distributors have been mailing out cards that have invalid numbers.

The Functions that was used are:

Implement validateCred(): This function checks if a single credit card number is valid using the Luhn algorithm.
Implement findInvalidCards(): This function iterates through a nested array of card numbers and returns a nested array of invalid card numbers.
Implement idInvalidCardCompanies(): This function takes the invalid card numbers and identifies the issuing companies, ensuring no duplicates.


My Explanation is:

Explanation:

validateCred():
Implements the Luhn algorithm:
Double every other digit starting from the second-to-last digit.
Subtract 9 if the doubled value is greater than 9.
Sum all digits.
Check if the sum modulo 10 is 0.

findInvalidCards():
Loops through the nested array batch and checks each card with validateCred().
Adds invalid cards to a new array.

idInvalidCardCompanies():
Checks the first digit of each invalid card to identify the company.
Ensures no duplicate companies in the output.

Let me know if you have any thoughts
