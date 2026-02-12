# JavaScript Learning Plan (By Stages)

> **Tip:** Mark each task as completed by replacing 🚧 with ✅.
>
> **Updated:** February 2026 — covers ES2024+

---

## Stage 1 — Introduction & Syntax Basics 🚧
- What is JavaScript 🚧
  - [ ] Role of JS in web development (client and server)
  - [ ] Adding scripts to HTML (`<script>`, `defer`, `async`)
  - [ ] Browser console (`console.log`, `console.table`, `console.dir`)
  - [ ] Strict mode (`'use strict'`)
- Variables 🚧
  - [ ] `let`, `const`, `var` — differences and when to use each
  - [ ] Variable naming rules
  - [ ] Scope of `var` vs `let`/`const` (introduction)
  - [ ] Variable hoisting (introduction)
- Data types 🚧
  - [ ] Primitives: `string`, `number`, `bigint`, `boolean`, `null`, `undefined`, `symbol`
  - [ ] Reference type: `object`
  - [ ] `typeof` operator
  - [ ] Dynamic typing
- Type conversions 🚧
  - [ ] Explicit conversion (`String()`, `Number()`, `Boolean()`)
  - [ ] Implicit conversion (type coercion)
  - [ ] `==` vs `===` (loose vs strict equality)
  - [ ] Falsy and truthy values
- Strings and template literals 🚧
  - [ ] String methods overview (`length`, `indexOf`, `slice`, `trim`, etc.)
  - [ ] Template literals (backticks, `${expression}`)
  - [ ] Multi-line strings
  - [ ] Tagged template literals (introduction)
- Basic I/O 🚧
  - [ ] `alert()`, `prompt()`, `confirm()`
  - [ ] Working with `console`
- Mini-project: Console calculator 🚧

**Useful Resources:**
- [MDN: JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [javascript.info — The JavaScript Tutorial](https://javascript.info/)
- [learn.javascript.ru (Russian)](https://learn.javascript.ru/)
- [MDN: typeof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof)
- [Eloquent JavaScript (free online book)](https://eloquentjavascript.net/)

---

## Stage 2 — Operators & Control Flow 🚧
- Operators 🚧
  - [ ] Arithmetic: `+`, `-`, `*`, `/`, `%`, `**`
  - [ ] Assignment: `=`, `+=`, `-=`, `*=`, `/=`
  - [ ] Comparison: `==`, `===`, `!=`, `!==`, `<`, `>`, `<=`, `>=`
  - [ ] Logical: `&&`, `||`, `!`
  - [ ] Nullish coalescing: `??`, `??=`
  - [ ] Logical assignment: `||=`, `&&=`
  - [ ] Optional chaining: `?.`
  - [ ] Ternary operator: `? :`
  - [ ] Comma operator, grouping
- Conditionals 🚧
  - [ ] `if` / `else` / `else if`
  - [ ] `switch` / `case` / `default`
  - [ ] Nested conditions
  - [ ] Ternary operator as a simple `if` replacement
- Loops 🚧
  - [ ] `for`
  - [ ] `while`
  - [ ] `do...while`
  - [ ] `for...of` (iterating over iterables)
  - [ ] `for...in` (iterating over object properties)
  - [ ] `break` and `continue`
  - [ ] Labels for loops (`label:`)
- Mini-project: Guess the number 🚧

**Useful Resources:**
- [MDN: Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_operators)
- [javascript.info — Operators](https://javascript.info/operators)
- [javascript.info — Loops](https://javascript.info/while-for)

---

## Stage 3 — Functions 🚧
- Function declarations 🚧
  - [ ] Function Declaration
  - [ ] Function Expression
  - [ ] Arrow functions (`=>`)
  - [ ] Differences and when to use each
- Parameters and arguments 🚧
  - [ ] Passing arguments
  - [ ] Default parameters
  - [ ] Rest operator (`...args`)
  - [ ] The `arguments` object (and why rest is preferred)
- Return values 🚧
  - [ ] `return` — explicit and implicit (arrow functions)
  - [ ] Functions without `return` (return `undefined`)
- Scope and closures (introduction) 🚧
  - [ ] Global and local scope
  - [ ] Lexical Environment
  - [ ] Closures — basic concept
  - [ ] Function hoisting
- Callbacks (introduction) 🚧
  - [ ] Function as an argument to another function
  - [ ] Callback examples (`setTimeout`, event handlers)
- Mini-project: String utility library 🚧

**Useful Resources:**
- [MDN: Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
- [javascript.info — Functions](https://javascript.info/function-basics)
- [javascript.info — Closures](https://javascript.info/closure)

---

## Stage 4 — Arrays 🚧
- Array basics 🚧
  - [ ] Creating arrays (literal, `new Array`, `Array.from`, `Array.of`)
  - [ ] Index access, `length` property
  - [ ] Checking for array (`Array.isArray`)
- Mutating methods 🚧
  - [ ] `push`, `pop`, `shift`, `unshift`
  - [ ] `splice`, `fill`, `copyWithin`
  - [ ] `sort`, `reverse`
- Non-mutating methods 🚧
  - [ ] `slice`, `concat`, `flat`, `flatMap`
  - [ ] `includes`, `indexOf`, `find`, `findIndex`
  - [ ] `join`, `toString`
  - [ ] `at` (ES2022)
- Iteration methods 🚧
  - [ ] `forEach`
  - [ ] `map`
  - [ ] `filter`
  - [ ] `reduce` and `reduceRight`
  - [ ] `some`, `every`
  - [ ] Method chaining
- Array destructuring 🚧
  - [ ] Basic destructuring
  - [ ] Skipping elements
  - [ ] Rest element in destructuring
  - [ ] Default values
- Spread operator (`...`) for arrays 🚧
  - [ ] Copying an array
  - [ ] Merging arrays
  - [ ] Passing an array as arguments
- Mini-project: Console task manager 🚧

**Useful Resources:**
- [MDN: Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
- [javascript.info — Arrays](https://javascript.info/array)
- [javascript.info — Array Methods](https://javascript.info/array-methods)

---

## Stage 5 — Objects 🚧
- Object basics 🚧
  - [ ] Creating objects (literal, `new Object`)
  - [ ] Properties and methods
  - [ ] Accessing properties (dot, bracket notation)
  - [ ] Adding, modifying, deleting properties (`delete`)
  - [ ] Checking for a property (`in`, `hasOwnProperty`)
- Computed properties and shorthand 🚧
  - [ ] Computed property names (`[expr]`)
  - [ ] Property and method shorthand
- Iterating over objects 🚧
  - [ ] `for...in`
  - [ ] `Object.keys()`, `Object.values()`, `Object.entries()`
  - [ ] `Object.fromEntries()`
- Object destructuring 🚧
  - [ ] Basic destructuring
  - [ ] Renaming variables
  - [ ] Default values
  - [ ] Nested destructuring
  - [ ] Rest properties
- Spread operator for objects 🚧
  - [ ] Shallow copying objects
  - [ ] Merging objects
- References and copying 🚧
  - [ ] Primitives vs reference types
  - [ ] Shallow copy (`Object.assign`, spread)
  - [ ] Deep copy (`structuredClone`)
- JSON 🚧
  - [ ] `JSON.stringify()` — converting to string
  - [ ] `JSON.parse()` — parsing a string
  - [ ] Using JSON for data storage
- Optional chaining (`?.`) 🚧
  - [ ] Accessing nested properties
  - [ ] Calling methods (`?.()`)
  - [ ] Accessing elements (`?.[]`)
- Mini-project: Console phone book 🚧

**Useful Resources:**
- [MDN: Working with Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects)
- [javascript.info — Objects](https://javascript.info/object)
- [MDN: JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)

---

## Stage 6 — DOM Manipulation 🚧
- What is the DOM 🚧
  - [ ] DOM tree structure
  - [ ] `document` as the entry point
  - [ ] Relationship between HTML and DOM
- Selecting elements 🚧
  - [ ] `getElementById`
  - [ ] `querySelector` and `querySelectorAll`
  - [ ] `getElementsByClassName`, `getElementsByTagName`
  - [ ] When to use which
- Modifying elements 🚧
  - [ ] `textContent`, `innerText`, `innerHTML`
  - [ ] Attributes: `getAttribute`, `setAttribute`, `removeAttribute`
  - [ ] Data attributes (`dataset`)
  - [ ] Working with styles (`style`, `cssText`)
  - [ ] Managing classes (`classList`: `add`, `remove`, `toggle`, `contains`)
- Creating and removing elements 🚧
  - [ ] `createElement`, `createTextNode`
  - [ ] `append`, `prepend`, `before`, `after`
  - [ ] `remove`, `replaceWith`
  - [ ] `cloneNode`
  - [ ] `DocumentFragment`
- DOM navigation 🚧
  - [ ] `parentElement`, `children`, `firstElementChild`, `lastElementChild`
  - [ ] `nextElementSibling`, `previousElementSibling`
  - [ ] `closest`
- Dimensions and scrolling 🚧
  - [ ] `offsetWidth`, `offsetHeight`, `clientWidth`, `clientHeight`
  - [ ] `scrollTop`, `scrollLeft`, `scrollTo`, `scrollIntoView`
  - [ ] `getBoundingClientRect`
- Mini-project: Dynamic list (add/remove items on page) 🚧

**Useful Resources:**
- [MDN: Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
- [javascript.info — Document](https://javascript.info/document)
- [javascript.info — Modifying the Document](https://javascript.info/modifying-document)

---

## Stage 7 — Events 🚧
- Event basics 🚧
  - [ ] `addEventListener` and `removeEventListener`
  - [ ] Inline handlers and why to avoid them
  - [ ] Event object (`event`)
  - [ ] `event.target` and `event.currentTarget`
- Bubbling and capturing 🚧
  - [ ] Phases: capturing → target → bubbling
  - [ ] `event.stopPropagation()`
  - [ ] `event.stopImmediatePropagation()`
  - [ ] `capture: true` option
- Event delegation 🚧
  - [ ] Delegation principle
  - [ ] Using `event.target` and `closest`
  - [ ] Practical examples
- Default browser actions 🚧
  - [ ] `event.preventDefault()`
  - [ ] Examples: forms, links, context menu
- Mouse events 🚧
  - [ ] `click`, `dblclick`, `contextmenu`
  - [ ] `mousedown`, `mouseup`, `mousemove`
  - [ ] `mouseenter`, `mouseleave` vs `mouseover`, `mouseout`
- Keyboard events 🚧
  - [ ] `keydown`, `keyup`
  - [ ] Properties: `key`, `code`
  - [ ] Key combinations
- Form and input events 🚧
  - [ ] `submit`, `reset`
  - [ ] `input`, `change`, `focus`, `blur`
  - [ ] `FormData` (introduction)
- Other events 🚧
  - [ ] `DOMContentLoaded`, `load`, `beforeunload`
  - [ ] `scroll`, `resize`
  - [ ] `transitionend`, `animationend`
- Mini-project: Interactive form with validation 🚧

**Useful Resources:**
- [MDN: Events](https://developer.mozilla.org/en-US/docs/Web/Events)
- [javascript.info — Events](https://javascript.info/events)
- [javascript.info — Event Delegation](https://javascript.info/event-delegation)

---

## Stage 8 — Asynchronous Programming 🚧
- Synchronous vs asynchronous code 🚧
  - [ ] Call Stack
  - [ ] Web API, Task Queue and microtasks
  - [ ] Event Loop
  - [ ] Visualizing the Event Loop
- Timers 🚧
  - [ ] `setTimeout` and `clearTimeout`
  - [ ] `setInterval` and `clearInterval`
  - [ ] `requestAnimationFrame`
- Callbacks and "callback hell" 🚧
  - [ ] Callback pattern for async operations
  - [ ] Nested callbacks problem (callback hell)
  - [ ] Why Promises are needed
- Promises 🚧
  - [ ] Creating a Promise (`new Promise`)
  - [ ] States: `pending`, `fulfilled`, `rejected`
  - [ ] `.then()`, `.catch()`, `.finally()`
  - [ ] Promise chaining
  - [ ] `Promise.all`, `Promise.allSettled`
  - [ ] `Promise.race`, `Promise.any`
  - [ ] `Promise.resolve`, `Promise.reject`
- Async/Await 🚧
  - [ ] `async` function syntax
  - [ ] `await` operator
  - [ ] Error handling with `try/catch`
  - [ ] Parallel execution with `await Promise.all`
  - [ ] Top-level await
- Practical async patterns 🚧
  - [ ] Retry logic (retrying failed requests)
  - [ ] Timeout wrapper (`Promise.race` with timeout)
  - [ ] Async IIFE
- Fetch API 🚧
  - [ ] Making GET requests
  - [ ] Making POST requests
  - [ ] Headers and request parameters
  - [ ] Handling JSON responses
  - [ ] HTTP error handling
  - [ ] `AbortController` for cancelling requests
- Mini-project: Weather search app (Fetch API) 🚧

**Useful Resources:**
- [MDN: Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [javascript.info — Promises, async/await](https://javascript.info/async)
- [MDN: Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- [MDN: Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)

---

## Stage 9 — Object-Oriented Programming 🚧
- The `this` context 🚧
  - [ ] `this` in object methods
  - [ ] `this` in regular functions vs arrow functions
  - [ ] Losing `this` context
  - [ ] `call`, `apply`, `bind`
- Prototypes 🚧
  - [ ] `[[Prototype]]` and `__proto__`
  - [ ] `Object.getPrototypeOf`, `Object.setPrototypeOf`
  - [ ] Prototype chain
  - [ ] The `prototype` property on constructor functions
- Constructor functions 🚧
  - [ ] Creating with `new`
  - [ ] The `constructor` property
  - [ ] Adding methods via `prototype`
- Classes (ES6+) 🚧
  - [ ] Class declaration (`class`)
  - [ ] Constructor (`constructor`)
  - [ ] Class methods
  - [ ] Getters and setters (`get`, `set`)
  - [ ] Static methods and properties (`static`)
- Inheritance 🚧
  - [ ] `extends` and `super`
  - [ ] Method overriding
  - [ ] Type checking (`instanceof`)
- Encapsulation 🚧
  - [ ] Private fields and methods (`#`)
  - [ ] Protected properties (convention `_`)
- Polymorphism and abstraction 🚧
  - [ ] Polymorphism through method overriding
  - [ ] Template method pattern
- Mini-project: Library management system (OOP) 🚧

**Useful Resources:**
- [MDN: Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
- [javascript.info — Classes](https://javascript.info/classes)
- [javascript.info — Prototypes](https://javascript.info/prototypes)

---

## Stage 10 — Modules & Error Handling 🚧
- ES Modules 🚧
  - [ ] `export` and `import` (named)
  - [ ] `export default` and `import`
  - [ ] Renaming on import/export (`as`)
  - [ ] Re-exporting (`export { ... } from`)
  - [ ] Dynamic import (`import()`)
  - [ ] Using modules in HTML (`<script type="module">`)
  - [ ] Module specifics (`strict mode`, own scope)
- Error handling 🚧
  - [ ] `try` / `catch` / `finally`
  - [ ] `Error` object and its properties (`message`, `name`, `stack`)
  - [ ] Error types: `TypeError`, `ReferenceError`, `SyntaxError`, `RangeError`
  - [ ] Creating custom errors (`class CustomError extends Error`)
  - [ ] `throw` operator
  - [ ] Error handling in async code
  - [ ] Global handlers: `window.onerror`, `unhandledrejection`
- Browser data storage 🚧
  - [ ] `localStorage` and `sessionStorage`
  - [ ] API: `setItem`, `getItem`, `removeItem`, `clear`
  - [ ] Data serialization (JSON)
  - [ ] `storage` event
  - [ ] Limitations and security
- Mini-project: Notes app with localStorage persistence 🚧

**Useful Resources:**
- [MDN: Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)
- [javascript.info — Modules](https://javascript.info/modules)
- [MDN: Error](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error)
- [MDN: Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)

---

## Stage 11 — Advanced JavaScript 🚧
- Closures — deep dive 🚧
  - [ ] Lexical Environment in detail
  - [ ] Practical applications of closures
  - [ ] IIFE (Immediately Invoked Function Expression)
  - [ ] Module pattern via closures
- Advanced functions 🚧
  - [ ] Higher-Order Functions
  - [ ] Currying
  - [ ] Partial application
  - [ ] Memoization
  - [ ] Debounce and throttle
  - [ ] Recursion
- Functional programming patterns 🚧
  - [ ] Pure functions and immutability
  - [ ] Function composition (`compose`, `pipe`)
  - [ ] Data transformation pipelines
- Symbol and iterators 🚧
  - [ ] `Symbol` type and its usage
  - [ ] Built-in symbols (`Symbol.iterator`, `Symbol.toPrimitive`)
  - [ ] Iterable protocol
  - [ ] Creating custom iterators
- Generators 🚧
  - [ ] Generator functions (`function*`)
  - [ ] `yield` and `next()`
  - [ ] Generators as iterators
  - [ ] Async generators (`async function*`)
- Map, Set, WeakMap, WeakSet 🚧
  - [ ] `Map` — creation, methods, iteration
  - [ ] `Set` — unique values, methods
  - [ ] `WeakMap` and `WeakSet` — weak references and garbage collection
  - [ ] When to use instead of plain objects/arrays
- Proxy and Reflect 🚧
  - [ ] Creating a `Proxy`
  - [ ] Traps: `get`, `set`, `has`, `deleteProperty`
  - [ ] `Reflect` API
  - [ ] Practical applications (validation, logging)
- Property descriptors 🚧
  - [ ] `Object.defineProperty`, `Object.defineProperties`
  - [ ] Flags: `writable`, `enumerable`, `configurable`
  - [ ] `Object.freeze`, `Object.seal`, `Object.preventExtensions`
- Design patterns 🚧
  - [ ] Observer pattern
  - [ ] Publisher-Subscriber (Pub/Sub) pattern
  - [ ] Factory pattern
  - [ ] Singleton pattern
  - [ ] Decorator pattern
- Mini-project: Simple reactive data system 🚧

**Useful Resources:**
- [javascript.info — Advanced Working with Functions](https://javascript.info/advanced-functions)
- [javascript.info — Generators](https://javascript.info/generators-iterators)
- [MDN: Proxy](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy)
- [Refactoring Guru — Design Patterns](https://refactoring.guru/design-patterns)
- [You Don't Know JS (book series)](https://github.com/getify/You-Dont-Know-JS)
- [Eloquent JavaScript — Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html)

---

## Stage 12 — Practical Projects 🚧

### Project A: Full-featured Todo App 🚧
- [ ] Adding, editing, deleting tasks
- [ ] Filtering (all / active / completed)
- [ ] Saving to `localStorage`
- [ ] DOM manipulation and event delegation
- [ ] Modular structure (ES modules)
- [ ] CSS animations for add/remove

### Project B: API-Powered App 🚧
- [ ] Working with a public REST API
- [ ] Search, filter, and display data
- [ ] Pagination or infinite scroll
- [ ] Network error handling
- [ ] Loading indicators
- [ ] Async/await + Fetch API

### Project C: Browser Game 🚧
- [ ] Game loop (`requestAnimationFrame`)
- [ ] Keyboard and mouse controls
- [ ] OOP architecture (classes for game objects)
- [ ] Score tracking and game states
- [ ] Sound effects (Web Audio API — optional)
- [ ] High score saving

**Useful Resources:**
- [Public APIs list](https://github.com/public-apis/public-apis)
- [MDN: Game development](https://developer.mozilla.org/en-US/docs/Games)
- [javascript.info — Full tutorial](https://javascript.info/)

---

## Summary of Stages

| Stage | Topic | Key Skills | Duration |
|-------|-------|------------|----------|
| 1 | Syntax Basics | Variables, types, conversions | 1-2 weeks |
| 2 | Operators & Control Flow | Conditions, loops, operators | 1-2 weeks |
| 3 | Functions | Declarations, arrows, scope, closures | 1-2 weeks |
| 4 | Arrays | Array methods, map/filter/reduce | 1-2 weeks |
| 5 | Objects | Properties, destructuring, JSON | 1-2 weeks |
| 6 | DOM Manipulation | Selecting, creating, modifying elements | 2 weeks |
| 7 | Events | Handlers, bubbling, delegation | 1-2 weeks |
| 8 | Async Programming | Promises, async/await, Fetch API | 2-3 weeks |
| 9 | OOP | Classes, prototypes, inheritance | 2 weeks |
| 10 | Modules & Errors | ES modules, try/catch, localStorage | 1-2 weeks |
| 11 | Advanced JS | Generators, Proxy, patterns | 2-3 weeks |
| 12 | Projects | Todo, API app, game | 4-6 weeks |

**Total estimated time: 20-30 weeks (~5-7 months)**

---

## Timeline Breakdown

### Phase 1: Language Fundamentals (Stages 1-5) — 5-10 weeks
Goal: confidently command basic syntax, functions, and data structures.

### Phase 2: Browser & Interaction (Stages 6-7) — 3-4 weeks
Goal: create interactive web pages, work with DOM and events.

### Phase 3: Advanced Concepts (Stages 8-10) — 5-7 weeks
Goal: understand async code, OOP, modules, and error handling.

### Phase 4: Mastery & Practice (Stages 11-12) — 6-9 weeks
Goal: master advanced patterns and build portfolio projects.

---

*You can adjust the pace and topics as needed during your learning journey.*
*Plan created: February 2026*
