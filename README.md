# Project Title
Enhanced_Mortgage_Loan_Process

# Executive Summary
The enhancements are done in the exisiting Mortgage Application Process designed in KIE- Drools. This project implementation using workshop exercises provides a very good insight of the power of KIE tools.
Implemented the following assets through the project:
1. Business Process Definition Asset
2. Checked the Mortage eligibility of the applicant using Guided Decision Tables
3. Automated the limit check process of the application by using Guided Rule Asset
4. Defined the Machine Reasoning Rules of checking eligibility in Guided Decision Tables
5. Created Users and assigned them to different groups based on roles

# User Guide
[ 1 ] Run the system using iss-vm
-Download pre-built virtual machine from http://bit.ly/iss-vm
-start iss-vm
-Launch KIE 7.12 via the shortcut "Tool KIE 7.12"
-After startup is complete, launch Google Chrome and click on the "KIE WB" shortcut
-Login using role "wbadmin"
-Create New Workspace
-Import Project from Github link
-Name the Project and click OK
-Deploy Project

[ 2 ] Run the system in local machine:
-Download jBPM Server 7.12.0 from https://download.jboss.org/jbpm/release/7.12.0.Final/jbpm-server-7.12.0.Final-dist.zip
-Download and unzip it.
-On Linux/Mac, run jbpm-server-7.12.0.Final-dist/bin/standalone.sh
-On Windows, run jbpm-server-7.12.0.Final-dist/bin/standalone.bat
-Open browser and go to http://localhost:8080/jbpm-console/kie-wb.jsp
-Login using role "wbadmin"
-Create New Workspace
-Import Project from Github link
-Name the Project and click OK
-Deploy Project


