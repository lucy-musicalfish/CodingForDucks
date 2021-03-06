# CodingForDucks
ENGR101 Project 3 Team 23

## CONTENTS

* For Marking
* AVC Plan
* Install Instructions
* Versions
* Notes
* Files on Master

## FOR MARKING
To Mark our Project: Please follow the install instructions included in this README.md file to the letter. They are written to take you through, step by step, how to install SFML and the right compiler, and exactly how to download, install and run our robot. It includes how to install our version of server3.cpp, but this is marked as an optional step - our server3.cpp file only makes changes to the cosmetic appearance of the robot, nothing else has been changed. We understand that for the purposes of marking, you have to run our robot on the original server3.cpp file. Our robot will run on my teams server3.cpp, and will also run on the original server3.cpp. We would love it if you would run our server3.cpp file (in the install instructions it is explained how to download it) because our robot Wilson (named after the Duck) was a lot of fun to create!!

The issues tab on our repository shows where we have been communicating, and there is an issue that explains the naming of the branches. Each branch has an issue with the same name explaining that branch, to make it easier to communicate as a team. We also used the wiki (not so much when we started using the issues), so there is some work in there too.

robot.cpp and server3.cpp on the master branch are the most up to date versions.

# AVC Plan

***

## Team Name: CodingForDucks

***

## Team Members & Contact Info:
Lucy Carver, 0273115725, carverlucy1@myvuw.ac.nz , ID: 300439983

***

Liam Hurren, 0210366176, hurrenliam@myvuw.ac.nz , ID: 300534302

***

Stephen Thessman, 0277774033, thessmstep@myvuw.ac.nz , ID: 300539537

***

Toby Balls, 0211527242, ballstoby@myvuw.ac.nz , ID: 300494308

## Communication Tool:
Discord, Github

## Roles:
Lucy - Project Manager (organising team meetings, reporting regularly on progress)

***

Stephen - Software Architect (writing core code and extending functionality)

***

Liam - Software Writer (Writing, testing and documenttaion. Debugging software and committing to Git, writing test cases and documenting performance against milestones)

***

Toby - Software Writer (Writing, testing and documenttaion. Debugging software and committing to Git, writing test cases and documenting performance against milestones)

***

Github: https://github.com/lucy-musicalfish/CodingForDucks

**Week One Objectives**


**DATE:** Week Ending 5 June


**Objectives:** Start the Project


**Due Date:** 4 June


**Item Due:** AVC Plan


**Conflicts:**
* ENGR121 Assignment 6 Due 3 June
* COMP102 Assignment 7 Due 4 June
* ENGR121 Lab 3 Due 5 June


**Tasks:**


All: Complete AVC plan
* Lucy - Finish the written plan and edit it, put all the wiki stuff on the plan doc. Make the excel spreadsheet to keep records for the individual logs. Post on github for download by monday 8th june meeting
* Stephen - Find Arthurs Github. Email and ask what exactly does the plan need to have. Help install SFML stuff
* Liam - Help Toby sort SFML. Liam is moving back to wellington this week, so will be in and out.
* Toby - Email Arthur, sort SFML. If possible, make a start on looking at the code and getting ideas up. 

**Week Two Objectives**

**DATE:** Week Ending 14 June


**Objectives:** Core and Completion


**Due Date:** 11 June


**Item Due:** Core Code


**Conflicts:**


**Tasks:**


Video Meeting: Monday Wednesday Friday 1pm
* Lucy - Updating progress on github and wiki, help resolve issues on Github. Make an excel doc for logging hours and distribute to team. put ducks in code. Edit real ducks to take photo shop, to put in place of other ducks in code. Write install instructions into pdf to make it look nice
* Liam - Writing code, make notes on changes. Keep track of hours and logs. Make the core code look "pretty"
* Stephen - Write core code, document additions to code. Mark any issues on Github. Keep track of hours and logs. Photoshop our own duck photos. 
* Toby - Writing code, make notes on changes. Keep track of your hours and logs. Make the core code look "pretty"

* All - Keep track of hours, excel doc will be posted on github for all to download and use to keep track of hours by Monday meeting. Will check in about making sure everyone is keeping on top of keeping records at fridays meeting

**Week Three Objectives**

**DATE:** Week Ending 21 June


**Objectives:** Challenge, Logs


**Due Date:** 19 June


**Item Due:** All Code


**Conflicts:**
* ENGR121 Test Two - 17 June
* COMP102 Assignment 9 - Due 18 June


**Tasks:**
* Lucy - Ensure all documentation is on github, on the readme. Make sure everyones logs are up to scratch. Edit and proofread stuff. Check all the issues are in place. MERGE LATEST VERSION TO MASTER- TUESDAY 16 JUNE
* Liam - Find someone to test the install procedure on FOR WINDOWS ONLY- make sure it fits the marking criteria of "There should be clear instructions (imagine that you are writing a game for 12 years old) on how to install (download, compile, build and run) your code from the scratch (including SFML library) in Install section of README.md. It is acceptable to provide version for specific Operating System.". (Liam find someone to test Windows only, Lucy is testing Linux on Monday)
* Stephen - Keep working on code - finish challenge, and then work on tidying up the code. If time allows, find a way to make the Robot look like Wilson (the duck) and the obstacles look like ducks/arthur. 
* Toby - Make sure all bugs are fixed. Work on the code. If it is not fixed already, get make the core algorithm nice - currently it doesnt work at high speeds. Help Stephen finish challenge


**Week Four Objectives**

**DATE:** Week Ending 28 June


**Objectives:** Finish Project


**Due Date:** 24 June


**Item Due:** Group and Individual Logs


**Conflicts:** Potentially CYBR171 Test


**Tasks:**
* Lucy - Make sure you've finished your logs and reports
* Liam - Make sure you've finished your logs and reports
* Stephen - Make sure you've finished your logs and reports 
* Toby - Make sure you've finished your logs and reports. 

**INSTALL INSTRUCTIONS:**

**CUSTOM ROBOT ICON MUST HAVE YES YES!!!**

HELLO Tutors & Arthur!!! Today is a good day. For we all know how much the ECS department (aka Arthur and the Tutors) LOVE. DUCKS. We here at CodingForDucks have decided that the simple robot icon was too boring. So I have spent some time changing the robot icon. Now I know I had to change the server3.cpp file which is against the marking code. BUT I promise you, promise you that I did not touch the robot x,y coords at all the robot still has to make its way through the maze. Otherwise it is too boring.
BUT please download our server3.cpp and Wilson.png for an AMAZING robot icon and place them in the AVC_server folder that you have.

**Install Instructions for Windows Using Geany:**

**Step 1:**
Go to https://www.sfml-dev.org/download/sfml/2.5.1/ and download the “GGC 7.3.0 MinGW (SEH) – 64-bit” version of SFML. Unzip this file into C:\ (If you cannot extract here, anywhere is fine. I will explain what to do in later steps). At the same time download the “MinGW Builds 7.3.0 (64-bit)” compiler version located in the red warning box as the versions MUST MATCH for SFML to work.

**Step 2**
Extract MinGW 7.3.0 64-bit version, the folder name should be “x86_64-.3.0-release-posix-she-rt_v5-rev0”. Copy the folder that is inside this folder named “mingw64” to the C: drive e.g. C:\mingw64. THIS MUST BE IN THE C: DRIVE
Next search "system environment variable" open the window. Click "Environment Variables" button. In System Variables select "Path" and click edit. Click New and add the Path location for mingw64 bin folder e.g. C:\mingw64\bin. Click OK 3 times. We can check that we have installed MinGW correctly. Open powershell and type g++ --version. It should say we have version 7.3.0. If a red error appears, try restarting your computer as the new system variable might not be activated yet. Try powershell again with g++ --version and you should see the version shown as 7.3.0.

**Step 3:**
Download the AVC_Win10.zip from the attachments in Assignment 3 page. Extract this to any file location you want E.G. C:\User\Documents\ENGR101\Assignment\Project3\ You will have two folders AVC_robot and AVC_server. Ensure that there are no spaces in the path name you are extracting to. Next go to CodingForDucks github and download robot.cpp from the master branch and replace robot.cpp in the AVC_robot folder.

**Step 3a: (OPTIONAL, lets robot be a duck)**
This is a completely optional step, but we have made our robot look like a duck. To get the robot to look like a duck. Download our server3.cpp file and Wilson.png. Please note we have only changed the image. Put these two files into the AVC_server folder. Our code works with the base server3.cpp file.

**Step 4:**
In AVC_robot open the "makefile" with Geany. Where it says DIR = C:\\SFML by default SFML extracts to SFML-2.5.1 change C:\\SFML to C:\\SFML-2.5.1 or where you extracted SFML to e.g. DIR = C:\\Users\Stephen\Downloads\SFML-2.5.1. In the make file where it just says robot: (line 5) add the extension .exe onto the name e.g. robot.exe: . Do the same for line 6 where it also has robot with no extension.
Repeat the above step for the AVC_server "makefile".

**Step 5:**
Delete the server3.o and server3.exe from their folder (if they exist). Delete the robot.o and robot.exe from their folder (if they exist).

**Step 6:**
From where you extracted SFML-2.5.1, Copy all the .dll files from the bin folder. Paste and replace the .dll files in both AVC_server and AVC_robot folders.

**Step 7:**
Open server3.cpp from the AVC_server folder with Geany. Open the Build drop down menu from the top and then click "Set Build Commands". Where it says Independent commands. Change the Make command to “mingw32-make”. Click Ok.

**Step 8:**
With server3.cpp still open, click build and then make, or Shift + F9. Click Execute and the server program will start. Allow it through your firewall with public/private at least public access. A white program that has a loading icon as the mouse. The map will then load and wait for the robot to start.

**Step 9:**
While the server program is still running. Open robot.cpp from AVC_robot in a new Geany window. Geany will still have the custom make commands saved in its build option. All you need to do is build and then make, or Shift + F9. You then need to execute robot.cpp (F5 by default). May need to execute twice to run the program.
In our version you need to select which map mode you want (core, completion, or challenge). The robot will then start to move on its own.

**Install Instructions for Linux Using Geany:**

**Step 1:**
Go to https://sfml-dev.org/download/sfml/2.5.1/ download the Linux 64-bit version of SFML, it downloads a zipped file. Extract it to where you want it to be. For me after I extracted the SFML zip file the file location was: /home/thessmstep/ENGR101/SMFL-2.5.1

**Step 2:**
Download AVC_Linux from the Assignment 3 page and extract it to where you want it. Open up AVC_server folder located inside this file. Open the makefile with Geany. Where it says SFML = PATHFILE. Make the PATHFILE equal the location where you extracted SFML too. For example: SFML = /home/thessmstep/ENGR101/SMFL-2.5.1 . Do the same for AVC_robot's makefile.

**Step 3:**
Download from CodingForDucks github page robot.cpp file. Place this file in the AVC_robot folder.

**Step 3a: (OPTIONAL, lets robot be duck)**
This is an optional step but lets the robot look like a duck. Download our server3.cpp and Wilson.png. Place these in the AVC_server folder.

**Step 4:**
Delete the server3.o and server3 file (if they exist). Delete the robot.o and robot file if they exist.

**Step 5:**
Open server3.cpp in Geany and make the file (build, make or just shift + F9). Now execute the file. Now open robot.cpp in a new Geany window. Make robot.cpp and then execute it also. You need to input what maze version the robot will run.


**VERSIONS:**

12/6/20: Stephen-Robot-Completion-v.0.2 . 

12/6/20: Liam-Robot-Completion-v.0.3 . 

12/6/20: Toby-Robot-Completion-v.0.4 . 

13/6/20: Lucy-Robot-Completion-v.0.5 . 

13/6/20: Stephen-Robot-Completion-v.0.6 . 

13/6/20: Toby-Robot-Completion-v.0.7 .

13/6/20: Lucy-Robot-Completion-v.0.8 . 

14/6/20: Lucy-Robot-Challenge-v.0.9 . 

15/6/20: Stephen-Robot-Challenge-v.1.0 .

16/6/20: Liam-Robot-Challenge-v.1.1 .

17/6/20: Lucy-Robot-Challenge-v.1.2 .

18/6/20: Stephen-Robot-Challenge-v.1.3 . 

18/6/20: Stephen-Robot-Challenge-v.1.4 .

18/6/20: stephen-robot-challenge-v.1.5 .

18/6/20: Liam-Robot-Challenge-v.1.6 .

18/6/20: Toby-Robot-Challenge-v.1.7 .

19/6/20: Master Branch . CURRENT MOST UP TO DATE VERSION

**NOTES:**

Core works, now need to finesse it.
We will have video meetings on Monday/Wednesday/Friday at 1pm. Notes from the meetings are on the Wiki.
Emailed Arthur with a few questions
Changed the github photo, made it a duck photo
completion is up, doesnt work yet. The robot will run, but thats about it.

Trying to get completion to work, bit of a struggle.
Check the issues to see team discussion

Photo of wilson is up. This is a want not a need, but side objective is to make robot look like the duck

Edited the install instructions here on readme. Will be tested on monday 15/6/20

This is our Read Me file, we will use this to keep track of all the files. I will update this regularly when I see new files/anything changes - Lucy

Planning is being done on the wiki.
I will add all changes to here (the ReadMe) as well

please make sure you have all read the project 3 document fully and properly, and understand it. Especially the stuff around the marking. 

Make sure you understand how to use github, and read the wiki. 

**FILES ON MASTER**

### Excel Logs.xlsx
This is a blank template file that I made to provide to the team, so that they could keep track of their time
### README.md
You're reading this right now!!
### Stephen Testing - Motor Controls.xlsx
Stephens testing document. Was unable to continue with writing up every test due to the number of tests we were running
### Wilson.png
This is the image to be used to change our robots appearance to the Duck. This is explained in the install instructions
### robot.cpp
This is the most up to date robot.cpp file, on the master branch
### server3.cpp
This is our own most up to date version of server3.cpp , on the master branch
