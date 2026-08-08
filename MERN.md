1. Your JavaScript section is already very strong

Honestly, don't keep adding random JavaScript questions.

For 1–2 YOE, if you can confidently answer and code the questions you've listed, especially:

closures
this
prototypes
execution context
event loop
microtasks/macrotasks
promises
async/await
call/apply/bind
currying
memoization
debounce/throttle
polyfills
shallow/deep copy
garbage collection
event delegation
browser rendering
type coercion
ES modules
Node event loop

…you're already at a very good JS level.

I'd actually merge/remove duplicates. For example:

#27, #61, #62, #63 → one prototype section
#38, #93, #94, #95, #96 → one memory/GC section
#19, #97 → one event delegation section
#44, #98 → one event-control section
#40, #102, #103 → one rendering-performance section
#47, #100 → one XSS section

That will make your sheet much easier to revise.

2. The biggest missing part: React

For a MERN interview, this is the biggest hole.

I'd add at least these:

React fundamentals
What is React and why use it?
What is the Virtual DOM?
How does reconciliation work?
What is the difference between Virtual DOM and real DOM?
What are components?
Functional vs class components.
What are props?
What is state?
Props vs state.
What happens when state changes?
Why should state not be mutated directly?
Controlled vs uncontrolled components.
What are keys in React and why are they important?
Why should we avoid using array index as a key?
What is conditional rendering?
What is lifting state up?
What is prop drilling?
How can you solve prop drilling?
Hooks — very important for 1–2 YOE
Explain useState.
Explain useEffect.
What does the dependency array do?
What happens if the dependency array is empty?
What happens if there is no dependency array?
Why does useEffect sometimes run twice in development?
What is cleanup in useEffect?
How can useEffect cause an infinite loop?
Explain useRef.
useRef vs useState.
Explain useMemo.
Explain useCallback.
useMemo vs useCallback.
When should you NOT use useMemo/useCallback?
Explain useContext.
What are custom hooks?
Create a custom hook.
Rules of Hooks.
What happens when hooks are called conditionally?
React performance
What causes unnecessary re-renders?
How do you optimize a React application?
What is React.memo?
React.memo vs useMemo vs useCallback.
How would you optimize a large list?
What is lazy loading in React?
Explain React.lazy and Suspense.
What is code splitting?
How would you implement pagination/infinite scrolling?
React practical questions

These are very important because interviewers often stop asking theory and give you a situation:

Build a search box with debouncing.
Build a pagination component.
Build a modal.
Build a reusable form component.
Fetch API data and handle loading/error/success states.
Cancel an API request when a component unmounts.
Implement authentication-protected routes.
Implement a shopping cart.
Explain how you would structure a large React project.
3. Express.js is completely missing

Add:

What is Express.js?
What is middleware?
How does Express middleware work?
Application-level vs router-level middleware.
What is error-handling middleware?
How do you create a centralized error handler?
What is req, res, and next?
Difference between req.params, req.query, and req.body.
How do you validate request data?
How do you handle async errors in Express?
How do you structure an Express application?
Controller vs service vs repository.
What is REST?
GET vs POST vs PUT vs PATCH vs DELETE.
What are HTTP status codes?
What is idempotency?
What are HTTP headers?
What is CORS?
Why does CORS happen?
How do you configure CORS?
What is rate limiting?
How would you secure an Express API?
How do you handle file uploads?
How do you implement pagination in an API?
How do you implement filtering/sorting/searching?
4. MongoDB is another major gap

For MERN, I'd consider this mandatory.

MongoDB fundamentals
What is MongoDB?
SQL vs NoSQL.
Database vs collection vs document.
What is BSON?
Embedded documents vs references.
What is _id and ObjectId?
What are indexes?
How do indexes improve query performance?
What are the disadvantages of indexes?
Single-field vs compound indexes.
What is a unique index?
What is a TTL index?
What is aggregation?
Explain $match, $group, $project, $sort, $lookup, $unwind.
find() vs findOne().
updateOne() vs updateMany().
deleteOne() vs deleteMany().
replaceOne() vs updateOne().
What is MongoDB projection?
What is pagination in MongoDB?
Offset pagination vs cursor-based pagination.
What are transactions?
When would you use a MongoDB transaction?
What is atomicity in MongoDB?
5. Mongoose — extremely important

If you're putting MERN developer on your resume, expect Mongoose questions.

What is Mongoose?
Schema vs model.
What is a Mongoose document?
What are schema types?
What are defaults?
What are validators?
required, unique, enum, min, max.
What are Mongoose middleware/hooks?
Pre vs post middleware.
What is populate()?
populate() vs MongoDB $lookup.
What is .lean()?
Why and when would you use .lean()?
What is select()?
What are virtuals?
What are timestamps?
How do you implement pagination using Mongoose?
How do you optimize a slow Mongoose query?
6. Authentication & security — very important

This is another area I'd expect at 1–2 YOE.

What is authentication vs authorization?
How does JWT authentication work?
What are access tokens and refresh tokens?
Where should you store JWTs?
localStorage vs cookies for authentication.
What is an HTTP-only cookie?
What is CSRF?
What is XSS?
How do you prevent XSS?
What is password hashing?
Why should passwords never be stored directly?
Explain bcrypt.
What is salting?
What is CORS and how does it affect authentication?
How do you implement role-based authorization?
How do you protect an Express route?
What happens when a JWT expires?
How does refresh-token rotation work?
7. REST API design

Add practical questions like:

Design a user registration API.
Design a login API.
Design a product CRUD API.
Design a blog API.
How would you design /users, /posts, /comments?
How would you implement pagination?
How would you implement search?
How would you implement filtering?
How would you implement sorting?
How would you version an API?
How would you handle API errors consistently?
What response format would you use?
How would you prevent duplicate requests?
How would you handle concurrent updates?
8. Add project-based questions

This is very important for 1–2 YOE.

Interviewers will often look at your resume and ask:

"Explain your project."

You should be able to answer:

Why did you choose this architecture?
Why MongoDB?
Why React?
How does the frontend communicate with backend?
Explain your folder structure.
Explain one complete API from frontend → Express → controller → service → database → response.
How did you implement authentication?
How did you handle errors?
How did you validate requests?
How did you handle loading states?
How did you optimize performance?
What was the hardest bug you faced?
How did you debug it?
What would you change if you rebuilt the project?
How would your application handle 10× traffic?
How did you deploy it?
Where are environment variables stored?
How do you protect secrets?
How do you monitor production errors?

These questions can matter more than knowing an obscure JavaScript feature.

9. Your coding section needs more depth

Your #108–117 is a good start, but I'd add:

Two Sum
Three Sum
Anagram
First non-repeating character
Character frequency
Array chunking
Flatten nested array
Flatten nested object
Merge two sorted arrays
Intersection of two arrays
Union of two arrays
Missing number
Move zeroes
Rotate array
Valid parentheses
Longest substring without repeating characters
Binary search
Linear search
Stack implementation
Queue implementation
LRU cache
Linked-list basics
Tree traversal basics
BFS/DFS basics

For 1–2 YOE MERN, you don't necessarily need hardcore competitive programming, but you should be comfortable with easy + some medium DSA.

10. One important change I'd make to your sheet

Don't prepare this as:

117 questions I need to memorize.

Prepare it as:

Interview concepts I need to be able to explain + implement.

For example, for Promises, you shouldn't just memorize:

"Promise.all waits for all promises..."

You should be able to do:

Promise.all([
  fetchUser(),
  fetchPosts(),
  fetchComments()
])

and explain:

what happens internally
what happens if one rejects
microtask behavior
ordering
why Promise.allSettled() differs
when you'd use each
implement a simplified polyfill

That's the level that will make the sheet useful.

My recommended priority

If you're preparing specifically for a 1–2 year MERN interview, I'd divide your preparation roughly like this:

🔴 Tier 1 — Must know

JavaScript

scope/hoisting/TDZ
closures
this
prototypes
promises
async/await
event loop
microtasks/macrotasks
array/object methods
destructuring/spread/rest
error handling
ES modules
debounce/throttle

React

components
props/state
hooks
useEffect
useMemo/useCallback
useRef
Context
custom hooks
rendering/re-rendering
forms
API calls

Node/Express

event loop
middleware
routing
error handling
REST APIs
authentication
CORS
validation

MongoDB/Mongoose

CRUD
schema/model
indexes
aggregation
populate
transactions
pagination
query optimization

Practical

authentication
CRUD
API integration
project architecture
debugging

🟡 Tier 2 — Strong advantage

streams
buffers
worker threads
child processes
generators
iterators
WeakMap/WeakSet
Proxy
memory leaks
browser rendering
advanced Promise questions
advanced MongoDB aggregation
caching
Redis
WebSockets
🟢 Tier 3 — Don't over-invest initially

Things like:

obscure JS edge cases
complicated polyfills
advanced Node internals
deep V8 internals
complicated distributed-system concepts

They're useful, but not before you have React + MongoDB + Express + authentication solid.