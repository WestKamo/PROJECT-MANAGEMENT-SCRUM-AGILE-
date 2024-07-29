# CMPG-323-Overview--38924846
# Project Overview
This repository serves as the central hub for comprehensive planning accross all projects.
🚴‍♀️🚴‍♂️
# Repositories
1. CMPG-323-Overview-38924846  This repository will be used for project 1.
2. CMPG-323-Project 2-38924846 This repository will be used for project 2.
3. CMPG 323-Project 3-38924846 This repository will be used for Project 3.
4. CMPG 323-Project 4-38924846 This repository will be used for project 4.
5. CMPG 323-Project 3-38924846 This repository will be used for project 5.

# Documentation
This is the lean document [https://github.com/WestKamo/CMPG-323-Overview--38924846/blob/main/Lean%20Technical%20Documentation%20Template.docx](https://github.com/WestKamo/CMPG-323-Overview--38924846/blob/main/Lean%20Technical%20Documentation%20Template_38924846.docx)  
#Burndown Chart


# Branching Strategy Overview
1.	Main Branches:
Represents the production-ready state of the project. Code in this branch is thoroughly tested and ready for deployment to production environments.
2.	Development Branches:
Serves as the integration branch for ongoing development efforts. All feature branches merge into develop once their changes are completed and tested.
3.	Feature Branches:
Each feature or user story is developed in its own branch to isolate changes and facilitate parallel development.
Feature branches are merged into the develop branch via pull requests (PRs) after thorough testing and code review.
4.	Release Branches:
Created from develop to prepare for a new release. Final testing, bug fixes, and minor feature adjustments occur in the release branch.
Merged into both develop and main branches upon completion to deploy changes to production while maintaining ongoing development in develop.
5.	Hotfix Branches:
Address critical issues or bugs found in production (main branch) that require immediate resolution.
 Once fixes are validated, merged into both main and develop branches to ensure the fix is applied across current development efforts and production.

# .gitinore usage
The .gitignore file is a crucial component within each project's repository, serving to specify which files and directories Git should ignore when tracking changes and staging files for commits. Here's how the .gitignore file is utilized within each project .
Project 1:Analysis & Planning
1. In the analysis and planning phase, the .gitignore file ensures that sensitive or temporary files related to documentation tools (such as project management software exports, diagrams, and spreadsheets) are excluded from version control.
2. Project 2:Web API:In the Web API project, the .gitignore file excludes environment-specific configuration files, dependencies managed by package managers (like node_modules for Node.js projects), and log files that are not necessary for collaboration or deployment.
3. Project 3:Web App (Standards):For the Web App adhering to standards, the .gitignore file excludes compiled assets, build artifacts, and local development settings that vary between developers' environments.
4. Project 4 :In the RPA Testing project, the .gitignore file ensures that test data, logs generated during testing, and results from automated test runs are excluded from version control, focusing on code and scripts.
5. Project 5:Reporting:For the Reporting project, the .gitignore file excludes temporary files generated during report generation, cached data used for visualization, and files specific to reporting tools that do not need to be versioned.

# Securing credentials and sensitive information
1.  Avoid Hardcoding: Never embed credentials directly into code or configuration files to prevent accidental exposure.
2. Use Environment Variables: Store sensitive data like API keys and passwords in environment variables, ensuring they are set locally and in deployment environments.
3. Utilize Secrets Management Tools: Employ dedicated secrets management solutions (e.g., AWS Secrets Manager, Azure Key Vault) to securely store and manage sensitive information.
4. Encrypt Data at Rest: Apply strong encryption to sensitive files and data stored at rest to protect against unauthorized access.
5.  Monitor and Audit Access: Implement logging and monitoring mechanisms to track access to sensitive information and promptly detect any suspicious activity.
6.  Educate Team Members: Ensure all team members are trained in security best practices, emphasizing the importance of safeguarding credentials and sensitive data.
