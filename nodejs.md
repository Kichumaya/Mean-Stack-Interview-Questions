# Node.js Interview Questions

## Core Concepts
- Is Node.js single-threaded? How does it handle concurrency?
- Node.js architecture & phases of the event loop
- Event loop (queues, microtask/macrotask)
- Two types of queue in Node.js
- Import in Node.js
- Predefined modules (fs, http, https, path, os, crypto, stream, events, url, timers, buffer, querystring)
- Libuv

## Middleware & Request Handling
- body-parser usage
- Middleware (Express, Body Parser, Logging, Authentication)
- Payload — usage with other HTTP methods
- Express beyond routing
- REST API basics

## Database Integration
- How to connect MongoDB to Node.js
- Sharding in MongoDB
- Transactions in Node.js (ACID, race conditions)
- Scaling — monolith vs microservices

## Authentication & Security
- JWT — usage, expiration, pros & cons, stateful/stateless
- Authentication vs Authorization
- How to secure Node.js routes (middleware, JWT, role-based)
- API security (JWT, multifactor, CORS, helmet, rate limiting, validation)
- OTP authentication handling
- Secure backend rendering from frontend
- CORS & preflight requests
- Store DB passwords securely (.env)
- Prevent SQL injection

## Performance & Scaling
- Increase core usage (Cluster)
- Multi-threading in Node.js (Cluster, worker_threads)
- Make async code synchronous (callbacks, promises, async/await)
- Promise vs Promise.all — why Promise.all for parallel requests
- Redis usage (cache, pub/sub)
- Rate limiting (in-memory, Redis)

## Asynchronous Programming
- Callback & callback hell (avoid with promises/async-await)
- Error handling in Node.js (try/catch, .catch, error-first callbacks)

## Streams & Buffers
- Buffer in Node.js
- Streams (readable, writable, duplex, transform)

## DevOps & Tooling
- CI/CD pipelines (Jenkins, GitHub Actions)
- Swagger in Node.js
- Unit testing in Node.js (Jest)

## GraphQL in Node.js
- Query, mutation, scalar types
