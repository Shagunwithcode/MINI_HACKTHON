# MINI_HACKTHON


Student Result & Grade Analyzer
C PROGRAMMING · MINI HACKATHON · PROBLEM 03
RESULT PROCESSING · GRADE ENGINE · CLASS INSIGHTS
Five subjects. One clear performance report.



01 / PROJECT IDENTITY


* Project
      Student Result & Grade Analyzer
*  Language
     C
*  Team number
     2
* Batch
   51
* Members
SHAGUN SAINI
AASTHA SINGH
* Challenge
Mini Hackathon — Problem 3


02 / THE CHALLENGE



Manually processing results for many students takes time and risks calculation errors. GradeCraft is a proposed menu-driven C program that accepts five subject marks per student and calculates totals, percentages, grades, pass/fail decisions, and class-level insights.
Mission: Turn raw marks into readable, consistent student results.


03 / FEATURE MAP

Module
What it does

🧑‍🎓 Student registration
Enter a name and five subject marks

🛡️ Input validation
Accept only marks from 0 to 100; reject invalid menu choices

🧮 Result engine
Calculate total out of 500 and percentage

🏅 Grade assignment
Assign A+, A, B, C, D, E, or F

📊 Class dashboard
Show class average and highest-percentage student

🔁 Menu navigation
Add student, view results, view summary, exit


04 / GRADING POLICY

Project assumptions — confirm with faculty. Each subject is out of 100. A student must score at least 40 in every subject to pass.
Percentage
Grade
Condition
* 90–100
A+
All subjects passed
* 80–<90
A
 All subjects passed
* 70–<80
B
All subjects passed
* 60–<70
C
All subjects passed
* 50–<60
D
All subjects passed
* 40–<50
E
All subjects passed
* Any percentage
F
  At least one subject below 40


* Core formulas

Total Marks  = Subject 1 + Subject 2 + Subject 3 + Subject 4 + Subject 5

Percentage   = (Total Marks / 500.0) * 100

Class Average = Sum of Student Percentages / Number of Students

Topper       = Student with the Highest Percentage



05 / HOW IT WORKS
            
             
             
             +-----------------------+
       
             |    START GRADECRAFT   |
             +-----------+-----------+
                         |
                  +------v------+
             
                  |  MAIN MENU  |
                  +------+------+
                         |
           +-------------+-------------+
           |             |             |
    
       ADD STUDENT    VIEW RESULTS  CLASS SUMMARY
           |             |             |
   
     Validate 5 marks  Show totals   Topper + average
           |
   
   
     Total + percentage
           |
  
     Pass/fail + grade
           |
 
     Save student record
           |
       
           +----------> RETURN TO MENU
                              |
                    
                           
                 
                        EXIT -> END




Algorithm:

Initialize an empty student collection → display menu → process the chosen operation → validate marks → calculate and store results → display individual or class reports → repeat until Exit.
For an empty class, display an informative message.
For tied topper percentages, the proposed rule is to display the first entered student.


06 / C CONCEPTS APPLIED
struct for student records 
· arrays for five marks and multiple students
· strings for names · functions for modular logic 
· loops for menu and input
· conditionals for validation, pass/fail, and grading 
· arithmetic operators for calculations.


07 / BUILD & RUN

Save the final C source file as Minihack.c
gcc -g Minihack.c -o Minihack
./Minihack

On Windows Command Prompt, run student_result_analyzer.exe after compilation.
This README describes planned behavior, not a verified implementation. Match the final code to these rules and record actual outputs after testing.



08 / QUALITY ASSURANCE

See SAMPLE_TEST_CASES.md for 12 scenarios, including normal results, grade boundaries, failure despite a high overall percentage, invalid inputs, class summary, and topper ties.
Class topper: Priya
Total Marks: 475/500
Percentage: 95%
Grade: A+
Result: PASS


09 Batch_TeamNo 12


│
├── student_result.c
├── README.md
├── presentation.pptx
│
├── screenshots/
│   ├── main_menu.png
│   ├── student_result.png
│   └── topper_result.png
│
└── documentation/
    └── flowchart.png
    
