Completed Lab 1: Lexical Analyzer & Syntax Analyzer for CSE 420

This commit implements a complete lexical and syntax analyzer for a subset 
of the C language using Flex (Lex) and Bison (Yacc).

Features Implemented:
- Token recognition for C keywords (if, else, for, while, int, float, etc.)
- Constant identification (integer and floating-point literals)
- Operator and punctuator tokenization (ADDOP, MULOP, RELOP, LOGICOP, etc.)
- Identifier parsing with proper validation rules
- Line counting and whitespace handling
- Context-free grammar implementation for C syntax
- Ambiguity resolution (if-else dangling else problem)
- Zero shift/reduce conflicts in parser
- Symbol information passing between lexer and parser
- Grammar rule matching and logging

Files Included:
- <student_id>.l - Flex lexical analyzer specification
- <student_id>.y - Bison parser specification with C grammar rules
- symbol_info.h - Symbol table data structure
- script.sh - Build and execution script
- input.txt - Sample C source code for testing

Output:
- Generates log file with tokens, line numbers, and matched grammar rules
- Reports total line count
- Follows specified output format requirements

Course: CSE 420 - Compiler Design (Spring 2025)
Assignment: Lab 1 - Lexical & Syntax Analysis
