# mail-sender_using_springboot
By using this you are able to send emails

This is a simple Mail Sender application built using Spring Boot. It allows users to send emails through a user-friendly web interface. The application utilizes the JavaMail API to send emails and is implemented as a Spring Boot RESTful service.

Features
Send emails with attachments to one or multiple recipients.
Supports text-based and HTML-based email content.
User-friendly web interface for composing and sending emails.
Email history and status tracking for sent emails.
Getting Started
Prerequisites
Before running this application, make sure you have the following installed:

Java Development Kit (JDK) 8 or higher
Apache Maven

API Endpoints
The application exposes the following REST API endpoints:

POST /api/sendMail: Send an email with the given parameters.
You can use these API endpoints directly for integrating the Mail Sender functionality into your applications.

Troubleshooting
If you encounter any issues, check the console output for error messages.
Ensure the database connection properties in application.properties are correctly configured.
