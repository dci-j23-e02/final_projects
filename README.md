# Final Project Template for Java Projects

## Overview

This template is designed to guide students through the development of a Java-based application as their final project. The project will incorporate essential software development practices such as using an agile methodology, version control, continuous integration, and deployment to a cloud environment.

## Project Requirements

### Common Requirements

- **Authentication and Authorization**: Implement a registration and login page using secure practices.
- **Security**: Utilize a security framework or library to enhance application security.
- **Currency Conversion**: Integrate with the `currency-converter-api` to provide currency exchange services.
- **Testing**: Develop basic test classes to ensure functionality works as expected.
- **Database**: Use PostgreSQL for data storage.
- **Project Management**: Utilize GitHub for version control and project management (issues, PRs, projects).
- **Deployment**: Deploy the application to a cloud provider that offers a free tier (e.g., AWS, GCP).

### Specific Project Details

#### 1. Banking Application

##### Features & Capabilities

- **Secure Authentication and Login**
  - Encrypt or hash passwords and PINs.
  - Implement email confirmation for login.
  - Limit login attempts and manage sessions securely.

- **Account Management**
  - Display all user accounts (active/inactive).
  - Check balances and display transaction history.
  - Enable funds transfer and manage saved/quick payments.

##### Bonus Features

- **Multi-Currency Accounts**: Allow users to open accounts in different currencies and transfer money between them using the currency exchange service.
- **Savings Account**: Implement features specific to savings accounts like blocked transactions.

#### 2. Expense Management System

##### Objectives

- Streamline the process of managing employee expenses from submission to reimbursement.

##### Features & Capabilities

- **Receipt Tracking**: Allow employees to upload receipts via smartphones.
- **Spending Policies**: Document and manage spending limits and company policies.
- **Approvals**: Route receipts for approval and manage the approval process.

##### Bonus Features

- **Expense Statistics**: Display statistics of expenses per day.
- **Expense Filtering**: Enable filtering of expenses by category.

#### 3. Employee Management System

##### Objectives

- Manage employee details, time tracking, and leave management efficiently.

##### Features & Capabilities

- **Company and Department Setup**: Allow creation of companies and departments with initial setup of employees.
- **Employee Registration and Profile Management**: Manage new employee registration, department assignment, and profile setup.
- **Time and Attendance**: Implement check-in/check-out functionality and manage attendance records.

##### Bonus Features

- **Leave Management**: Implement a system for employees to request leaves and for supervisors to approve or reject these requests.
- **Meeting Scheduling**: Integrate with Google Calendar API to schedule meetings with various configurations.

## Development Process

1. **Project Setup**: Set up the project repository on GitHub. Initialize with README, .gitignore, and basic project structure.
2. **Task Management**: Create tasks in GitHub Projects or Trello. Organize tasks into sprints.
3. **Development**: Follow the feature-branch workflow. Each new feature should be developed in a separate branch.
4. **Code Review**: Use pull requests for code review. Merge features into the main branch after approval.
5. **Testing**: Write unit and integration tests for each feature. Use a CI tool to automate testing.
6. **Deployment**: Set up continuous deployment to a cloud service. Ensure the application is deployed securely and is accessible.
7. **Documentation**: Document the setup process, how to run the application, and any usage instructions.

## Evaluation Criteria

- **Functionality**: Does the application perform the tasks it is supposed to?
- **Code Quality**: Is the code clean, well-organized, and properly commented?
- **Use of Technologies**: Are the required technologies and frameworks used appropriately?
- **Security Practices**: Are security best practices followed?
- **Testing and Deployment**: Is the application well-tested and deployed successfully?

This template provides a structured approach to developing a robust Java application, incorporating modern development practices and tools.
