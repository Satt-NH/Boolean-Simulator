README – Boolean Expression & Truth Table Simulator

This simulator allows you to enter Boolean expressions using variables A, B, and C, and it will generate a full truth table with step-by-step evaluation.

How to Run:
• Open the project in CLion or any C++ IDE.
• Build and run the main.cpp file.

How to Use:
1. Input a Boolean Expression
• Example: (A AND B) OR (NOT C)
• Supported operators: AND, OR, NOT, XOR, NAND, NOR
2. Get Results
• The program shows operator explanations and the full truth table.
• Includes intermediate steps like A AND B, NOT C, etc.
3. Save to File (Optional)
• After the table is shown, choose Y to save.
• Enter a filename (e.g., truth1)
• A .txt file will be saved with your full output.

Example Output

Generating TruthTable for : ( A AND B ) OR ( NOT C )

 Operators Detected and Explained:
- AND : True only if both inputs are true
- OR : True if at least one input is true.
- NOT : Inverts the input.

| A | B | C | (A AND B) | NOTC | ((A AND B) OR NOTC) |
|---|---|---|-----------|------|---------------------|
| 0 | 0 | 0 |         0 |    1 |                   1 |
| 0 | 0 | 1 |         0 |    0 |                   0 |
| 0 | 1 | 0 |         0 |    1 |                   1 |
| 0 | 1 | 1 |         0 |    0 |                   0 |
| 1 | 0 | 0 |         0 |    1 |                   1 |
| 1 | 0 | 1 |         0 |    0 |                   0 |
| 1 | 1 | 0 |         1 |    1 |                   1 |
| 1 | 1 | 1 |         1 |    0 |                   1 |


