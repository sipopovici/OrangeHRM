Jira table { mso-displayed-decimal-separator:"\\."; mso-displayed-thousand-separator:"\\,"; } body { margin: 0px; font-size: 12px; font-family: Arial, sans-serif; color:black; }    @page { mso-page-orientation:landscape; margin:.25in .25in .5in .25in; mso-header-margin:.5in; mso-footer-margin:.25in; mso-footer-data:"&R&P of &N"; mso-horizontal-page-align:center; mso-vertical-page-align:center; } td.issuekey, td.issuetype, td.status { mso-style-parent: ""; mso-number-format: \\@; text-align: left; } br { mso-data-placement:same-cell; } td { vertical-align: top; }

![Jira](https://svtestjira2022.atlassian.net/images/icon-jira-family-logo.png)

[Jira](https://svtestjira2022.atlassian.net/issues/?jql=project+%3D+%22OH%22+AND+type+IN+%28%22Bug%22%2C%22Story%22%2C%22Task%22%29+ORDER+BY+created+DESC)

Displaying **36** issues at **22/Mar/23 9:18 PM**.

Project

Key

Summary

Issue Type

Status

Priority

Resolution

Assignee

Reporter

Creator

Created

Last Viewed

Updated

Resolved

Affects versions

Fix versions

Components

Due date

Votes

Watchers

Images

Original estimate

Remaining Estimate

Time Spent

Work Ratio

Sub-tasks

Linked Issues

Environment

Description

Security Level

Progress

Σ Progress

Σ Time Spent

Σ Remaining Estimate

Σ Original Estimate

Labels

Status Category Changed

Status Category

Parent

Actual end

Actual start

Approvers

Change reason

Change risk

Change type

Compass

Epic Link

Flagged

Impact

Issue color

Locked forms

Open forms

Organizations

Parent Link

Rank

Request Type

Request participants

Satisfaction

Sprint

Start date

Story Points

Story point estimate

Submitted forms

Target end

Target start

Team

Total forms

Work category

\[CHART\] Date of First Response

Development

OrangeHRM

[OH-108](https://svtestjira2022.atlassian.net/browse/OH-108)

In Pay Grades, in the Currencies field, Maximum Salary we can register negative number, appear error "Should be a number".

Bug

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 2:48 PM

14/Feb/23 2:48 PM

14/Feb/23 2:48 PM

 

OrangeHRM Release 1

OrangeHRM Release 1

 

 

0

1

[Screenshot 2023-02-14 144549.jpg](https://svtestjira2022.atlassian.net/secure/attachment/10003/Screenshot+2023-02-14+144549.jpg)

 

OH-5, OH-94

Testing  
Browser: Opera 95.0.4635.37

Preconditions: Does not exist.  
  
Steps to reproduce:  
1\. Go to https://opensource-demo.orangehrmlive.com/  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the Admin on the left side >> Job>> Pay Grades.  
4\. Click on the edit button represented by a pen on the right.  
5\. In form Currencies click button "Add".  
6\. In the field Currency select from the dropdown currency.  
7\. In the field Minimum Salary introduce the positive number 1000.  
6\. In the field Maximum Salary introduce the negative number -1 (minus one).  
  
Expected Result: Will appear under the field Maximum Salary error: "Should be a 0 (zero) or positive number".  
Actual Result: Will appear under the field Maximum Salary error: "Should be a number".

14/Feb/23 2:48 PM

To Do

0|i000ar:

OrangeHRM

[OH-107](https://svtestjira2022.atlassian.net/browse/OH-107)

In Pay Grades, in the Currencies field, Minimum Salary we can register negative number, appear error "Should be a number".

Bug

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 2:35 PM

 

14/Feb/23 2:35 PM

 

 

OrangeHRM Release 1

 

 

0

1

[изображение\_2023-02-14\_143515265.png](https://svtestjira2022.atlassian.net/secure/attachment/10002/%D0%B8%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5_2023-02-14_143515265.png)

 

OH-5, OH-93

Preconditions: Does not exist.  
  
Steps to reproduce:  
1\. Go to https://opensource-demo.orangehrmlive.com/  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the Admin on the left side >> Job>> Pay Grades.  
4\. Click on the edit button represented by a pen on the right.  
5\. In form Currencies click button "Add".  
6\. In the field Currency select from the dropdown currency. Introduce Minimum Salary number -1 (minus one).  
  
Expected Result: Will appear under the field Minimum Salary error: "Should be a 0 (zero) or positive number".  
Actual Result: Will appear under the field Minimum Salary error: "Should be a number".  

14/Feb/23 2:35 PM

To Do

0|i000aj:

OrangeHRM

[OH-106](https://svtestjira2022.atlassian.net/browse/OH-106)

In Leave Entitlements and Usage Report, in the field Leave Period, there is no button Create PDF/XPS Document Report

Bug

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 1:54 PM

 

14/Feb/23 1:57 PM

 

OrangeHRM Release 1

OrangeHRM Release 1

 

 

0

1

 

OH-86, OH-89

Testing  
Browser: Opera 95.0.4635.37

Preconditions: Does not exist.  
  
Steps to reproduce:  
1\. Go to \[https://opensource-demo.orangehrmlive.com/|https://opensource-demo.orangehrmlive.com/\]  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the Leave on the left side >> Reports >> Leave Entitlements and Usage Report  
4\. Click button Leave Type and in the field Leave Period we enter the period. Click button Generate.  
5\. The report is generated at the bottom of the application.  
  
Expected Result: To export or save the report: Click button "Export/Save As"  
Actual Result: It's not the button "Export/Save As".

14/Feb/23 1:54 PM

To Do

0|i000ab:

OrangeHRM

[OH-104](https://svtestjira2022.atlassian.net/browse/OH-104)

In My Leave List, in the field Show Leave with Status, the list Status is not active when click dropdown button which is required.

Bug

Backlog

High

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 1:10 PM

09/Mar/23 10:25 AM

09/Mar/23 10:26 AM

 

OrangeHRM Release 1

OrangeHRM Release 1

 

 

0

1

[изображение\_2023-02-14\_130956079.png](https://svtestjira2022.atlassian.net/secure/attachment/10000/%D0%B8%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5_2023-02-14_130956079.png)

 

OH-86, OH-87

Testing  
Browser: Opera 95.0.4635.37

Preconditions: Does not exist.  
  
\*Steps to reproduce:\*  
1\. Go to \[https://opensource-demo.orangehrmlive.com/|https://opensource-demo.orangehrmlive.com/\]  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the Leave on the left side >> My Leave  
4\. Click on the dropdown button Show Leave with Status. This field is required.  
  
5\. The Status list opens.  
  
5\. From the open list, selected and click on the Status "Cancelled".  
  
\*Expected Result:\* In the dropdown Show Leave with Status, the Status "Cancelled" is displayed in the field.  
\*Actual Result:\* In the dropdown Show Leave with Status it not active the list of Status and the Status “Cancelled“ is not displayed in the field.

14/Feb/23 1:10 PM

To Do

0|i0009v:

OrangeHRM

[OH-103](https://svtestjira2022.atlassian.net/browse/OH-103)

In Job Details, in the field Contract Details on Add Attachment in the message that appears, the type of the attached format is not specified.

Bug

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 12:39 PM

 

18/Mar/23 1:11 PM

 

OrangeHRM Release 1

OrangeHRM Release 1

 

 

0

1

 

OH-77

Testing  
Browser: Opera 95.0.4635.37

Preconditions: Does not exist.  
  
Steps to reproduce:  
1\. Go to https://opensource-demo.orangehrmlive.com/  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the PIM on the left side >> Employee List.  
4\. Choose employee and click on the edit button represented by a pen on the right.  
5\. Click on the Job.  
6\. Click the button Include Employment Contract Details  
  
  
Expected Result: Under the dropdown Contract Details the message appears: "Accepts format docx, xlsx, doc, pdf and up to 1MB"  
Actual Result: Under the dropdown Contract Details the message appears: "Accepts format up to 1MB"

14/Feb/23 12:39 PM

To Do

0|i0009n:

OrangeHRM

[OH-102](https://svtestjira2022.atlassian.net/browse/OH-102)

In Job Details, in the field Contract Start Date, we can register a date future than today.

Bug

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 12:23 PM

09/Mar/23 10:33 AM

09/Mar/23 10:35 AM

 

OrangeHRM Release 1

OrangeHRM Release 1

 

 

0

1

 

OH-77, OH-84

Testing  
Browser: Opera 95.0.4635.37

Preconditions: Does not exist.  
  
\*Steps to reproduce:\*  
1\. Go to \[https://opensource-demo.orangehrmlive.com/|https://opensource-demo.orangehrmlive.com/\]  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the PIM on the left side >> Employee List.  
4\. Choose employee and click on the edit button represented by a pen on the right.  
  
5\. Edit Personal Details form will appear.  
6\. Click on the Job.  
  
7\. Job Details form will appear.  
8\. Click the button Include Employment Contract Details.  
9\. In the field Contract Start Date put a future date than today.  
  
\*Expected Result:\* The following error should appear under the Contract Start Date field: "The future date than today is not accepted".  
\*Actual Result:\* In the field Contract Start Date is saved with a future date than today.

14/Feb/23 12:23 PM

To Do

0|i0009f:

OrangeHRM

[OH-101](https://svtestjira2022.atlassian.net/browse/OH-101)

In Job, in the field Joined Date, we can register a date future than today

Bug

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 12:13 PM

09/Mar/23 10:38 AM

09/Mar/23 10:41 AM

 

OrangeHRM Release 1

OrangeHRM Release 1

 

 

0

1

 

OH-77, OH-83

Preconditions: Does not exist.  
  
\*Steps to reproduce:\*  
1\. Go to \[https://opensource-demo.orangehrmlive.com/|https://opensource-demo.orangehrmlive.com/\]  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the PIM on the left side >> Employee List.  
4\. Choose employee and click on the edit button represented by a pen on the right.  
  
5\. Edit Personal Details form will appear.  
6\. Click on the Job.  
  
7\. Job Details form will appear.  
8\. In the field Joined Date put a future date than today.  
  
\*Expected Result:\* The following error should appear under the Joined Date field: "The future date than today is not accepted".  
\*Actual Result:\* In the field Joined Date is saved with a future date than today.

14/Feb/23 12:13 PM

To Do

0|i00097:

OrangeHRM

[OH-100](https://svtestjira2022.atlassian.net/browse/OH-100)

In Immigration, In the field Issued Date of passport., we can register a date future than today.

Bug

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 11:59 AM

09/Mar/23 10:42 AM

09/Mar/23 10:46 AM

 

OrangeHRM Release 1

OrangeHRM Release 1

 

 

0

1

 

OH-77, OH-82

Testing  
Browser: Opera 95.0.4635.37

Preconditions: Does not exist.  
  
\*Steps to reproduce:\*  
1\. Go to \[https://opensource-demo.orangehrmlive.com/|https://opensource-demo.orangehrmlive.com/\]  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the PIM on the left side >> Employee List.  
4\. Choose employee and click on the edit button represented by a pen on the right.  
  
5\. Edit Personal Details form will appear.  
6\. Click on the Immigration and on the Assigned Immigration Records click button "Add".  
  
7\. Add Immigration form will appear.  
  
8\. Click button “Passport“.  
9\. In the field Issued Date of passport put a future date than today.  
  
\*Expected Result:\* The following error should appear under the Issued Date field: "The future date than today is not accepted".  
\*Actual Result:\* In the field Issued Date is saved with a future date than today.

14/Feb/23 11:59 AM

To Do

0|i0008z:

OrangeHRM

[OH-97](https://svtestjira2022.atlassian.net/browse/OH-97)

In Personal Details, in the field SSN Number a number is accepted of more than 30 characters

Bug

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 11:20 AM

09/Mar/23 10:58 AM

09/Mar/23 11:02 AM

 

OrangeHRM Release 1

OrangeHRM Release 1

 

 

0

1

 

OH-77, OH-79

Testing  
Browser: Opera 95.0.4635.37  
  

Preconditions: Does not exist.  
  
\*Steps to reproduce:\*  
1\. Go to \[https://opensource-demo.orangehrmlive.com/|https://opensource-demo.orangehrmlive.com/\]  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the PIM on the left side >> Employee List.  
  
4\. Choose employee and click on the edit button represented by a pen on the right.  
  
5\. Personal Details form will appear.  
6\. In the field SSN Number enter a number of 31 characters..  
  
\*Expected Result:\* It must not allow us to enter a number with 31 characters (from the keyboard).  
The following message should appear under the SSN Number field: "Should not exceed 30 characters".  
  
\*Actual Result:\* Are recorded 31 characters from the keyboard.  
The following message should appear under the SSN Number field: "Should not exceed 30 characters".

14/Feb/23 11:20 AM

To Do

0|i0008b:

OrangeHRM

[OH-96](https://svtestjira2022.atlassian.net/browse/OH-96)

In Personal Detail, in the date of birth field, we can register a date future than today

Bug

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

14/Feb/23 10:53 AM

18/Mar/23 7:13 PM

09/Mar/23 10:53 AM

 

OrangeHRM Release 1

OrangeHRM Release 1

 

 

0

1

 

OH-77, OH-78

Testing  
Browser: Opera 95.0.4635.37  

Preconditions: Does not exist.  
  
\*Steps to reproduce:\*  
1\. Go to \[https://opensource-demo.orangehrmlive.com/|https://opensource-demo.orangehrmlive.com/\]  
2\. Enter Username: Admin  
Password: admin123  
3\. Enter the PIM on the left side >> Employee List.  
  
4\. Choose employee and click on the edit button represented by a pen on the right.  
  
5\. Edit Personal Details form will appear.  
6\. In the field Date of Birth put a future date than today.  
  
\*Expected Result:\* The following error should appear under the Date of Birth field: "The future date than today is not accepted".  
\*Actual Result:\* In the field Date of Birth is saved with a future date than today.

14/Feb/23 10:53 AM

To Do

0|i00083:

OrangeHRM

[OH-86](https://svtestjira2022.atlassian.net/browse/OH-86)

Leave Module

Story

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

09/Feb/23 5:24 PM

21/Mar/23 10:55 PM

14/Feb/23 1:54 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-104, OH-87, OH-88, OH-89, OH-106

A comprehensive leave management module with extensive possibilities of defining leave types, company  
holidays, applying for and assigning of leave for the employees of the company. It caters for all application  
and approval processes and is able to display information on leave entitlement, balance, history etc.  
  
The functionality of the Leave Module differs depending on the rights of the user. The Leave Module will be  
described from the perspective of an administrator, an ESS User who is a supervisor and the normal ESS  
user.  
  
The Admin can:  
  
 View Leave Entitlements for each employee and entitle leave days of each available type  
 Generate Leave Entitlements and Usage Reports for himself/herself and all employees  
 Configure leave periods, leave types, work week and holidays  
 Assign Leave for any employee  
 See Scheduled Leave for any employee  
 See list of Taken Leave for any employee  
 If the admin user is an employee then he will see the ‘Apply’ ‘My Leave’ and ‘Entitlements’ options  
along with the rest of the features.  
  
A Supervisor can:  
  
 View the Personal or Employee (subordinate) Leave Entitlements  
 Generate Leave Entitlements and Usage Reports for himself/herself and his/her subordinates  
 View the Leave List  
 Apply Leave  
 Assign Leave for his/her subordinates  
 Approve/Reject Leave for his/her subordinates  
  
The ESS User can:  
  
 View the Personal Leave Entitlement  
 Generate Leave Entitlements and Usage Reports for himself/herself  
 View the detailed leave information  
 Apply for leave

09/Feb/23 5:24 PM

To Do

0|i00077:

OrangeHRM

[OH-77](https://svtestjira2022.atlassian.net/browse/OH-77)

PIM Module

Story

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

09/Feb/23 2:05 PM

21/Mar/23 10:53 PM

14/Feb/23 12:39 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-78, OH-79, OH-80, OH-81, OH-82, OH-83, OH-84, OH-96, OH-97, OH-100, OH-101, OH-102, OH-103

This core module maintains all relevant employee related information, including different types of personal information, detailed qualifications, work experience, job related information etc. Information captured in  
this module is utilized by all other modules, thus eliminating data redundancy. Records can be either entered manually one by one or imported from a CSV file. You cannot import all the details but you can edit the  
remaining fields.  
  
The functionality of the PIM Module differs depending on the rights of the user.  
  
The HR can:  
  
 Configure optional/custom fields, data import from CSV, define reporting methods and termination  
reasons that will be used throughout the module.  
 View all employee details  
 Add employee on the list.  
 Generate employee report  
  
ESS-Supervisor can:  
  
 View his personal details as well as his/her subordinates.  
  
ESS-Employee:  
  
 Has no access to the PIM module but can view his personal details under the ‘My Info’ Module.

09/Feb/23 2:05 PM

To Do

0|i0005j:

OrangeHRM

[OH-25](https://svtestjira2022.atlassian.net/browse/OH-25)

Modules

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:20 PM

 

19/Jan/23 4:20 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

This feature enables the HR Admin to configure the display/hide settings of the modules of the system. To  
configure the module display settings, go to Admin>> Configuration>> Modules and the screen as shown  
in Figure 5.1 will appear.  
  
Click “Edit “to edit module display. You may select from the list the modules you want to be  
displayed/hidden.  
  
Click “Save” one module configuration is completed.

19/Jan/23 4:20 PM

To Do

Admin Module for OrangeHRM

0|i0005b:

OrangeHRM

[OH-24](https://svtestjira2022.atlassian.net/browse/OH-24)

Date Format Localization

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:18 PM

 

19/Jan/23 4:18 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

This feature allows the HR Admin to set up the date format that will be reflected throughout the whole  
system as shown in Figure 5.0.  
Once you have configured the localization settings, click “Save”.

19/Jan/23 4:18 PM

To Do

Admin Module for OrangeHRM

0|i00053:

OrangeHRM

[OH-23](https://svtestjira2022.atlassian.net/browse/OH-23)

Language Localization

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:16 PM

 

19/Jan/23 4:16 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

This feature enables the HR Admin to configure the language settings and translate the OrangeHRM system  
to the language of your choice. To configure localization settings, go to Admin>> Configuration>>  
Localization and the screen as shown in Figure 5.0 would appear. Click “Edit” to edit the fields.  
  
The default language of the system is US English however you may also use an already set up browser  
language to translate the system to the language of choice. For example: If you are using Firefox as your  
browser and it’s translated in UK English language and you want to use this particular language, click on the  
“Use Browser Language if set” and select from the “Supported Language” provided.  
  
The language pack tool can also be obtained from the website by clicking on “Language and font help” as  
shown in Figure 5.0, where you will be diverted to the web page or by simply browsing through the  
OrangeHRM Website (\[http://www.orangehrm.com|http://www.orangehrm.com|smart-link\] >> Community>> Translators).

19/Jan/23 4:16 PM

To Do

Admin Module for OrangeHRM

0|i0004v:

OrangeHRM

[OH-22](https://svtestjira2022.atlassian.net/browse/OH-22)

Email Subscriptions

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:15 PM

 

19/Jan/23 4:15 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

This feature will allow the admin to subscribe to email notifications that will be sent to the employees and  
supervisors in the system. A copy of the mail will be sent to the email address specified by the Admin. He/she  
can also select what copies of notifications he should receive. To subscribe to a notification type, go to  
Admin>> Configuration>> Email Subscriptions and a screen a shown in Figure 4.6 would appear.  
  
The HR Admin may also add other subscribers to the following notifications by clicking on the notification  
types and you will be directed to the screen as shown in Figure 4.7. Once the fields are added, click “Save”.  
  
The entry will then be listed as shown in Figure 4.8 and multiple entries of subscribers for a particular  
notification type may also be added or deleted.  
  
When you click “Back” you will be directed to the “Email Notification” screen as shown in Figure 4.9 with the  
added notification subscriber reflected on the screen.

19/Jan/23 4:15 PM

To Do

Admin Module for OrangeHRM

0|i0004n:

OrangeHRM

[OH-21](https://svtestjira2022.atlassian.net/browse/OH-21)

Email Configuration

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:13 PM

 

19/Jan/23 4:13 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

Configuration of mail settings is essential to accommodate sending and receiving notifications related to the  
operations performed within the OrangeHRM application (Ex: leave management).  
  
To configure the mail settings, go to Admin>> Configuration>>Email Configuration, a screen as shown in  
Figure 4.5 would appear. Enter the fields accurately by clicking “Edit”, and then a test mail to an email  
address of your choice could be sent to check functionality. Click “Save” when you have entered all the  
settings and you may check the email account if you specified an address to receive the test mail.

19/Jan/23 4:13 PM

To Do

Admin Module for OrangeHRM

0|i0004f:

OrangeHRM

[OH-20](https://svtestjira2022.atlassian.net/browse/OH-20)

Configuration

Story

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:08 PM

05/Mar/23 11:59 AM

28/Jan/23 12:05 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

As a HR Admin, I would like to subscribe and receive notifications and to configure the parameters in setting up the email so notifications will be sent to relevant persons which will quicken the communication processes.  
  
It also allows the HR admin to configure language localization for the entire system, set up a date format and enable/disable module display.

19/Jan/23 4:08 PM

To Do

Admin Module for OrangeHRM

0|i00047:

OrangeHRM

[OH-19](https://svtestjira2022.atlassian.net/browse/OH-19)

Nationalities

Story

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:06 PM

05/Mar/23 11:59 AM

28/Jan/23 12:05 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

As a HR Admin, I would like to add, save and delete the nationality. This feature allows the HR Admin to define the different nationalities that present in the company which can  
later be used in the PIM Module. Various nationalities are already pre-defined.  
  
To add a nationality, go to Admin>> Nationalities and click “Add”, a screen as shown in Figure 4.3 would  
appear.  
  
Click “Save” once the field is added.  
  
A list of nationalities as shown in Figure 4.4 would appear once a “Nationality” is added. You may also add  
multiple entries of nationalities.  
  
To delete a nationality, click on the check box next to the “Nationality”” name. It is also possible to delete  
multiple entries at the same time by clicking the check box entries you wish to delete and simply clicking  
“Delete”.

19/Jan/23 4:06 PM

To Do

Admin Module for OrangeHRM

0|i0003z:

OrangeHRM

[OH-18](https://svtestjira2022.atlassian.net/browse/OH-18)

Memberships

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:04 PM

 

02/Feb/23 5:44 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-71, OH-72, OH-73, OH-74

This feature allows the HR Admin to define different membership details of the employees which can be later  
used in the PIM Module. To add a membership, go to Admin>> Qualifications>> Membership and click  
“Add”, a screen as shown in Figure 4.1 would appear.  
  
Click “Save” once the field is added.  
  
A list of membership(s) as shown in Figure 4.2 would appear once a “Membership” is added. To view  
membership details, click on “Membership” name. You may also add multiple entries of memberships.  
  
To delete a membership, click on the check box next to the “Membership”” name. It is also possible to delete  
multiple entries at the same time by clicking the check box entries you wish to delete and simply clicking  
“Delete”.

19/Jan/23 4:04 PM

To Do

Admin Module for OrangeHRM

0|i0003r:

OrangeHRM

[OH-17](https://svtestjira2022.atlassian.net/browse/OH-17)

Languages

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:02 PM

 

02/Feb/23 5:26 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-67, OH-68, OH-69, OH-70

Different types of languages that employees in your company speak can be defined here and can be used in  
The PIM Module later. To add an entry, go to Admin>> Qualifications>>Languages and click “Add”, a  
screen as shown in Figure 3.9 would appear.  
  
Click “Save” once the field is added.  
  
A list of languages as shown in Figure 4.0 would appear once a “Language” type is added. You may also add  
multiple entries of languages.  
  
To delete language types click on the check box next to the “Language” name. It is also possible to delete  
multiple entries at the same time by clicking the check box entries you wish to delete and simply clicking  
“Delete”.

19/Jan/23 4:02 PM

To Do

Admin Module for OrangeHRM

0|i0003j:

OrangeHRM

[OH-16](https://svtestjira2022.atlassian.net/browse/OH-16)

Licenses

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 4:00 PM

 

02/Feb/23 5:07 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-65, OH-66

You can define various types of licenses which can be later used in the PIM Module. To add an entry go to  
Admin>> Qualifications>> Licenses and click “Add”, a screen as shown in Figure 3.7 would appear.  
  
Click “Save” once the field is added.  
  
A list of license type(s) as shown in Figure 3.8 would appear once a “License” type is added. You may also add  
multiple entries of licenses.  
  
To delete a license type click on the check box next to the “License” name. It is also possible to delete multiple  
entries at the same time by clicking the check box entries you wish to delete and simply clicking “Delete”.

19/Jan/23 4:00 PM

To Do

Admin Module for OrangeHRM

0|i0003b:

OrangeHRM

[OH-15](https://svtestjira2022.atlassian.net/browse/OH-15)

Education

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:59 PM

 

02/Feb/23 4:42 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-59, OH-60, OH-61, OH-62

You can define various types of educational qualifications which can be later used in the PIM Module. To add  
an entry select Admin>> Qualifications>> Education and click “Add”, a screen as shown in Figure 3.5  
would appear.  
  
Click “Save” once the field is added.  
  
A list of education as shown in Figure 3.6 would appear once an “Education” entry is added. You may also  
add multiple entries of skills.  
  
To delete education type click on the check box next to the “Education” name. It is also possible to delete  
multiple entries at the same time by clicking the check box entries you wish to delete and simply clicking  
“Delete”.

19/Jan/23 3:59 PM

To Do

Admin Module for OrangeHRM

0|i00033:

OrangeHRM

[OH-14](https://svtestjira2022.atlassian.net/browse/OH-14)

Skills

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:57 PM

 

02/Feb/23 4:11 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-55, OH-56, OH-57, OH-58

You can define various sets of skills which can be later used on the PIM Module. To add an entry go to  
Admin>> Qualifications>> Skills and click “Add” and a screen as shown in Figure 3.3 would appear.  
  
Click “Save” once the fields are added.  
  
A list of skill(s) as shown in Figure 3.4 would appear once a “Skill” is added. You may also add multiple  
entries of skills.  
  
To delete a skill click on the check box next to the “skill” name. It is also possible to delete multiple entries at  
the same time by clicking the check box entries you wish to delete and simply clicking “Delete”.

19/Jan/23 3:57 PM

To Do

Admin Module for OrangeHRM

0|i0002v:

OrangeHRM

[OH-13](https://svtestjira2022.atlassian.net/browse/OH-13)

Qualifications

Story

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:55 PM

05/Mar/23 11:59 AM

28/Jan/23 12:05 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

As a HR Admin, I want to define all information with regards to employees’ qualifications. The sub-menu  
consists of:  
  
● Skills  
● Education  
● Licenses  
● Languages

19/Jan/23 3:55 PM

To Do

Admin Module for OrangeHRM

0|i0002n:

OrangeHRM

[OH-12](https://svtestjira2022.atlassian.net/browse/OH-12)

Structure

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:45 PM

 

02/Feb/23 3:25 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-51, OH-52, OH-53, OH-54

This feature allows the admin to define the hierarchy of the company by defining sub units. Since the parent  
company is already defined in the General Information, it would automatically appear in the Company Structure screen.  
  
\*Note: You need to define the company name of the parent company before you create the Company  
Structure.  
  
To add a sub- unit to the company structure, go to Admin>> Organization>> Structure and click on \[+\] as  
shown in Figure 2.9 and the screen shown in Figure 3.0 would appear.  
  
\*Note: Company Structure may be defined according to the company’s specifications and hierarchy. When  
entering the fields, you need to specify if the sub-unit is a Department, Division or Team.  
  
Once you have entered the field, click “Save” and the Sub-Unit will appear as shown in Figure 3.1.  
  
You may also add further sub-units by clicking \[+\] option next to the relevant fields to indicate the hierarchy  
levels of the company and create a pyramidal structure of your organization as shown in Figure 3.2.  
  
To delete an entry, you can simply click “\[x\]” next to the relevant sub units. Click “Done” below the screen to  
save the information. You can also collapse/expand the sub-units by clicking on the (-) and (+) on the right hand side of the sub-units to further view the company structure hierarchy.

19/Jan/23 3:45 PM

To Do

Admin Module for OrangeHRM

0|i0002f:

OrangeHRM

[OH-11](https://svtestjira2022.atlassian.net/browse/OH-11)

Locations

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:38 PM

 

28/Jan/23 9:14 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-50

Basic details of the company can be entered on this screen. To start adding information, go to Admin>>  
Organization>> General Information and click “Edit”.  
  
Click “Save” once fields are entered as shown in Figure 2.6.

19/Jan/23 3:38 PM

To Do

Admin Module for OrangeHRM

0|i00027:

OrangeHRM

[OH-10](https://svtestjira2022.atlassian.net/browse/OH-10)

General Information

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:37 PM

 

28/Jan/23 8:59 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-49

Basic details of the company can be entered on this screen. To start adding information, go to Admin>>  
Organization>> General Information and click “Edit”.  
  
Click “Save” once fields are entered as shown in Figure 2.6.

19/Jan/23 3:37 PM

To Do

Admin Module for OrangeHRM

0|i0001z:

OrangeHRM

[OH-9](https://svtestjira2022.atlassian.net/browse/OH-9)

Organization

Story

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:34 PM

05/Mar/23 11:59 AM

28/Jan/23 12:05 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

As a HR Admin, I would like to add, save and delete all information about the organization, the structure and locations are defined here.

19/Jan/23 3:34 PM

To Do

Admin Module for OrangeHRM

0|i0001r:

OrangeHRM

[OH-8](https://svtestjira2022.atlassian.net/browse/OH-8)

Work Shifts

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:26 PM

 

28/Jan/23 8:20 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-45, OH-46, OH-47, OH-48

In this feature the HR Admin can define work shifts for an individual or a group of employees. To add an  
entry, go to Admin>> Job>> Work Shifts and click “Add” and a screen as shown in Figure 2.4 would appear.  
  
Click “Save” once the fields are added.  
  
You may assign employees to the particular shift by selecting the employee’s name from the “Available  
Employees” box and “Add” him/her to the “Assigned Employees” box.  
  
\*Note: An Employee list needs to be created first under the PIM Module before assigning employees to a  
particular work shift.  
  
A list of work shifts as shown in Figure 2.5 would appear once a “Work Shift” is added. To view Work Shift  
details, click on “Work Shift” name. You may also add multiple entries of work shifts.  
  
To delete a work shift click on the check box next to the “Work Shift”” name. It is also possible to delete  
multiple entries at the same time by clicking the check box entries you wish to delete and simply clicking  
“Delete”.

19/Jan/23 3:26 PM

To Do

Admin Module for OrangeHRM

0|i0001j:

OrangeHRM

[OH-7](https://svtestjira2022.atlassian.net/browse/OH-7)

Job Categories

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:23 PM

 

28/Jan/23 7:41 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-41, OH-42, OH-43, OH-44

This feature allows the HR Admin to create job categories specific to the company to aggregate job  
classifications.  
  
To add an entry, go to Admin>> Job>> Job Categories and click on “Add” and a screen as shown in Figure  
2.2 would appear.  
  
Click “Save” once the field is added.  
  
A list of Job Category as shown in Figure 2.3 would appear once a “Job Category” is added. To view Job  
Category details, click on “Job Category” name. You may also add multiple entries of Job Categories.  
  
To delete a Job Category click on the check box next to the “Job Category” name. It is also possible to delete  
multiple entries at the same time by clicking the check box entries you wish to delete and simply clicking  
“Delete”.

19/Jan/23 3:23 PM

To Do

Admin Module for OrangeHRM

0|i0001b:

OrangeHRM

[OH-6](https://svtestjira2022.atlassian.net/browse/OH-6)

Employment Status

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:18 PM

 

28/Jan/23 7:13 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-37, OH-38, OH-39, OH-40

Employment Status allows you to define the status of employment employees are hired for or if they are  
terminated. To add an entry, go to Admin>> Job>> Employment Status and click “Add” and a screen as  
shown in Figure 2.0 would appear.  
  
Click “Save” once the field is added.  
  
A list of Employment Status as shown in Figure 2.1 would appear once an Employment Status is added. To  
edit an employment status, click on the “Employment Status” name.  
  
To delete an Employment Status click on the check box next to the “Employment Status” name. It is also  
possible to delete multiple entries at the same time by clicking the check box entries you wish to delete and  
simply clicking “Delete”.

19/Jan/23 3:18 PM

To Do

Admin Module for OrangeHRM

0|i00013:

OrangeHRM

[OH-5](https://svtestjira2022.atlassian.net/browse/OH-5)

Pay Grade

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:16 PM

 

14/Feb/23 2:48 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-33, OH-34, OH-35, OH-36, OH-91, OH-92, OH-93, OH-94, OH-95, OH-107, OH-108

The HR Admin can define the pay grade by setting a minimum salary, maximum salary, step increase, and the  
currency to be paid in. To add an entry, go to Admin>>Job>> Pay Grades and click “Add” and a screen as  
shown in Figure 1.6 would appear.  
  
Click “Save” once the field is added.  
  
Once you click “Save” the screen in Figure 1.7 would appear and you can now define the currency and the  
minimum/maximum salary for each pay grade created. You can define the pay grade by clicking “Add” under  
“Assigned Currencies” and then providing the pay details under “Add Currency”. Click “Save” to save the  
currency for the Pay Grade.  
  
You can assign multiple currencies here and each currency defined will be listed as shown in Figure 1.8.  
  
You can edit details of a particular currency by clicking on the “Currency” name.  
  
All pay grades added will be listed as shown in figure in 1.9. To view Pay Grade details click on “Pay Grade  
name.  
  
To delete a Pay Grade click on the check box next to the “Pay Grade” name. It is also possible to delete  
multiple entries at the same time by clicking the check box entries you wish to delete and simply clicking  
“Delete”.

19/Jan/23 3:16 PM

To Do

Admin Module for OrangeHRM

0|i0000v:

OrangeHRM

[OH-4](https://svtestjira2022.atlassian.net/browse/OH-4)

Job Titles

Task

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:12 PM

 

05/Feb/23 11:56 AM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-30, OH-31, OH-32, OH-75

The job titles specific to the company can be defined in this option. To add an entry, go to Admin>> Job>>  
Job Titles and click “Add”. A screen as shown in Figure 1.4 would appear.  
  
Click “Save” once the fields are added.  
  
A list of job title(s) will appear as shown in Figure 1.5. You may also enter multiple job titles. You may view  
Job Title details by clicking on the name of the “Job Title”.  
  
To delete a Job Title click on the check box next to the Job Title name. It is also possible to delete multiple  
entries at the same time by clicking the check box entries you wish to delete and simply clicking “Delete”.

19/Jan/23 3:12 PM

To Do

Admin Module for OrangeHRM

0|i0000n:

OrangeHRM

[OH-3](https://svtestjira2022.atlassian.net/browse/OH-3)

Job

Story

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

19/Jan/23 3:08 PM

05/Mar/23 11:59 AM

28/Jan/23 3:49 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

As a HR Admin, I would like to add, save, view, edit and delete all job information. All job related information can be defined in this feature. The sub menu consists of the following items:  
  
● Job Titles  
● Pay Grades  
● Employment Status  
● Job Categories  
● Work Shifts

19/Jan/23 3:13 PM

To Do

Admin Module for OrangeHRM

0|i0000f:

OrangeHRM

[OH-2](https://svtestjira2022.atlassian.net/browse/OH-2)

User Management

Story

Backlog

Medium

_Unresolved_

robadi9664

robadi9664

robadi9664

18/Jan/23 7:50 PM

05/Mar/23 11:59 AM

09/Feb/23 1:28 PM

 

 

OrangeHRM Release 1

 

 

0

1

 

OH-76

As a HR Admin, I want to administer users by creating logins and defining privileges by assigning User Types (Admin or ESS).  
  
To add a system user, go to Admin>> User Management>> Users and click “Add”, a screen as shown in  
Figure 1.2 would appear.  
  
Click “Save” once the fields are added.  
  
\*Note: An employee list needs to be created first under the PIM Module to create user logins. Alternatively, a  
user login could be created when adding employees under the PIM Module (refer to Chapter 6.3.)  
  
To create a user login the following needs to be entered:  
  
● User Role: You can assign user roles for each user whether they would fall under as an “Admin” or  
“ESS” user type to define their user rights.  
  
● Admin: have access full access to the system.  
● ESS: limited access to the system. It could be an ESS-Supervisor or ESS-Employee.  
  
\# ESS-Supervisor: where the user has access to his/her particulars and his/her  
subordinates’ particulars.  
\# ESS-Employee: where the user has access only to his/her particulars.  
  
● Employee Name  
\*If an HR Admin is an existing employee, he/she needs to be defined in the PIM Module  
● Username  
● Status – Enabled or disabled  
● Password  
● Confirm Password (Re-enter the password)  
  
A list of user logins as shown in Figure 1.3 would appear once an entry is added. You may also add multiple  
entries of user logins. The default system user available will be Admin and has full access to the system.  
  
\*Note: System User Logins need to be communicated manually to employees.  
  
To delete a system user, click on the check box next to the “Username”. It is also possible to delete multiple  
entries at the same time by clicking the check box entries you wish to delete and simply clicking “Delete”.

19/Jan/23 3:13 PM

To Do

Admin Module for OrangeHRM

0|i00007:

Generated at Wed Mar 22 19:18:30 UTC 2023 by robadi9664 using Jira 1001.0.0-SNAPSHOT#100219-sha1:eb3f1fe6fc9588c9970f69b661232bd8cff92e79.