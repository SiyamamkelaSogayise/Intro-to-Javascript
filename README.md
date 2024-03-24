# Intro-to-Javascript
<h1>What is Javascripts</h1>

Javascript is a programming language used to program web browsers and servers.
Examples include client-side only (no server-side)
Creates interactivity.
Lets you create very rich interactivity.
If if works on a mobile, oits probably javascript .If you want to see what javascript can do, try disabling javascript and watch what happens, a lot of things disappear.
A lot of things might stop working, even the ones that do wont be working the same way.

Fundamental characteristics of a programming language is the set of data tuypes it supports.
These are the values that can be manipulated in a programming language.
Javascript allows you to work with 3 primitive data types.

1. Numbers, e.g. 123, 120.50 etc.
2. Strings of text e.g. "This is a text string"  etc.
3. Boolean e.g. True or False

Javascript also defines two trivial types, null and undefined, each of which defines only a single value.
Also supports a composite data type known as an object.
Javascript does not make a distinction between integer values and float-point values.
All numbers are represented as floating-point values.
Represnts numbers using 64-bit floating-point format defined by the IEEE 754 standard.

<h1>Variables</h1>

Can be thought of as named containers.
You can place data inside these containers and then refer to the data simply by naming the container.
A variable has to be declared before used.
Declared with the var keyword.
Storing a value in a variable is called initialization.
You  an do variable initialization during creation or when you need to use the variable.
You might ctreate a variable called money and assign the value 2000.50 to it later.
Variables are declared only once.
Javascript is an untyped language, meaning a javascript variable can hold a value of any data type.
There is nmo need to specify the variable type when declaring a javascript variable.
Variable types can be changed.

<h2>Activity 1 daily notes</h2>
 Declaring javascript variables using the var keyword with a semicolon at the edn.
 Variables are like containers you can put data inside of, so each variabl;e hjas to be assigned a value.
 Variables and their values can be put in the same line, e.g ( var myName = "Siya").
Javascript variables have to br written in camelCase.
When javascript values are declared, they have an initiual value of undefined until a value is assigned.

<h2>Strings and Arrays</h2>
<h3>Strings</h3>
    1.Definition: A string is a sequence of characters enclosed within single (' '), double (" "), or backtick (` `) quotes.
    2.Immutable: Strings in JavaScript are immutable, meaning once created, their values cannot be changed. However, you can create new strings based on existing ones.
    3.Properties and Methods: Strings have various properties and methods for manipulation, such as length, charAt(), concat(), slice(), substring(), indexOf(), lastIndexOf(), toUpperCase(), toLowerCase(), trim(), etc.
    4.Concatenation: You can concatenate strings using the + operator or template literals (backtick-enclosed strings with placeholders ${}).
    5.Unicode Support: JavaScript strings support Unicode characters, allowing for internationalization and working with various languages and symbols.
    6.Escape Characters: Strings can contain escape characters such as \n (newline), \t (tab), \\ (backslash), \' (single quote), \" (double quote), etc.
    
<h3>Arrays</h3>
    1.Definition: An array is a data structure used to store a collection of elements. In JavaScript, arrays can hold elements of different data types.
    2.Dynamic: Arrays in JavaScript are dynamic, meaning their size can change dynamically by adding or removing elements.
    3.Zero-based Indexing: Elements in an array are accessed using zero-based indexing, where the first element is at index 0, the second at index 1, and so on.
    4.Properties and Methods: Arrays have various properties and methods for manipulation, such as length, push(), pop(), shift(), unshift(), concat(), slice(), splice(), indexOf(), lastIndexOf(), forEach(), map(), filter(), reduce(), etc.
    5.Iteration: Arrays can be iterated over using loops (for, for-of) or higher-order functions (forEach, map, filter, reduce).
    6.Heterogeneous Elements: JavaScript arrays can contain elements of different data types in the same array.
    7.Mutability: Unlike strings, arrays are mutable, meaning you can change their elements directly.
    
Both strings and arrays are fundamental data structures in JavaScript, and understanding their properties, methods, and usage is essential for effective JavaScript programming.    

<h1>Functions</h1>
In JavaScript, functions are blocks of reusable code designed to perform a particular task. They are a fundamental building block of JavaScript programming and can be defined and used in various ways. Here's a summary of key aspects of functions in JavaScript:

   1. Function Declaration: Functions can be declared using the function keyword followed by a name and a set of parentheses containing optional parameters, and a block of code enclosed in curly braces.
   2. Function Expression: Functions can also be defined using function expressions, where the function is assigned to a variable.
   3. Arrow Functions: Introduced in ES6, arrow functions provide a more concise syntax for defining functions.
   4. Anonymous Functions: Functions without a name are called anonymous functions. They are often used as callback functions or immediately invoked function expressions (IIFE).
   5. Parameters: Functions can accept zero or more parameters, which are placeholders for values passed to the function when it's called.
   6. Return Statement: Functions can optionally return a value using the return statement. If no return statement is provided, the function returns undefined by default.
   7. Function Invocation: Functions are executed (or invoked) using parentheses after the function name, optionally passing arguments.
   8. Scope: Functions have their own scope, which means variables declared inside a function are not accessible from outside the function (unless explicitly exposed).
   9. Closures: Functions in JavaScript form closures, which means they retain access to variables in their lexical scope even after the parent function has finished executing.
   10. Higher-Order Functions: Functions can accept other functions as arguments or return functions, allowing for functional programming paradigms like map, reduce, filter, etc.
   11. Callback Functions: Functions passed as arguments to another function and are intended to be called later are called callback functions.
   12. Named Function Expressions: A function expression can have a name, which can be useful for self-reference or stack traces.
   13. Function Constructors: Functions can also be created using the Function constructor, although this method is less common and generally less recommended.
These are the core concepts and features of functions in JavaScript, which are crucial for building complex and modular applications.

<h2>Booleans</h2>

   1.Definition: Booleans are a primitive data type in JavaScript that represent logical values. They can have one of two values: true or false.
    2.Logical Operators: Booleans are primarily used in conjunction with logical operators such as AND (&&), OR (||), and NOT (!) for making logical decisions and comparisons.
    3.Comparison Operators: Booleans are often the result of comparison operators such as equal to (== or ===), not equal to (!= or !==), greater than (>), less than (<), greater than or equal to (>=), and less than or equal to (<=).
    4.Falsy Values: In JavaScript, certain values are considered falsy, meaning they evaluate to false in a boolean context. These include false, 0, '' (empty string), null, undefined, and NaN (Not-a-Number).
    5.Truthy Values: Conversely, values that are not falsy are considered truthy and will evaluate to true in a boolean context. These include non-empty strings, non-zero numbers, objects, arrays, functions, etc.
    6.Boolean Functions: Functions can return boolean values, which are often used to indicate success or failure, or to evaluate conditions.
    7.Boolean Conversion: Values in JavaScript can be explicitly converted to booleans using the Boolean() function, or they can be implicitly converted to booleans in contexts where a boolean value is expected, such as in if statements or boolean expressions.

Understanding booleans is crucial for implementing conditional logic, making decisions in code execution flow, and performing comparisons in JavaScript programs.

<h1>Week 2</h1>
<h2>JavaScript APIS</h2>

JavaScript APIs (Application Programming Interfaces) provide a way for developers to interact with the capabilities of web browsers or other environments where JavaScript is running. Here's a summary:

 1.DOM API (Document Object Model):
        Allows manipulation of HTML and XML documents.
        Provides methods and properties to access, create, modify, and delete elements, attributes, and text content on a webpage.
        Key objects include document, Element, Node, HTMLElement, etc.

   2.Web APIs:
        Fetch API: Provides an interface for fetching resources asynchronously across the network.
        Web Storage API: Provides mechanisms for storing data in the browser, including localStorage and sessionStorage.
        Geolocation API: Allows accessing a user's geographical location.
        Web Workers API: Enables running scripts in background threads to perform tasks without interfering with the UI.
        WebSockets API: Provides a protocol for full-duplex communication channels over a single TCP connection.
        Canvas API: Allows dynamic, scriptable rendering of 2D shapes and bitmap images.
        Web Audio API: Allows playing and manipulating audio in the browser.
        IndexedDB API: Provides a way to store large amounts of structured data persistently.
        MediaStream API: Allows access to streams of multimedia data, such as video and audio from webcams and microphones.

   3.Browser APIs:
        Window API: Provides methods and properties for manipulating browser windows.
        Location API: Allows interaction with the URL of the current webpage.
        History API: Provides methods for manipulating the browser's history, facilitating navigation within the same tab.
        Cookies API: Allows reading and writing cookies in the browser.
        Notifications API: Allows displaying system notifications to the user.
        Fullscreen API: Enables requesting and exiting fullscreen mode.
        Pointer Lock API: Provides input methods for applications that require control over mouse input.
        Gamepad API: Allows accessing data from connected gamepad controllers.
        Battery Status API: Provides information about the battery status of the device.
        Screen Orientation API: Allows querying and locking the orientation of the screen.
        Performance API: Provides performance-related information, such as timing and memory usage.
        
   4.Third-party APIs:
        APIs provided by third-party services for integration into web applications, such as social media APIs, payment gateways, mapping APIs, weather APIs, etc.

JavaScript APIs empower developers to create rich, interactive web applications by providing access to a wide range of functionalities and services offered by web browsers and external services. Understanding and effectively utilizing these APIs are essential skills for web development.

<h2>Javascript forms</h2>

JavaScript can be used to enhance HTML forms by providing interactive features and performing client-side validations. Here's a summary:

HTML Forms:

   Definition: HTML forms provide a way for users to input data, which can be submitted to a server for processing.
    Elements: Forms consist of various input elements like text fields, checkboxes, radio buttons, select dropdowns, buttons, etc.
    Attributes: Form elements can have attributes like name, id, value, placeholder, required, pattern, etc., to define their behavior and appearance.
    Form Submission: Forms can be submitted using the <form> tag, typically through a submit button or programmatically using JavaScript.

JavaScript Form Validations:

   Client-side Validation: JavaScript can perform validations on form data before submission to ensure it meets specific criteria.
    Event Handlers: Validation logic is often triggered by form events like submit, blur (when an input field loses focus), change (when the value of an input changes), etc.
    Validation Techniques:
        Required Fields: Check if mandatory fields are filled out using the required attribute or JavaScript validation.
        Data Formats: Validate data formats such as email addresses, phone numbers, dates, etc., using regular expressions (RegExp) or built-in HTML attributes like type="email", type="tel", etc.
        Custom Validation: Implement custom validation logic for complex requirements using JavaScript functions.
        Error Messaging: Display error messages near input fields or in a designated area to provide feedback to users about invalid input.
    Preventing Submission: Use event.preventDefault() to stop the form from being submitted if validation fails, allowing users to correct errors before submission.
    Feedback Mechanisms: Provide visual cues (e.g., highlighting fields with errors, changing border colors) to guide users through the validation process.
    Form Reset: Optionally, clear form fields and error messages upon successful submission or when the form is reset.

Benefits of Client-side Validation:

   Improved User Experience: Immediate feedback on input errors improves the user experience by reducing the need for server round-trips.
    Reduced Server Load: Validating data on the client side reduces the number of requests to the server, leading to improved performance and scalability.
    Data Integrity: Ensures that only valid data is submitted to the server, enhancing data integrity and reducing the likelihood of errors in server-side processing.
    
JavaScript enables developers to implement client-side form validations to enhance user experience, improve data integrity, and reduce server load by validating user input before submission.    

<h2>Switch statements</h2>   

Syntax: A switch statement evaluates an expression against multiple possible case values and executes the block of code associated with the first matching case.
 Switch statements are useful when there are multiple possible conditions to evaluate against a single expression, making the code more readable and efficient than using a series of nested if-else statements.Unlike most other programming languages, JavaScript's switch statement does not automatically exit after executing a matching case. Instead, it continues executing statements in subsequent cases until encountering a break statement. This allows for "fall-through" behavior, where multiple cases can execute the same code block.The default case is optional and is executed if no other case matches the expression.

 <h2>Difference between If statement and switch statement</h2>

   1.Expression: Switch statements evaluate a single expression against multiple possible values, while if statements evaluate one or more conditions using boolean expressions.

   2.Conditions: If statements allow for complex conditions and logical operators (&&, ||, !) to be used, while switch statements only compare equality between the expression and case values.

   3.Readability: Switch statements are often more readable and concise when comparing a single value against multiple possible values, whereas if statements are more suitable for complex branching logic and conditions.

  4.Execution: In switch statements, only one case block (or the default block) is executed based on the matching value, while in if statements, multiple blocks can be executed if multiple conditions evaluate to true.

   5.Performance: The performance difference between switch and if statements is negligible in most cases. However, switch statements may be slightly faster when evaluating a large number of cases due to their optimized internal structure.

<h2>Week 3</h2>
<h3>Javascript Events</h3>

avaScript events are actions or occurrences that happen in the browser or document, triggered by user interactions or the browser itself. Here's a summary:

   Definition: Events are interactions or occurrences within the browser environment that can be detected and responded to by JavaScript code.

   Types of Events:
        User Events: Triggered by user interactions such as clicks, mouse movements, keyboard inputs, form submissions, etc.
        Browser Events: Generated by the browser itself, such as page loading, resizing, scrolling, etc.
        Custom Events: Developers can create and dispatch their own custom events for specific purposes.

   Event Handlers:
        JavaScript code can respond to events using event handlers or listeners.
        Event handlers are functions that execute in response to specific events being triggered.
        Common event handlers include onclick, onmouseover, onkeydown, onsubmit, etc.

   Event Listeners:
        Event listeners provide a more flexible and powerful way to handle events compared to inline event handlers.
        They are added to elements using methods like addEventListener, allowing multiple event handlers to be attached to the same event.

   Event Object:
        When an event occurs, an event object is created and passed to the event handler.
        The event object contains information about the event, such as the type of event, target element, mouse coordinates, key pressed, etc.

   Event Propagation:
        Events in the DOM tree propagate through two phases: capturing phase and bubbling phase.
        Event propagation can be controlled using the addEventListener method's third parameter (useCapture) to specify whether the event should be handled during the capturing phase or bubbling phase.

   Event Delegation:
        Event delegation is a technique where a single event listener is attached to a parent element instead of individual child elements.
        It allows handling events for dynamically created or large numbers of elements more efficiently by leveraging event bubbling.

   Preventing Default Behavior:
        JavaScript can prevent the default behavior associated with certain events using the preventDefault method of the event object.
        This is commonly used to prevent form submission, anchor link navigation, or other default actions.

   Event Bubbling vs. Event Capturing:
        Event bubbling propagates events from the target element up to its ancestors, while event capturing propagates events from the root element down to the target element.
        Both phases provide opportunities to handle events at different levels of the DOM tree.
        
<h3>String Operations</h3>

String operations in JavaScript involve manipulating strings, which are sequences of characters. Here's a summary of common string operations:

   Concatenation:
        Joining multiple strings together using the concatenation operator + or the concat() method.
        Example: "Hello" + " " + "World" or "Hello".concat(" ", "World").

   Length:
        Determining the length of a string using the length property.
        Example: "Hello".length returns 5.

   Accessing Characters:
        Accessing individual characters within a string using bracket notation or the charAt() method.
        Example: "Hello"[0] or "Hello".charAt(0) returns 'H'.

   Substring Extraction:
        Extracting substrings from a string using methods like substring(), slice(), or substr().
        Example: "Hello World".substring(6, 11) returns "World".

   Case Conversion:
        Converting the case of characters within a string using methods like toUpperCase() and toLowerCase().
        Example: "Hello".toUpperCase() returns "HELLO".

   String Search:
        Searching for substrings within a string using methods like indexOf(), lastIndexOf(), includes(), startsWith(), and endsWith().
        Example: "Hello World".indexOf("World") returns 6.

   String Replacement:
        Replacing substrings within a string using the replace() method or regular expressions.
        Example: "Hello World".replace("World", "Universe") returns "Hello Universe".

   Whitespace Trimming:
        Removing leading and trailing whitespace characters using the trim() method.
        Example: " Hello ".trim() returns "Hello".

   Splitting:
        Splitting a string into an array of substrings based on a delimiter using the split() method.
        Example: "Hello World".split(" ") returns ["Hello", "World"].

   String Interpolation:
        Building strings dynamically using template literals (enclosed in backticks) with placeholders ${} for variable interpolation.
        Example: `Hello, ${name}!`.

   Character Code Access:
        Accessing the Unicode character code of a character using the charCodeAt() method.
        Example: "Hello".charCodeAt(0) returns 72.

   Character Code Conversion:
        Converting character codes to characters using the String.fromCharCode() method.
        Example: String.fromCharCode(72) returns 'H'.
        
 String operations are essential for manipulating textual data in JavaScript applications, enabling tasks such as formatting, searching, parsing, and modifying strings efficiently.     

 <h3>Dynamic Events</h3>

Dynamic events in JavaScript refer to the process of attaching event handlers to HTML elements that are created dynamically (i.e., added to the DOM after the initial page load):

   Definition: Dynamic events involve attaching event listeners to HTML elements that may not exist when the page initially loads. This is common when elements are added to the DOM dynamically, such as through user interaction or asynchronous data loading.

   Event Delegation:
        Event delegation is a technique where a single event listener is attached to a parent element that exists in the DOM at the time of attaching the listener.
        Events are then allowed to propagate from the target element up to the parent, where the event listener handles them.
        This approach is particularly useful for elements added dynamically, as it ensures that even newly added elements inherit the behavior defined by the event listener.
        Event delegation improves performance by reducing the number of event listeners and simplifies management of event handlers, especially for large or frequently changing DOM structures.

   Using Event Bubbling:
        Event bubbling is the default behavior in which an event triggered on a nested element propagates up through its ancestor elements.
        By leveraging event bubbling, dynamically added elements can trigger events on their parent elements, where event handlers are attached.
        This allows for consistent event handling regardless of when the elements were added to the DOM.

   Applying Event Listeners:
        When dynamically creating elements, event listeners can be attached using JavaScript after the elements are added to the DOM.
        This can be done using methods like addEventListener() to specify the event type and the corresponding event handler function.

   Benefits:
        Flexibility: Allows for the addition of event handling logic to elements that are created or modified dynamically, enhancing interactivity and responsiveness of web applications.
        Efficiency: Promotes efficient use of event handlers by delegating event handling responsibilities to parent elements, reducing memory usage and improving performance.
        Simplified Maintenance: Centralizes event handling logic within parent elements, making it easier to manage and update event-related behavior across the application.

Dynamic events are crucial for building interactive web applications that respond dynamically to user actions and changing data, providing a seamless and engaging user experience. By understanding and leveraging dynamic event handling techniques, developers can create robust and maintainable applications that adapt to evolving requirements and user interactions.

<h2>Keyboards, Form and Document/Window events</h2>

   Keyboard Events:
        Keyboard events are triggered by user interactions with the keyboard, such as pressing or releasing keys.
        Common keyboard events include keydown, keyup, and keypress.
        keydown: Fired when a key is pressed down.
        keyup: Fired when a key is released.
        keypress: Fired when a key is pressed down and then released.
        These events provide information about the key that was pressed, such as its keycode or character value.

   Form Events:
        Form events are triggered by user interactions with HTML form elements.
        Common form events include submit, reset, change, input, focus, and blur.
        submit: Fired when a form is submitted.
        reset: Fired when a form is reset.
        change: Fired when the value of a form element changes (e.g., input, select).
        input: Fired when the value of an input element changes.
        focus: Fired when an element receives focus.
        blur: Fired when an element loses focus.
        These events enable developers to validate form data, perform actions based on user input, and enhance user interaction with forms.

   Document/Window Events:
        Document and window events are triggered by interactions with the browser window or document.
        Common document/window events include DOMContentLoaded, load, resize, scroll, unload, beforeunload, focus, and blur.
        DOMContentLoaded: Fired when the HTML document has been completely loaded and parsed, without waiting for stylesheets, images, and subframes to finish loading.
        load: Fired when the entire page, including all external resources like images and stylesheets, has finished loading.
        resize: Fired when the browser window is resized.
        scroll: Fired when the document is scrolled.
        unload: Fired when the document is being unloaded (i.e., the user is navigating away from the page).
        beforeunload: Fired just before the document is unloaded, allowing the page to prompt the user to confirm leaving the page.
        focus: Fired when the window gains focus.
        blur: Fired when the window loses focus.
        These events enable developers to respond to changes in the document or window state, handle user navigation, and implement various UI/UX features.

 Understanding and effectively utilizing these events is crucial for building interactive and responsive web applications in JavaScript. They allow developers to create dynamic and engaging user experiences by responding to user actions and changes in the browser environment.

<h3>Javascript Slideshow</h3>

JavaScript slideshows are interactive components commonly used to display a series of images or content in a visually appealing manner:

   Definition:
        JavaScript slideshows are dynamic components that cycle through a series of images or content in a slideshow format.
        They often include features like navigation controls (e.g., previous and next buttons), pagination indicators, and autoplay functionality.

   Implementation:
        Slideshows can be implemented using JavaScript, HTML, and CSS.
        HTML: The slideshow structure is typically created using HTML elements such as <div> for the container, <img> for images, and navigation controls.
        CSS: Styling is applied to the slideshow elements using CSS to define the layout, appearance, and transitions.
        JavaScript: Functionality such as transitioning between slides, handling user interactions, and autoplay behavior is implemented using JavaScript.

   Key Features:
        Navigation Controls: Previous and next buttons or arrows allow users to manually navigate through the slides.
        Pagination Indicators: Indicators, such as dots or numbers, show the current slide position and provide visual cues for navigation.
        Autoplay: Automatic transitioning between slides at predefined intervals, enhancing user experience and engagement.
        Transition Effects: Smooth animations or effects (e.g., fade, slide) between slides improve the visual appeal of the slideshow.
        Responsive Design: Slideshows are often designed to be responsive, adapting to different screen sizes and devices for optimal viewing experience.

   Libraries and Plugins:
        There are many JavaScript libraries and plugins available for creating slideshows, such as Swiper, Slick, Glide, and Carousel.
        These libraries provide pre-built components and customizable options, simplifying the implementation process and enhancing functionality.

   Customization:
        Slideshows can be customized to match the design and requirements of a specific website or application.
        Developers can customize aspects such as transition effects, navigation styles, autoplay behavior, and slide content to create unique and engaging presentations.

JavaScript slideshows are versatile components commonly used in websites, blogs, portfolios, and other digital content to showcase images, products, or featured content in an interactive and visually appealing manner. They provide an effective way to capture users' attention and deliver engaging experiences.        
