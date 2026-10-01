# DAY-2-MY-Learning
JOINS IN SQL  WITH COMMANDS AND METHODS IN PYTHON
------------------------------------------------
Quick definitions:

**UNION**: Combines results of two SELECT queries and **removes duplicates**. Both queries need the same number of columns with compatible types.

**UNION ALL**: Same as UNION, but **keeps duplicates** (faster, no dedup step).

**CROSS JOIN**: Returns the **Cartesian product**: every row of table A paired with every row of table B (A has 3 rows, B has 4 → 12 rows). No ON condition.

**SELF JOIN**: A table joined **with itself** using aliases. Used for hierarchical data (employee → manager).


**NATURAL JOIN**: Automatically joins tables on **all columns with the same name** in both tables. No ON clause needed (risky if column names change or match unintentionally).



METHODS IN PYTHON
=============================
**Length**: len()
**Split**: 
 **syntax**:-str.split()
 ->Breaks a string into a list
**Slicing**: [start:stop:step]
->stop is excluded, and negative indexes count from the end.
**ord()**: returns the Unicode (ASCII) integer code of a single character.
 ->It only accepts one character. ord("ab") raises a TypeError.
 ->Handy to remember: 'A'–'Z' = 65–90, 'a'–'z' = 97–122, '0'–'9' = 48–57.
 **syntax**:- var=ord("letter")
**Replace**:returns a new string with old replaced by new. Strings are immutable, so the original doesn't change.
**syntax**:-var.replace("letter")
