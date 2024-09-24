Scanner:
- creates tokens, classifies tokens, and removes comments.
- groups characters into tokens to reduce the number of individual items that must be inspected by the parser.
Parser:
- checks the syntax, builds parse trees, and detects errors.
- more computationally intensive.

![image](https://github.com/user-attachments/assets/c26e7d11-553f-423e-a866-4a87740fea9d)

Look-ahead:
- The ability to examine characters beyond the current one before deciding on the token.

Types of scanners:
- Ad-hoc - quick and informal, good in cases where only a few token types need to be recognized; generally yields the fastest, most compact code.
- Semi-mechanical - pure DFA (if-else, switch-case); better for simple DFAs, hard to maintain for large DFAs.
- Table-driven - DFA (stored in a 2D array, transition table); for large and complex transitions.
