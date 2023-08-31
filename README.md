# text-editor
link: https://guarded-wildwood-37670-8c81a3b4e45b.herokuapp.com/
 # Features
The application provides a text editor that stores your content using IndexedDB.
You can enter content in the text editor, and it will be saved to IndexedDB immediately when you click off the DOM window.
Your saved content in the text editor is retrieved from IndexedDB when you reopen the text editor.
The application can be installed as an icon on your desktop using the "Install" button.
A service worker is registered using Workbox to provide offline functionality.
Static assets, subsequent pages, and other resources are pre-cached upon loading the application.
The application can be deployed to Heroku, and it includes proper build scripts for a webpack application.
# Technologies Used
JavaScript
Webpack
IndexedDB
Service Workers (Workbox)
Progressive Web App (PWA) principles
# Usage
This text editor application is designed for developers who want a reliable way to create, store, and access notes or code snippets with or without an internet connection. The offline functionality ensures that you can continue working on your notes even in situations where internet connectivity is limited or unavailable.