# Module 

Title : Easy QR scanner

Version : 1

## Introduction
---
You were recently enrol to a private university in Perak recently. The registration time taken in the orientation day are too long and you are very stress about it. You got the registration office to complain about this and luckily they explain to you all the process flows. Currently the system flow are quite straight forward, after the student completed their interview session and get the result, the selected student will be email an offer letter. Students are required to bring their offer letter to the engagement day (first big day). The offer letter will be valiated at the registration counter on that day after that they will be allowed to enter the hall for the opening ceremony. 

As it is your time to shine in the university, you are to propose a simple solution to automate this whole process, from the begining until the end. You would like to proposed a solution to build a simple UI system (Desktop application) to automate all the registration process on the registration day and also use a code scanning solution in order to validate the offer letter instead of doing it manually. 

## Description of project
---
Using automated registration system, system should cover the following scenarios : 

##### Basic features

>- The user should login prior using the application 
>- After login, the main interface should cover the following ability to "generate QR code" , "scan qr code" , "open spreadsheet"
>- The return button should be visible on different page
>- For each user every action done will be log properly in a log folder stating the date today "date_today.log"

##### Generate QR features

>- On the generating qr features, the system user should be compulsory to enter the student ic number before generating the QR code,(proper error message should be given)
>- QR code generated should be stored in a seperate folder name "QR Generated" with each qrcode named "student_ic.png" (later this images will be used by the staff to embeded on the offer letter on their emails to the students)
>- The generated code should contain student ic number and any related details 
>- if a qr is already generated, user will be given option to re-generate or cancel operation

##### Scanning QR features

>- On the scanning qr features, user should only have 2 functionality which is "scan qr", "insert data manually"
>- The scan qr functionality will open a local camera (Default desktop camera), that can be use by the user to scan the student offer letter
>- this scanning process should covers the following action and all should be done in a single scan :
>  1. check the database/spreadsheet for the ic number decoded from the qr code
>  2. input all the necessary details into the spreadsheet
>  3. mark attendance in the database/spreadsheet
>- The user will then be alert with complete status / "user registered"
>- The manual data insertion will open the database/spreadsheet allowing user to edit the spreadsheet manually
>- If the user ic is not found in the database, and alert should apear indicating ic is missing and user will open the manual registration just to check for confirmation or add it manually (depends on the user)

##### Open spreadsheet features

>- this will allow user to open the database/spreadsheet and enters the data manually
>- the spreadsheet should also be able to be used by the system in case user want to do it automatically

## Notes
---
- QR scanner library are allowed 

## Requirement
---
- Any code (python, C++ , C# , C, electron)

## References
---
```
Will update later - [nexxa](https://github.com/neonexxa) (or can request directly from the author)
```

## Contributors & Authors
---
1. [Neonexxa](https://github.com/neonexxa)
