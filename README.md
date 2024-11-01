# Contacts Management - Frontend

## Project Overview
This is the frontend for a contact management application, designed to provide a user-friendly interface for adding, viewing, updating, and deleting contacts. The frontend communicates with the backend API to perform CRUD operations on contact data stored in the server.

## Folder Structure
readme.md
scr code.html
codestyle.md

## Features
- **Add Contact**: Fill out a form to add a new contact with details like name, phone, email, group, company, and position.
- **View Contacts**: View all saved contacts in a structured list format.
- **Edit Contact**: Update existing contact details directly from the list.
- **Delete Contact**: Remove contacts from the list with a simple button click.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
Open contacts.html in a web browser.
Usage
After opening contacts.html in a web browser, you can interact with the application by adding new contacts, viewing existing contacts, editing, or deleting them.
API Communication
The frontend communicates with the backend API using fetch requests:

POST /contacts: To add a new contact.
GET /contacts: To retrieve all contacts.
PUT /contacts/{id}: To update a contact by ID.
DELETE /contacts/{id}: To delete a contact by ID.
Code Standards
The frontend code follows coding standards described in codestyle.md, including conventions for HTML, CSS, and JavaScript.
