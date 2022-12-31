# Audit-Report-Generator

This project reads in a text file UTD Computer Science transcript and generates an Audit report with a GUI for the advisor to edit the transcript if need be. 

## Prerequisite Software
1. Install Python 3 
2. Install numpy, tk, fpdf modules using pip
[command prompt command: py -m pip install [module] (e.g. py -m pip install numpy)]


## Building
```
1. open cmd
2. cd to the program location on PC
3. type the following command in line to compile:
	pyinstaller -F -n AuditReportGenerator.exe  AuditReportGenerator.py
  
It will build an application for you to run
```

## Running
1. Double Click the AuditReportGenerator.py file to run the program
2. Select a Track
3. Click Choose File to select a transcript .txt file
4. Optionally Select Multiple Leveling Courses/Prerequisites
5. Optionally Select Courses to be removed
6. A Degree Audit Report will be generated in the same folder as the program
