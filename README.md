# credit-card-validator
Created a credit-card-validator using CPP


This system uses the Luhn algorithm to validate a given credit card number. Consider the example of an account number “79927398713“.
Starting from the rightmost digit, double the value of every second digit.
"7" "18" "9" "4" "7" "6" "9" "16" "7" "2" "3"

 If doubling of a number results in a two digit number i.e greater than 9(e.g., 6 × 2 = 12), then add the digits of the product (e.g., 12: 1 + 2 = 3, 15: 1 + 5 = 6), to get a single digit number. 
"7" "9" "9" "4" "7" "6" "9" "7" "7" "2" "3"

 Now take the sum of all the digits.
sum=70

if(sum%10) = 0 then the credit card number is valid(Luhn Algorithm conclusion)
70%10 = 0...therefore its a valid credit card number


