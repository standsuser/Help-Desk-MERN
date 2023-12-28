# Helpdesk MERN Application

## Overview

This project is a comprehensive Helpdesk software application developed using the MERN stack (MongoDB, Express.js, React, Node.js). The application aims to enhance the support and ticketing process, facilitate communication between support agents and users, and offer a robust knowledge base for swift issue resolution.

## Technologies Used

- MongoDB
- Express.js
- React
- Node.js
- Socket.io
- JWT Authentication
  
## Features

### 1. User Management
- **User Authentication and Role-Based Access Control**: Secure login system with JWT-based authentication. Administrators can create and manage user roles.
- **User Profile Management**: Users can update their profile details.

### 2. Ticketing System
- **Create, Update, and Close Support Tickets**: Users can submit new tickets, and support agents can update and resolve them.
- **Categorization and Prioritization**: Tickets are categorized into Software, Hardware, and Network issues. Each category has its priority.

### 3. Knowledge Base
- **Organized Repository of FAQs**: Accessible and organized Knowledge Base with solutions to common problems.
- **Search Functionality**: Users can search the Knowledge Base for immediate solutions.

### 4. Communication Tools
- **Integrated Email and Notification System**: Email notifications for ticket updates.
- **Real-Time Chat**: Real-time chat feature using Socket.io for immediate assistance.

### 5. Reporting and Analytics
- **Generate Reports**: Managers can create reports on ticket status, resolution time, and agent performance.
- **Analytics**: Identification of common issues and trends.

### 6. Automation and Workflows
- **Automated Repetitive Tasks**: Automated workflows for specific issue types.

### 7. Customization and Branding
- **Customize Look and Feel**: Administrators can customize the application's appearance.

### 8. Security and Data Protection
- **Security Measures**: Encryption/decryption for data protection.
- **Data Backup**: Automated backups using `mongodump`.

---

For any queries or feedback, please contact mariamalmotawally@gmail.com

---
Detailed demonstration of the frontend:
---
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/ca5b28a3-132d-405b-8b2b-9b508037397d)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/0c18adb7-f87c-41d7-961a-76c65480b7eb)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/8ed483f1-4f0f-4b38-974d-57a5be79d4e7)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/faa7994f-6b04-47f9-9322-986e763b0989)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/664a5353-275a-4cb5-b73b-e960f5520424)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/32f65457-71f7-4d31-a7ba-b30e48d0858c)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/76e51adb-bff3-4bf0-9ef3-eed1229a54ba)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/587aef1b-a2f9-45e6-b7a9-9a0d47d79e90)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/af4a90a3-6b72-4c10-a08c-1c40797abb1a)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/3dc92b95-27b1-4c6e-ae29-58c28b865cca)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/83bc962d-3fcf-4457-a0eb-8ebe00f01443)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/383d5d9c-ae51-4774-939f-16c1286b311e)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/007f3b6e-5c19-415c-94e0-a244bfd060fd)
![image](https://github.com/standsuser/Help-Desk-MERN/assets/34959945/a419c3ef-a5dc-4c16-aac6-d341dc0181d1)

## Environment Variables

### Backend (.env)

- `MONGODB_URI`
- `PORT`
- `REACT_APP_API_BASE_URL`
- `NODE_ENV`
- `DB_URL`
- `ORIGIN`
- `Hash_Security_Key`
- `MAIL_ADD`
- `MAIL_PASS`
- `JWT_SECRET`
- `CLIENT_URL`

### Frontend (.env)

- `PORT`: Ensure to set a different port than the backend.

## Usage

Follow these steps to run the project:

1. **Backend Setup**
   ```bash
   cd Backend
   npm start
   ```

2. **Frontend Setup**
   ```bash
   cd Frontend
   npm start
   ```

3. **Machine Learning Model for Ticket Assignment to Agents**
   ```bash
   cd Backend
   cd python
   python app.py
   ```



