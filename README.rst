==============
A Student's Phonebook
==============
As we all know, smartphones have became very important over the years and it's hard to find someone without one. With that being said, learning how to use one can be challenging for first timers.
A Student's Phonebook is a program that will help you put your contacts into a smartphone.

James
-----------------------


Details
-----------------------
James is a full time student at CUNY SPS. Is 40 years old and pursuing his bachelor degree with information systems. He's ready to enter the workforce.

Goals
-----------------------
To learn how use his smartphone  so when it's time to graduate James can start looking for a job immediately.


Problem Scenario: How to Program Contacts into a Smartphone.
-----------------------
James just got his first smartphone, before that he was using his home  phone to communicate with potential employers. 
However, putting his contacts into the smartphone has been diffcult for him.

Current Alternatives
-----------------------
James calls the manufacturer but no one answers

Value Proposition
-----------------------
The purpose of creating a module is to allow James to have access to his contacts. 
The menu will have the person's name and number set up for James so he can add, display, remove, and search for them  with ease.

User Stories
============

James' Phonebook
------------
As a future employee, I want to be able to reach people at anytime and also be available for them as well. 
I also want to be able to search my phone and see all the contacts I put into it right away.

Acceptance Stories
-----------------

Scenario 1: Entering a new contact
----------------------------------

::

| Given that I have a new contact
| And I need to enter new contact info in my phone book,
| When I choose Option 2, 
| Then I will get a prompt asking me to enter the contact information,
| And  I will add the person's first name and telephone number.


Scenario 2: Remove a Phone Number
----------------------------------

::

| Given that I don't need this number anymore,
| And need to remove the contact info from my phone book,
| When I choose Option 3, 
| Then the contact will be deleted,
| And I will get a statement saying that my contact has been deleted.

Scenario 3: Displaying all contacts
-----------------------------------

::

| Given that I want to view all contacts,
| And I need to see who is in my phone book,
| When I choose Option 1, 
| Then I will get a prompt displaying all contact information,
| And I will be able to view all contact info

Scenario 4: Searching for an existing contact
-------------------------------------------------

::

| Given that I have to search for an existing contact
| And I need to enter new contact info in my phone book,
| When I choose Option 4, 
| Then I will get a prompt asking me to enter the contact first name,
| And my phone book will retrieve my contact.

Scenario 5: Quitting the Program
---------------------------------
::

| Given that I am done using the phonebook
| When I choose Option 5, 
| Then I will be able to quit the program
