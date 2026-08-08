# MERN Interview Preparation — 1–2 YOE

## 1. JavaScript

Your JavaScript section is already very strong.

Honestly, don't keep adding random JavaScript questions.

For **1–2 YOE**, if you can confidently answer and code the questions you've listed, especially:

* Closures
* `this`
* Prototypes
* Execution context
* Event loop
* Microtasks / macrotasks
* Promises
* `async/await`
* `call/apply/bind`
* Currying
* Memoization
* Debounce / throttle
* Polyfills
* Shallow / deep copy
* Garbage collection
* Event delegation
* Browser rendering
* Type coercion
* ES modules
* Node.js event loop

...you're already at a very good JavaScript level.

### Merge duplicate topics

I'd actually merge/remove duplicates. For example:

* **#27, #61, #62, #63** → One **Prototype** section
* **#38, #93, #94, #95, #96** → One **Memory / Garbage Collection** section
* **#19, #97** → One **Event Delegation** section
* **#44, #98** → One **Event Control** section
* **#40, #102, #103** → One **Rendering / Performance** section
* **#47, #100** → One **XSS** section

This will make your sheet much easier to revise.

---

# 2. React

For a MERN interview, this is the biggest hole.

I'd add at least these:

## React Fundamentals

* What is React and why use it?
* What is the Virtual DOM?
* How does reconciliation work?
* What is the difference between Virtual DOM and real DOM?
* What are components?
* Functional vs class components.
* What are props?
* What is state?
* Props vs state.
* What happens when state changes?
* Why should state not be mutated directly?
* Controlled vs uncontrolled components.
* What are keys in React and why are they important?
* Why should we avoid using array index as a key?
* What is conditional rendering?
* What is lifting state up?
* What is prop drilling?
* How can you solve prop drilling?

## React Hooks — Very Important for 1–2 YOE

* Explain `useState`.
* Explain `useEffect`.
* What does the dependency array do?
* What happens if the dependency array is empty?
* What happens if there is no dependency array?
* Why does `useEffect` sometimes run twice in development?
* What is cleanup in `useEffect`?
* How can `useEffect` cause an infinite loop?
* Explain `useRef`.
* `useRef` vs `useState`.
* Explain `useMemo`.
* Explain `useCallback`.
* `useMemo` vs `useCallback`.
* When should you **not** use `useMemo` / `useCallback`?
* Explain `useContext`.
* What are custom hooks?
* Create a custom hook.
* Rules of Hooks.
* What happens when hooks are called conditionally?

## React Performance

* What causes unnecessary re-renders?
* How do you optimize a React application?
* What is `React.memo`?
* `React.memo` vs `useMemo` vs `useCallback`.
* How would you optimize a large list?
* What is lazy loading in React?
* Explain `React.lazy` and `Suspense`.
* What is code splitting?
* How would you implement pagination / infinite scrolling?

## React Practical Questions

These are very important because interviewers often stop asking theory and give you a situation.

* Build a search box with debouncing.
* Build a pagination component.
* Build a modal.
* Build a reusable form component.
* Fetch API data and handle loading / error / success states.
* Cancel an API request when a component unmounts.
* Implement authentication-protected routes.
* Implement a shopping cart.
* Explain how you would structure a large React project.

---

# 3. Express.js

Express.js is completely missing.

Add:

## Express Fundamentals

* What is Express.js?
* What is middleware?
* How does Express middleware work?
* Application-level vs router-level middleware.
* What is error-handling middleware?
* How do you create a centralized error handler?
* What is `req`, `res`, and `next`?
* Difference between `req.params`, `req.query`, and `req.body`.
* How do you validate request data?
* How do you handle async errors in Express?
* How do you structure an Express application?
* Controller vs service vs repository.

## REST and HTTP

* What is REST?
* GET vs POST vs PUT vs PATCH vs DELETE.
* What are HTTP status codes?
* What is idempotency?
* What are HTTP headers?
* What is CORS?
* Why does CORS happen?
* How do you configure CORS?

## Express API Security and Practical Development

* What is rate limiting?
* How would you secure an Express API?
* How do you handle file uploads?
* How do you implement pagination in an API?
* How do you implement filtering / sorting / searching?

---

# 4. MongoDB

MongoDB is another major gap.

For MERN, I'd consider this **mandatory**.

## MongoDB Fundamentals

* What is MongoDB?
* SQL vs NoSQL.
* Database vs collection vs document.
* What is BSON?
* Embedded documents vs references.
* What is `_id` and `ObjectId`?
* What are indexes?
* How do indexes improve query performance?
* What are the disadvantages of indexes?
* Single-field vs compound indexes.
* What is a unique index?
* What is a TTL index?

## MongoDB Queries and Aggregation

* What is aggregation?
* Explain `$match`.
* Explain `$group`.
* Explain `$project`.
* Explain `$sort`.
* Explain `$lookup`.
* Explain `$unwind`.
* `find()` vs `findOne()`.
* `updateOne()` vs `updateMany()`.
* `deleteOne()` vs `deleteMany()`.
* `replaceOne()` vs `updateOne()`.
* What is MongoDB projection?
* What is pagination in MongoDB?
* Offset pagination vs cursor-based pagination.

## MongoDB Transactions

* What are transactions?
* When would you use a MongoDB transaction?
* What is atomicity in MongoDB?

---

# 5. Mongoose

Extremely important.

If you're putting **MERN developer** on your resume, expect Mongoose questions.

## Mongoose Fundamentals

* What is Mongoose?
* Schema vs model.
* What is a Mongoose document?
* What are schema types?
* What are defaults?
* What are validators?
* `required`, `unique`, `enum`, `min`, `max`.

## Mongoose Middleware and Relationships

* What are Mongoose middleware / hooks?
* Pre vs post middleware.
* What is `populate()`?
* `populate()` vs MongoDB `$lookup`.

## Mongoose Query Optimization

* What is `.lean()`?
* Why and when would you use `.lean()`?
* What is `select()`?
* What are virtuals?
* What are timestamps?
* How do you implement pagination using Mongoose?
* How do you optimize a slow Mongoose query?

---

# 6. Authentication & Security

This is another area I'd expect at **1–2 YOE**.

## Authentication Fundamentals

* What is authentication vs authorization?
* How does JWT authentication work?
* What are access tokens and refresh tokens?
* Where should you store JWTs?
* `localStorage` vs cookies for authentication.
* What is an HTTP-only cookie?

## Web Security

* What is CSRF?
* What is XSS?
* How do you prevent XSS?
* What is password hashing?
* Why should passwords never be stored directly?
* Explain bcrypt.
* What is salting?
* What is CORS and how does it affect authentication?

## Authorization and Token Management

* How do you implement role-based authorization?
* How do you protect an Express route?
* What happens when a JWT expires?
* How does refresh-token rotation work?

---

# 7. REST API Design

Add practical questions like:

## API Design Questions

* Design a user registration API.
* Design a login API.
* Design a product CRUD API.
* Design a blog API.
* How would you design `/users`, `/posts`, `/comments`?
* How would you implement pagination?
* How would you implement search?
* How would you implement filtering?
* How would you implement sorting?
* How would you version an API?
* How would you handle API errors consistently?
* What response format would you use?
* How would you prevent duplicate requests?
* How would you handle concurrent updates?

---

# 8. Project-Based Questions

This is very important for **1–2 YOE**.

Interviewers will often look at your resume and ask:

> "Explain your project."

You should be able to answer:

## Architecture

* Why did you choose this architecture?
* Why MongoDB?
* Why React?
* How does the frontend communicate with the backend?
* Explain your folder structure.
* Explain one complete API from:

  * Frontend
  * Express
  * Controller
  * Service
  * Database
  * Response

## Authentication and Error Handling

* How did you implement authentication?
* How did you handle errors?
* How did you validate requests?
* How did you handle loading states?

## Performance and Scalability

* How did you optimize performance?
* What was the hardest bug you faced?
* How did you debug it?
* What would you change if you rebuilt the project?
* How would your application handle 10× traffic?

## Deployment and Production

* How did you deploy it?
* Where are environment variables stored?
* How do you protect secrets?
* How do you monitor production errors?

These questions can matter **more than knowing an obscure JavaScript feature**.

---

# 9. Coding & DSA

Your **#108–117** is a good start, but I'd add:

## Arrays and Strings

* Two Sum
* Three Sum
* Anagram
* First non-repeating character
* Character frequency
* Array chunking
* Flatten nested array
* Flatten nested object
* Merge two sorted arrays
* Intersection of two arrays
* Union of two arrays
* Missing number
* Move zeroes
* Rotate array
* Valid parentheses
* Longest substring without repeating characters

## Searching and Algorithms

* Binary search
* Linear search

## Data Structures

* Stack implementation
* Queue implementation
* LRU cache
* Linked-list basics
* Tree traversal basics
* BFS / DFS basics

For **1–2 YOE MERN**, you don't necessarily need hardcore competitive programming, but you should be comfortable with **easy + some medium DSA**.

---

# 10. How to Prepare This Sheet

One important change I'd make to your sheet:

Don't prepare this as:

> **117 questions I need to memorize.**

Prepare it as:

> **Interview concepts I need to be able to explain + implement.**

For example, for Promises, you shouldn't just memorize:

> "Promise.all waits for all promises..."

You should be able to do:

```javascript
Promise.all([
  fetchUser(),
  fetchPosts(),
  fetchComments()
])
```

And explain:

* What happens internally?
* What happens if one rejects?
* Microtask behavior.
* Ordering.
* Why `Promise.allSettled()` differs.
* When you'd use each.
* How to implement a simplified polyfill.

That's the level that will make the sheet useful.

---

# 11. Recommended Priority

If you're preparing specifically for a **1–2 year MERN interview**, I'd divide your preparation roughly like this:

## 🔴 Tier 1 — Must Know

### JavaScript

* Scope / hoisting / TDZ
* Closures
* `this`
* Prototypes
* Promises
* `async/await`
* Event loop
* Microtasks / macrotasks
* Array / object methods
* Destructuring / spread / rest
* Error handling
* ES modules
* Debounce / throttle

### React

* Components
* Props / state
* Hooks
* `useEffect`
* `useMemo` / `useCallback`
* `useRef`
* Context
* Custom hooks
* Rendering / re-rendering
* Forms
* API calls

### Node.js / Express

* Event loop
* Middleware
* Routing
* Error handling
* REST APIs
* Authentication
* CORS
* Validation

### MongoDB / Mongoose

* CRUD
* Schema / model
* Indexes
* Aggregation
* `populate`
* Transactions
* Pagination
* Query optimization

### Practical

* Authentication
* CRUD
* API integration
* Project architecture
* Debugging

---

## 🟡 Tier 2 — Strong Advantage

* Streams
* Buffers
* Worker threads
* Child processes
* Generators
* Iterators
* `WeakMap` / `WeakSet`
* `Proxy`
* Memory leaks
* Browser rendering
* Advanced Promise questions
* Advanced MongoDB aggregation
* Caching
* Redis
* WebSockets

---

## 🟢 Tier 3 — Don't Over-Invest Initially

Things like:

* Obscure JavaScript edge cases
* Complicated polyfills
* Advanced Node.js internals
* Deep V8 internals
* Complicated distributed-system concepts

They're useful, but **not before you have React + MongoDB + Express + authentication solid**.

---

# Final Preparation Strategy

Your goal should not be:

> **"I need to memorize every question."**

Your goal should be:

> **"I can explain the concept, write the code, debug it, and explain why I chose that approach."**

For a **1–2 YOE MERN interview**, prioritize:

**JavaScript → React → Node/Express → MongoDB/Mongoose → Authentication → REST APIs → Projects → DSA**

Once those are strong, move into the Tier 2 topics.
