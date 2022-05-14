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
- When opened in editor, the client server folder structure is visible.
- When npm run start occurs at the root, than the backend starts and serves the client.
- When run, the JavaScript files have been bundled via webpack.
- When the webpack plugins are run, a: HTML file, service worker, and manifest file are generated.
- When next-gen JavaScript is used; it still functions without errors.
- When opened, the IndexedDB immediately creates a database storage.
- When content is entered and click off the DOM window, the application content is saved with IndexedDB.
- When reopened, then the text content is retrieved from IndexedDB.
- When the install button is clicked, the web application is downloaded to desktop.
- When it loads, a service worker is registered via workbox.
- When a service worker registers, then static assets are pre cached upon loading.
- When deployed to Heroku, proper build scripts ate generated.

## Deployed application

### Github Repository
https://github.com/LisaCR01/Text-Editor.git
[Link to Github Repository](https://github.com/LisaCR01/Text-Editor.git)

## Contact Information
- [Email](mailto:lcrgunn@gmail.com)
- [Github](https://github.com/LisaCR01)
- [LinkedIn](https://www.linkedin.com/in/LisaCR01)
