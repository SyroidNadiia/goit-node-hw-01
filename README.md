# Contacts CLI App

This is a command-line application for managing contacts. It allows you to perform various actions such as listing contacts, adding a new contact, getting a contact by ID, and removing a contact.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
Navigate to the project directory:


cd goit-node-hw-01
Install the dependencies:


npm install
Usage
To use the Contacts CLI App, run the following commands in the terminal:

List all contacts :
node index.js --action="list"

Get a contact by ID:
node index.js --action="get" --id <contact-id>


Add a new contact:
node index.js --action="add" --name <name> --email <email> --phone <phone>


Remove a contact by ID:
node index.js --action="remove" --id <contact-id>
Replace <contact-id>, <name>, <email>, and <phone> with the corresponding values.

You can access the screenshots here: https://monosnap.com/list/6489cd068b144fc13a65e2dc