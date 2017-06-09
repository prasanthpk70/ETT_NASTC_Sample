# ETT_NASTC_Sample
Introduction:

About the verification of NASTC members for ETT using NASTC API and NASTC Web Client

Requirements:

OS: Windows 7 or Higher
IDE: Visual Studio 2013
Core Framework: Dot.Net
Database: SQL Server 2014

NASTC API Client:

This is the API client we used to communicate with Database for reading the NASTC Member details.
From Web client requests will be posting to API client and then API client will sned back the results whether entered 
member details are correct or not.

NASTC Web Client:

This is Web Client that will have a screen to input the membership details. 
Data entered here will be forwarded to API Client and get back the results whether entered meber exists or not

Configuration:

We had database file in App Data folder. Please add it to your SQL Server and follow the below steps to run the projects.

First run the API project and then run the Web client project.

1.NASTC.Web.API
2.NASTC.Web.Client 

Second you can able to see a Page named "NASTC Member Verification" when you run NASTC.Web.Client project
In that page enter the below listed test data to check the memeber verification process.

