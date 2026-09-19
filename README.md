Employee Payroll Management System

Experiential Learning project for Python Programming Language (N-PCCCM304P) Department of CSE (AI & ML), S. B. Jain Institute of Technology, Management and Research, Nagpur

Student: Tejal Rajkumar Hedau (CM25060) Guide: Mrs. Mayuri Getme Session: 2026-27 (ODD)

Purpose

Automate the calculation of employee salaries from attendance, allowances and deductions, and generate a printable payslip for each employee.

Files in this repository
File	Description
payroll.py	Complete Python source code
employees.txt	Sample payroll data written by the program
Employee_Payroll_Management_System.pptx	Project Assessment presentation
README.md	This file
How to run
bash
python payroll.py

No external libraries are required — the program uses only the Python standard library.

Features
Store employee details and attendance
Calculate HRA (20%), DA (10%) and TA (5%) from the basic salary
Calculate PF (12%), slab-wise income tax and absent-day deductions
Compute gross and net salary
Generate a formatted payslip on the console
Persist payroll records to employees.txt and reload them at start-up
Handle invalid input with try / except instead of crashing
Salary formulas
Gross Salary    = Basic Salary + HRA + DA + TA
Total Deduction = PF + Income Tax + Absent-day Deduction
Net Salary      = Gross Salary - Total Deduction

Absent-day deduction = (Total working days − Days present) × (Basic salary ÷ Total working days)

Income tax slabs (monthly, on gross salary)
Gross salary	Tax
up to 25,000	Nil
25,001 – 50,000	5%
50,001 – 1,00,000	10%
above 1,00,000	20%
Sample output
==============================================
              EMPLOYEE PAYSLIP
==============================================
Employee ID    : E101
Employee Name  : Tejal Hedau
Attendance     : 24 / 26 days
----------------------------------------------
Basic Salary   :     40000.00
HRA (20%)      :      8000.00
DA  (10%)      :      4000.00
TA  (5%)       :      2000.00
Gross Salary   :     54000.00
----------------------------------------------
PF  (12%)      :      4800.00
Income Tax     :      5400.00
Absent Days    :      3076.92
Total Deduction:     13276.92
----------------------------------------------
NET SALARY     :     40723.08
==============================================
Python concepts used

Variables and data types · if-elif-else · loops · functions · lists and dictionaries · file handling · exception handling · string formatting

Project status

Phase-II: approximately 70% complete.

Module	Status
Input and validation	Completed
Allowance calculation	Completed
Deduction calculation	Completed
Gross and net salary computation	Completed
Payslip generation	Completed
File handling	Completed
Month-wise summary report	In progress
Remaining work
Month-wise consolidated payroll report
Update and delete options in the main menu
CSV storage for easier analysis
Simple Tkinter data-entry screen
User manual and final project report
