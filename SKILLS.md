# Skills

A personal map of topics. The color is a status, not a claim that every green item is used at work every day.

| Mark | Meaning | What to do with it |
| --- | --- | --- |
| 🟩 | Learned | Keep it sharp by using it in a project |
| 🟦 | Required in the program, still open | Study this next if you follow the program |
| 🟨 | Required for JavaScript, still open | Same, for the JavaScript track |
| ⬜ | Optional, not started | A study idea, not a gap you must close today |
| 🟥 | Declined | Left out on purpose |

How to read the page:

1. **Program track** is the original checklist: fundamentals, paradigms, async, Node.js.
2. **Study list** is everything marked ⬜. That is the pool of things worth learning next.
3. The stack used in projects (TypeScript, React, Node.js, SQL, Git) is on the profile README. This file is the wider map.

## Contents

- [Fundamental concepts](#fundamental-concepts)
- [Multi-paradigm programming](#multi-paradigm-programming)
- [Asynchronous programming](#asynchronous-programming)
- [Node.js and backend](#nodejs-and-backend)
- [Worth knowing next](#worth-knowing-next)

## Fundamental concepts

Language and everyday code. Almost all of this is marked learned. The columns are syntax, control flow, functions, data structures, and how code is written and reviewed.

| Syntax | Statements | Functions | Data structures | Process and style |
| --- | --- | --- | --- | --- |
| 🟩 value | 🟩 if | 🟩 recursion | 🟩 array | 🟩 refactoring |
| 🟩 identifier | 🟩 loops | 🟩 function | 🟩 instance | 🟩 code review |
| 🟩 variable | 🟩 assignment | 🟩 return | 🟩 object | 🟩 antipatterns |
| 🟩 constant | 🟩 prototype | 🟩 signature | 🟩 collection | 🟩 paradigm |
| 🟩 scalar | 🟩 class | 🟩 argument | 🟩 hash table | 🟩 algorithm |
| 🟩 literal | 🟩 while | 🟩 parameter | 🟩 linked list | 🟩 magic numbers |
| 🟩 expression | 🟩 do..while | 🟩 pure function | 🟩 queue | 🟩 hardcode |
| 🟩 heap | 🟩 for | 🟩 lambda | 🟩 stack | 🟩 complexity |
| 🟩 type | 🟩 for..in | 🟩 side effects | 🟩 deque | 🟩 decomposition |
| 🟩 primitive types | 🟩 for..of | 🟩 closure | 🟩 serialization | 🟩 spaghetti |
| 🟩 reference | 🟩 for await | 🟩 partial | 🟩 mixin, extend | 🟩 silver bullet |
| 🟩 flag | 🟩 throw | 🟩 curry | 🟩 iterator | 🟩 not invented here |
| 🟩 lexical scope | 🟩 try..catch | 🟩 chaining | 🟩 typed arrays | 🟩 dead code |
| 🟩 code block | 🟩 equality operators | 🟩 higher order | 🟩 Map | 🟩 unreachable code |
| 🟩 Object | 🟩 logical operators | 🟩 callback | 🟩 Set | 🟩 duplicate code |
| 🟩 this | 🟩 bitwise operators | 🟩 listener | 🟩 weak collections | 🟩 exception |
| 🟩 arrow function | 🟩 break, continue | 🟩 pipe | 🟩 Proxy | 🟩 return early |
| 🟩 generator | 🟩 switch | 🟩 compose | 🟩 Symbol | 🟩 linter |
| 🟩 async function | 🟩 new Error | 🟩 memoize | 🟩 string parsing | 🟩 prettier |
| 🟩 call, bind, apply | | 🟩 factory | 🟩 timers | 🟩 unittest |
| 🟩 Array | | 🟩 pool | 🟩 EventEmitter | 🟩 git |
| 🟩 instanceof | | 🟩 wrapper | 🟩 RegExp | 🟩 github |
| 🟩 ...spread | | 🟩 default parameters | 🟩 global | 🟩 node.js |
| 🟩 ...rest | | | 🟩 undefined | 🟩 npm |
| 🟩 typeof | | | 🟩 null | |

## Multi-paradigm programming

Ways to structure a program. Theory and OOP basics are mostly learned. Introspection is still open. Patterns so far list only Singleton; more patterns are in the study list below.

| Theory | OOP basics | Abstractions | Patterns |
| --- | --- | --- | --- |
| 🟩 Procedural programming | 🟩 constructor | 🟩 struct, record | 🟩 Singleton |
| 🟩 Imperative programming | 🟩 new | 🟩 Mutable state | |
| 🟩 Structured programming | 🟩 Static method | 🟩 Immutable state | |
| 🟩 Non-structured programming | 🟩 Method | 🟩 Enum | |
| 🟩 Functional programming | 🟩 Async method | 🟩 Linked list | |
| 🟩 Prototype-based programming | 🟩 Getters, Setters | 🟩 Doubly list | |
| 🟩 Object-oriented programming | 🟩 Public fields | 🟩 Unrolled list | |
| 🟩 Object-based programming | 🟩 Private fields | 🟩 Circular list | |
| 🟩 Generic programming | 🟩 Field declarations | 🟩 Trees | |
| 🟩 Concurrent computing | 🟩 Inheritance | 🟩 Graphs | |
| 🟩 Asynchronous programming | 🟩 Parent class | 🟩 Functor | |
| 🟩 Parallel programming | 🟩 Polymorphism | 🟩 Functional object | |
| 🟩 Reactive programming | 🟩 Abstract class | 🟩 Monad | |
| 🟩 FRP (functional-reactive) | 🟩 Interface | 🟩 Generator | |
| 🟩 Automata-based programming | 🟩 Encapsulation | 🟩 Iterator | |
| 🟩 Domain-specific languages | 🟩 Hidden class | 🟩 Async Iterator | |
| 🟩 Multi-paradigm programming | 🟩 Object form | | |
| 🟩 Metaprogramming | 🟩 instance | | |
| 🟩 Actor model | ⬜ Introspection | | |
| | 🟩 Reflection | | |

## Asynchronous programming

Promises, the event loop, and Node.js scheduling. Green items are the everyday tools (`async`/`await`, `Promise.all`, timers). Blue items are still required. White items (Rx.js, cancelable promises, thread pool) are optional and not started.

| Async contracts | JavaScript and Node.js | Theory | Techniques |
| --- | --- | --- | --- |
| 🟩 Callback-last | 🟩 Timers | 🟩 Event Loop | 🟩 async.js library |
| 🟩 Error-first | 🟩 setImmediate | 🟩 Async error | ⬜ Async composition |
| 🟩 Promise | 🟩 nextTick | 🟩 try..catch | ⬜ Rx.js |
| 🟩 Async function | 🟩 AbortController | 🟩 Non-blocking | 🟩 Sequential async |
| 🟩 await | 🟩 Promise unhandled rejection | 🟩 Async I/O | 🟩 Parallel async |
| 🟩 Generator | 🟩 Promise double resolve | 🟦 Pattern Reactor | 🟩 Promise.all |
| 🟩 Async Generator | 🟦 child_process | ⬜ CAS operations | 🟩 Promise.allSettled |
| 🟩 Async Iterator | 🟦 worker_threads | ⬜ epoll | 🟩 Promise.race |
| 🟩 Thenable | 🟦 Atomics | ⬜ kqueue | 🟩 Promise.any |
| 🟩 EventEmitter | 🟦 Blocking operations | ⬜ Completion ports | ⬜ Web Locks API |
| ⬜ Cancelable callback | 🟦 Non-blocking loop for Array | ⬜ Event ports | ⬜ Async Pool |
| ⬜ Cancelable Promise | 🟩 High resolution clock | 🟩 libuv | ⬜ Thread Pool |
| 🟩 Asynchronous Queue | 🟩 Callback hell | 🟦 Race conditions | 🟦 callbackify |
| ⬜ Future | 🟩 Promise hell | 🟦 Dead locks | 🟦 promisify |
| ⬜ Deferred | | 🟦 Live locks | ⬜ IPC |
| 🟦 Observer | | ⬜ Actor Model | ⬜ Channel API |
| ⬜ Async Collector | | | ⬜ Revealing Constructor |
| ⬜ Coroutine | | | |
| ⬜ Goroutine | | | |

## Node.js and backend

Node.js internals, architecture, HTTP, and production problems. Green is what is already studied. Blue is still required by the program (streams, clustering, security issues, DDD, clean architecture). White is optional (addons, WebAssembly, serverless, HTTP/3).

| Internals | Theory | Network | Technique | Problems |
| --- | --- | --- | --- | --- |
| 🟩 Nonblocking I/O | 🟩 I/O bound tasks | 🟩 HTTP(S) | 🟩 Logging | 🟩 Memory leaks |
| 🟩 Event Loop | 🟦 CPU bound tasks | 🟩 TCP/SSL | 🟩 Testing | 🟦 Resource leaks |
| 🟩 CommonJS | 🟦 Memory bound tasks | 🟩 UDP | 🟩 CI/CD | 🟩 Blocking code |
| 🟩 ECMAScript modules | 🟩 Multilayer approach | 🟩 TLS | 🟦 Readable | 🟦 Data race |
| 🟦 Network API | 🟩 Separation of concerns | 🟩 Websocket | 🟦 Writable | 🟦 Graceful shutdown |
| ⬜ Addons | 🟦 Inversion of control | ⬜ SSE | 🟦 Transform | 🟩 Dependencies |
| ⬜ N-API | 🟦 Dependency injection | ⬜ HTTP/3 (QUIC) | ⬜ back pressure | |
| ⬜ WebAssembly | 🟩 GRASP for JS and Node.js | ⬜ Long polling | 🟩 Buffer | |
| 🟩 npm | 🟩 SOLID for JS and Node.js | 🟩 REST | 🟩 Console | |
| 🟩 node_modules | 🟦 GoF for JS and Node.js | 🟦 RPC | 🟩 Inspector | |
| 🟩 package.json | 🟩 Distributed systems | 🟩 Routing | 🟩 Reliability | |
| 🟦 vm isolation | 🟩 Highload applications | 🟦 IP sticky | 🟩 Quality | |
| 🟦 command line args | 🟦 DDD | 🟦 DoS | 🟩 Availability | |
| ⬜ Node.js CLI | 🟦 Clean architecture | 🟦 DDoS | 🟩 Flexibility | |
| 🟦 Streams | 🟦 Domain in the middle | 🟦 XSS | | |
| 🟦 Clustering | 🟦 Message queue | 🟦 Path traversal | | |
| 🟩 Load balancing | 🟦 Transport-agnostic server | 🟦 CSRF | | |
| ⬜ Serverless clouds | 🟦 Framework-agnostic app | 🟩 DNS | | |
| ⬜ FaaS clouds | ⬜ Interactive applications | 🟩 Fetch | | |
| 🟩 Debugging Node.js | 🟩 Real-time applications | 🟦 zlib | | |
| 🟩 crypto | 🟦 CQS and CQRS | | | |
| ⬜ SharedArrayBuffer | 🟦 Event Sourcing | | | |
| 🟦 child_process | 🟦 Shared memory | | | |
| 🟦 worker_threads | | | | |

## Worth knowing next

Topics that are not in the tables above. Every row here is still open (⬜). They are grouped so you can pick one column and study it, instead of reading a flat list.

Practical frontend and full-stack work:

| Frontend | TypeScript and React | Data and API | Delivery | Engineering |
| --- | --- | --- | --- | --- |
| ⬜ Accessibility | ⬜ Strict mode and narrowing | ⬜ PostgreSQL | ⬜ Git branching | ⬜ TDD |
| ⬜ Semantic HTML | ⬜ Generics | ⬜ Indexes and query plans | ⬜ Pull requests | ⬜ Unit tests with a runner |
| ⬜ Responsive layout | ⬜ Utility types | ⬜ Migrations | ⬜ Code review on a real PR | ⬜ Integration tests |
| ⬜ CSS layout (flex, grid) | ⬜ React hooks in depth | ⬜ Transactions | ⬜ CI on GitHub Actions | ⬜ Testing Library |
| ⬜ CSS animations | ⬜ Component state vs server state | ⬜ MongoDB aggregation | ⬜ Docker basics | ⬜ End-to-end tests (Playwright) |
| ⬜ Forms and validation | ⬜ React Router | ⬜ REST error shapes | ⬜ Docker Compose | ⬜ Debugging in the browser |
| ⬜ Design systems | ⬜ Data fetching | ⬜ Pagination and cursors | ⬜ Environment variables | ⬜ Performance profiles |
| ⬜ Browser rendering | ⬜ TanStack Query | ⬜ Filtering and search | ⬜ Linux command line | ⬜ Core Web Vitals |
| ⬜ HTTP caching | ⬜ Error boundaries | ⬜ File uploads | ⬜ npm scripts | ⬜ Web security (XSS, CSRF, auth) |
| ⬜ Browser storage | ⬜ Redux Toolkit | ⬜ Auth sessions vs JWT | ⬜ Package publishing | ⬜ OWASP basics |
| ⬜ Internationalization | ⬜ Zustand or similar stores | ⬜ OAuth and OpenID | ⬜ Semantic versioning | ⬜ Content Security Policy |
| ⬜ Dark mode and themes | ⬜ Next.js | ⬜ Webhooks | ⬜ Changelog | ⬜ Logging in production |
| ⬜ SVG and icons | ⬜ Server components | ⬜ Rate limiting | ⬜ Feature flags | ⬜ Monitoring and alerts |
| ⬜ Canvas basics | ⬜ Forms libraries (React Hook Form) | ⬜ Idempotent APIs | ⬜ Preview deployments | ⬜ Error tracking (Sentry) |
| | ⬜ Storybook | ⬜ OpenAPI | ⬜ Monorepos | ⬜ Design patterns beyond Singleton |
| | ⬜ Module bundlers (Vite, webpack) | ⬜ GraphQL basics | | ⬜ Refactoring a large file |
| | | ⬜ Redis basics | | ⬜ Reading other people's code |

Server, hosting, and how work is organized. Same rule: nothing here is marked learned.

### Backend, platform, and product

| Backend | Platform | Product and collaboration |
| --- | --- | --- |
| ⬜ Validation on the server (Zod) | ⬜ DNS and domains | ⬜ Writing a short spec before coding |
| ⬜ ORM beyond a first Prisma schema | ⬜ HTTPS and certificates | ⬜ Splitting work into small tasks |
| ⬜ Background jobs and queues | ⬜ Object storage (S3) | ⬜ Estimating a task in hours |
| ⬜ Caching (HTTP and Redis) | ⬜ CDN | ⬜ Writing a README a stranger can run |
| ⬜ Email sending | ⬜ Linux processes and logs | ⬜ Reproducing a bug before fixing it |
| ⬜ File storage | ⬜ Nginx or Caddy basics | ⬜ Asking for a code review |
| ⬜ WebSockets in an app | ⬜ Cloud deploy (one provider) | ⬜ Giving a code review |
| ⬜ Cron and scheduled tasks | ⬜ Backups and restore | ⬜ Writing user-facing copy |
| ⬜ Search (Postgres full-text) | ⬜ Secrets management | ⬜ Analytics events, without tracking people secretly |
| ⬜ SQL joins in real queries | ⬜ Cost of a small cloud app | ⬜ Accessibility checks with a keyboard |

### Further out

Still open, and less tied to day-to-day frontend work:

- ⬜ Cybersecurity as a field
- ⬜ Mobile applications
- ⬜ High-performance computing
- ⬜ Edge computing
- ⬜ Data warehouses
- ⬜ Low-code and no-code platforms
