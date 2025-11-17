## Section B: JavaScript Variables & Datatypes (Theory)# Jahswill-Omoware-
TechyJaunt submission

### What is backend development and how is it different from frontend development?
**Backend Development: Refers to the server-side of an application, focusing on databases, servers, APIs, and the logic that powers the frontend. It handles data storage, processing, security, and communication with the frontend. Users don't directly interact with the backend.
** Difference from Frontend Development:
Frontend: Deals with the user interface (UI) and user experience (UX) – everything the user sees and interacts with in a web browser or mobile app (e.g., HTML, CSS, JavaScript), While Backend: Deals with the "behind-the-scenes" logic, data management, and server operations that make the frontend functional (e.g., databases, APIs, server-side languages like Python, Node.js, Java).
### Mention three backend programming languages.
*Python
*Node.js (JavaScript)
*Java
### What is a server, explain its role backend development.
* Server: A computer program or a device that provides functionality for other programs or devices, called "clients." In web development, a server is typically a powerful computer that stores website files, databases, and applications.
Role in Backend Development: The server hosts the backend application. It receives requests from client applications (e.g., web browsers), processes them using the backend logic, interacts with databases to retrieve or store data, and sends responses back to the client. It's the central hub for data and business logic.
### Define an API and explain its purpose.
* API (Application Programming Interface): can be defined as a set of rules and protocols that allows different software applications to communicate with each other. It defines the methods and data formats that applications can use to request and exchange information.
* Purpose: APIs enable integration and interoperability between systems. They allow developers to access specific functionalities or data from another application without needing to understand its internal implementation. For example, a weather app can use  a weather API to get forecast data, or a social media app can an API to share content.
### What is a database and why is it important in backend systems?
Database: Refers to an organized collection of structured information, or data, typically stored electronically in a computer system. It allows for efficient storage, retrieval, and management of data.
      Databases are crucial for backend systems because they provide a persistent storage mechanism for all application data (user profiles, product information, orders, etc.). The backend logic interacts with the database to store new data, retrieve existing data, update records, and delete information, ensuring data integrity and availability.
### List two differences between SQL and NoSQL databases.
* SQL (Relational Databases)  Uses a structured, tabular schema with predefined columns and rows, while NOSQL Uses a dynamic schema, often document-based, key-value, graph, or column-family.
Typically SQL scale vertically (more powerful server) eg MySQL, PostgreSQL, Oracle, SQL Server, while NoSQL  Typically scale horizontally (add more servers) eg MongoDB, Cassandra, Redis, Neo4. 
### What is a backend framework? Mention one example.
* A Backend Framework can be defined as a collection of pre-written code, libraries, and tools that provide a structure and common functionalities for building backend applications. They streamline development by handling routine tasks like database interaction, routing, security, and session management, allowing developers to focus on business logic.
Example: Node.js
### Explain what HTTP and why it's important.
* HTTP (Hypertext Transfer Protocol): is the foundation of data communication for the World Wide Web. It's an application-layer protocol for transmitting hypermedia documents, such as HTML. It defines how messages are formatted and transmitted, and what actions web servers and browsers should take in response to various commands.
Importance: HTTP is essential because it enables communication between web clients (browsers) and web servers. Without it, browsers wouldn't be able to request web pages, images, or other resources from servers, and servers wouldn't be able to send them back. It's the standard language for web communication.
### Mention two responsibilities of a backend developer.
*Managing databases and ensuring data integrity.
* Writing server-side logic and Ensuring application security and performance. 
### What does CRUD stand for? Explain each word.
C - Create: Adding new data records (e.g., creating a new user account, adding a new product).
R - Read: Retrieving existing data records (e.g., fetching a user's profile, listing all products).
U - Update: Modifying existing data records (e.g., changing a user's identity like email address) 
D - Delete: Removing data records (for example ., deleting a user account, removing a product.

### What is authentication and why is it important for backend applications?
* Authentication: can be defined as the process of verifying the identity of a user, system, or application. It confirms identity (who you are) by checking credentials like usernames and passwords, tokens, or biometric data.
* Importance for Backend Applications: Authentication is critical for security. It ensures that only authorized users can access specific resources, data, or functionalities within the application. Without proper authentication, sensitive data could be exposed, and unauthorized actions could be performed, leading to data breaches, system compromise, and loss of trust.
### What is the difference between a GET request and a POST request?
GET Request: is  Used to retrieve data from the server, while Post request is Used to send data to the server to create or update a resource.
Data Transmission: Parameters are appended to the URL (query string), while POST Request Parameters are sent in the body of the HTTP request. 
Security: Less secure for sensitive data as parameters are visible in the URL and browser history, while POST Request is more secure for sensitive data as parameters are not visible in the URL.
Caching: Can be cached by browsers and proxies, while POST Request are  generally not cached.Generally not cached.

## Section B: JavaScript Variables & Datatypes (Theory)

### What is a variable in JavaScript? 
* A variable in JavaScript is a named storage location for data. It allows you to store values (like numbers, text, objects, etc.) and refer to them by a name throughout your code. Variables can hold different types of data, and their values can change during the execution of a program.
### List the three ways to declare variables in JavaScript. 

* var
* let
* const
### Explain the difference between let and const.
* let: Declares a block-scoped local variable. Its value can be reassigned later in the code.
* const: Declares a block-scoped local variable whose value cannot be reassigned after its initial assignment. It must be initialized at the time of declaration.
### Mention the seven primitive datatypes in JavaScript. 
* string
* number
* boolean
* undefined
* null
* symbol 
* bigint 
### What datatype is assigned to the value: true? 
* The datatype assigned to the value true is boolean.
### What datatype is a JavaScript array? 
* In JavaScript, an array is a special type of object. When you use typeof on an array, it returns "object".
### Give one example of a string in JavaScript.
"Hello, World!"
### Give one example of a number in JavaScript
100
### What will be the output of this expression? typeof "123" 
* u think the output will be: "string"
### Explain the difference between null and undefined.
* undefined:
Indicates that a variable has been declared but has not yet been assigned a value.
It's also the value returned by functions that don't explicitly return anything.
It's the value of non-existent object properties or array elements.
typeof undefined returns "undefined".
* null:
Represents the intentional absence of any object value. It's a primitive value.
It's a value that a programmer can assign to a variable to explicitly indicate "no value" or "empty."
typeof null returns "object" (which is a historical bug in JavaScript, but null is conceptually a primitive value)
## Section C Coding Questions. 
### Declare a variable using let and assign your name to it.
let myName = "Jahswill omoware";
### Write JavaScript code to add two numbers and log the result.
let num1 = 30:
let num2 = 30:
let num3 = 40:
let sum = num1 + num2+ num3; 
console.log (The sum is:", sum);/

### Create an object called student with properties name, age, and department.
let student = {
    name: "Jahswill Omoware ",
    age: 22,
    department: "techyjaunt cohort 7"
};console.log(student);
// Output: 
### Write a JavaScript function called greet() that prints "Hello World".
function greet() {
    console.log("Hello World");

