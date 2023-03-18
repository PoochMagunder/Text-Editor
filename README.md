# IndexedDB Text Editor - Progressive Web Application (PWA)

This is a Progressive Web Application (PWA) version of the simple text editor that uses IndexedDB for client-side storage. This PWA version can be installed on your device and used offline, giving you the flexibility to use it anywhere, anytime. This application allows users to create, read, update, and delete (CRUD) text documents stored locally on their device, even when offline.

## Features

Create new documents
Loads existing documents
Automatic saving of changes
Responsive and user-friendly interface
Installable to use offline

## Getting Started

To use this application, simply visit the application's URL in your browser, and you will be prompted to install the application. Once installed, you can start creating, opening, and editing text documents immediately, even when offline.

## How it Works

This text editor PWA uses IndexedDB to store documents locally on the user's device. When a user creates or opens a document, the contents of the document are retrieved from the IndexedDB database and displayed in the editor. As the user makes changes to the document, those changes are automatically saved to the IndexedDB database.

The PWA version of the text editor uses a service worker to cache the application's resources, enabling the application to be installed and used offline. When the user is offline, the application can still retrieve the cached resources and access the IndexedDB database to allow the user to create, read, and update text documents.

## Dependencies

This text editor PWA does not have any external dependencies, as it is built entirely using native browser technologies.

## Contributions

Contributions to this project are welcome! If you find any bugs or have any feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
