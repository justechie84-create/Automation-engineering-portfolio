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
https://private-user-images.githubusercontent.com/294649413/619975306-8c30be2b-e071-4774-a85c-dff900c11f9f.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODM2ODI5NzAsIm5iZiI6MTc4MzY4MjY3MCwicGF0aCI6Ii8yOTQ2NDk0MTMvNjE5OTc1MzA2LThjMzBiZTJiLWUwNzEtNDc3NC1hODVjLWRmZjkwMGMxMWY5Zi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNzEwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDcxMFQxMTI0MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1lNmQwYmY2YzJlYWFiOGY0NTM1ZGI2NWI1OGNlMmMxZTE0ZTk3ZjBiNmVjN2IxOGI4NzNhZTcxZjVlZDBhNzg5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.cTQvDuwxPX1Y6d804RducTrMUHkiZzw_AkQ--82JQr0

### Confirmation Email

![Confirmation Email](images/confirmation-email.png)

---

### Google Sheets Ticket Database
https://private-user-images.githubusercontent.com/294649413/619980196-24268219-c30c-417e-ae81-90f772d24f75.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODM2ODMwOTUsIm5iZiI6MTc4MzY4Mjc5NSwicGF0aCI6Ii8yOTQ2NDk0MTMvNjE5OTgwMTk2LTI0MjY4MjE5LWMzMGMtNDE3ZS1hZTgxLTkwZjc3MmQyNGY3NS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwNzEwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDcxMFQxMTI2MzVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yNzk5YTFhZDdhOTk3MTdkYzM1Mzg0NmIyMmU1NzBlODlmNjM0OGU0NWY5ZGIwZGI5MDIzZDcxZTExNDIzYjM1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.q3Vw-j4JHHvpLEvzcJTYjDmwxr-02rpeIYEBgnf09pc

---

### Telegram Notification

![Telegram Notification](images/telegram-notification.png)

---

## Lessons Learned

This project strengthened my understanding of event-driven automation and demonstrated how workflow automation can reduce repetitive tasks while improving customer support operations.
