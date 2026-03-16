# Palindrome Checker App

## USE CASE 1: WELCOME MESSAGE
- Created a class to display welcome message.

- UC1 commit in UC1-WelcomePage branch.

## USE CASE 2: HARDCODE PALINDROME

- Input text divided into half.

- First half compared to the Second half for palindrome check.

- Boolean result returns true, if not, returns false.

## USE CASE 3: STRING REVERSE PALINDROME

- Input text traversed from the end.

- Reversed String is compared with the input string. 

- Result returns true else false.

## USE CASE 4: CHARACTER ARRAY BASED PALINDROME

- Input text is converted into character array.

- Compares characters from the beginning and end moving towards the center.

## USE CASE 5: STACK BASED PALINDROME CHECK

- Each character of input text is pushed into stack.

- Pop each character from the stack in reverse order.

- Compare with original input text.

- Return true if equal, else false.

## USE CASE 6: QUEUE AND STACK PALINDROME CHECK

- Enter array into queue and stack

- Remove element from queue in FIFO

- Pop element from stack in LIFO

-Compare both and if true, palindrome, else false

## USE CASE 7:DEQUE-BASED OPTIMIZED PALINDROME CHECK

- Characters of the input string are inserted into the deque.

- Elements are compared by removing characters from both ends

- If all characters match during comparison, the string is confirmed as a palindrome.

## USE CASE 8 – LINKED LIST BASED PALINDROME CHECK

- Characters of the string are inserted into the LinkedList.

- Elements are compared by removing characters from both ends.

- If all characters match, the string is confirmed as a palindrome.

## USE CASE 9 – RECURSIVE PALINDROME CHECK

- Implemented palindrome validation using **recursion**.

- Characters are compared from the **outermost positions** of the string.

- The recursive method checks whether the first and last characters match, then calls itself for the remaining substring.

- The process continues until all characters match or a mismatch is found.

## Use Case 10 – Normalized Palindrome Validation

- Implemented palindrome validation after normalizing the input string.

- Normalization removes spaces and special characters.

- All characters are converted to lowercase before comparison.

- Characters are then compared symmetrically from both ends of the string.

- This allows phrases with spaces and punctuation to be correctly checked as palindromes.

## USE CASE 11: OBJECT-ORIENTED PALINDROME 

- Implemented palindrome validation using a separate service logic.

- The palindrome checking logic is placed inside a dedicated function.

- The main program calls this function to verify whether the input string is a palindrome.

- This approach improves code organization, readability, and modular design.

