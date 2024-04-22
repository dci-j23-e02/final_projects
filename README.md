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
- **Meeting Scheduling**: Integrate with Calendar API to schedule meetings with various configurations.



### Java Project #4: E-Commerce Platform

#### Objectives
- Develop a comprehensive platform for online shopping, allowing users to browse, search, and purchase products.

#### Features & Capabilities
1. **User Account Management**
   - Registration, login, and user profile management.
   - Password recovery and user authentication.

2. **Product Management**
   - Add, edit, and remove products.
   - Categorize products and manage inventory levels.

3. **Shopping Cart and Checkout System**
   - Implement a shopping cart where users can add or remove products.
   - Secure checkout process including payment integration.

4. **Order Management**
   - Track order status from placement to delivery.
   - Allow users to view their order history and track shipments.

#### Bonus Features
- **Product Recommendations**: Implement an algorithm to suggest products based on user behavior and preferences.
- **Dynamic Pricing**: Use market and user data to adjust product prices in real-time.

### Java Project #5: Social Media Dashboard

#### Objectives
- Create a dashboard to monitor and manage multiple social media accounts from a single interface.

#### Features & Capabilities
1. **Account Integration**
   - Connect multiple social media platforms (e.g., Twitter, Facebook, Instagram).
   - Authenticate and manage access permissions.

2. **Post Management**
   - Create, schedule, and publish posts across different platforms.
   - Edit and delete existing posts.

3. **Analytics and Reporting**
   - Generate reports on engagement metrics such as likes, shares, and comments.
   - Visualize data through charts and graphs for better insight.

#### Bonus Features
- **Sentiment Analysis**: Analyze the sentiment of comments and posts to gauge public opinion.
- **Automated Responses**: Set up automated responses for common inquiries or comments.

### Java Project #6: E-HealthCare Management System

#### Objectives
- Develop a web-based application to facilitate virtual healthcare services, enabling doctors to consult with patients remotely and manage medical prescriptions online.

#### Features & Capabilities
1. **User Account Management**
   - Separate registration and login modules for doctors and patients.
   - Profile management for storing medical history and contact information.

2. **Appointment Scheduling**
   - Patients can book appointments with available doctors.
   - Doctors can view and manage their appointment schedules.

3. **Virtual Consultations**
   - Implement a secure video conferencing feature for virtual doctor-patient interactions.
   - Chat functionality for communication without video.

4. **Prescription Management**
   - Doctors can create, send, and manage prescriptions digitally.
   - Patients can view and download their prescriptions.

5. **Medical Records Management**
   - Secure storage and management of patient medical records.
   - Access controls to ensure patient confidentiality and data security.

#### Bonus Features
- **Health Monitoring Tools**: Implement basic health monitoring tools that allow patients to input daily health metrics such as temperature, blood pressure, and symptoms. These inputs can be tracked over time and viewed by both the patient and their doctor to monitor health trends without the need for advanced AI integration.
- **Health Tips and Notifications**: Provide health tips and send notifications for follow-up appointments or medication reminders.

### Submission Requirements
- **Code Repository**: Provide a link to the GitHub repository.
- **Unit Testing**: Ensure that all critical functionalities of the application are covered by unit tests. Provide documentation on how to run these tests and include test results in your submission.
- **Live Demo**: Deploy the application and provide access to the live demo.
- **Documentation**: Include a README file with setup instructions, features, and any other relevant information.

### Evaluation Criteria
- **Functionality**: How effectively does the application facilitate services?
- **Code Quality**: Is the code clean, efficient, and well-organized?
- **User Experience**: Is the application easy to navigate and use for the users ?
- **Security and Privacy**: How well does the application protect user data and ensure privacy?
- **Creativity and Innovation**: How creative and innovative are the solutions implemented to address the project challenges and the features implemented?


This template provides a structured approach to developing Java-based applications with specific features and capabilities, ensuring students are exposed to real-world software development practices.
