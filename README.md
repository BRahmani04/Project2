# Project 02 | Project - Login Function

On this project I am  testing the Login form and make sure that it LOG IN when we give the right username and password,
while if we give a wrong information we get an message error that it tells us of what we are missing.

## How to set up the project
Before we running the project we need to make sure we have downloaded **Node.js**
For setting up the project  we need to creat a folder on our desktop which we need to open the **Terminal** in our desktop.
Then we creat the folder by running **mkdir** and our folder name.
After that we will need to install **Cypress** by using **npm install** and our dependecies get installed as well.
Then we go on our Visual Code and we open the folder that we have created, after we open the Terminal and we run **npx cypress open** this will open Cypress.


## TOOLS

The tools we are using in this project are **JAVASCRIPT**, **CYPRESS** and **TEST CASES**.

## Running the

First I created a folder called Pages that is where my POM - **LoginPage.js** is and it defines all the main Locators that we will be using on our testing file.
After I creat a folder for our test which is called **homework** and our file which is called **project02.cy.js**.

My project defines 10 Test Cases there are 6 Positives which are:

**1. Test Case 01 - Validate the login form**

**2. Test Case 02 - Validate the valid login**

**3. Test Case 03 - Validate the logout**

**4. Test Case 04 - Validate the Forgot Password? Link and Reset Password modal**

**5. Test Case 05 - Validate the Reset Password modal close button**

**6. Test Case 06 - Validate the Reset Password form submission**

And 4 Negative test cases which are: 

**1. Test Case 07 - Validate the invalid login with the empty credentials**

**2. Test Case 08 - Validate the invalid login with the wrong username**

**3. Test Case 09 - Validate the invalid login with the wrong password**

**4. Test Case 10 - Validate the invalid login with the wrong username and password**

When I am done with writing my test cases I start running the test by writing on my Terimanl **npx cypress run**, while if I want to run these tests in a browser I run **npx cypress open**.






