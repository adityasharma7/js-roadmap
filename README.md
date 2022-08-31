# JS Roadmap

## Git Module  
Version Control System - Benefits & types
Git - Introduction
Configuration - Git config
Repository
Commit
Stages of a file - Untracked, Staged, Tracked & Modified/Dirty
.gitignore
Diffing
Branching
Log command
Reset and Revert
Cherry Pick
Merge conflicts
Stashing
Remote
Pull & Push
GitHub & GitLab
Merge Request
Pull Request
Forking

Task:  
1. Set your user name (user.name) and email address (user.email) using terminal
2. Create a GitHub repository for the js assignments with the main branch as default branch.
3. Create a new branch, update ReadMe with description, Add LICENSE file (Apache 2.0) and create a Pull request assigning it to me 
(https://github.com/adityasharma7/hc-js-assignment)

Reference:
https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
https://dev.to/smitterhane/git-pull-vs-git-fetch-66m
https://learngitbranching.js.org/
https://git-scm.com/docs/git-config
https://git-scm.com/docs/git-add 
https://github.com/git-guides/git-init 
https://www.atlassian.com/git/tutorials/inspecting-a-repository 
https://www.atlassian.com/git/tutorials/using-branches 
https://www.atlassian.com/git/tutorials/saving-changes/git-stash 
https://git-scm.com/docs/git-pull 
https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts 
https://docs.github.com/en/get-started/quickstart/hello-world 
https://docs.github.com/en/get-started/quickstart/fork-a-repo 
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests 
https://www.simplilearn.com/tutorials/devops-tutorial/version-control 
https://www.javatpoint.com/git-log 

## HTML:
Introduction to HTML
Elements and Attributes
Classes and identifiers
Forms & Inputs
Semantic HTML

Task:
1. Create a Registration and Login page for an eCommerce website

Reference:
1. https://blog.dareboost.com/en/2020/05/preload-prefetch-preconnect-resource-hints/

## CSS Basic Module:                                                                            Expected: 3 hours
Introduction to CSS
CSS Selectors
Inline, Internal, and External CSS
CSS Properties
Viewport

Reference:
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Properties_Reference
https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit
https://uxplanet.org/figma-all-you-need-to-know-156b52b88e54
https://www.seobility.net/en/wiki/Viewport
https://flukeout.github.io/

## JS Module

### JS Module 1:                                                                                             Expected: 8 hours
Introduction to JavaScript
Variables
var, let, and const
Data types
Primitives
Type Conversions
Operators
Comparisons
Interaction: alert, prompt, confirm
Conditional operators: if, '?'
Logical operators
Loops & iteration
The "switch" statement
Functions
Function expressions
console object and its methods  

Task:
1. Find out about the most popular JavaScript frameworks. (At least 5)
2. Find out about the most popular open-source JavaScript frameworks. (At least 5)
3. Provided the following  array:
    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
   Filter out odd, even, and prime numbers and print them
4. Provided the following  array:
    [0, 2, 4, 6, 8, 10, 12, 14, 16]
Generate and print another list such that: 
 a. every element being twice of elements in the current list.
 b. every element being half of the elements in the current list.
5. Provided the following  array:
    [10, 1, 42, 36, 4, 75, 6, 97, 81, 19, 10]
  a. Find the sum, min, and max
  b. Print “List is full of prime no” if every element is prime
  c. Print “List has a prime no” if there is a prime no in it
  d. Remove duplicate values from the list ()
Note: Use loops for above problems


### JS Module 2:
- [ ] Objects and its methods (Object.keys(), values(), entries())
- [ ] Array
- [ ] Map and Set
Garbage Collection
Explore map(), filter(), reduce(), find(), some() and every() methods
Strict keyword
Cookies
Arrow functions
Task:
1. Find the difference between Object and Map.
2. Identify the difference between regular functions and arrow functions
3. Provided the following  array:
    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
   Filter out odd, even, and prime numbers and print them
4. Provided the following  array:
    [0, 2, 4, 6, 8, 10, 12, 14, 16]
Generate and print another list such that: 
 a. every element being twice of elements in the current list.
 b. every element being half of the elements in the current list.
5. Provided the following  array:
    [10, 1, 42, 36, 4, 75, 6, 97, 81, 19, 10]
  a. Find the sum, min, and max
  b. Print “List is full of prime no” if every element is prime
  c. Print “List has a prime no” if there is a prime no in it
  d. Remove duplicate values from the list.
 
Note: Use map(), filter(), reduce(), some() and every() methods for above problems

 e. Remove duplicate values from the list without using loop or any of the above methods (map(), filter(), reduce(), some() and every())

6.  Provided an array of integers, find if there are any duplicates in the array.

Output:
true -  if any value appears at least twice in the array,
false - if every element is distinct.

Example:
Array ->  [10, 1, 42, 36, 4, 75, 6, 97, 81, 19, 10]
Output -> true

Array ->  [10, 1, 42, 36, 4, 75, 6, 97, 81, 19]
Output -> false

Module 3:                                                                                             Expected: 8 hours
“this” keyword
Constructor functions and the "new" operator.
Numbers
Strings
Array and its methods
Hoisting
Scoping
Super keyword
Error Handling, “try...catch”
throw keyword
Modules
export/import 
Dynamic import
Nested functions
Classes
Class basic syntax
Class Inheritance
Extending built-in classes
Task:
1. Provided following array:

[
{“id”: 1, “name”: “Amit Kumar”, “age”: 25},
{“id”: 2, “name”: “Rahul Dixit”, “age”: 20},
{“id”: 3, “name”: “Ravi Joshi”, “age”: 55},
{“id”: 4, “name”: “Rohit Verma”, “age”: 35},
{“id”: 5, “name”: “Ajay Jain”, “age”: 17},
]

  a. Print id and name of the youngest and oldest person
  b. Create another list having id and name of all the person above 18 years
  c. Find the average age
  d. Create 2 list with names starting with only ‘A’ and ‘R’ respectively


Note: Use map(), filter(), reduce, some() and every() methods for above problems

2.  Try the below code and identify which of the below programs are a valid case of hoisting?

Program 1:
a = 10;
console.log(a);
var a;


Program 2:
a = 5;
console.log(a);
let a;




Module 4:                                                                                             Expected: 8 hours
JSON and its methods(toJSON)
Rest Parameters  
arguments keyword  
Spread Syntax  
Recursion and Stack
Variable Scope
Regular Expressions
Task:
Implement code to deep clone an object using JSON methods
Implement regular expression for name with letters
Implement code for sum using recursion
Reference:
1. 

Module 5:                                                                                             Expected: 8 hours
DOM
Searching: getElement*, querySelector*
Introduction to Events
Introduction to browser events
Bubbling and capturing
Event delegation
Browser default actions
Dispatching custom events

Task: -
Implement 2 event listener on click event of which one executes on bubbling and while other on capture
Reference:
1. https://javascript.info/bubbling-and-capturing

Module 6:                                                                                             Expected: 8 hours
UI Events
Mouse events basics
Scrolling
Forms, controls
Form properties and methods
Focusing: focus/blur
Forms: event and method submit
Page: DOMContentLoaded, load, beforeunload, unload
Scripts: async, defer

Task: -
To change the background color of the second column of a table having “n ” rows on click by using querySelector.


Module 7:                                                                                             Expected: 8 hours
Resource loading: onload and onerror
Popups and window methods
Binary data, files
LocalStorage, sessionStorage
Static properties and methods
Private and protected properties and methods
Class checking: "instanceof"

Task: -
To create a textarea and if a user makes changes to it without saving then show an alert that data is not saved. (Similar to https://stackoverflow.com/questions/ask)
Change the color of the cell to red when the user clicks on a cell and revert when the user again clicks.


Module 8:                                                                                             Expected: 8 hours
Blob
File and FileReader
REST API
GraphQL
XMLHttpRequest and AJAX
Fetch API
Fetch methods
Preflight Request
FormData
URL objects

Task: - 
Change image on runtime when it is not available on the specified path while loading the page.


Module 9:                                                                                             Expected: 8 hours
Date and time
Object to primitive conversion
Scheduling: setTimeout and setInterval
Callbacks
Promise
Promises chaining
Error handling with promises
Promise API
Promisification
Async/await
The "new Function" syntax
Task: -
Implement a simple code to use a Promise
Implement code to handle multiple promises. You have to fetch information of 5 different products from API


Module 10:                                                                                             Expected: 8 hours
Function binding
Custom errors, extending Error
Async iterators and generators
Destructuring assignment
ECMAScript 5(EC5)
ECMAScript 6(EC6)


Module 11:                                                                                             Expected: 8 hours
WebSocket
SPA(Single Page Applications)
SEO(Search Engine Optimization) and how it works with SPA?
SSR(Server Side Rendering)
CORS (Cross-Origin Resource Sharing)
JavaScript & Typescript Best Practices

Task:
Verify your code comply with the best practices and fix them if required.

Reference:
https://www.w3.org/wiki/JavaScript_best_practices
https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS
​​https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/crossorigin 


CSS Advanced                                                                              Expected: 8 hours
Object fit property
Media Queries
Box Model
Specificity
CSS Grid
Flexbox
Comments
Responsive design
Material Design
Figma
NPM and Yarn
Task:
You are writing a responsive layout for a website that has dramatically different layouts for mobile and desktop. Which of the following media queries would you use and why?

@media (max-width: …
@media (min-width: …

Cite 3 sources that back up your position. You cannot cite Stackoverflow.
Provide links for all sources and time codes for videos.




Vue.js Training

Module 1:                                                                                              Expected: 8 hours
Vue.js : Introduction
The Vue Instance
Data and Methods
Instance Lifecycle Hooks
Life cycle diagram
Template Syntax
Computed Property and Watchers

Task:
Create a basic “Hello World!” Vue application.

Module 2:                                                                                             Expected: 8 hours
Declarative Rendering
Conditionals and Loops
Class and Style Bindings
List Rendering
Event Handling
Form Input Bindings
Component Basics
Task:
Create a  new branch from last task and Implement a Login and Registration page

Module 3:                                                                                             Expected: 8 hours
Transitions
Props
Filters
Directives
Custom Directives
Mixins
Slots

Module 4:                                                                                              Expected: 8 hours
Routing
Routing Guards
Working with API
Axios

Task: - 
Create a ecommerce-clone branch and push files & folders generated for new fresh app using Vue CLI 
Create a  new branch from the last task branch and Implement e-commerce web application (Clone any popular website like Amazon, Flipkart etc or any template of your choice) with a home page and top navigation with dead links.
Create a  new branch from the last task branch and add a category page which lists all products belonging to the category.  Create a new PR with the last task branch as the target branch.
You could use Fakestoreapi (https://fakestoreapi.com/) or any other public APIs (https://github.com/public-apis/public-apis)

Module 5:                                                                                              Expected: 8 hours
1. Event Bus
2. State Management
3. Vuex
4. Composition API
Task: - 
Create a  new branch from the last task branch. Add features to sort and filter out products based upon price, color or any other field on the category page. Create a new PR with the last task branch as the target branch.
Create a  new branch from the last task branch. Implement product details page.  Create a new PR with the last task branch as the target branch.

Module 6:                                                                                              Expected: 8 hours
Debugging
Interceptor and its use with Axios
Internationalisation/Localisation in applications
Using Vue I18n (https://kazupon.github.io/vue-i18n/)

Task: -
Implement Registration and Login page.
Store the token in local storage
Implement a interceptor which adds token to headers
Use Axios cache plugin to cache product API
Update application labels to use internationalization



Module 7:                                                                                             Expected: 8 hours
PWA(Progressive Web App)
Service Worker
Precaching
Reference:
1. https://developers.google.com/web/tools/workbox/modules/workbox-precaching




Module 8: 
SSR in Vue and prerendering
Dynamic content rendering in Vue
Vue best practices
Modes and Environment Variables
Dev Tools ()
Postman
Task:
Verify your code comply with the best practices and fix them if required.

Module Resources:
https://vuejs.org/v2/style-guide/
https://v3.vuejs.org/style-guide
https://cli.vuejs.org/guide/mode-and-env.html#modes

Ionic Training
Ionic Framework - Introduction
Hybrid, cross platform and native apps
Cordova and Capacitor
Webview
Components
Slots

Task:
Build Netflix/Twitter UI using Ionic components.
Reference:
https://www.youtube.com/playlist?list=PLgsLdFrhfGLTYUUf5dwD6YiT9a1O9QHoE
https://www.youtube.com/watch?v=_X0FzNBKEZg&list=PLgsLdFrhfGLQ9tz-akOEucCch8HjHgOlc
https://www.youtube.com/watch?v=qoH3-JISa4w&list=PLgsLdFrhfGLRNhU4DL8a0ONEAUhcAfdXR
https://youtu.be/3_XPLojd83I
https://youtu.be/xCZmlkKc36Y
https://youtu.be/zyBY4xTga8M 
https://youtu.be/lhY79cBaH_o
https://youtu.be/WKwfP_6e044
https://youtu.be/P4ok5td5_gY 
https://youtu.be/ySVNifnuq3Q 
https://youtu.be/n0q8E615eOI
https://youtu.be/xSy73Fx0qlE 
https://youtu.be/-rkHVDLSSrU 
https://youtu.be/PY5xqeWYpTw 
https://youtu.be/Xk_Jc7BwJqw 
https://youtu.be/OobddatK434 
https://ionicframework.com/docs/core-concepts/fundamentals
https://ionicframework.com/getting-started
https://ionicframework.com/docs/vue/quickstart
https://ionicframework.com/docs/core-concepts/cross-platform
https://ionicframework.com/docs/core-concepts/webview
https://www.youtube.com/channel/UC1zRV-9GAScMjydTPRf-tSw
https://capacitorjs.com/
https://capacitorjs.com/docs
https://www.youtube.com/watch?v=d70jQxQuSeY
https://stackoverflow.com/questions/63084828/gitignore-for-an-ionic-project-with-android-target
https://developer.apple.com/design/human-interface-guidelines/ios/views/popovers/
https://www.youtube.com/watch?v=0ZiSjFj8tMI&list=RDCMUCZZPgUIorPao48a1tBYSDgg&start_radio=1
