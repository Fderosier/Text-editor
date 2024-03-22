# Text-editor
# Table of Contents

# Descripion
This versatile text editor serves as a handy tool for crafting and saving notes or code snippets, ready for future reference. It operates as a single-page application, adhering to Progressive Web App (PWA) standards, thus guaranteeing a smooth and consistent user experience across various devices and web browsers.

Employing resilient data-persistence methods such as local storage and IndexedDB, user data remains safeguarded even in scenarios where specific browser functionalities are inaccessible. Additionally, its offline functionalities guarantee uninterrupted access, rendering it perfect for utilization regardless of time or location.

Deployed on Render for simplicity and scalability, this editor offers reliable performance. 


# Technologies Used
HTML
CSS
Javascript
Express.js
Node.js
Webpack for bundling
Service Worker for offline use
IndexedDB for database storage

# Usage
Upon initiating the text editor, IndexedDB promptly establishes a database storage.
Content entered into the text editor is automatically stored in IndexedDB upon clicking outside the DOM window.
Upon reopening the text editor post-closure, content is fetched from IndexedDB for restoration.
By clicking the install button, the web application can be downloaded and installed as a desktop icon.
Even in offline mode, the page loads smoothly due to pre-caching of static assets during initial loading, including subsequent pages and static assets.

# Author-Credits
https://github.com/Fderosier/Text-editor.git
