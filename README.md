# ReactJS Contacts App

This project is a simple ReactJS application that displays a list of contacts in a webpage. Each contact is displayed in a Card component, which contains their name, avatar, phone number and email address.

## Installation

To install and run this project on your local machine, follow these steps:
1. Clone the project from the GitHub repository:
git clone https://github.com/your-username/your-project-name.git

2. Install the required dependencies using npm or yarn:
`npm install`
or
`yarn install`

3. Start the development server:
`npm start`
or
`yarn start`

## Usage
- Once the project is running, you can view it by opening your web browser and navigating to `http://localhost:3000/.` You should see a list of contacts displayed on the page.

## Components
This project contains the following components:

- App
The App component is the top-level component of the application. It renders a list of Contact components based on data from the contacts.js file.

- Card
The Card component is used to display information about a single contact. It takes in props such as the contact's name, avatar, phone number and email address, and renders them in a card format.

- Avatar
The Avatar component is used to display the avatar of a contact. It takes in a URL to an image file and displays it in a circular format.

- Data
The data for the contacts is stored in the contacts.js file. It is an array of objects, where each object represents a single contact. The object contains properties such as the contact's name, avatar URL, phone number and email address.

## Conclusion
This ReactJS project is a simple but useful application for displaying a list of contacts in a webpage. It demonstrates the use of components, props and data handling in a ReactJS application. Feel free to modify and use it in your own projects!