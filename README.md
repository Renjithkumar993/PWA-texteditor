# PWA-texteditor
 
This is a text editor web application that runs in the browser and provides an offline-first experience. It features data persistence using IndexedDB for local storage and follows the Progressive Web App (PWA) criteria. The application is built with modern JavaScript using webpack for bundling and workbox for service worker functionality.

## Features

```md
Client-server folder structure
Backend server to serve the client
Bundling of JavaScript files using webpack
Generation of HTML file, service worker, and manifest file
Compatibility with next-gen JavaScript
IndexedDB integration for immediate database storage creation
Automatic saving of content in the text editor upon leaving the DOM window
Retrieval of saved content from IndexedDB when reopening the text editor
Installation of the web application as a desktop icon using the Install button
Registered service worker using workbox for offline functionality
Pre-caching of static assets upon loading and for subsequent pages
Proper build scripts for deployment to Heroku
```

## Technologies Used
```md
JavaScript
HTML
CSS
Node.js
Express.js (backend server)
webpack (module bundler)
idb (IndexedDB wrapper)
workbox (service worker library)
Heroku (deployment platform)
```

## Usage

```md
Clone the repository: git clone https://github.com/Renjithkumar993/PWA-texteditor
Navigate to the project directory: cd PWA-texteditor
Start the backend server and serve the client: npm run start
Open your browser and access the application at http://localhost:3000
Use the text editor to enter and edit content. It will be automatically saved to IndexedDB.
Close the browser window and reopen it to see the saved content retrieved from IndexedDB.
Click on the Install button to download the web application as a desktop icon (if supported by the browser).
Load the web application and enjoy the offline functionality provided by the service worker.
```

## License

This project is licensed under the MIT License. You can find more details in the LICENSE file.

