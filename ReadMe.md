1. Introduce yourself and about the current project?

   I am core UI Developer and my area of expertise involves building the .com website using html5, css3, javascript, react, angular and redux. Currently I am working for capital group in building tool called creative workbench. It is a writing tool where writer, designer and project manager can write the articles and publish it to capital ideas website. Not only focused on the development but also involved in integration of apps like discover, disclosure, percolate and workfront to creative workbench.

2. Have you used react? redux?

   React is a JavaScript library for building user interfaces. I am working from past 3 years on ReactJS.
   Redux is a predictable state container for JavaScript apps. Redux is used for application state management.
   It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. we can use Redux together with React, or with any other view library.

3. Asynchronous calls?

- "axios" module used to make the asynchronous calls.
  GET Request - fetch all employee information
  POST Request - add new employee
  PUT Request - update employee information
  DELETE Request - delete the existing employee.

4.  For Making API calls what did you use? Axios

5.  Have you heard about the Vertex library?
    A vertex represents a 2D point in the image. NOTE: the vertex coordinates are in the same scale as the original image.

6.  Have you used other library other than react?
    DENO, ExpressJS, VueJS
    ExpressJS - - express module is 3rd party module, used to develop Rest API.

7.  API methods? Axios.get(), Axios.post()

8.  employee information --> submit rest api calls--> submit or save button

9.  Explain how to manage the state?
    React Component LifeCycle Hooks

            1. constructor
            2. componentWillMount()
            3. render()
            4. componentDidMount()
            5. componentWillReceiveProps()
            6. shouldComponentUpdate()

            // component kill methods

            7. componentWillUpdate()
            8. componentDidUpdate()
            9. componentWillUnmount()

Context API, useEffect, useState --- Newly added version by version

Explanation:

# Constructor()

        constructor will execute at booting time of component --constructor will execute only once
        Define state in constructor

# componentWillMount()

        componentWillMount() will execute after constructor
        componentWillMount() will execute only once
        in general we will do the initial modifications in state
        in general we will set global parameters like width, height

# render()

        after componentWillMount() automatically render() function will execute
        render() is mandatory lifecycle hook(main lifecycle hook)
        in general, we will place presentation logic in render()
        when ever change detected in state or props automatically this lifecycle hooks will execute

# componentDidMount()

        after render function immediately componentDidMount() life cycle hook will execute
        in general we will make asynchronous calls in ComponentWillMount()
        this is recommended state to change the state of component

# componentWillReceiveProps()

        when component will receive props from redux

# shouldComponentUpdate()

        if we want to update the state return "true" else "false"

# UNSAFE_componentWillUpdate()

        death method --> perform cleanup operations

# componentDidUpdate()

        if we integrate any third party UI elements
        plugin logic will write here

# componentWillUnmount()

        Before killing the component componentWillUnmount is executed.
        death method --> perform cleanup operations

10. what is state and props?

    ### State

    • state is the predefined object in react library
    • state used to store the component data.
    • we will define state by using "state" keyword
    • "state" keyword is the predefined keyword.
    • constructor is the best place to define the state

    ### Props

    In a React component, props are variables passed to it by its parent component.
    Example: EMS application SideBar, Header, PageHeader, Footer. Passing the data from parent component to child component is called props. Title, subtitle, icon.

11. what is class level and functional level component ? differences.
    A functional component is just a plain JavaScript function which accepts props as an argument and returns a React element.
    A class component requires you to extend from React. Component and create a render function which returns a React element.

12. What is reducer?
    A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.

13. arrow function ?

    Anonymous Functions / Arrow Functions / Fat Arrow Functions / CallBack Functions

    - without name
    - ES6
    - ()=>{}
    - Arrow functions acts like "callbacks" to receive the response from server.

14. what is this? with Es6 features
    this refers to the current context and current object the code is written in.
    in constructor functions, everything will start with "this" keyword.

15. JSON? explain.

- JSON Server used to create the rest apis.

      GET
      POST
      PUT
      DELETE
      HEAD
      ----
      ----
      ----

  - json server supports only json.

  - json server is light weight server.

  - by default json server running on port no.3000

  - we will install json server by using following command.

    > npm install -g json-server@latest

    - "npm" stands for node packaging manager.

    - "npm" is the part of nodejs.

    - "-g" stands for global installation

  - we will deploy the json files by using following command.

    > json-server --watch demo.json

  - we will test the rest apis by using "Postman".

16. Do you follow the Agile methodology? Sprint Planning?

    Agile is a process by which a team can manage a project by breaking it up into several stages and involving constant collaboration with stakeholders and continuous improvement and iteration at every stage. This clarifies the customer's expectations to the project team.

17. How many members are there in the team?
    Product owner-mika
    Designer-brian
    Manager-ricardo
    Scrum master/po- haseeb rahman
    Project Head- Doug Mehagan
    Front end vijay
    Architect manish
    Backend viraj
    Front end+ backend jitendra
    Product owner - Eric Chen

18. how do you implement the feature from start to end?
    After having a brief discussion with writer the designer comes up with requirements and Zeplin designs to build App.
    Once the design is ready we divide each sprint into stories. Each sprint is 2 weeks we need to complete all the stories in 10 days and move to testing, complete in JIRA board.

19. Backend vertex front end oneapp Amex is using.

20. are you comfortable with working in the backend?

        Yes i get oppotunity i can work on backend.

    =====================

21. What are the different JavaScript Data Types?
    undefined, Boolean , Number , String , BigInt , Symbol

22. What is ES6 and what are some features of ES6?
    ES6 is ECMAScript 6. It is nothing but Javascript Version.
    ES6 allows let and const for variable declaration.
    we have 8 types of functions (ES6-ES11)

        1) Named Functions

        2) Anonymous Functions / Arrow Functions  (ES6)

        3) Rest Parameters in Functions

        4) Default Parameters in Functions

        5) Optional Parameters in Functions

        6) IIFE (Immediate Invokable Functional Expressions) (ES9) (2019)

        7) Generator Functions

        8) Constructor Functions.

23. How is ReactJS different than Angular?

    ReactJS is UI library(View), Angular is Framework(MVC).
    React follows 1-way data binding, angular follows 2-way data binding.

24. What are some examples of key features required of web sites to be Accessible?
    Good use of HTML headings(<h1> - <h6>).
    Accessible with keyboard, images, menus, forms, tables, color, link text.

===============================

25. Tell me about your current project?

26. How many years of experience on react?

27. What CSS styling did you use? Did you use SASS ?

    Sass (which stands for 'Syntactically awesome style sheets) is an extension of CSS that enables you to use things like variables, nested rules, inline imports and more. It also helps to keep things organised and allows you to create style sheets faster.

28. What is the disadvantage of Closure?
    One drawback to using closures is that they can lead to over-consumption of memory, and possibly memory leaks if not handled properly.

29. What is Babel?
    React uses JSX syntax. Babel is a transpiler i.e. it converts the JSX to vanilla JavaScript. React also uses ES6, which is not supported by most of the browsers. Babel converts the ES6 code to a code which is compatible with the browsers.

30. How to install multiple packages in package.json? How are they classified?
    Normal dependency, dev dependency, peer dependency
    json is used to store the metadata associated with the project as well as to store the list of dependency packages.
    In order to add dependency packages to your projects, you need to create package. json file. The file makes it easy for others to manage and install the packages associated with the project.

31. What is strict mode in react?

    StrictMode is a tool for highlighting potential problems in an application. Like Fragment , StrictMode does not render any visible UI. It activates additional checks and warnings for its descendants. Note: Strict mode checks are run in development mode only; they do not impact the production build.

32. Have you used redux?
    Redux for state management. When you make ajax call update redux store.
    Redux is a predictable state container designed to help you write JavaScript apps that behave consistently across client, server, and native environments and are easy to test. With Redux, the state of your application is kept in a store, and each component can access any state that it needs from this store.

33. Have you used context api?

    React Context API is a way to essentially create global variables that can be passed around in a React app. This is the alternative to "prop drilling", or passing props from grandparent to parent to child, and so on. Context is often touted as a simpler, lighter solution to using Redux for state management.

34. Have you used Memo() hooks?

    React's useMemo Hook can be used to optimize the computation costs of your React function components. While useMemo is used to memoize values, React memo is used to wrap React components to prevent re-renderings.

35. What does useEffect do?
    By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we'll refer to it as our “effect”), and call it later after performing the DOM updates.

36. What testing library did you use? Explain? What is jest and enzyme?

    Jest is a unit test framework designed by Facebook to test react applications. Jest allows to write unit tests using the Snapshot feature. Enzyme allows to write unit tests using regular assertions. Using Enzyme with Jest makes writing tests for React applications a lot easier.

37. Difference between shallow() and mount()?
    shallow() tests components in isolation from the child components they render while mount()goes deeper and tests a component's children.

38. What technologies are you using? Html5, css3, JavaScript, ReactJS, Angular 10, Redux.

39. Team size 8-10 people. Different technologies. EDAM, Disclosure, Discover,Material-UI, Bootstrap, React, Java, Microservices.

==============

40. How to deploy applications in multiple environments and how do you configure it? Do you have hands on experience on pipelines?
    environment --> Development, Staging/QA , Production

41. What is VirtualDOM and Real DOM? Does react use Virtual DOM or not?
    A virtual DOM object has the same properties as a real DOM object, but it lacks the real thing's power to directly change what's on the screen. Manipulating the DOM is slow. Manipulating the virtual DOM is much faster, because nothing gets drawn onscreen.

42. What is State and Props? Differences?

    In a React component, props are variables passed to it by its parent component. State on the other hand is still variables, but directly initialized and managed by the component. The state can be initialized by props.

43. How do you manage state in react without redux? usecontext and contextapi

    React Context API is a way to essentially create global variables that can be passed around in a React app. This is the alternative to "prop drilling", or passing props from grandparent to parent to child, and so on. Context is often touted as a simpler, lighter solution to using Redux for state management.

44. What is axios and fetch ?

    Axios is a library that helps us make http requests to external resources. In our React applications we often need to retrieve data from external APIs so it can be displayed in our web pages. Axios uses methods like get() and post() that perform http GET and POST requests for retrieving or creating resources.

45. Which methods are used in React? GET, POST, PUT, DELETE

46. What is Axios? Axios is an hugely popular HTTP client that allows us to make GET and POST requests from the browser. Therefore, we can use Axios with React to make requests to an API, return data from the API, and then do things with that data in our React app.

47. What is prime react controlles ? substitue for bootstrap and material ui
    PrimeReact is a rich set of open source native components for React.
    PrimeReact is available at npm, if you have an existing application run the following commands to download PrimeReact and PrimeIcons to your project.
    npm install primereact --save
    npm install primeicons --save

48. How does routing work in react JS?
    React Router is a standard library for routing in React. It enables the navigation among views of various components in a React Application, allows changing the browser URL, and keeps the UI in sync with the URL. Let us create a simple application to React to understand how the React Router works.

49. how to bundle in react?
    Run npm run build or npx react-scripts build to create an optimized production build for your React App and then run the command npx gulp to bundle all the JS and CSS files in the static build folder into the single main html file.

50. What is Mobx.js ? mvvm pattern how to implement?
    MobX is a battle tested library that makes state management simple and scalable by transparently applying functional reactive programming (TFRP).

51. how to implement lazy loading in react?
    Lazy loading is the technique of rendering only-needed or critical user interface items first, then quietly unrolling the non-critical items later.

52. What is swagger UI used for?
    Swagger UI allows anyone — be it your development team or your end consumers — to visualize and interact with the API's resources without having any of the implementation logic in place.

53. What are the solid principle in oops?
    React is based on Javascript which is obviously object oriented(but not exactly similar to languages such as Java, C++, and many other traditional Object Oriented languages ).

    React itself does not enforces any object oriented technique but React components are totally reusable. You can create generic components from very simple input text box, labels to complex one and can be reused many times.

54. Jquery? SASS?
    jQuery is a lightweight, "write less, do more", JavaScript library. The purpose of jQuery is to make it much easier to use JavaScript on your website. jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

    Sass is a stylesheet language that's compiled to CSS. It allows you to use variables, nested rules, mixins, functions, and more, all with a fully CSS-compatible syntax. Sass helps keep large stylesheets well-organized and makes it easy to share design within and across projects.

55. I have 2 different types of users 1 simple user and 2nd is premium user but css is written in separate modules and based on the user login i want to load particular css only.

    After logging in i will make a fetch call and inject the link tag dynamically

56. What is lazy routing?
    Code-splitting your app can help you “lazy-load” just the things that are currently needed by the user, which can dramatically improve the performance of your app. While you haven’t reduced the overall amount of code in your app, you’ve avoided loading code that the user may never need, and reduced the amount of code needed during the initial load.

57. Did you build the application in Multi lingual like english and spanish? No

58. What are the features of ES6
    ES6 is ECMAScript 6. It is nothing but Javascript Version.
    ES6 allows let and const for variable declaration.
    we have 8 types of functions (ES6-ES11) 1) Named Functions 2) Anonymous Functions / Arrow Functions (ES6) 3) Rest Parameters in Functions 4) Default Parameters in Functions 5) Optional Parameters in Functions 6) IIFE (Immediate Invokable Functional Expressions) (ES9) (2019) 7) Generator Functions 8) Constructor Functions.

59. How do you link in react?
    To add the link in the menu, use the <NavLink /> component by react-router-dom . The NavLink component provides a declarative way to navigate around the application. It is similar to the Link component, except it can apply an active style to the link if it is active.

60. What is react router used for?
    React Router, and dynamic, client-side routing, allows us to build a single-page web application with navigation without the page refreshing as the user navigates. React Router uses component structure to call components, which display the appropriate information.

61. Why Webpack is used in react?
    Webpack is a popular module bundling system built on top of Node. js. It can handle not only combination and minification of JavaScript and CSS files, but also other assets such as image files (spriting) through the use of plugins.

62. What is Switch in router?
    It just means that whenever a route's path matches the url path, the router will render the route's component.

63. What is node.js ? purpose of node ? why ?

    - Node JS is Server Side Scripting language.
    - by using NodeJS we can develop Http Servers.
    - we can develop Node Applications by using JavaScript.
    - Node Follows Event Driven Model.
    - Node Supports the Modules
      Predefined Modules & Custom Modules

64. What is functional component and Class Component?
    A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React. Component and create a render function which returns a React element. There is no render method used in functional components.

65. How to make functional component as state component? useState hook
    useState is a Hook that lets you add React state to function components.

---

66. Tell me about yourself and current project you are working on?

67. HTML4.1 and HTML5 differences?
    <!-- <article> Represents an independent piece of content of a document, such as a blog entry or newspaper article
    <aside > Represents a piece of content that is only slightly related to the rest of the page.
    <audio> Defines an audio file.
    <canvas> This is used for rendering dynamic bitmap graphics on the fly, such as graphs or games.
    <command> Represents a command the user can invoke.
    <datalist> Together with the a new list attribute for input can be used to make comboboxes
    <details> Represents additional information or controls which the user can obtain on demand
    <embed> Defines external interactive content or plugin.
    <figure> Represents a piece of self-contained flow content, typically referenced as a single unit from the main flow of the document.
    <footer> Represents a footer for a section and can contain information about the author, copyright information, et cetera.
    <header> Represents a group of introductory or navigational aids.
    <hgroup> Represents the header of a section.
    <keygen> Represents control for key pair generation.
    <mark> Represents a run of text in one document marked or highlighted for reference purposes, due to its relevance in another context.
    <meter> Represents a measurement, such as disk usage.
    <nav> Represents a section of the document intended for navigation.
    <output> Represents some type of output, such as from a calculation done through scripting.
    <progress> Represents a completion of a task, such as downloading or when performing a series of expensive operations.
    <ruby> Together with <rt> and <rp> allow for marking up ruby annotations.
    <section> Represents a generic document or application section
    <time> Represents a date and/or time.
    <video> Defines a video file.
    <wbr> Represents a line break opportunity. -->

68. Local storage vs session storage

    - whenever we close the browser, opens the new tab data won't be lost, then such type of storage called as local storage.

    - whenever we close the browser, opens the new tab data will be lost from session storage.

    - "localStorage" is the predefined object in JavaScript, used to work with the local Storage.

    - "sessionStorage" is the predefined object in JavaScript, used to work with the session Storage.

69. Why we need HTML, CSS, JS ? purpose ? how they communicate?
    HyperText Markup Language (HTML), Cascading Style Sheets (CSS), and JavaScript are the languages that run the web. HTML is for adding meaning to raw content by marking it up. CSS is for formatting that marked up content. JavaScript is for making that content and formatting interactive.

70. Have you build application for mobile platform ? minwidth or maxwidth?

71. Did you run your application on IE 11 vs chrome what is the difference?

72. HTML5 new elements?

73. HTML5 Semantic Web? types?
    Semantic elements = elements with a meaning.
    A semantic element clearly describes its meaning to both the browser and the developer.

    Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.

    Examples of semantic elements: <form>, <table>, and <article> - Clearly defines its content.

## CSS IQ

74. display:none, display:block visibility property in css

    The display property is the most important CSS property for controlling layout.

    The display property specifies if/how an element is displayed.

    Every HTML element has a default display value depending on what type of element it is. The default display value for most elements is block or inline.

75. What is Inline CSS, Internal CSS, External CSS?
    CSS can be added to HTML documents in 3 ways:
    Inline - by using the style attribute inside HTML elements
    Internal - by using a <style> element in the <head> section
    External - by using a <link> element to link to an external CSS file

76. What does a css elements hierachy? class, id, attributes, tag

- Every selector has its place in the specificity hierarchy. There are four categories which define the specificity level of a selector:

- Inline styles - An inline style is attached directly to the element to be styled. Example: <h1 style="color: #ffffff;">.

- IDs - An ID is a unique identifier for the page elements, such as #navbar.

- Classes, attributes and pseudo-classes - This category includes .classes, [attributes] and pseudo-classes such as :hover, :focus etc.

- Elements and pseudo-elements - This category includes element names and pseudo-elements, such as h1, div, :before and :after.

77. display: block !important;
    he display property specifies the display behavior (the type of rendering box) of an element.

    In HTML, the default display property value is taken from the HTML specifications or from the browser/user default style sheet. The default value in XML is inline, including SVG elements.
    p.ex1 {display: none;}
    p.ex2 {display: inline;}
    p.ex3 {display: block;}
    p.ex4 {display: inline-block;}

78. media queries?

    Media queries in CSS3 extended the CSS2 media types idea: Instead of looking for a type of device, they look at the capability of the device.

    Media queries can be used to check many things, such as:

    width and height of the viewport
    width and height of the device
    orientation (is the tablet/phone in landscape or portrait mode?)
    resolution

79. css precprocessor?
    SASS

80. why jqeuery?
    jQuery is a lightweight, "write less, do more", JavaScript library. The purpose of jQuery is to make it much easier to use JavaScript on your website. jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

## JS

81. === vs ==
    compares 2 values
    === there is strict check for the datatype

82. datatypes in JS?

undefined : typeof instance === "undefined"
Boolean : typeof instance === "boolean"
Number : typeof instance === "number"
String : typeof instance === "string"
BigInt : typeof instance === "bigint"
Symbol : typeof instance === "symbol"

83. how to convert string to integer?

    parseInt("3"), Number("3")

84. How will you debug the errors in code ?

breakpoints, reverse engineering, f8 line by line execution

85. What is class vs filter?

    collection of "variables" and "functions" called as class

    before ES6 version, we will create classes by using "constructor functions"

    Filter() it is used to create the new array based on condition

86. how do you integrate aem with react?

87. which version of java did you use?
    1.8

88. What is <label> and what comes after <label>?

    Always add the <label> tag for best accessibility practices!
    <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
    <label for="vehicle1"> I have a bike</label><br>

=====================

89. "Function.prototype.call()" & "Function.prototype.apply()" difference in what scenario you use them?

Call() -- if we want to create second memory location will interact with 1st memory location.

Apply() – if we want to pass array instead of independent parameter

91. What is diff between function & Arrow function

## Named Functions

    - The function with the particular name(custom) called as Named Function.

    - we will create the functions by using "function" keyword.

## Syntax

//function definition
function functionname( parameters ){
//business logic
};

//call the function
functionname(arguments)

## Anonymous Functions / Arrow Functions / Fat Arrow Functions / CallBack Functions

    - without name
    - ES6
    - ()=>{}

92. What is closure?

    - if any inner function holding the outer function data, then such scenario called as closure.

93. What is currying function?

    - converting the complex level business logic to readable code is called currying.

    - loosely coupled code is nothing but currying.

    - converting tighlty couple code to easily readeable code is currying.

94. Hoisting ? Definition? Syntax error why? What happens with var and let keyword?
    • accessing any variables before declaration.
    • variable hoisting because of "var" keyword.
    • we can overcome variable hoisting with "let" keyword.
    • getting undefined instead of error called variable hoisting.

95. Difference between state and props in React?

    ## state

    store the component data.

    ## props

    properties, passing data from parent to child component

96. Can a callback function passing as prop? Scenario how code works?

    Passing "one function" to "another function" as an argument called as "CallBack"

97. how to update state value?

    The only way to update a state inside a store is to dispatch an action and define a reducer function to perform tasks based on the given actions. Once dispatched, the action goes inside the reducer functions which performs the tasks and return the updated state to the store. This is what Redux is all about.

98. is "setState" async method? Yes or no ? Explain?

99. Coding questions--> have use used the second argument of "setState"?

100.  What is the difference between Server Side rendering and Client side rendering? Did you work on server side rendering?

101.  What is "this" keyword? Why is "this" keyword a current class member or current obj?

102.  Did you work on writing tools?

103.  Explain current project in detail?

104.  How to balance state from front end and backend?

105.  Explain the application architecture? Redux architecture?

106.  Using a function syntax add 2 numbers?

107.  What is difference between callback function and arrow function?

108.  How to read the null inside the console.log for call() and apply()

109.  What is class in JavaScript?

110.  Define Arrow function? Why arrow functions are more secure? Some code show how arrow function works? Arrow function is not call back function why?

111.  What is settimeout()? Write code that prints 1 for every 1 second?

112.  Difference between var and let keyword? Syntax?
      var let


    1) ES1                               1) ES6

    2) duplicate variables allowed       2) duplicate variables not allowed

    3) won't obey scope rule             3) obeys scope rule

    4) global polluting issue raised     4) we can overcome global polluting issue

    5) variable hoisting raised          5) we can overcome variable hoisting

    6) var keyword is the global scope6) let keyword is the block scoped member
       member
