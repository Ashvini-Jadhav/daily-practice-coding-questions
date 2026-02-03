# daily-practice-coding-questions
Palindrome Checker (Python)
This repository contains two different Python implementations to check if a string or number is a palindrome (a sequence that reads the same backward as forward).
These examples were developed within a Jupyter Notebook environment. 

Features
The project demonstrates two primary logic patterns for palindrome detection:

1. Slicing Method
A concise approach using Python's string slicing capabilities to reverse a string and compare it to the original. 


Input: User enters a value. 


Logic: Uses [::-1] to reverse the input. 


Result: Prints "palindrome" or "not palindrome" based on the match. 

2. Two-Pointer (Iterative) Method
A more algorithmic approach using a while loop and pointers to compare characters from both ends of the string. 


Efficiency: Iterates through the string character by character. 

Logic:

Initializes left and right pointers. 

Compares characters at both positions. 

Breaks early if a mismatch is found. 

Technical Details

Environment: Jupyter Notebook (IPython) 


Language: Python 3 


File Name: Untitled3.ipynb 

How to Run
Ensure you have Python 3 and Jupyter Notebook (or JupyterLab) installed. 

Clone this repository.

Open the .ipynb file in your Jupyter environment. 

Run the cells and provide input when prompted (e.g., entering 46 will return "not palindrome"). 

