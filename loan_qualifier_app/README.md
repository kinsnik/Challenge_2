# **Loan Qualifier Application**

This purpose of this project is to develop an application that allows users to interact with the app to determine whether or not they are eligible for a loan and the details of the bank(s) that will allow them to take out a loan. 

This will efficiently and quickly allow users who are looking to take out a loan to identify if they qualify for at least one loan and how many loans they qualify for as well as their DTI and LTV ratios. 

---

## **Technologies**

This program is written in python and uses the following libraries: pathlib (specifically the Path function), csv, sys, fire and questionary. 

To run this application, there are multiple different functions running within the app some using modular programming to allow for an organized primary app. 
The modules that the app is dependent on is qualifier which contains the following sub-modules: 
* filters (which determine the user's loan eligibility based on their financials eg. credit score)
* utils (which in turn contains 1. calculators for financial ratios and 2. fileio, a file that handles file input)

---

## **Installation Guide**

1. First you would want to navigate to GitHub to the Challenge_2 repository and click on the green Code button which allows you to clone the repository. 
![<Green Code button in GitHub>](./GitHub_Code.png)
2. Once clicking on either SSH or HTTPS as a clone method, it automatically copies the link. You will then navigate to the Terminal or GitBash and type 
git clone (paste ssh/https for Challenge_2 repo) and run the command. 
![<SSH or HTTPS Option for Cloning Repo>](./GitHub_SSH_HTTPS.png)
3. Once complete, you can use the "git pull" command in Terminal or GitBash to pull the repository from the remote repository to a local directory of your choice. 
![<Git Pull Command>](./GitPull.png)
4. Now you should have access to the application (app.py) as well as other files within the repository upon which app.py depends for the functions. 

---

## **Usage**

1. Upon installing app.py and other files by pulling the repo, you would want to navigate to the Terminal or Git Bash and run the following command: 
python app.py
2. Follow the Command Line Interface prompts to enter the data requested: file path to the daily_rate_sheet, credit score, debt, income, loan amount and home value. 
![<Git Run Command and Prompts>](./RunCommand.png)
3. The app will calculate your debt-to-income ratio, your loan-to-value ratio, and the number of loans you qualify for, and then exit.

---

## **Contributors**

The author of this application is Kanika Sharma with Github username kinsnik, who also goes by Niki. She can be reached at ksharmaconnect3@gmail.com or on LinkedIn under Kanika Sharma: https://www.linkedin.com/in/kanika-sharma-aa28a6134/.

---

## **License**

Users have permissions to read this file, but not write or edit the code. The code within, if used, should be properly recognized and cited as the intellectual property of the author. 