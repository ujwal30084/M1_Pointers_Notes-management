# REQUIREMENTS 


## Hardware Requirements
 - Ram 512MB or higher.
- Minimum 10MB hard disk space.
- Intel/Pentium powered system.
 - Processor speed 1.7 GHZ

## Software Requirements: -
-	 Windows 8 or higher versions.
-	 Visual Studio/Code::Blocks software/Dev-C++.



## Functional Requirements: -

In this project we used the concept of file handling, data structures, pointer and functions.
The basic user-defined functions used in this project are listed below:
-	Password– contains/manages/handles password protection
-	Addrecord– to add new diary record
-	Viewrecord– to view added record in list
-	Editrecord– to modify and update an added record
-	Editpassword– to modify/change a password
-	Deleterecord– to delete or remove a record permanently from system file.


#  TEST PLANS

##  High level test plan

|Test ID| Description | Exp I/P | Exp O/P | Act O/P | Type of test |
|---|---|---|---|---|---|
|H_01|Register the user|username-bittu, Pass - sam12222|Register|Passed|Registration|
|H_02|Register the user|username-ujwal, Pass - sam12222|Register|Passed|Registration|
|H_03|Register the user|username-bittu, Pass - ujwal|Register|Passed|Registration|
|H_04|login the user|username-bittu, Pass - sam12222|Register|Passed|login|
|H_05|login the user|username-bittu, Pass - sam12222|Register|Passed|login|
|H_06|login the user|username-ujwal, Pass - sam12222|Register|Passed|login|
|H_07|adding the data to diary|We are going to our company for some work|should add the dta|Passed|ADD RECORD|
|H_08|adding the data to diary|888888888888888888888888888|Should add the dta |Passed|ADD RECORD|
|H_09|adding the data to diary|Type a paragraph to see the result|Should add the data|Passed|ADD RECORD|
|H_10|adding the data to diary|The work|should add the data |Passed|ADD RECORD|
