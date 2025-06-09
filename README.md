# Check-for-Balanced-Brackets
A string is considered balanced if:  Opening brackets are closed by the same type of brackets.  Brackets are closed in the correct order.

Explanation:
Uses a stack to track opening brackets.

For every closing bracket, it checks if it matches the top of the stack.

If everything matches and the stack is empty at the end, it is balanced.
