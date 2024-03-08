### Text Editor Web Application

### Description:

Welcome to our Text Editor Web Application! This intuitive and feature-rich text editor is designed to provide a seamless writing experience with advanced functionalities. Whether you're jotting down notes, drafting documents, or coding snippets, our web application offers a robust set of tools to streamline your workflow.

### Table of Contents:

1. Introduction
2. Installation
3. Usage
4. Features
5. Deployment

### Introduction:

This web application is a text editor built to meet specific criteria. It provides functionality for creating, editing, and saving text content, utilizing technologies such as IndexedDB, webpack, service workers, and workbox.

### Installation:

To install and run the application locally, follow these steps:

1. Clone the repository 
2. Navigate to the project directory
3. Install dependencies

### Usage:

Once installed, you can use the text editor web application as follows:

1. Start the backend and serve the client: npm run start 
2. Bundle JavaScript files using webpack: npm run webpack
3. Open the text editor application in your browser.
4. Enter content in the text editor. IndexedDB will immediately create a database storage and save the content.
5. If you click off the DOM window, the content will be saved automatically.
6. Upon reopening the text editor, the content will be retrieved from IndexedDB.
7. Click on the "Install" button to download the web application as an icon on your desktop.

### Features:

* Client-server folder structure
* Bundled JavaScript files using webpack
* Generated HTML file, service worker, and manifest file using webpack plugins
* Supports next-gen JavaScript without errors
* IndexedDB for database storage of text content
* Service worker registration using workbox
* Static assets pre-cached upon loading using service worker

### Deployment:

To deploy the application to Render, ensure you have proper build scripts for a webpack application. Follow the deployment guidelines provided by Render or your hosting provider of choice.







