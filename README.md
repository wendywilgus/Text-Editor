# Progressive Web Application Text Editor

## Overview

This application is a text editor that runs in the browser as a single-page application.  This app not only meets the Progressive Web Application criteria, but also features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.  Site is deployed here:  https://thawing-falls-01629.herokuapp.com/ 

## Table of Contents

- [Story](#user-story)
- [Mockup](#mockup) 
- [License](#license)
- [Resources](#resources)

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

## Mock-Up

The following animation demonstrates the application functionality:

![Demonstration of the finished application being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished application with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished application with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished application with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)

## License
This project was completed as part of Georgia Tech's Full Stack Development Boot Camp course. 
---
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.


## Resources
The following resources were helpful in researching best practices and problem-solving on the project.
* [Mini-Css-Extract-PlugIn](https://www.npmjs.com/package/mini-css-extract-plugin)
* [Webpack](https://www.npmjs.com/package/webpack)