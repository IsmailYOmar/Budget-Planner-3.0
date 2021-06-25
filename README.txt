--------------Budget Planner application version 3.0--------------
------------------------------------------------------------------
-  Installation Readme for Budget Planner application version 3.0.

-  Refer to the system requirements for the operating systems
   supported by the Budget Planner application.
-  Refer to the user manual for direction on how to use the
   application.
------------------------------------------------------------------
------------------------------------------------------------------
-  CONTENTS OF THIS DOCUMENT
------------------------------------------------------------------

This document contains the following sections:

1.  Overview
2.  System Requirements
3.  Installing the Software
4.  Changes made in version 2.0 based on version 1.0 feedback
5.  Changes made in version 3.0 based on version 2.0 feedback
6.  New features and other changes
7.  Link to git repo

------------------------------------------------------------------
------------------------------------------------------------------
- 1.  OVERVIEW
------------------------------------------------------------------
The above program is a C# wpf application. This personal budget 
planning application allows a user to calculate their estimated monthly 
excess income with the hope of helping user understand their financial 
situation better and budget properly.

------------------------------------------------------------------
------------------------------------------------------------------
- 2.  SYSTEM REQUIREMENTS
------------------------------------------------------------------

-The system must be running following operating system:
    
	-Microsoft Windows 7
	-Microsoft Windows 8
	-Microsoft Windows 10

-The additional software is required: 
 	
	-Microsoft Visual Studio Community 2019 Version 16.9.4
	-Microsoft.NET Framework Version 4.8.04084 

------------------------------------------------------------------
------------------------------------------------------------------
- 3.  INSTALLING THE SOFTWARE
------------------------------------------------------------------

1. Unzipp the [Ismail Yusuf Omar 19331746_PROG 2A POE] folder
    Right click on folder and then select extract all

2. There are 2 options to run the code:
	Option 1:
	 -Open [PROG2A_POE_Ismail_Yusuf_Omar_19331746] folder
	 -Select [PROG2A_POE_Ismail_Yusuf_Omar_19331746.sln] 
	  file with Microsoft Visual Studio
	 -Run the program by clicking run or pressing F5

	Option 2:
	 -Open [exe file] folder
	 -Select [PROG2A_POE_Ismail_Yusuf_Omar_19331746.exe]

3. Run Code 

------------------------------------------------------------------
------------------------------------------------------------------
- 4.  Changes made in version 2.0 based on version 1.0 feedback
------------------------------------------------------------------

-Coding Standard adjusted to the same naming format 
-Main method has been cleaned up making it easier to read
-All classes are now in separate files
-Added validation through out the program 
	- validation for zeros
	- validation for negative values
	- validation for null inputs and special charcters
	- deposit amount can no longer be larger than the 
	  purchase price 
	- Tax amount can no longer be larger than gross income 
	- validation for percentage amounts (interest rate) now only 
	  allows 0 to 100
-Get and and Set methods impelmented for all user inputs  
-Code no longer exits input a value other than 1 or 2 when choosing
 to buy or rent
-Buying terms implemented when buying property 
-User now has the option to enter a new property if loan is unlikely

------------------------------------------------------------------
------------------------------------------------------------------
- 5.  Changes made in version 3.0 based on version 1.0 feedback
------------------------------------------------------------------

-I recived 100% for Task 2 and have not been given feedback as of
 writting this README (23/06/21 10pm)   
- Other changes made
	- Rent and Home loan now have different keys in dictonary
	  allowing the user to know exactly which option they 
	  selected.
	- Class Expenses no longer inherits abstarct methods from
	  abstract class due to needing to use INotifyPropertyChanged
	  class ObservableObject.
	- Home Loan claculated in Property Class
	- Program can not move to next page if there is a validation
	  error
------------------------------------------------------------------
------------------------------------------------------------------
6.  New features and other changes
------------------------------------------------------------------

-Option to save up a specified amount by a certain date 
-Program is now a wpf application to be more user friendly  
-WPF uses MVVM design pattern.
-UI design has optional Lght Mode and Dark Mode Themes  
-.exe File created to make it easier to run 

------------------------------------------------------------------
------------------------------------------------------------------
7. Link to git repo
------------------------------------------------------------------

https://github.com/IsmailYOmar/Budget-Planner-3.0.git

------------------------------------------------------------------
------------------------------------------------------------------
