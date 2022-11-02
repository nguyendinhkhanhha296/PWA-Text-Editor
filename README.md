<h1 align="center">Text Editor</h1>
   
   
## Description
  
🔍 A text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline. 
  
## Screenshot

The app can be installed as a PWA on your device (mobile or desktop) by tapping the install button at the top left or the install button in the browser in the URL bar.
![Screenshot](./assets/Screen%20Shot%202022-11-01%20at%2010.21.39%20PM.png)

The app works offline.
![Screenshot](./assets/Screen%20Shot%202022-11-01%20at%2010.18.42%20PM.png)


Using devtools, you can see both the Service Worker in action, along with a loaded Manifest.
![Screenshot](./assets/Screen%20Shot%202022-11-01%20at%2010.19.26%20PM.png)

![Screenshot](./assets/Screen%20Shot%202022-11-01%20at%2010.20.21%20PM.png)

## Deployed App

:atom_symbol: [Heroku App](https://ha-text-editor.herokuapp.com/)
        
## User Story
  
```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```
  
## Acceptance Criteria
  
``` 
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```
  
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)

## Installation
💾   
  ```
   npm install express 
   npm install --save-dev webpack 
   npm install webpack-dev-server --save-dev 
   npm install --save-dev webpack-pwa-manifest 
   npm install babel 
   npm install --save-dev css-loader 
   npm install concurrently --save 
   npm npm install idb 
  ```

## Usage
💻   
  
Run the following command at th root of your project and answer the prompted questions:
  
`npm start`

