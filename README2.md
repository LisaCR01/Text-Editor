# Text Editor

In this project I built a single page text editor application; that runs in the browser and meets the PWA (Progressive Website Application) criteria that allows it to functions offline. The motivation for creating this application is to provide the users with a unique experience through the use of a PWA rather than a normal website or an app. Through this application I gained knowledge on new techniques through the webpack bundle, such as: the webpack-pwa-manifest plugin, asset caching and workbox plugins.

## Technology

- HTML
- CodeMirror
- Custom CSS
- Node.js
- JavaScript
- webpack plugin
- JSON
- npmrc configuration file
- eslintrc configuration file
- WebpackPwaManifest plugin
- idb package

## Criteria I met
- Having opened the application in their editor; the client server folder structure is viewable.
- When npm run start is run in the root directory than the application should start up the backend and serve the client
- When the application is run; then the js files have been bundled via webpack.
- When the webpack plugins are run than a: HTML file, service worker, and manifest file are generated.
- When next-gen JavaScript is used in the application; then it still functions in the browser without errors.
- When the applicationn


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
## Deployed application

### Github Repository
https://github.com/LisaCR01/Text-Editor.git
[Link to Github Repository](https://github.com/LisaCR01/Text-Editor.git)

## Contact Information
- [Email](mailto:lcrgunn@gmail.com)
- [Github](https://github.com/LisaCR01)
- [LinkedIn](https://www.linkedin.com/in/LisaCR01)
