Progressive Web Applications (PWA) Challenge: Text Editor
==============================

This web application allows you to create and save notes or code snippets with or without an internet connection. You can access your saved notes anytime and anywhere, without the need to rely on an internet connection.

### Deployed Website: https://jate-naz.herokuapp.com/

Features
--------

-   Create and save notes or code snippets.
-   Store data locally using IndexedDB.
-   Offline functionality using service workers and workbox.
-   Installable as a PWA on your desktop or mobile device.
-   Compatible with next-gen JavaScript.
-   Backend server with client-server folder structure.
-   Heroku deployment.

Getting Started
---------------

### Prerequisites

-   Node.js installed on your machine.
-   NPM package manager installed on your machine.

### Installation

1.  Clone the repository from Github to your local machine.
2.  Open the cloned repository in your preferred code editor.
3.  In the terminal, navigate to the root directory of the project.
4.  Run the command `npm install` to install all the necessary dependencies.
5.  Run the command `npm run start` to start up the backend server and serve the client.
6.  Open your web browser and navigate to `http://localhost:3000` to access the text editor application.

### Usage

When you open the text editor, IndexedDB will immediately create a database storage. Enter your content in the text editor and click off of the DOM window to save your content with IndexedDB. If you close the text editor and reopen it later, your content will be retrieved from IndexedDB.

You can also install the application as a PWA on your desktop or mobile device by clicking on the Install button. When you load the web application, it will be registered as a service worker using workbox, allowing you to access the application offline. Static assets will be pre-cached upon loading, along with subsequent pages and static assets.

### Deployment

To deploy the application to Heroku, you need to have proper build scripts for a webpack application. Follow these steps to deploy the application to Heroku:

1.  Create a Heroku account if you don't have one already.
2.  Create a new app on the Heroku dashboard.
3.  Connect your cloned repository to the Heroku app.
4.  Set up the necessary environment variables in the Heroku app settings.
5.  Push your changes to the Heroku remote branch using `git push heroku main`.
6.  Once the deployment is complete, open the app in your browser by visiting the Heroku app URL.

Technologies Used
-----------------

-   Node.js
-   Express.js
-   IndexedDB
-   Webpack
-   Workbox
-   Heroku

Author: Naz Yasar
-----------------
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nazyasar)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nazyasar/)
