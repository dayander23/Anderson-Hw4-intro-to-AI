# Anderson-Hw4-intro-to-AI
Decision Tree Assignment – README
---------------------------------

Files:
- decision_tree.py   : Python implementation of the decision tree classifier
- trainData.csv      : Training data
- testData.csv       : Test data
- report.pdf / report.docx : Analysis report

Requirements:
- Python 3.x
- pandas (for reading CSV files)

How to run:
1. Make sure trainData.csv and testData.csv are in the same directory as decision_tree.py.
2. Run the program from the command line:

   python decision_tree.py

What the program does:
- Reads trainData.csv and testData.csv.
- Trains two decision trees:
  * One using Gini Index
  * One using Information Gain
- Prints each decision tree in a textual, indented format.
- Predicts the 'profitable' label for each row in testData.
- Prints the number of correct predictions and the accuracy for each method.
- Prints simple statistics (number of nodes and training time) for both trees.
