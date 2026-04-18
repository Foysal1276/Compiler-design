Tokenizer in C (Simple Lexical Analyzer)
📌 Overview

This project is a simple Lexical Analyzer (Tokenizer) written in C.
It reads a string and breaks it into meaningful components called tokens, then classifies each token into categories like:

Keyword
Identifier
Number
Operator
Punctuation
🎯 Objective

The goal of this program is to demonstrate the basic concept of lexical analysis used in Compiler Design.

🛠️ Features
Detects keywords (int, float, char, etc.)
Identifies identifiers
Recognizes numbers
Detects operators (+, -, *, /, =)
Handles punctuation (;)
📂 Code Description
1. isKeyword()

Checks whether a given word is a C keyword.

2. isOperator()

Checks whether a character is an operator.

3. main()
Takes a string as input
Scans character by character
Separates tokens
Prints token type
▶️ How to Run
Step 1: Save the file

Save your code as:

tokenizer.c
Step 2: Compile

Open terminal / VS Code terminal and run:

gcc tokenizer.c -o tokenizer
Step 3: Execute
./tokenizer
🧪 Sample Input
This is a int sum = 10; and a + b = 20
📊 Sample Output
Tokens and their types:

This --> Identifier
is --> Identifier
a --> Identifier
int --> Keyword
sum --> Identifier
= --> Operator
10 --> Number
; --> Punctuation
and --> Identifier
a --> Identifier
+ --> Operator
b --> Identifier
= --> Operator
20 --> Number
