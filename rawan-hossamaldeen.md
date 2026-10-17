# Learning Journey & Technical Self-Assessment

**Name:** Rawan Hossam Aldeen
**Role:** Squad Member
**Squad:** Squad B
**Date:** October 2026

---

## 1. What I Learned in the Bootcamp So Far
- **Backend & Web Concepts:** I learned that a backend is the part that receives requests from a client, runs the logic, and sends a response back. In Express, a request goes through middleware functions one by one. Each middleware gets `req`, `res` and `next`, and it either calls `next()` to pass the request on or sends a response to finish it. I also learned that the order of middleware matters: for example, the JSON parser has to come before the routes, otherwise `req.body` is empty. Error handlers are special because they take four arguments, and a response should never be sent twice for the same request.
- **JavaScript Fundamentals & ES6+:** I practiced scopes, data types, arrow functions, destructuring, spread/rest, and array methods like filter, find, map, some, and reduce on arrays of objects.
- **Advanced JavaScript:** I was introduced to OOP, timers, promises, and async/await. I understand the idea behind them, and I am still clarifying the finer points, especially how they are used with databases.
- **TypeScript:** I learned type annotations, type aliases, literal types, interfaces, optional and readonly properties, and typing function parameters and return values. I applied them in a 30-function library task (ShelfStack).
- **Node.js & Ecosystem:** I learned that Node.js is a runtime that lets JavaScript run outside the browser. It uses the V8 engine to run the code, and libuv together with the operating system to handle slow work like files and network. My code runs on one main thread, and the event loop takes care of returning the results as callbacks when the slow work is done. This is why async code does not block the app, but a heavy CPU loop still would, because the event loop does not make it parallel. I also learned the difference between CommonJS and ES Modules.
- **Git & GitHub:** I learned the Git workflow (workspace, staging area, local repo, remote repo), init, add, commit, push, branching, fetch and merge, and I am now practicing team collaboration through branches.

---

## 2. JavaScript Proficiency Self-Assessment
- **Current Confidence Rating:** 7 / 10
- **My Strengths in JS:** Array methods including reduce, writing clean functions, and applying TypeScript types to real data.
- **Areas I am Actively Improving:** I find complex, multi-step functions harder to solve, such as functions that combine several data sources or build reports and statistics. I am also clarifying how async/await and the event loop apply to databases, and getting comfortable with Git from the command line.
- **Overall Reflection:** I have built a solid base and I learn best by practicing on real tasks and asking questions when I am stuck. I want to get better at breaking complex problems into smaller steps so I can follow the upcoming Express and MongoDB lectures with confidence.
