# Operating IndexedDB in a Browser

## Introduction
IndexedDB is a database built into modern browsers, providing a way to store significant amounts of structured data. It allows for high-performance searches and can be used for offline applications. This guide explores how to interact with IndexedDB, highlighting its features and demonstrating basic operations.

## Features of IndexedDB
- **Online & Offline Support**: IndexedDB works both online and offline.
- **Same Origin Policy**: Data is stored per origin (protocol, domain, port).
- **Key-Value Storage**: Stores data in key-value pairs.
- **Transactional Database Model**: Supports transactions for reliable data storage.
- **Asynchronous Operations**: Non-blocking operations for improved performance.
- **No SQL Required**: Uses JavaScript for database operations instead of SQL.

## Getting Started
This guide includes an example HTML setup to demonstrate how to create and manipulate an IndexedDB. The following sections describe various operations that can be performed using IndexedDB.

## Operations

### Creating a Database
First, create a database by pressing the "Create IndexedDB" button. This initializes a new database named `MyTestDatabase`.

### Creating an Object Store
Press the "Create Object Store in IndexedDB" button to create an object store within the database. The object store functions similarly to a table in SQL databases and is named `customer`.

### Inserting Data
Register data into the object store by pressing the "Insert Data into IndexedDB" button. This example uses a predefined data entry with an ID and name.

### Searching for Data
Retrieve data from the object store by pressing the "Search Data in IndexedDB" button. This searches for the previously inserted data.

### Updating Data
Update the existing data in the object store by pressing the "Update Data in IndexedDB" button. This changes the name field of the stored data.

### Deleting Data
Remove data from the object store by pressing the "Delete IndexedDB Data" button. This deletes the specified data entry from the store.

### Deleting an Object Store
Remove the entire object store by pressing the "Delete IndexedDB Object Store" button. This deletes the `customer` object store from the database.

### Deleting a Database
Completely delete the database by pressing the "Delete IndexedDB" button. This removes `MyTestDatabase` from the browser's storage.

## Additional Information
- **Developer Tools**: Keep your browser's developer tools open to view the execution results and any error messages.
- **Data Persistence**: Data may not immediately disappear from the developer tools after deletion; refresh the view to see the changes.
- **Security**: Ensure to understand security implications and best practices when using IndexedDB.

## Conclusion
This guide provides a basic overview of using IndexedDB to manage data within a browser. IndexedDB is a powerful tool for front-end development, offering capabilities that were traditionally reserved for backend databases. Explore and experiment with IndexedDB to fully leverage its potential in your web applications.