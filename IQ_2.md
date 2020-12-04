66. Tell me about yourself and current project you are working on?

67. HTML4.1 and HTML5 differences?
<article>	Represents an independent piece of content of a document, such as a blog entry or newspaper article
<aside >	Represents a piece of content that is only slightly related to the rest of the page.
<audio>		Defines an audio file.
<canvas>	This is used for rendering dynamic bitmap graphics on the fly, such as graphs or games.
<command>	Represents a command the user can invoke.
<datalist>	Together with the a new list attribute for input can be used to make comboboxes
<details>	Represents additional information or controls which the user can obtain on demand
<embed>		Defines external interactive content or plugin.
<figure>	Represents a piece of self-contained flow content, typically referenced as a single unit from the main flow of the document.
<footer>	Represents a footer for a section and can contain information about the author, copyright information, et cetera.
<header>	Represents a group of introductory or navigational aids.
<hgroup>	Represents the header of a section.
<keygen>	Represents control for key pair generation.
<mark>	       Represents a run of text in one document marked or highlighted for reference purposes, due to its relevance in another context.
<meter>	Represents a measurement, such as disk usage.
<nav>	Represents a section of the document intended for navigation.
<output>	Represents some type of output, such as from a calculation done through scripting.
<progress>	Represents a completion of a task, such as downloading or when performing a series of expensive operations.
<ruby>	Together with <rt> and <rp> allow for marking up ruby annotations.
<section>	Represents a generic document or application section
<time>	Represents a date and/or time.
<video>	Defines a video file.
<wbr>	Represents a line break opportunity.

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

    Every selector has its place in the specificity hierarchy. There are four categories which define the specificity level of a selector:

    Inline styles - An inline style is attached directly to the element to be styled. Example: <h1 style="color: #ffffff;">.

    IDs - An ID is a unique identifier for the page elements, such as #navbar.

    Classes, attributes and pseudo-classes - This category includes .classes, [attributes] and pseudo-classes such as :hover, :focus etc.

    Elements and pseudo-elements - This category includes element names and pseudo-elements, such as h1, div, :before and :after.

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
