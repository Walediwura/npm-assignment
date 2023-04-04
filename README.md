# npm-assignment

Question 1: What is the Event loop ? 

Event loop is a mechanism that enables asynchronous programming by handling and executing code in response to events. The event loop continuously checks for any events in the event queue, which can include user input, network requests, timers, and other types of events.


Question 2: Explain the 6 phases of the event loop ?

i. Timers: In this phase, the event loop checks for any timer callbacks that have expired. Timer callbacks are added to the timer queue and executed after a specified time delay using functions like setTimeout() and setInterval().

ii. Pending I/O callbacks: This phase executes I/O callbacks that were deferred during the previous loop iteration.

iii. Idle, prepare: These phases are used internally by the event loop and are typically empty in most applications.

iv. Poll: This is the main phase of the event loop, where the loop waits for events to occur. If there are no timer callbacks or pending I/O callbacks, the event loop will block and wait for new events to occur.

v. Check: In this phase, any callbacks registered with the setImmediate() function are executed.

vi. Close callbacks: This phase executes any close event callbacks registered on the event emitter objects.


Question 3: List some best practices in server-side code development?

i. Write secure code: Follow security best practices to prevent attacks such as SQL injection, cross-site scripting (XSS), and cross-site request forgery (CSRF). This includes input validation, escaping user input, and using encryption and hashing where appropriate.

ii. Write scalable code: Design the application architecture in a way that allows it to scale to handle large amounts of traffic and data. This includes using caching, load balancing, and database sharding.

iii. Write automated tests: Write unit tests, integration tests, and end-to-end tests to ensure that the code works as expected and catches errors early in the development cycle. This can help to improve code quality and reduce the risk of regressions.

iv. Use a framework: Use a well-established framework that has been tested and proven in production environments. This can save time and help ensure that the code is reliable, secure, and scalable.

v. Keep it simple: Keep the code simple and easy to understand. Avoid complex logic, overly nested structures, and unnecessary abstractions.


Question 4: What is NPM5: How do you initialize a package in npm?

i. NPM 5 is a version of the Node Package Manager (npm) which was released in 2017. It introduced several new features and improvements over previous versions of npm, including better performance, a new lock file format for deterministic package installs, and better support for managing multiple packages at once. npm is used to install, manage, and share packages or modules of code written in JavaScript.

b. You initialize a package in npm by using the 'npm init' command.


Question 6: How do you run a script in the package.json ?

By running the command 'npm run <script-name>'



