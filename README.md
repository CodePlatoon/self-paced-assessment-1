# Self-Paced Curriculum Assessment 1: Algorithms
- **Change Maker**

## Important Grading Information
- Make sure you read the [Assessment-1 Grading Rubric](https://docs.google.com/spreadsheets/d/1CjVoEPvswccsGTU5xc0WLaQ87Ql_mqGSeCEoZhSFyCM/edit?usp=sharing).
  - Algorithm Correctness (50%)
  - Code Design (25%)
  - Testing (25%)
- This assessment is worth 15% of your final grade. You need to get a 75% or better to pass. (You must pass all assessments in order to receive a Code Platoon certificate).
- If you fail the assessment, you have can retake it once to improve your score. For this assessment... 
  - *5% penalty*: If you complete and submit the retake **within one week** of receiving your grade. 
  - *10% penalty*: If you complete and submit the retake **after one week** of receiving your grade. A retake for this assessment WILL NOT be accepted after this date.
- Once you finish this assessment, please email jon@codeplatoon.org and let him know that you wish for him to grade assessment 1

## Rules / Process
- This test is fully open notes and open Google, but is not to be completed with the help of any other student/individual.
- Do not open a pull request against this repository. We will evaluate your code individually with you.

## Requirements
- This assessment should be completed using Python.

## Challenge
You are writing a computer program for an electronic vending machine to give you the optimal change for an item's cost. Write a method called `optimal_change` that takes in two arguments: `item_cost` and `amount_paid`. The method will `print` a string with optimal change which follows the following convention:

```
optimal_change(62.13, 100)
> "The optimal change for an item that costs $62.13 with an amount paid of $100 is 1 $20 bill, 1 $10 bill, 1 $5 bill, 2 $1 bills, 3 quarters, 1 dime, and 2 pennies."

optimal_change(31.51, 50)
> "The optimal change for an item that costs $31.51 with an amount paid of $50 is 1 $10 bill, 1 $5 bill, 3 $1 bills, 1 quarter, 2 dimes, and 4 pennies."
```

Don't forget to account for plural denominations (i.e., quarters, dimes, pennies, bills) and punctuation (i.e., commas and the period at the end of a sentence) to delineate between different denominations. Some other things to note:
- This is **optimal** change. Obviously, you can give the change in pennies, but we're looking for the most optimal (least amount of) change possible.
- Only consider *common* monetary denominations (i.e. ignore any denomination larger than $100-bill, ignore $2-bills, half-dollars, etc...)
- Fully understand the data types of your input and output
- Don't forget about edge cases and special cases!
- Write at least 4-5 unit tests. Feel free to start with the two examples above. Make sure you test various parts of your algorithm (common cases, edge cases, special cases, etc...)
