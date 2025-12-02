# Sample Test Plan – Spotify Mobile Application

Test Plan

Project: Spotify mobile application

### ChangeLog
| Test Plan Version | Change Date |  By | Description  |Spotify Version  |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| 1  | October 18, 2023  | Claudia Reyes  | Foundation data for test plan and test cases  | 8.8.78.587  |

## 1. Introduction
This test plan describes approaches and methodologies that will apply to the functional and non functional testing of the Spotify mobile application. It includes the objectives, test responsibilities, entry and exit criteria, scope, test deliverables, and what are the tools necessary to start testing.

## 2. Scope

### In Scope
    * Search
        - Search
        - Play song
        - Play
        - Pause

### Out of Scope
    * Sign up
        - Sign up free
        - Continue with Google
        - Continue with Facebook
    * Login
        - Credentials
        - No Credentials
    * Profile
        - View profile
            - Edit
            - Find Friends
            - Share
            - Preview profile
            - Show Spotify Code
        - Playlists
        - What's new
        - Listening history
        - Settings and privacy
    * Home
        - All
        - Music
        - Podcasts & Shows
            - Playlists
        - Your Library
            - Search
            - Add
        - Podcasts & Shows
        - Albums
        - Recents
        - Add artists
        - Add podcasts & shows
    * Search
        - Scan
        - Start Browsing
    * Play song
        - Next
        - Previous
        - Shuffle
        - Repeat
        - Add song to playlist
        - Remove song from playlist
        - Undo removing a song from a playlist
        - Current Device
        - Share
        - Recommended songs
        - See Lyrics
        - Add to queue
        - View album
        - View artist
        - Share
        - Audio Quality
        - Video Quality
        - Sleep Timer
        - Go to song radio
        - Show credits
        - About recommendations
        - Show Spotify Code

## 3. Quality Objective

* Primary Objectives
    - Assure that AUT meets all requirements (functional and non-functional) 
    - Assure that AUT satisfies the test case scenarios and maintain the quality of the product

* Secondary Objectives
    - Identify and expose all issues and associated risks to the project team
    - Ensure that all issues are addressed in an appropriate manner before release


## 4. Roles and Responsibilities

| Role   | Responsabilities  |
| ------------- | ------------- |
| Project Manager  |<ul><li>Acts as a primary contact for development and QA team.</li><li>Responsible for Project schedule and the overall success of the project.</li></ul>|
| QA Lead  |<ul><li>Participates in the project plan creation/ update process.</li><li>Plans and organizates of the test process for the release.</li><li>Coordinates with QA analysts/engineers on any issues/problems encountered during testing.</li><li>Reports progress on work assignments to the PM.</li></ul>|
| QA Analyst  | <ul><li>Understands requirements</li><li>Prepares test data</li><li>Writes and executes Test cases</li><li>Organizes RTM</li><li>Reports and tracks defects</li><li>Retests and performs regression testing</li><li>Coordinates with QA Lead for any issues or problems encountered during test preparation/execution/defect handling.</li></ul>|

## 5. Item Pass and Fail Criteria

The following criteria will be used to determine if a Test Case failed or passed:
* Failed:  Any scenario that shows an error or does not return a valid result according to the expected behavior of the corresponding Test Case definition.
* Passed: Test shows the expected behavior according to the Test Case definition.


## 6. Entry and Exit Criteria

### Entry Criteria

* The application construction is completed
* All test hardware platforms must have been successfully installed, configured, and functioning properly
* All the necessary documentation, design, and requirements information should be available for  QA Analysts so they are able to operate the application and judge the correct behavior
* All the standard software tools including the testing tools must have been successfully installed and functioning properly
* Proper test data is available
* The test environment such as, lab, hardware, software, and system administration support should be ready
* QA Analysts have completely understood the requirements
* QA Analysts have sound knowledge of functionality, reviewed test scenarios, test cases and RTM

### Exit Criteria

* A certain level of requirements coverage has been achieved
* No high priority or severe bugs are left outstanding
* All high-risk areas have been fully tested, with only minor residual risks left outstanding
* All the errors of high priority and severity are fixed
* The test results are evaluated, discussed and approved
* There are no show-stopping errors
* When the budget has been spent


## 7. Suspension Criteria and Resumption Requirements 

### Suspension Criteria

* The build contains many serious defects which seriously or limit testing progress
* Significant change in requirements suggested by client  
* Software/Hardware problems
* Resources are not available when needed by the test team

### Resumption Requirements

* Resumption will only occur when the problem(s) that caused the suspension have been resolved.

## 8. Test Methodology

### Test Levels

* Exploratory Testing: This kind of test allows to learn about the developed functionality, in order to create test case specification and update old test case
* Functional Testing: Functional testing is carried out in order to find out unexpected behavior of the report. The characteristics of functional testing are to provide correctness, reliability, testability and accuracy of the report output/data.
* GUI Testing: GUI testing will include testing the UI part of the application. It covers format, look and feel, error messages, spelling mistakes,etc. 
* Regression Testing: Identify whether regression testing needs to be performed for any applications and detail the testing required. Regression testing is verification of system functionality that was previously working, or is not considered to have changed 
* Integration Testing: It is a systematic technique for constructing the program structure while conducting tests to uncover errors associated with interacting. In Report, integration testing includes the testing Report from respective location(s). 
* System Testing: System testing of software is testing conducted on a complete, integrated system to evaluate the system's compliance with its specified requirements. 

### Non Functional Testing

* Compatibility Testing: The purpose of a mobile app compatibility test, in general, is to ensure an app’s key functions behave as expected on a specific device. 
* Localization Testing: Nowadays, most of the apps are designed for global use and it is very important to care about regional trails like languages, time zones, etc.
* Laboratory Testing: This test is performed to find out any glitches when a mobile application uses data connection to perform some functions. 
* Performance Testing: Mobile performance test covers client application performance, server performance, and network performance. 
* Stress Testing: It is a must to find exceptions, hangs, and deadlocks that may go unnoticed during functional and user interface testing. 
* Security Testing: It tests vulnerabilities to hacking, authentication, and authorization policies, data security, session management and other security standards. 
* Memory Leakage Testing: Memory testing is exceptionally important for mobile applications to ensure that each application maintains optimized memory usage throughout the user journey. 
Power Consumption Testing: This kind of testing requires measuring the state of the battery at each activity level. It will give us a better understanding of power consumption by an individual application.
* Interrupt Testing: An application, while functioning, may face several interruptions like incoming calls or network coverage outage and recovery. This can again be distinguished for:  Incoming and Outgoing SMS and MMS, incoming and outgoing calls, incoming notifications, battery removal when possible, cable Insertion and removal for data transfer. 
* Installation/Uninstallation Testing: Installation testing verifies that the installation/uninstallation  process goes smoothly without the user having to face any difficulty.
Updates Testing: Under the update testing, we test that the application will work as it was working previously. 

## 9. Bug Triage

Bug Severity and priority fields are both very important for categorizing bugs and prioritizing if and when the bugs will be fixed. The bug severity and priority levels will be defined as outlined in the following tables below. Testing will assign a severity level to all bugs. 

| ID | Severity | Description |
| ------------- | ------------- |------------- |
| 1  | Critical | The module crashes or causes nonrecoverable conditions. System crashes, DB corruption, or potential data loss, application hangs, etc. |
| 2  | Major | Application component unusable due to failure. Bugs cause serious problems such as a lack of functionality, or insufficient error messages that can have a major impact on the user, etc. |
| 3  | Medium | Incorrect functionality of component or process. There is a simple work around for the bug. |
| 4  | Minor   | Documentation errors or simple cosmetic issues.|

The QA Lead, Development Lead and Project Manager will participate in bug review meetings to assign the priority of all currently active bugs. This meeting will be known as “Bug Triage Meetings” it also can be done during “Planning Meetings”.

| ID | Priority  | Description |
| ------------- | ------------- |------------- |
| 1 | High | This bug must be fixed immediately; the product cannot ship with this bug. |
| 2 | Medium | The problem should be fixed within the time available. If the bug does not delay the shipping date, then fix it. |
| 3 | Low | It is not important (at this time) that these bugs be addressed. Fix these bugs after all other bugs have been fixed. |

## 10. Test Deliverables

During Quality assurance process it will be delivered
* Test Plan
* Test Cases Specification
* Test Estimation Document
* List of Reported Bugs categorized by test case, module and mobile OS.


## 11. Resource & Environment Needs

### Testing Tools

| Process | Tool |
| ------------- | ------------- |
| Test plan  | Microsoft Word**  |
| Test case creation | Microsoft Word / Excel**  |
| Test case execution | Microsoft Word / Excel**  |
| Test case management | Microsoft Word / Excel**  |
| Defect management | Microsoft Word / Excel**  |
| Test reporting | Microsoft Word / Excel**  |


**Microsoft Word / Excel are very good options, but due to the project nature is hardly recommended to use an advanced management tool, such as Jira or DevOps

## 12. Test environment 

Mobile devices are typically handheld computers. They have many variants based on their characteristics such as physical dimension, hardware and software capability, what are they meant for, etc.

For this test plan and project in particular, only smartphones will be used. A smartphone is a mobile phone that is designed to run a variety of applications in addition to providing phone service. Here is a list with common and popular devices.


1 (device) of each:
* Samsung Galaxy S9+ (Android 10)
* Samsung Galaxy S23 Ultra (Android 13) 
* Google Pixel 8 Pro (Android 13) 
* iPhone 15  (iOS 17.0.3)

| OS | Developed by | Popularity | Latest Version Available | 
| ------------- | ------------- |------------- |------------- |
| Android | Google Inc | High | 14 |
| iOS | Apple Inc | High | 17.0.3 |

## 13. Terms/Acronyms 
Make a mention of any terms or acronyms used in the project

| Term/Acronym | Definition |
| ------------- | ------------- |
| AUT | Application Under Test |
| RTM | Requirements Traceability Matrix |
| QA  | Quality Assurance |
| GUI | Graphical User Interface |
| UI  | User Interface |
| SMS | Short Message Service |
| MMS | Multimedia Message Service |
| DB  | Database |