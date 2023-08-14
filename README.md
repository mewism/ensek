# Intro
This repo holds the files created for the Ensek Test

# Test Plan Creation

I have created a Test Plan in the fromat of a mind map (very light weight). The Test Plan details my plan to target the 'Buy energy' web page (https://ensekautomationcandidatetest.azurewebsites.net/Energy/Buy)

The mindmap is a PDF and located in 'ensek/Test Plan'

# Test Plan Execution

An Exploratory Test Charter, with refernces TC1, has been created. It targets the 'Number of Units Required' field data validation. 

The document lists the actions completed during exploratory testing as well as a list of issues found while testing. 

Bug #1, a bug report, has been created to cover the core issue found while testing. 

Both documents are located in 'ensek/Test Execution'

# Rest APU Testing

Automated tests based of the swagger: https://qacandidatetest.ensek.io/ 

You can run these tests using two methods. You can use run the Postman suite from Postman or alternativly you can run from Git Bash using newman. 

To run from Git Bash:
1. Install Git Bash
2. Install Node.js on your machine.
3. Launch Git Bash and install Newman by running the following command in GitBash: npm install -g newman.
4. within Git Bash navigate to the directory where your Postman collection is saved.
5. Run the following command in GitBash: newman run <collection-name>.json

A bug report has been added covering the restful api testing.