# Interview Questions which i appeared for

Technical Question:
1.
```javascript
(function() {
    console.log(1); 
    setTimeout(function(){console.log(2)}, 1000); 
    setTimeout(function(){console.log(3)}, 0); 
    console.log(4);
})();
```

=> 
Output = > 1 4 3 2

2. Find two elements in an array such that their sum equals target return indexes
arr = [2,4,9,6,5] and element target = 14

3. Guess the output
```javascript
console.log('start');
const promise1 = new Promise((resolve, reject) => {
  console.log(1)
  resolve(2)
  console.log(3)
})
promise1.then(res => {
  console.log(res)
})

console.log('end');
```
=> Output => start 1 3 end  2


* Is Node a single threaded application? how it handles concurrency
* diff between filter and find ?
* How to prevent Callback Hell ?
* What is use of body-parser? 
* What are middlewares ?
* What is payload ? Can we use it with other http methods ?
* What is map ?
* primary & foreign key difference
Important concepts:- 
1. Arrow function
2. Normal function
3. Hoisting
4. Closure
5. Namaste javascript (See his videos on YouTube channel)
6. Async await
7. Promises
8. Spread operator (...) function reference or call are called?
9. Event loop
10. New features in ES6 node js
11. Is asynchronous function present in javascript? Then why node js is called asynchronous? Is it came from node or js?
12. Body parser node js?

• INTERVIEW-1 Questions (javascript & node.js):
1. Square of even number return in array using map.
2. Difference between map and filter.
3. SessionStorage vs LocalStorage. (js)
4. Data binding in angular? (ngModel, ngValue, etc) (expression/interpolation binding, property binding, event binding, two way binding)
5. Authentication vs Authourization ? (JWT token)
6. What security you used in your project ? (JWT, multifactor authentication, cors, rate limiting, express-validator, environment variables, helmet)
7. How we connect mongodb to node.js
8. How can you reduce or optimize the time in your project?
9. What problems you faced in your project?
10. There is a Student table, and you need to update the address in the table. How will you do it?

• INTERVIEW-2 Questions (javascript & node.js):
1. How to increse the core size if node.js is a single threaded and uses only 1 core? (I have 8 core and want to use all cores - use clusture)
2. Authentication vs Authorization ?
3. Promises. (reject & resolve)
4. If node.js is asynchronous and if we want to make it synchronous then what should we do? (If we want to wait for some data before sending to the client server) (ans: use callback, promises, async await)
5. How do you provide Authentication in your app?
6. Can you tell me? What work you have done in node.js side?
7. What is the use of Express? What does it do beyond routing?
8. Diffrence between "in" and "of" in for loop?

• INTERVIEW-3 Questions (Angular and scenario based questions):
1. http interceptor (An HTTP interceptor intercepts all HTTP requests/responses in Angular, used to add tokens, handle errors, modify headers, and show loaders globally. )
2. constructor vs ngonint
3. Where we should add services in constructor or in ngOnInit? Why?
4.  Interface and Abstract
5. How will you show relatime data from database into your frontend? (use socket)

• INTERVIEW-4 Questions (NodeJS Question)
1. If Node.js is single threaded then how it handles concurrency?
2. Two types of queue in node.js. What they are? [Ans: 1. Built-in Event Queue (Event Loop), 2. Custom Queues]
3. Authentication and Authorization. (where you can set the token and authorize the user)
4. Custom --- (not remeber - skip this)
5. Promise and Promise.all 
6. Why don't we use a for loop to collect data from multiple requests instead of Promise.all in Node.js? (Ans: Using a for loop to handle multiple requests in Node.js can lead to callback hell or inefficient sequential execution, as it may not take advantage of asynchronous operations effectively. Promise.all, on the other hand, allows you to parallelize multiple asynchronous tasks, improving performance by executing them concurrently. It's a more scalable and readable approach for handling multiple asynchronous operations in Node.js.)
7. CORS ? (A browser security mechanism that controls whether)
8. What is Middleware? Tell me one of the middleware name. (Express) [1. Express Middleware, 2. Body Parser Middleware 3. Logging Middleware 4. Authentication Middleware]
9. How to use JOIN ?
10. What is inner join and outer join ? (see all the joins)
11. Difference between http and https?

• INTERVIEW questions - 5 (Angular questions)
1. RxJS?
2. RxJS Operator
3. Observable vs promises
4. Pipe
5. Map operator in RxJS
6. Write a program to show count of duplicate names in array. E.x arr1 = ["krish", "krishn", "ashw"].
7. Latest features in Angular.

• INTERVIEW questions - 6.1 (Drishtee L1)
1. If node js is single threaded then how it handle concurrency?
2. Disadvantages of node js? In which type of application we have to avoid node js ? (Computational, CPU-Intensive Applications, Applications with Heavy Data Processing Requirements)
3. Can we use multi-threading in NodeJS? How? (Cluster, worker_threads)
4. How do you use API in your project? (tell them about how you call api from angular side, then it comes to node then you use Express, routing(get, post, delete, put), middleware like this and last you store the data inside the database.)
5. Tell them how your project work? What type of work you have done on your project?
6. What is import in node js?
7. What are the two types of API in Node js? (Asynchronous-non-blocking, Synchronous-blocking)

• INTERVIEW questions - 6.2 (Drishtee L2)
1. NodeJS pros & cons.
2. NodeJS Features (Highly scalable, Event driven, Non-blocking) 
3. ES6 Features (map, find, filter, (constants or immutable variables => let, const, var), Rest & Spread parameter, promises, classess, modules, multi-lines String)
4. How to create table using postgres. 
5. How to create schema for user which has {name, mobile, email} in postgres. e.g. CREATE TABLE users ( id SERIAL PRIMARY KEY, name VARCHAR(100) NOT NULL, mobile VARCHAR(15) UNIQUE NOT NULL, email VARCHAR(100) UNIQUE NOT NULL );
6. Install Express and Print "Hello World" using express get API.
7. Remove Duplicate Element from array using spread operator. e.g. arr = [1,2,3,4,5,1,2,3,4,5] ans => [...new Set(arr)]
8. Write Object, how to declare variables, how to declare object array.
9. Reverse the string using JS. (string = 'krishna', then string.split("").reverse().join(""))
10. Event Flow for Node JS or Control flow function ? (generic piece of code runs between several asynchronous functions, tell them about event loop)
11. Why dont we use NodeJS for highly computational work? explain with example. (single-threaded and event-driven) (Node.js is excellent for building scalable network applications due to its non-blocking nature)
12. What are your Role & Responsibilities in your project ?
13 What is callback & Callback hell?


• Interview questions - 7 (Adit - Ahamadabad Company - WFH - MEAN Stack)
-- Node JS:
1. Rest and Spread Operator.
2. Event Loop.
3. Socket, What is event emmiter in node js?
4. What is middleware? Explain with example. (request handler which allow us to intercept or manipulate req, res) (you can change req.body)
5. Do you know about CI/CD pipelines? How do you build your project? (Optional)
6. If setTimeout is used then how the event loop will work for this task. (It will create microservice queue and priorties the queue and first perform task inside microservice queue and the it will perform event queues tasks.)
7. If i have to perform 4 api request and r1,r2,r3 requests data is needed to perform the r4th request then what will you do? (use promise.all e.g. promise.all([r1, r2, r3]))
8. Let, const & var difference.

-- Angular
1. What are directives ? (adding behaviour to existing DOM element)
2. How do you send data from one component to another component. (Parent to Child via @Input decorator, Child to Parent via @Output decorator and EventEmitter, Child to Parent via @ViewChild decorator, Datasharing service)
3. Difference between Observable and Promise. (promise are eager use .then, observable are lazy use subscribe)

-- Tell me the Output:
```javascript
// problem 1
console.log(isNaN(true)) // false (isNaN is always false) if there is isNaN(NaN) then true
```

```javascript
// problem 2
let arr = [1,2,3,4,5]
let arr1 = [6,7,8]
let arr2 = [...arr, ...arr1]
arr2.splice(0, arr1.length - 1)
console.log(arr2) // [3,4,5,6,7,8]
```

```javascript
// problem 3
var a = 0;
console.log(a) // 0
```

```javascript
// problem 4
console.log(a); // Cannot access 'a' before initialization
let a = 0;
```

```javascript
// problem 5
const promise = new Promise((resolve, reject) => {
    console.log('111');
    resolve('222');
});
console.log('333')
promise.then(message => 
    console.log(message) // 111, 333, 222
)
```

• Interview questions - 8 (Impetus AI) (Coding Programs)
1. Find the missing elements between min and max in array. 
```javascript
// Input:  [5,3,8,10,14,5,7,15,17,12]
// Output: [4,6,9,11,13,16]
```

2. JavaScript Program to Check Valid Parentheses Using String

• Interview questions - 9 (neoSoft - Pune)

1. JWT Token, expiration, how it work?
2. How to authenticate any user with JWT token.
3. What is use of middleware.
4. How to use express in node js.
5. How do you encrypt the password when user registered.
6. Indexing in Database.

• Interview questions - 10 (neoSoft - Mumbai)

1. Slice & Splice Difference in JS
2. Rest and Spread operator.
3. Do you use ORM in your Project? or used Raw queries?
4. ACID Property in DBMS.
5. What is advantages of PostgresSQL over SQL. (Postgres support many datatype and prefer for Write operations and complex queries, MySQL used for read operation Basically.)
6. What are the use of Express?
7. What is the CORS? If we dont use the CORS then can we unable to create connection between frontend & backend? (without CORS we can create connection using Websocket, JSONP, Proxy server)
8. Predefined modules in node js. (e.g. fs, http, https, path, OS, events, util, stream, buffer, crypto, queryString, url, timers)
9. Parse package in node.js.
10. How to alter two columns in database. (i.e. add two columns in existing table)
11. Cluster in node ?
12. Shallow copy & Deep copy. (shallow copy - original object modifies, deep copy - original object cannot modify)
13. When we declare const name =  "Krishna" then we cannot change its content, but if there is an object i.e. name = {id: "krishna"}. then we can change it inner content. Why? (const ensures that the reference to the object is constant, not the object content)
14. When we declare an object with a key named 'name', how can we match the key name of the object? (Object.keys(var_name))
15. Hoisting in JS.
16. Put & Patch difference in JS.
17. Which is faster process nextTick() and setImmediate() in node?
18. Call by reference vs Call by value. (
e.g. call by value - Original value cant be affected
```javascript
function test(a){
     a = 10; 
     console.log(a) // 10
}
let b = 5
test(b)
console.log(b) // 5
```

call by reference - Original value get affected
```javascript
function test(obj){
     object.name = 'john'
     console.log(obj) // 'john'
}
let person = {name: "Krish"}
test(person)
console.log(person) // 'john'
```

• Interview questions - 11 (roombr - Banglore - Fullstack - node + angular)
1. Triggers in database
2. Thread in nodejs
3. How to authorize api in middleware.
4. How login functionality is performed in nodejs?
5. Directives (structural, component, attribute directive) in angular. Why we use component directive.
6. Modules vs Service in angular.
7. Decorators in angular. (@component, @ngModules)
8. RxJS ? RxJS operator in angular. (filter, map, reduce they use like value.pipe(filter(x => x %2 == 0)).subscribe())
9. What is DOM.
10. If there are bug in backend and when you are giving demo. The issue is arises and demo is not properly done. So what will be your asnwer at the point. (scenario based question)

• Interview questions - 12 (infosys banglore 29-06-24)
-- Angular
1. Pure and impure pipe (• A pure pipe is only called when Angular detects a change in the value or the parameters passed to a pipe.
• impure pipe is called often, as often as every keystroke or mouse-move.)
2. Constructor vs ngOnInin
3. Dependency injection and why we use dependency injection in constructor?
4. Lifecycle hooks
5. Share data between components 
6. How to write test cases?
7. Optimization in angular?

-- Node
1. What is node.js and How we handle concurrency in node js?
2. How to connect database ?
3. How to store database password ? (.env or environment variable)
4. How to send parameter when querying ?
5. Callback function explain with example ?
6. Callback hell and how to avoid it ?
7. What is promises and when we reject any request ? (When some error occurred)
8. Authentication vs Authorization 
9. How we can handle error in node js ? (Try & catch, catch in promises, error first callback)
10. How we can secure routes in node js? (We use middleware for securing routes)
11. What is Rest APIs
12. How to access array which has array inside an array ?

• Interview questions - 13 (Deqode final Round 15-07-24)
1. State management in Angular (ngRx)
2. Sharing data from 1 component to another
3. What is JWT
4. If hacker got our token then how we will protect our website?
5. Caching strategy (redis & memcache)
6. How to implement logging.
7. Acid properties in db
8. Sequelize in node js

• Interview questions - 14 (Zalevate first Round 26-07-24)
1. package.json vs package.lock.json in angular?
2. How we can access variable in node.js ? Environment variables 
3. Dependencies vs devDependencies

• Interview questions - 15 (Accenture 31-07-24 - Pune - Angular)
1. Some vs filter vs find
2. ng-container in angular
3. NgAfterViewInit vs NgContentInit
4. Tell the output isNan(true) // false; isNan(undefined) // true
5. const b = {name: 'John'}; b['name'] = 'test'
6. canActivate in app.routing.module in routing.
7. interceptor in angular?
8. How many ways we can share data between components?
9. Hostlistner vs hostbinding in angular
10. How we can implement lazy loading in angular?
11. RxJS operator - concat
12. Can we use two way bindings in reactive forms? //Ans:- No, we can use two way bindings in template driven forms
13. Subject vs behaviour subject 
14. Pure & impure pipe

• Interview questions - 15 (Gammastack 02-08-24 - Banglore - wfh - Node)
Angular:- 
  1. What's is selector in angular?
  2. How many bindings are there in angular?
  3. How to share data between the components?
  4. Pure and impure pipe?
  5. Shallow copy vs deep copy?
  6. Promises vs Observable 
  7. RxJS and RxJS operator?
  8. Lifecycle hooks? ngOnInit vs NgAfterViewInit 
  9. Dependency injection?
  10. What is providers in app.module ?
  11. What is http interceptor?
  12. How to navigate to components?
  13. How to secure routes in angular? (Ans:- use role based authentication in Auth guard)

Node:- 
  1. Event loop?
  2. Promises.all vs promise.allSettled and  Promises vs async await?
  3. How we handle errors in node js?
  4. What is Express?
  5. What is middleware in express?
  6. Authentication vs Authorization?
  7. How you can make node.js multi threaded?
  8. What is process in node js? (Ans:- process.env)

Programs:- 
1.  Expected output:- {"depA":["userA","userD"],"depB":["userE,"userF"]}

```javascript
const inputArray = [
  {name:"userA", deptId:"depA"},
  {name:"userB", deptId:"depC"},
  {name:"userC", deptId:"depD"},
  {name:"userD", deptId:"depA"},
  {name:"userE", deptId:"depB"},
  {name:"userF", deptId:"depB"},
  {name:"userG", deptId:"depC"},
]
```

inputArray = []
```javascript
let obj = {}
for(let i=0; i< inputArray.length; i++){
 inputArray[i].deptId = [inputArray[i].name]
 let deptId = inputArray[i].deptId
 let name = inputArray[i].name

  if(!obj[deptId]){
        obj[deptId] = []
   }
     inputArray[i].deptId = []
    // console.log(object, inputArray[i].deptId)
   obj[deptId].push(name)
}
console.log(obj)
```

```sql
-- Calculate the 2nd highest salary of user
-- select name from users limit 1;
select salary from employee where salary < (select salary from employee);
```

```javascript
// Show only one entry using having 
// select 1 from users group by id having sum(1) > 0;
```


Guess the output:- 
```javascript
const a ={} 
const b = {} 
```

```javascript
 const k = {...a,...b}
 a.data = {user_id:12345}
const c = a
```

```javascript
console.log("c = ",c)
console.log("c = ",k)
```


---------------------------------------- 
Encora Pune:
Angular + Node:

Angular:
1. What is Subjects. (Both observable and observer are subject)
2. Dependency injection?
3. How many types of loading pages. (Eager Loading, Lazy Loading, Preloading)
4. Can We lazy load modules in angular? 
```typescript
// (Yes
//  - ex. 
{
   path: 'admin',
   loadChildren: () => import('./admin/admin.module').then(m => m.AdminModule)
}
// )
```
5. What is <!DOCTYPE html> ? (It tells the browser to render in standard mode and not in quirk mode which uses old html and behaves inconsistently)
6. What are the features in angular 13 (TypeScript 4.4 & RxJS 7.4 and other), and what features are in latest angular? (angular 20)
7. What is Multicasting in angular? ((via RxJS), multicasting means sharing a single observable execution with multiple subscribers — so that all subscribers receive the same values emitted by the observable.  e.g. .pipe(share()))
8. sessionStorage vs localStorage.

Node:
1. Buffer in node. (A Buffer is a temporary memory space in Node.js used to store binary data, especially when working with streams, files, or network.)
2. How the code execute in javascript. (global exe context, memory allocation)
3. Hoisting
4. Closure
5. Guess the output

```javascript
function func1(){
  setTimeout(()=>{
    console.log(x);
    console.log(y);
  },3000);
  var x = 2;
  let y = 12;
}
func1();
// OP - 2   12
```
 
```javascript
function func2(){
  for(var i = 0; i < 3; i++){
    setTimeout(()=> console.log(i),2000);
} }
func2();
// OP - 3  3  3
```
 
```javascript
function func2(){
  for(let  i = 0; i < 3; i++){
    setTimeout(()=> console.log(i),2000);
  }
}
func2();
// op: 0 1 2
```
 
```javascript
console.log("A" - 1); // NaN
console.log(2 + "-2" + "2"); // 2-22
console.log("Hello" - "World" + 78); // NaN
```
// -------------------------------
IIFE - Immediately Invoked Function Expressions.
```javascript
var x = 23;
(function(){
  var x = 43;
  (function random(){
    x++;
    console.log(x);
    var x = 21;
  })();
})();

// op: NaN

// OP - NaN <-- because of the closure inside random function x will be undefined and undefied++ => NaN. Because x is not intialized yet
// if var x = 21 commented then result => 44
```

```javascript
// -------------------------------
(function(a){
  return (function(){
    console.log(a);
    a = 23;
  })()
})(45);

// OP - 45
```


```javascript
for(var i = 0; i < 3; i++){
    function func2(num){ 
         setTimeout(()=> console.log(num), 2000);
     }
     func2(i); 
}
// OP - 0  1  2
```


• Neosoft Pune 1st round 24-06-2025 (Tuesday)
1. What is fs in node? (built-in module in Node.js that allows you to read, write, update, delete, and work with files and directories. )
2. What is sharding in mongodb? (Sharding in MongoDB is a method of horizontal scaling where data is split across multiple servers (called shards). Each shard holds a portion of the data based on a shard key. )
3. Is JWT is stateful? (No, JWT is stateless because token is not stored in database. It stored locally. Server doesn't store the session data)
4. Pros & Cons of JWT.
5. Git workflow? (commit on develop => pull req to stage => stage to prod )
6. coding questions.
```javascript
// ------------------------------- 
// get required prefix matching in all array

let strArr =  ['hello', 'helicopter', 'hello world']
let prefix = strArr[0]
for(let i =1; i < strArr.length; i++){
  while(!strArr[i].startsWith(prefix)){
     prefix = prefix.slice(0, -1)
     console.log('prefix', prefix)
    // console.log('prefix', prefix)
    if(!prefix) return ""
  }
}
console.log(prefix)
return prefix;
```

```javascript
// write update query in mongodb
/*
collection:
{name:
age: ,
friends: [{name: 'friend1'}, {name: 'friend2'}]}
*/ 

Ans =>
    db.users.updateOne(
    { name: "Krishna" },             // Filter
    { $set: { age: 26 } }            // Update
    );
    db.users.updateOne(
    { name: "Krishna" },
    { $push: { friends: { name: "friend3" } } }
    );
*/
```

```javascript
// get all users whos freind length is greater than 10
/*
db.users.find({
  $expr: { $gt: [ { $size: "$friends" }, 10 ] }
});
*/
// ------------------------------- 
```

• Neosoft Pune 2nd round- Technical Coding Round - 26-06-2025 (Thursday) 
Angular: 
## Angular Template Elements Summary

### 🔶 1. `<ng-container>`
- **Purpose:** Logical grouping of elements without adding extra DOM.
- **Used for:** Structural directives (`*ngIf`, `*ngFor`), grouping multiple elements conditionally.
- **Example:**
```html
<ng-container *ngIf="isLoggedIn">
  <p>Hello, user!</p>
</ng-container>
```
**DOM Output (if true):**
```html
<p>Hello, user!</p>
```
_ℹ️ `<ng-container>` itself is not rendered in the DOM._

---

### 🔷 2. `<ng-content>`
- **Purpose:** Content projection (insert parent content into child).
- **Used in:** Custom reusable components (similar to slots in other frameworks).
- **Example:**
Parent Component:
```html
<app-alert>
  <p>This is projected!</p>
</app-alert>
```
Child Component (`app-alert.component.html`):
```html
<div class="alert">
  <ng-content></ng-content>
</div>
```
_Renders the parent content where `<ng-content>` is placed._

---

### 🟪 3. `<ng-template>`
- **Purpose:** Defines template blocks not rendered until explicitly used.
- **Used for:** Deferred rendering, reusable templates, `ngIf`, `ngFor`, `ngTemplateOutlet`.
- **Example:**
```html
<ng-template #errorTemplate>
  <p>Error loading data!</p>
</ng-template>

<div *ngIf="hasError; else successTemplate">
  <ng-container *ngTemplateOutlet="errorTemplate"></ng-container>
</div>

<ng-template #successTemplate>
  <p>Data loaded successfully!</p>
</ng-template>
```
2. subject vs promises
3. How to share data between two components?
4. If we dont clear the clearInterval then what happens?. (it will keep running for every 1 sec, unnecesary check)
5. Coding question: 
Create Angular component which will have a progress bar. (check code => https://chatgpt.com/c/6853e11f-d2a8-8012-9c0f-840c390bb237)
1. It will initiate from 0% on page load
2. It will increment after 1 secs by 10%
3. The progress bar will keep on incrementing till the width of the page is met.

Node:
1. What is authentication? How it is used?
2. What is ideal expiration time in JWT?
3. Guess the output:

```javascript
// ----------------2nd-------------------------------
console.log("1. Synchronous log");
 
setTimeout(() => {
  console.log("5. setTimeout with 0ms");
}, 0);
 
Promise.resolve().then(() => {
  console.log("3. First Promise then");
});
 
async function asyncFunc() {
  console.log("2. Inside async function");
  await Promise.resolve();
  console.log("4. After await inside async function");
}
asyncFunc();
console.log("6. After async function call")


// output
// 1. Synchronous log
// 2. Inside async function
// 6. After async function call
// 3. First Promise then
// 4. After await inside async function
// 5. setTimeout with 0ms

/*
Explain - 
- first the synchronous task will run
- microtasks (Promises)
- macrotask (setTimeout)
*/
```


- typescript - type = any , never, utility function
- Yml file vs docker file in docker 


//--------------------------------------------------
• NSEIT - Mumbai (Thane) (06-07-2025 - Sunday)

```javascript
let a = 'krishna'
{
  a = 'bawane'
}
console.log(a)
```

---------------------------------------- 

```javascript
console.log("start");
process.nextTick(() => {
  console.log('2 process.nextTick');
});
 
Promise.resolve().then(() => {
  console.log('3 Promise resolved');
});

setTimeout(() => {
  console.log('4 setTimeout');
}, 0);

console.log('5 End');
/*
Output:
start
5 End
2 process.nextTick
3 Promise resolved
4 setTimeout
*/
```


```javascript
// Get repeat numbers
let arr = [1, 2, 1, 3, 5, 2]
let repeat = []
// console.log(arr.filter())

for(let i = 0; i < arr.length; i++){
  if(arr.filter(x => x == i).length > 1){
    repeat.push(arr[i])
  }
}
console.log(repeat)
```

---------------------------------------- 

```javascript
// how many char are repeated 'a - count', 'n'
let str1 = 'Krishna Bawane'
let result = {}
for(let i = 0; i< str1.length; i++){
  // console.log('char', str1[i], 'count', str1.split('').filter(x => x == str1[i]).length);
  let length = str1.split('').filter(x => x == str1[i]).length
  if(length > 1){
    result[str1[i]] = length
  }
}
console.log(result);
```


----------------------------------------
```javascript
// closure
function a(){
    let b = 'test'
    function c1(){
        console.log(b)
    }
    c1();
}
a()
```
----------------------------------------
- primitive vs non primitive datatype
- what is js?
- validation of api - joi package, how to validate req, res. (express-validator)
- asynchronous vs synchronous
- error handling
- REST api vs SOP
- Data types in javascript - primitive and non-primitive (primitive - number, bigint, boolean, undefined, null, string; (Snnub) non-primitive - objects, array, functions - Primitive types are stored by value and are immutable.
Non-primitive types (objects, arrays, functions) are stored by reference and are mutable. ) 
- Joins in db
- let, const and var difference.

----------------------------------------
- Infosys 12 july 2025 
~1.2.3 vs ^.2.3 in package .json
• What is map in JS?
• What is callback function?
• AOT vs JIT angular? 
• How to build angular? What file is created for build?
• Architecture of angular? Lifecycle hooks and how it works when page is initialized?
• Advantages and disdvantage of typescript.
• What is array? How to declare array and objects in typescript
• How to Navigate from one page to another page angular. (router => this.router.navigate)
• Where we give routing routes in angular. (routing module)
• Lazy loading in angular.
• Promise in js.
• what is middleware?
• How to handle http requests? (fronend - http interceptor, backend - express)
• What is lambda function? (Js - arrow function, AWS - serverless compute service )
• Shallow copy and Deep copy. (shallow - Copies only the first level , deep - Copies all levels, including nested ones)
• What is Event Loop? What is call stack?
• How to commit and push?
----------------------------------------

• Persistent L1 - 14-07-2025 (Monday)
- Node js architecture.
- Phase of the event loop? (Expired Timers, IO polling, SetImmediate Callbacks, Close Callbacks, Pending [then again run with 1st step] )
- What is polling in node? What we can use instead of polling? (Socket)
- How to secure node js server? 
- What is Hoisting in JS? with example.
- Shallow copy vs Deep Copy? (shallow copy - Copies only the first level , deep copy - Copies all levels, including nested ones)
- console.log(test); let test = '123'; . What will be the output of this? (err - Cannot access test before initialization)
- What is CORS? What methods exists in CORS? ({origin: '*', methods: [get, post], credentials: true})
- What is preflight request? 
- What is Streams? What are the different types? Write the readable stream code. [type - Readable (fs.createReadStream()), Writable (fs.createWriteStream()), duplex, transform]
- postgres - what is Normalization? 

Angular: 
- Angular - How to share data between components?
- Angular - What is RxJS? Why it is used?

Cloud:
- What is Autoscalling? (Auto Scaling ensures your app can handle traffic spikes automatically, while saving cost when demand is low.)
- EC2 Vs Elastic Beanstack
- Tell the other cloud services name
- What is cloudwatch?
- EBS (Elastic Block Store -  It allows you to create storage volumes that can be attached to EC2 instances, acting like a hard drive for your cloud-based applications )

Code:
```javascript
// Flat the array  without using inbuild function. (arr.flat(2))

let arr = [1,2,5,[5,6, [7,3, [10,11]]], 9]
let flat = []
function accessArray(array){
  for(let i =0; i< array.length; i++){
    if(Array.isArray(array[i])){
      accessArray(array[i])
    }else{
      flat.push(array[i])
    }
  }
}
accessArray(arr)
console.log(flat)
```

----------------------------------------
PixelQueue Pune - 18-07-2025 (Friday)

- AOT (Ahead of Time)  and JIT (Just in Time) in Angular?
- CAP theorem in node (Mongodb)?  [C — Consistency (Every read gets the most recent write.
), A — Availability (Every request gets a response, even if some nodes are down.
), P — Partition Tolerance (The system continues to operate even if there's a network partition (i.e., communication breaks between parts of the system)]
- indexing methods in mongodb? Types of indexing in mongodb? (Single Field Index , Compound Index , Multikey Index , Text Index, Hashed Index, Geospatial Indexes, Wildcard Index)
- Prevent server from sql injection attack. [Use libraries like pg (PostgreSQL), mysql2, or ORMs like Sequelize/TypeORM, Use libraries like Joi, validator, or express-validator, Avoid Dynamic SQL]
- soft delete in any database [Soft delete means marking a record as deleted without actually removing it from the database.
] (UPDATE users SET isDeleted = true WHERE id = 5;)
- What is cross site scripting (XSS)


```javascript
// Implement a rate limiter using in memory map or redis.
const rateLimitMap = new Map()
const WINDOW = 60000;
const MAX_REQUEST = 5;
function rateLimiter((req, res, next) => {
  const ip = req.ip
  const currentTime = Date.now()
  
  if(!rateLimitMap.has(ip)){
    rateLimitMap.set(ip, [])
  }

  const timeStamps = rateLimitMap.get(ip).filter(
      ts => currentTime - ts < WINDOW
    )
    timeStamps.push(currentTime)
    rateLimitMap.set(ip, timeStamps)

    if(timeStamps.length > MAX_REQUEST){
      return res.send('To Many request, try again later')
    }
    next()
})
```

----------------------------------------
Pickright Technologies - Banglore (21-07-2025 - Monday) - MEAN stack

• 
• What are Transactions in Node and how we use? Race in transactions?
• ACID properties
• Indexing in Database. Pros and Cons of Indexing.
• Microservices and Monolythic architecture. If i want to scale then what will the challenges? (System Design)
• RxJS and Observables and Observer?
• Promises and Async await?
• Callback Vs Promises? What are the issues in callbacks?
• Event Loop in JS? What are event queue and microtask and macrotask?
• What is Closure and its use cases?
• Difference between put and patch? How to update the data? (put method)
• Difference between get and post method?
• Libuv ?
• code - Write to get Longest Common Prefix in JS.

```javascript
let arr = ["flower","flw","flight", "flo"]
let key = arr[0]
```

for(let i=1; i< arr.length; i++){
```javascript
  // while(!arr[i].includes(key)){
  while(!arr[i].startsWith(key)){
    key = key.slice(0, -1)
```
    
```javascript
    if(!key) return ''
  }
}
console.log(key)
----------------------------------------
• Torana - Angular - Nagpur 28-07-2025 (Monday)
```

Angular
 - RxJS operator
 - RxJS (Imp)
 - HTML 4 Vs HTML 5
 - decorator in CSS
 - same service is subscribe by multiple and it has interval so how we emit the same result.
 - Latest features in angular.
 - Can we use multiple http call
 - How we create custom pipe
 - How to handle http errors globally
 - How we can handle multiple apis which are dependent on one another with rxjs?
 - If data is streaming with a delay (interval) and multiple apis subscribe to it and want to stream same data then what we use? (Use shareReplay or a Subject to multicast the delayed stream)
 - When the file is uploading then how we can cancel the uploading in between if cancelled button click? (Use AbortController or takeUntil with a Subject)
 - how can we optimize the multiple components.
---------------------------------------- 
• EPAM - 1st Technical Round - 29/05/2025 (Tuesday) - fullstack development - hyderabad - 29-07-2025 (Tuesday)

- for in vs for of
- Stream apis
- Cold observables vs Hot observables
- How to Optimize the webpage from frontend and backend? (frontend optimize - Lazy loading modules, ChangeDetectionStrategy.OnPush, using trackBy with *ngFor, pure pipes for caching, async pipe for observables, unsubscribing to avoid memory leaks, smart use of RxJS operators. )
- How to make page responsive
- When code reviewing what things should be checked
- guess the output - 
```javascript
console.log([1,2,3] == [1,2,3])
console.log([1,2,3] === [1,2,3])
console.log(({key: '1,2,3'} == {key: '1,2,3'}))
console.log(({key: '1,2,3'} === {key: '1,2,3'}))

// OP: all false because object compare by memory address
```

OP- all false (non premitive check by the memory address)
- How did you check the logs in node js? (wintson package - logger)
- Arrow functions vs regular functions
- code - Todo application with add, remove functionality and filter by name also.
- code - Find the duplicate from the array = [1,2,3,3,3,4,4,5,5,6]
- Foreign key vs primary key
- typescript - static keyword, super keyword, new keyword
- How to create and access environment variable ? (require(doenv) and process.env.PORT)
- How to write Test cases in node and angular?
- Cors
- Do you know about swagger in nodejs?
- What is buffer? (A buffer is temporary memory used to handle binary data, especially when reading from or writing to streams in Node.js.)
- Reactive forms - setValue vs patchValue? (Use setValue() for full form updates and patchValue() for partial updates.)
- Error handling in node?
- REST API vs Graphql APIs?
- Generics or Generic type in TypeScript.
- How to write npm script? (inside package.json => { 'scripts': { 'start': 'node server.js'}})
----------------------------------------
• Nagarro - Node.js - (31-07-2025 - Thursday)

- What is the difference between app.use and app.get in express? (app.use() is used to register middleware functions that run for all HTTP methods and routes (unless specified).
app.get() handles GET requests for a specific route.)
- Unit testing in Node? (Jest for unit testing)
- Do you have experience with the design patterns?
- TDZ (temporal dead zone happens with let and const and not with var)
- Closure, Hoisting
- Microservices calls or how the communication happens with microservices?
- Why we use Redis? (asynchronous call - Tools: RabbitMQ, Kafka, Redis Pub/Sub, NATS , syncronous - Libraries used: axios, node-fetch, http, express )
- Transactions? If we sending money from acc A to acc B then how it is done with transactions?
```javascript
   ✅ Example: Sending money from Account A to Account B 
   1️⃣ Start a transaction.
   2️⃣ Debit Account A (subtract amount).
   3️⃣ Credit Account B (add amount).
   4️⃣ If both succeed → COMMIT transaction.
   5️⃣ If any fails → ROLLBACK (undo changes). 
```

- Normalisation vs denormalisation 
- How do you completed the tasks in your company? What structure follow? (We followed Agile with Jira for task tracking, GitHub for code reviews, and CI/CD pipelines for deployment. Tasks were completed in sprints with proper testing and peer reviews. )
- Do you familiar with Jenkins, Docker or CI/CD pipelines? What you use for CI/CD pipeline? 

CODE - 
----########
```javascript
// Given an array arr[] containing only 0s, 1s, and 2s. Sort the array in ascending order.
// Input:  [0, 1, 2, 0, 1, 2]
// Output: [0, 0, 1, 1, 2, 2]

 let arr = [0, 1, 2, 0, 1, 2]
 let count0 = 0, count1 = 0, count2=0
 
 for(let i=0; i < arr.length; i++){
   if(arr[i] === 0){
      count0++
   }else if(arr[i] === 1){
     count1++
   }else{
     count2++
   }
 }
 
 for(let i = 0; i < arr.length; i++){
  if(i < count0) arr[i] = 0
  else if(i < count0 + count1) arr[i] = 1
  else arr[i] = 2
 }
 console.log(arr)
```

----######## Guess the output
```javascript
function createCounter() {
  let count = 0;

  return function () {
    count++;
    console.log(count);
  };
}
const counter1 = createCounter();
const counter2 = createCounter();

counter1();  // 1 
counter1(); // 2
counter2();  // 1
```
 
----########
```javascript
console.log('A');
 
setTimeout(() => {
  console.log('B');
}, 0);

Promise.resolve().then(() => {
  console.log('C');
  setTimeout(() => {
    console.log('D');
  }, 0);
});
 
Promise.resolve().then(() => {
  console.log('E');
});
 
queueMicrotask(() => {
  console.log('F');
});

console.log('G');

/*
OP - 
A
G
C
E
F
B
D
*/
```

----########  Why this is print undefined?

```javascript
var a = 1;
function foo() {
  console.log(a); // it is initialize var with undefined. It is inside scope thats why above var a = 1 is not to do with below because of hoisting
  var a = 2; 
}
foo(); // undefined
----######## 
```

---------------------------------------- 
code:  Tecnotree


```javascript
// valid paranthesis or not
/*
Input: s = "()[]{}"
Output: true
 
Input: s = "()["
Output: false
 */

function validPara(input){
  let matchPara = {
    '[' : ']',
    '(': ')',
    '{': '}'
  }

  let stack = []

  for(let i=0; i< input.length; i++){
    if(matchPara[input[i]]){
      stack.push(matchPara[input[i]])
    }else if(stack.pop() != input[i]){
      return false
    }
  }
  return stack.length === 0
}
let input = '[[]()'
console.log(validPara(input))
```
---------------------------------------- 
Vinove - Remote - Mean Stack

1. Write a syntax for behavioral subject.
Ans =>  
```typescript
const subject = new BehaviorSubject<string>('Initial Value');
// Subscribe
subject.subscribe(value => console.log(value));
// Emit new value
subject.next('New Value');
```
 
2. Conver this json into formGroup.
```typescript
 const data = {
    "stack": "MEAN",
    "version": "15",
    "environments": {
      "dev": "https://dev.com",
      "prod": "https://prod.com",
      "uat": "https://uat.com",
    }
 }
// Ans => 
this.form = new FormGroup({
  stack: new FormControl('MEAN'),
  version: new FormControl('15'),
  environments: new FormGroup({
    dev: new FormControl('https://dev.com'),
    prod: new FormControl('https://prod.com'),
    uat: new FormControl('https://uat.com')
  })
});
// - How can we setValue for environments => 
// -> setValue = 
this.form.get('environment')?.setValue({
  dev: 'https://dev.com',
  prod: 'https://prod.com',
  uat: 'https://uat.com'
});
// -> patchValue = 
this.form.get('environment')?.patchValue({
  prod: 'https://prod-updated.com'
})
// 3. difference between setValue and patchValue 
// Ans => setValue updates all form controls, patchValue updates only specified controls.
```

4. What is forkjoin?
Ans => forkJoin in Angular is an RxJS operator that runs multiple observables in parallel and emits a single combined result when all complete. 

5. What is Rest operator?
Ans => It allows iterables to be expanded into single element. e.g. [...[1,2,3], ...[4,5,6]]

6. What is Deep copy and Shallow copy?
Ans => 
Shallow Copy → Copies only top-level properties; nested objects still reference the original.
Deep Copy → Creates a completely independent copy, including all nested objects. 

6. Write a program to get the sum of these array = [1, 2, [3, 4], 5]
=>  
```javascript
  let value = [1, 2, [3, 4], 5]
  let arr = value.flat(1)
  let result = arr.reduce((a,b) => a+b)
  console.log(result)
```

----------------------------------------------------------
• Emorphis - 13-08-2025 - MEAN Stack - client round (Wednesday)

- What is difference in Angular 14 and latest angular?
- Graphql vs Rest API
- How node.js handles the concurrency?
- What is Query and Mutation?
- Scalar type in graphql? (Int, float, string, boolean, ID)
- How many types of authentication? (Session based and token based authentication?)
- How to secure routes?
- Node.js and Angular difference.
- Authentication and Authorization.
- How to access the s3 image in node?
- Do you work with OTP authentication?
- How to render backend from frontend?
 ----------------------------------------------------------
