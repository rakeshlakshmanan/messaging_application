# Rock Messaging System

A Java-based instant messaging desktop application with user authentication, real-time chat functionality, and comprehensive profile management.

## Overview

**Rock** is a  instant messaging system built with Java Swing and MySQL. The application provides a complete messaging solution with user registration, authentication, chat management, and profile customization capabilities.

## Features

### User Management
- **User Registration**: Create new accounts with secure password confirmation
- **Login System**: Secure authentication with username and password
- **Password Recovery**: Multi-step password reset using security questions
- **Profile Management**: Update user details including name, email, phone number, and security questions
- **Account Deletion**: Permanent account removal with automatic chat cleanup

### Messaging Features
- **Real-time Messaging**: Send and receive text messages
- **Chat History**: View conversation history sorted by date and time
- **New Chat**: Search and initiate conversations with other users
- **Chat List**: View all active conversations sorted by most recent activity
- **Message Timestamps**: Track when messages were sent

### Security Features
- **Password Validation**: Real-time password matching verification
- **Security Questions**: 5 predefined security questions for account recovery
- **Username Uniqueness**: Automatic checking to prevent duplicate usernames
- **Data Validation**: Input validation across all forms

## Technology Stack

- **Language**: Java (Java SE)
- **GUI Framework**: Java Swing with NetBeans GUI Builder
- **Database**: MySQL
- **JDBC Driver**: MySQL Connector/J
- **Look and Feel**: Nimbus (cross-platform)

## Prerequisites

Before running this application, ensure you have:

- Java Development Kit (JDK) 8 or higher
- MySQL Server 5.7 or higher
- MySQL Connector/J (JDBC Driver)
- NetBeans IDE (optional, for development)



## Installation & Setup

### Option 1: Using NetBeans IDE

1. Clone the repository:
```bash
   git clone https://github.com/rakeshlakshmanan/messaging_application.git
```

2. Open NetBeans IDE

3. Go to `File > Open Project` and select the cloned directory

4. Right-click on the project and select `Clean and Build`

5. Run the `Welcome.java` file as the main entry point

### Option 2: Using Command Line

1. Clone the repository:
```bash
   git clone https://github.com/rakeshlakshmanan/messaging_application.git
   cd messaging_application
```

2. Add MySQL Connector/J to classpath and compile:
```bash
   javac -cp .:mysql-connector-java-x.x.xx.jar *.java
```

3. Run the application:
```bash
   java -cp .:mysql-connector-java-x.x.xx.jar Welcome
```

## Future Enhancements

- Implement password encryption
- Add prepared statements for SQL queries
- Include file/image sharing capability
- Add group chat functionality
- Implement online/offline status
- Add message read receipts
- Create mobile-responsive version
- Add emoji support
- Implement message search
- Add notification system
