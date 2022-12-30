# React
==========================================
1.What is Emmet?

Ans: 
Emmet is a plugin for text editors that allows users to quickly write and expand abbreviations and snippets of HTML, XML, and other structured code. It is designed to help users write and edit code more efficiently by allowing them to use shorthand notations to represent longer, more complex code structures.

For example, instead of manually writing out an entire HTML tag, a user can type p and then press the tab key to expand it to a fully formed <p></p> tag. Emmet also supports more advanced features, such as attribute formatting and text wrapping, which allow users to easily generate and format complex code structures with just a few keystrokes.

Emmet is available as a plugin for many popular text editors, including Sublime Text, Visual Studio Code, and Atom.
==================================================
2.Difference between a Library and Framework?

Ans:
In general, a library is a collection of code that you can use to perform specific tasks in your own code. It provides a set of functions, classes, or other code constructs that you can use to perform specific operations or tasks, without having to write all of the code yourself. A library is typically designed to be flexible and reusable, so that you can use it in a variety of different projects or contexts.

On the other hand, a framework is a set of code that provides a structure for building applications. A framework defines a set of conventions and best practices for building an application, and provides a set of abstractions and tools that you can use to build your application more quickly and efficiently. A framework is typically more opinionated than a library, and often requires you to follow a specific set of guidelines or patterns in order to use it effectively.

In general, a library is a more flexible and reusable codebase that you can use to perform specific tasks in your own code, while a framework is a set of tools and conventions that you can use to build an entire application more quickly and efficiently.
========================================================
3.What is CDN? Why do we use it?
Ans:
A content delivery network (CDN) is a system of distributed servers that deliver web content to users based on their geographic location. CDNs are used to improve the performance and availability of websites and other web-based services by reducing the distance that data has to travel between the server and the user's device.

CDNs work by storing copies of static content, such as images, videos, and other media files, on servers that are distributed across multiple locations around the world. When a user requests content from a website that is served by a CDN, the CDN will redirect the request to the server that is closest to the user's location, which helps to reduce the time it takes for the content to be delivered.

There are several reasons why CDNs are commonly used:

Improved performance: CDNs help to improve the performance of websites and other web-based services by reducing the distance that data has to travel between the server and the user's device. This can help to reduce the time it takes for content to be delivered, which can improve the user experience.

Increased availability: CDNs can help to improve the availability of a website or service by distributing the load across multiple servers and locations. This can help to reduce the risk of outages or other disruptions that can occur when a single server becomes overloaded.

Enhanced security: CDNs can also help to improve the security of a website or service by providing features such as DDoS protection, which can help to prevent attacks on a server or network.

Cost savings: Using a CDN can also help to reduce the costs associated with hosting and delivering content, as it allows content to be served from servers that are closer to the user, which can reduce the amount of bandwidth required.
======================================================
4.Why is React known as React?
Ans:
React is a JavaScript library for building user interfaces that was developed by Facebook. It is known as "React" because it was designed to be a reactive system, meaning that it is designed to respond to changes in the data that it is working with.

React was designed to be fast, efficient, and easy to use, and it has become popular among developers due to its ability to efficiently update and render large lists of data, as well as its flexibility and extensibility. React allows developers to create reusable components that can be easily shared and integrated into larger projects, which makes it easier to build complex user interfaces.

In addition to its core features, React is also supported by a large ecosystem of third-party libraries and tools, which makes it easier for developers to build, test, and deploy their applications. Overall, the combination of React's performance, flexibility, and extensibility have made it a popular choice among developers building modern web applications.
============================================================
5.What is crossorigin in script tag?

Ans: The crossorigin attribute is used in the <script> tag to indicate that the script should be loaded using CORS (Cross-Origin Resource Sharing). CORS is a mechanism that allows a web page to make requests to a different domain than the one that served the page. By default, web browsers block these types of requests to prevent malicious websites from making requests to other domains on behalf of the user.

The crossorigin attribute allows the server hosting the script to specify that the script can be loaded from a different domain, and that the browser should allow the request to be made. The attribute can be set to either anonymous or use-credentials, depending on whether or not the server wants to send cookies or other credentials with the request.

For example, the following <script> tag specifies that the script should be loaded using CORS, and that the browser should not send any credentials (such as cookies) with the request:

<script src="https://example.com/script.js" crossorigin="anonymous"></script>

Using the crossorigin attribute can help to improve the performance of web pages by allowing them to load resources from servers that are optimized for serving those resources, rather than relying on the server that served the page itself. It can also be used to allow web pages to make requests to APIs or other services hosted on different domains.
==========================================================================
6.What is diference between React and ReactDOM

ANS: React and ReactDOM are two different libraries that are commonly used together to build web applications with React.

React is a JavaScript library for building user interfaces that was developed by Facebook. It provides a set of tools and abstractions that make it easier to build complex, interactive user interfaces using reusable components. React allows developers to declaratively describe the structure of a user interface, and it automatically updates the interface whenever the underlying data changes.

ReactDOM, on the other hand, is a separate library that provides the methods that are needed to interact with the Document Object Model (DOM) in a web browser. The DOM is a tree-like structure that represents the structure of a web page, and it is used to manipulate the content and layout of a page using JavaScript. ReactDOM provides methods that allow React components to be rendered to and updated in the DOM.

In general, React is used to define the structure and behavior of a user interface, while ReactDOM is used to interact with the DOM and render the interface to the web page. Together, these two libraries form the core of the React framework, which is widely used to build modern, interactive web applications.
==============================================================================================
7.What is difference between react.development.js and react.production.js files via CDN?
Ans:
The react.development.js and react.production.js files are different versions of the React library that are optimized for different environments.

The react.development.js file is intended for use during the development and testing of a React application. It includes additional debugging and error checking features that can help to identify and fix problems during the development process. This version of the library is larger and slower than the production version, but it provides more information and helpful tools for debugging and testing.

The react.production.js file, on the other hand, is intended for use in a production environment, where the focus is on performance and reliability. This version of the library has been optimized for size and speed, and it does not include the additional debugging and error checking features that are present in the development version. This makes it faster and more efficient, but it also means that it may not provide as much information when things go wrong.

In general, it is recommended to use the react.development.js file during the development and testing of a React application, and to switch to the react.production.js file when deploying the application to a production environment. This will help to ensure that the application is efficient and reliable in production, while also providing the necessary tools and information for debugging and testing during the development process.
=================================================================
8.What is async and defer?
Ans:
The async and defer attributes are used in the <script> tag to specify how a script should be loaded and executed by the browser. These attributes can be used to improve the performance of a web page by allowing the browser to load and execute scripts in a more efficient way.

The async attribute tells the browser to load the script asynchronously, meaning that it will be loaded in the background while the page continues to load and render. This can help to improve the overall performance of the page, as it allows the browser to continue loading and rendering the rest of the page while the script is being fetched. However, it also means that the script may not be executed in the order in which it appears in the HTML, as it may not be fully loaded and parsed until after the rest of the page has finished loading.

The defer attribute tells the browser to load the script and execute it after the page has finished loading. This can also help to improve the performance of the page, as it allows the browser to continue loading and rendering the rest of the page while the script is being fetched, and it ensures that the script is executed in the order in which it appears in the HTML.

In general, it is recommended to use the async attribute for scripts that are independent of one another and do not need to be executed in a specific order, and to use the defer attribute for scripts that need to be executed in a specific order or that depend on one another. This will help to ensure that the scripts are loaded and executed in the most efficient way possible, while also ensuring that they are executed in the correct order if necessary.
================================================================================
References:
- https://beta.reactjs.org/apis/react/createElement
- https://www.youtube.com/watch?v=IrHmpdORLu8


