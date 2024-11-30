# DoxMail: Temporary Anonymous Email Service

DoxMail is a lightweight and fully anonymous temporary email service that allows users to generate disposable inboxes without any registration. This service enables easy handling of one-time emails, secure browsing, and quick retrieval of messages without compromising your privacy.

---

## Features

- **Anonymous Email Generation**: Create a temporary inbox with a single click.
- **Automatic Email Retrieval**: Inbox auto-refreshes every 10 seconds to fetch new messages.
- **Email Viewing and Attachments**: View the details of received emails, including attachments.
- **User-Friendly Interface**: Simple controls to generate, refresh, and navigate emails.
- **Temporary Nature**: Disposable inbox designed for short-term use.

---

## Table of Contents

1. [How to Use](#how-to-use)
2. [Technical Overview](#technical-overview)
3. [Requirements](#requirements)
4. [Disclaimer](#disclaimer)

---

## How to Use

1. **Generate an Email**: 
   - Open the app and click the `Generate` button to create a random temporary email address.
   - The generated email address will appear in the input field.

2. **Check for Messages**:
   - Click `Refresh` or wait for auto-refresh (every 10 seconds) to fetch incoming messages.

3. **View Messages**:
   - Messages in the inbox will be displayed in the list. Click a message to open and view its content.

4. **Attachments**:
   - If a message includes attachments, links to download the files will appear.

5. **Navigate**:
   - Use the `Back` button to return to the inbox from a specific email.

---

## Technical Overview

### Frontend
- **HTML/CSS**: Structure and styling of the interface.
- **JavaScript (jQuery)**: Core functionality for handling events, fetching emails, and dynamic UI updates.

### Backend API
DoxMail uses the [1secmail API](https://www.1secmail.com) to:
- Generate random mailbox addresses.
- Fetch message lists.
- Read individual messages and download attachments.

### Key Features
- **Email Generation**: Generates a random email address using the API.
- **Inbox Refresh**: Pulls messages from the server.
- **Message Viewing**: Fetches and displays email content, including sender details, subject, and body.

---

## Requirements

To use or host the service:
- **Web Browser**: Modern browser with JavaScript enabled.
- **Dependencies**:
  - jQuery (`https://code.jquery.com/jquery-3.6.0.min.js`)

Optional for hosting:
- Internet connection to access the 1secmail API.

---

## Disclaimer

- **Temporary Use Only**: This service is intended for temporary email use. We are not liable for any locked accounts or misuse.
- **No Storage Guarantee**: Emails are not permanently stored and may be deleted after a short duration.
- **Security**: This service does not encrypt messages. Avoid using it for sensitive or private communications.

---

Enjoy the simplicity and privacy of DoxMail!
