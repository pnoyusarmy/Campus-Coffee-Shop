# Campus-Coffee-Shop
A simple text menu where a customer can order drinks and check out

Test Case 1 Ordering a coffee (normal case) 
* Input: 1
* Expected: Prints "Success! 1 Coffee added to your order." and shows the menu again
* Actual: Printed the success message and showed the menu again

Test Case 2 Typing a letter instead of a number (edge case)
* Input: a
* Expected: Prints "Invalid input. Please type a number from 1 to 5." The program does not crash and shows the menu again
* Actual: Printed the error message and showed the menu again

Test Case 3 Number that isn't on the menu (edge case)
* Input: 9
* Expected: Prints "Invalid choice. Please pick a number from 1 to 5." and shows the menu again
* Actual: Printed the error message and showed the menu again

Test Case 4 Pressing Enter without typing anything (edge case)
* Input: (blank)
* Expected: Prints "Invalid input. Please type a number from 1 to 5." The program does not crash
* Actual: Printed the error message and showed the menu again

Test Case 5 Ordering two drinks, then checking out
* Input: 1, 2, 5
* Expected: Lists Coffee $2.50 and Latte $3.75, shows "Total: $6.25", then exits
* Actual: Listed both drinks, showed Total: $6.25, and exited
