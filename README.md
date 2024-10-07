## **Project Overview**

This project demonstrates a web application deployed on an AWS EC2 instance. The application provides user registration, login, and profile features. Additionally, it implements extra credit functionality for file upload, word count calculation, and persistent storage of user data.

### **Key Features**

**User Registration:**
Captures username, password, first name, last name, and email.
Stores user information securely in a SQLite3 database.

**Login:**
Authenticates users based on their username and password.

**Profile:**
Displays the user's registered information (username, first name, last name, and email).
For users who have uploaded files, it displays the word count and provides a download link.

**File Upload (Extra Credit):**
Allows users to upload text files.
Stores uploaded files securely on the EC2 instance.
Calculates and displays the word count of the uploaded file.
Preserves uploaded file information across login sessions.

**Technologies Used**

AWS EC2: Elastic Compute Cloud instance for hosting the application.
Amazon Ubuntu: Operating system for the EC2 instance.
Apache: Web server for serving the application.
mod_wsgi: Gateway interface for integrating Python applications with Apache.
Python 3: Programming language for the Flask application.
Flask: Python web framework.
SQLite3: Database for storing user information and file metadata.
Werkzeug: Library for secure file uploads.
pandas: Library for text processing (used for word count calculation).
