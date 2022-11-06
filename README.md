
  <h1 align="center">PWA-Text-Editor</h1>

  ![badge](https://img.shields.io/badge/license-MIT--brightgreen)<br />

  ## Description 
  ```md
  I created a text editor that runs in the browser. The app is a single page application that meets pwa  criteria. The application 
  also functions offline.
  ```
  ## Table of Contents
 * [Description](#description)
 * [About](#about)
 * [User Story](#user-story)
 * [Acceptance Criteria](#acceptance-criteria)
 * [Screenshots](#screenshots)
 * [Video](#video)
 * [Installation](#installation)
 * [Link to Deployed Heroku App](#link-to-deployed-heroku-app)
 * [License](#license)
 * [Test](#test)
 * [Contributers](#contributers)
 * [Qusetions](#questions)

  ## About
  ```md
  For this application I used indexedDB as the database. I used webpack to bundle the front end . I also used workbox to create a 
  service worker that caches static assets. Finally I deployed the finished product to Heroku for  deployment.
```
  ## User Story
  ```md
  AS A developer
  I WANT to create notes or code snippets with or without an internet connection
  SO THAT I can reliably retrieve them for later use
   ```
  ## Acceptance Criteria
  ```md
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
  ## Screenshots
  ![HerokuJATE](https://user-images.githubusercontent.com/102045473/200180942-afd434b0-c36c-4863-911e-63b14e71319a.png)
![installapp](https://user-images.githubusercontent.com/102045473/200180951-d25b5ba8-8cd9-465c-bda0-7ea7cf828ace.png)
![Serviceworker](https://user-images.githubusercontent.com/102045473/200180958-d0f78e2c-d3b2-44e4-a092-77e34a4cc29e.png)
![JATEindexeddb](https://user-images.githubusercontent.com/102045473/200180964-77830e07-f5cf-4eb9-b971-285dace42a35.png)

## Video 



https://user-images.githubusercontent.com/102045473/200180986-2e4ddc3b-db11-4cf6-882f-00e9e61cc069.mp4


 
  ## Installation
  * You have to clone my starter code. 
  * Then you have to open the root directory in your terminal. 
  * run npm install to install all dependencies.  
  * run the command npm run build.  
  * run npm run start 
  * open your local host and click the install button. 
  
  ## Link to Deployed Heroku app
  
  <a href="https://text-editor-41.herokuapp.com">Heroku app</a>
  
    

  ## License
![badge](https://img.shields.io/badge/license-MIT--brightgreen)
<br />
This application is licensed by MIT

## Test 
None

## Contributers
Cyrus Khiabani

## Questions
Contact Me<br />
<br />
 email me cyrusk81@gmail.com<br />
 <br />
 find me on Github,  [cykj40](https://github.com/cykj40)<br />
<br /> 

This Readme was made by 🚀 Cy ⚡


