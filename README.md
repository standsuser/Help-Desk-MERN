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
- 
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

3. **Machine Learning Model**
   ```bash
   cd Backend
   cd python
   python app.py
   ```


---

For any queries or feedback, please contact mariamalmotawally@gmail.com

---

**Note**: Ensure to set up the necessary environment variables and configurations as specified in the project documentation.

---
For a detailed demonstration of the frontend, refer to the images provided

