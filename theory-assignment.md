1. what is Emmet?

Emmet provides a way to write a HTML and CSS code with shortucts and abbreviations, it allows developers to generate repetitive code quickly and efficiently.

Example:

    HTML -

        html:5 - generates html5 boilerplate 
        ui>li - nested elements
        h1.#heading.conatiner.con - Creates h1 tag with id = heading and class = container and con
        header+div+footer - generate siblings

2. Difference between framework and library?
    Library - collection of pre-defined helper functions, objects, classes, modules that can be used in code to boost the development. By using a library, you can control the flow of the application and call the library. Eg: React, JQuery, Lodash

    Framework - Foundation upon which applications are built. In contrast, when you use a framework, the control is inverted, i.e., the framework controls the flow and calls your code. Eg: Node JS, Angular, Spring

3. What is CDN ? Why do we use it ?

    A CDN also called a content distribution network, is a group of geographically distributed and interconnected servers. They provide cached internet content from a network location closest to a user to speed up its delivery.

4. Why is React known as React ?

    React was developed for applications (Facebook) that have constantly changing data. Since React is a front-end framework or the View in MVC, this means that as the user clicks around and changes the app's data, the view should react or change with those user events.

5. What is cross-origin in script tag ?

    The crossorigin attribute provides support for CORS , defining how the element handles cross-origin requests. CORS stands for Cross-Origin Resource Sharing. If cross-origin is set to "user-credential", then user authentication is required to access the file.

6. What is difference between React and ReactDOM?

    React library contains functionality utilised in web and mobile apps (react native). ReactDOM library contains functionality utilised in web browser. It contains DOM manipulation utilities.

7. What is the difference between react.production.js and react.development.js ?

    react.production.js - production code of react library that is minified and production ready. react.development.js - More readable and developer friendly react library code that can be used to debug.

8. What is async and defer - check Akshay Saini's Youtube channel ?

    Without async/defer : Browser stops the html parsing once script tag is encountered. It resumes parsing only after script is fetched and executed.

    Async : Html parsing is done in parallel while scripts are being fetched from the network and executed. Once the script is done with execution, html parsing is resumed. This can be used for external scripts like google analytics. It is better to avoid async for scripts that are dependent on other scripts since we dont know in which order script will be executed.

    Defer : Similar to async, Html parsing is done in parallel while scripts are being fetched from the network. But scripts are executed only after the html parsing is done 
