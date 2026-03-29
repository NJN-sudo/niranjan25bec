 CGPA Calculator in Python

This project is a simple command-line **CGPA Calculator** built using
Python. It allows users to enter subject names, credits, and grades,
then calculates the **CGPA** and the **equivalent percentage** based on
the entered data.


##  Objective

To develop a Python program that: - Accepts grades and credits for
multiple subjects - Converts grades into grade points - Computes total
credit points - Calculates final CGPA - Converts CGPA into percentage

-

## Grade to Point Mapping

    Grade   Grade Point
  
        O            10
       A+             9
        A             8
       B+             7
        B             6
        C             5
        D             4



##  Features

-   User input validation for grades and credits
-   Handles invalid inputs safely
-   Works for any number of subjects
-   Displays subject-wise credit points
-   Calculates CGPA accurately
-   Converts CGPA to percentage using formula:

Percentage = (CGPA - 0.75) × 10



##  How to Run

1.  Install Python (3.x)
2.  Save the program as `cgpa_calculator.py`
3.  Open terminal / command prompt
4.  Run:

python cgpa_calculator.py



##  Sample Output

Enter number of subjects: 3

----- Subject 1 ----- Enter subject name: Maths Enter subject credit: 4
Enter Grade: A+

----- Subject 2 ----- Enter subject name: Physics Enter subject credit:
3 Enter Grade: O

----- Subject 3 ----- Enter subject name: English Enter subject credit:
2 Enter Grade: B+

RESULT Total Credits Earned : 9 Total Credit Points : 78 Final CGPA :
8.67 Equivalent Percentage: 79.2 %



##  Concepts Used

-   Functions
-   Loops
-   Conditional statements
-   Dictionaries
-   Exception handling
-   String handling
-   Mathematical calculations

------------------------------------------------------------------------

##  Conclusion

This CGPA Calculator helps students quickly determine their academic
performance with proper input validation and accurate computation.
