# Final Project Template: Java Projects Overview

## General Instructions

### Project Management and Development Practices
- **Agile Board**: Utilize an agile board (e.g., Trello) to manage and track project tasks.
- **Version Control**: Use Git on GitHub for version control. Ensure to follow proper software development processes including branching and pull requests.
- **Code Reviews**: Implement code reviews before merging pull requests to ensure code quality and consistency.
- **Testing**: Write relevant test cases for your code and ensure they pass before code merges.
- **Linting**: Use a linting tool to maintain code quality and style consistency.
- **Deployment**: Deploy the application in a cloud environment (GCP or AWS).
- **Database**: Utilize PostgreSQL for data storage in the cloud environment, integrating via ORM libraries.
- **Authentication**: Implement secure API endpoints with authentication.
- **Role Distribution**: Optionally, distribute roles among team members (e.g., product manager, engineering lead) and consider rotating these roles to simulate real-world scenarios.

### Common Requirements for All Java Projects
1. **Authentication System**: Implement a registration and login page.
2. **Security**: Utilize security dependencies to enhance application safety.
3. **External API Integration**: Connect to an external service using a Java library.
4. **Testing**: Develop basic test classes.
5. **Database**: Use PostgreSQL for data storage.
6. **GitHub Features**: Utilize GitHub project management features.
7. **Version Control System**: Use GitHub for all code and documentation.
8. **Cloud Deployment**: Deploy the application to a cloud platform offering a free tier.

## Specific Project Details

### Java Project #1: Banking Application

#### Features & Capabilities
1. **Secure Authentication and Login**
   - Encrypt or hash passwords and PINs.
   - Implement email confirmation for login.
   - Limit login attempts and manage sessions securely.

2. **Account Management**
   - Display all accounts (active and inactive).
   - Check balances and transaction history.
   - Enable funds transfer and manage saved payments.
   - Implement multi-currency accounts and savings accounts with specific rules.

#### Bonus Features
- **Multi-Currency Accounts**: Allow users to open accounts in different currencies and transfer money between them.
- **Savings Account**: Enable users to open and manage savings accounts with visibility on compatible features.

### Java Project #2: Expense Management System

#### Objectives
- Streamline the process of managing employee expenses from submission to reimbursement.

#### Features & Capabilities
- Track and capture employee receipts.
- Centralize receipt management on a dashboard.
- Document and manage spending limits and company policies.
- Integrate with corporate credit cards and manage approvals.
- send reports and statistics via email.

#### Bonus Features
- **Expense Statistics**: Show daily expense statistics.
- **Category Filtering**: Allow filtering expenses by categories to identify cost-heavy areas.

### Java Project #3: Employee Management System

#### Objectives
- Manage employee details, time tracking, and leave management efficiently.

#### Features & Capabilities
1. **Company and Department Setup**
   - Create companies and departments with initial setup of supervisors.

2. **Employee Registration and Profile Management**
   - Manage new employee additions, department assignments, and profile setups.

3. **Time & Attendance Management**
   - Facilitate employee check-ins and track attendance.

#### Bonus Features
- **Leave Management**: Implement a system for managing and approving leave requests.
- **Meeting Scheduling**: Integrate with Google Calendar API to schedule meetings with various configurations.

### Submission Requirements
- **Code Repository**: Provide a link to the GitHub repository.
- **Live Demo**: Deploy the application and provide access to the live demo.
- **Documentation**: Include a README file with setup instructions, features, and any other relevant information.

### Evaluation Criteria
- **Functionality**: How well does the application work?
- **Code Quality**: Is the code clean, well-organized, and properly commented?
- **User Experience**: Is the application easy to use and visually appealing?
- **Creativity and Innovation**: How creative and innovative are the features implemented?

This template provides a structured approach to developing Java-based applications with specific features and capabilities, ensuring students are exposed to real-world software development practices.
