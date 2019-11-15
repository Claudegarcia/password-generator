# password-generator

Deployed Link:
https://claudegarcia.github.io/password-generator/

app logic/how the generator works:

4 constant arrays, one for uppercase letters, lowercase letters, special characters, and numbers.

2 changing arrays, one "character pool" that potential characters are randomly selected from and a "final password array"
that the random character from the pool is taken from and pushed into to create a final password (on "generate" button push) that is printed in the html box.

check boxes operate if statements which merge coresponding constant array into character pool array.

character length is set by running a random character select and "push" function for X number of times using for loop, determined by user password length selection.

character pool and password arrays cleared on each "generate" button click to prevent passwords stacking with multiple password generate clicks.

page sends alert and reloads if selected character count is below/above 8 and 128 chars respectively.

potential for improvement: could guarantee that 1 of each selected character type is in password by adding a random character select and push operation to checkbox if statements and subtracting corresponding number of characters from "for" loop count. Could also use alternate method for button onclick functionality.