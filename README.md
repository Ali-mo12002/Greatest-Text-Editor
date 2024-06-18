# Text-Editor-PWA
### JATE 

JATE is a web-based text editor application built using JavaScript. It allows users to write, edit, and save text content directly in the browser. The application leverages IndexedDB for local storage, enabling offline functionality and persistent data storage across sessions.

## Features
- Text Editing: Write and edit text with syntax highlighting using CodeMirror.
- Offline Support: Utilizes IndexedDB for local storage, allowing the application to work offline.
- Automatic Saving: Content is automatically saved to IndexedDB when the editor loses focus.
- Progressive Web App: Can be installed as a Progressive Web Application (PWA) for enhanced usability.
- Service Worker: Implements a service worker with Workbox to cache static assets for improved performance.
- Babel Integration: Supports modern JavaScript features like async/await using Babel.
- Webpack Bundling: Uses webpack for bundling JavaScript and other assets for production.


## Installation

To install and run the application locally, follow these steps:

1. Clone the repository
2. Install dependencies
3. Start the application using npm run start:dev
4. Open your browser and navigate to http://localhost:3000 to view the application.

## Usage

- Write and edit text in the editor.
- Content is automatically saved to IndexedDB when the editor loses focus.
- Install the application as a PWA for offline access (available in supported browsers).


## Deployment
To deploy the application to a production environment, follow these steps:

Build the client application using npm run build
Start the server using npm start
The application will be accessible at the specified server endpoint.

## Technologies Used

- Frontend: JavaScript, React, CodeMirror, webpack, Babel
- Backend: Node.js, Express
- Database: IndexedDB
- Service Worker: Workbox
- Other Tools: Concurrently, nodemon (for development)

## screenshots of application 
[screenshot of editor](./client/src/images/editor%20screenshot.png)
[screenshot of text](./client/src/images/text%20screenshot.png)

## link to try Jate out
https://text-editor-747g.onrender.com/
## Contributing
Contributions are welcome! 