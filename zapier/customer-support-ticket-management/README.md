# 📧 Customer Support Ticket Management System

## Overview

This project automates the customer support ticket intake process using **Zapier**, **Gmail**, **Google Sheets**, and **Telegram**.

When a customer sends a support request via email, the workflow automatically acknowledges the request, logs it into a ticket database, assigns a Ticket ID and priority, and notifies the support team through Telegram.

This eliminates repetitive manual tasks and improves response time.

---

## Business Problem

Many organizations receive hundreds of customer support emails daily. Manually acknowledging requests, creating tickets, and notifying support staff is repetitive, time-consuming, and prone to human error.

This automation ensures every support request is tracked consistently and responded to immediately.

---

## Solution

The workflow automatically:

- Detects new support request emails.
- Sends an acknowledgement email to the customer.
- Logs the ticket in Google Sheets.
- Assigns a Ticket ID.
- Sets the ticket priority.
- Notifies the support team via Telegram.

---

## Workflow

Customer Email

↓

Gmail Trigger

↓

Send Confirmation Email

↓

Create Google Sheets Row

↓

Update Ticket ID

↓

Telegram Notification

---

## Technologies Used

- Zapier
- Gmail
- Google Sheets
- Telegram Bot
- Google Workspace

---

## Features

- Automatic acknowledgement email
- Ticket database creation
- Automatic Ticket ID generation
- Priority assignment
- Telegram notification
- Centralized ticket tracking

---

## Business Value

This solution helps organizations:

- Reduce manual administrative work
- Improve customer response time
- Maintain an organized ticket database
- Increase support team visibility
- Build the foundation for intelligent ticket routing

---

## Future Improvements

### Version 2

- AI-based priority classification
- Automatic team assignment
- Customer location detection
- Sentiment analysis
- SLA monitoring
- Dashboard reporting

---

## Skills Demonstrated

- Workflow Automation
- Business Process Design
- Google Workspace Automation
- Event-Driven Automation
- Data Management
- Notification Systems
- Process Optimization

---

## Screenshots

The `/images` folder contains:

- Workflow
- Confirmation Email
- Google Sheet
- Telegram Notification

## Screenshots

### Workflow
<img width="546" height="475" alt="image" src="https://github.com/user-attachments/assets/a031decd-7bf3-45e9-99cb-544b6b13f2d6" />


### Confirmation Email

![Confirmation Email](images/confirmation-email.png)

---

### Google Sheets Ticket Database

![Google Sheet](images/google-sheet.png)

---

### Telegram Notification

![Telegram Notification](images/telegram-notification.png)

---

## Lessons Learned

This project strengthened my understanding of event-driven automation and demonstrated how workflow automation can reduce repetitive tasks while improving customer support operations.
