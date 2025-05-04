# LongestCommonSubsequence
Author: Sanniddhya Bibekkumar Bardhan
Course: 605.420 Algorithms for Bioinformatics, Johns Hopkins University
Environment: Java 23, Eclipse IDE
# Description
This project implements the Longest Common Subsequence (LCS) problem using two algorithmic approaches:

- Dynamic Programming

- Brute Force with Memoization

The program reads biological sequence pairs from an input file, computes the LCS for all unique pairs using both methods, compares their performance (time and comparisons), and writes the results to a dynamically named output file.
# Project Structure
LCSProject-Java/

├── src/

│   ├── module-info.java

│   └── LCS/

│       └── LCSProject.java

├── Myinput.txt

├── Myinput_output.txt

└── README.md
# Input Format
S1 = AGCTGATC

S2 = GATCGAT

...
# Output Format
Output is saved in a file automatically named using this pattern:
- php-template
- <original_filename>_output.txt

Each result includes:
- Pair identifiers
- Input sequences
- LCS result
- Length of LCS
- Number of comparisons
- Execution time in milliseconds


# How to Run
Open the project in Eclipse IDE

Right-click LCSProject.java → Run as Java Application

When prompted, provide the full path to your input file
Example:

- makefile

- C:\Users\Downloads\Myinput.txt

Output is saved as:


Myinput_output.txt

# Features
Counts and compares dynamic programming vs brute force calls

- Measures execution time

- Works with all sequence pairs in the input

- Auto-labels outputs and filenames

- Modular, documented code structure

