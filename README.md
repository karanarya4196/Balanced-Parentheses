# Balanced-Parentheses

The task is to write a program in language of your choice that receives a quoted input string containing just the characters '(', ')', '{', '}', '[' and ']' as a command line argument and determine if the input string is valid or not. Do not ask for input from the user interactively.

An input string is valid if:

Open brackets must be closed by the same type of brackets.
Open brackets must be closed in the correct order.
Note that an empty string is also considered valid.


Example 1:

Input: "()"
Output: true

Example 2:

Input: "()[]{}"
Output: true

Example 3:

Input: "(]"
Output: false

Example 4:

Input: "([)]"
Output: false

Example 5:

Input: "{[]}"
Output: true

Example 6:

Input: ""
Output: true

