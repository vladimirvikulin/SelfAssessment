## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js: 🖐️ used
  - Stateful and stateless servers: 🖐️ used
  - Nonblocking I/O and blocking code: 🎓 known
  - Event loop phases: 🎓 known
  - Event loop microtasks and macrotasks: 👂 heard
  - Garbage collection: 🖐️ used
  - Node.js LTS schedule: 🖐️ used
  - I/O-bound, CPU-bound, memory-bound tasks: 👂 heard
  - Interactive applications (close to real-time): 👂 heard
- Modularity, layers and dependencies
  - CommonJS modules: 🖐️ used
  - ECMAScript modules: 🖐️ used
  - Module `node:module`: 🖐️ used
  - Caching in CJS and ESM
  - Modules as singletons
  - Contexts and scripts module `node:vm`
  - Dependencies: `npm`, `node_modules`: 🖐️ used
  - Files `package.json`, `package-lock.json`: 🖐️ used
  - Module-based permissions model: 👂 heard
  - Isolation with modularity: 🖐️ used
  - Dependency injection: 🖐️ used
  - DI containers
  - Coupling and cohesion
  - Framework agnostic approach
- Environment
  - Command line arguments: 🖐️ used
  - Node.js CLI: 🎓 known
  - Process-based permissions: 👂 heard
  - Graceful shutdown: 🎓 known
  - Clustering: 👂 heard
  - Watch filesystem changes with --watch
- Internal API
  - Streams API
  - Web Streams API
  - Crypto API: 🎓 known
  - Password hashing with crypto.scrypt: 🖐️ used
  - Web Crypto API: 🎓 known
  - File system API (sync and async)
  - Copy folder recursively
  - Worker threads: 👂 heard
  - Performance hooks
  - Native fetch and nodejs/undici: 🎓 known
  - async_hooks
  - AsyncLocalStorage
  - AsyncResource
  - Deprecated domain API
  - Node.js single executable
  - SharedArrayBuffer
  - Module `node:worker_threads`
  - Module `node:child_process`
  - MessageChannel, MessagePort
  - BroadcastChannel: 👂 heard
  - Generating crypto random UUID: 🖐️ used
  - Module `node:url` vs `new URL`: 🖐️ used
  - Module `node:assert`: 🖐️ used
  - Internationalization
  - Blob, File, Buffer, module `node:buffer`: 👂 heard
  - Module `node:zlib`
- Network
  - Endpoint throttling
  - ALPN
  - SNI callback
  - SSL certificates
  - Protocol agnostic approach
  - Fetch API: 🖐️ used
  - IncomingMessage
  - HTTP(S): 👂 heard
  - TCP/SSL: 👂 heard
  - UDP: 👂 heard
  - TLS
  - Websocket: 👂 heard
  - SSE
  - HTTP/3 (QUIC)
  - Long polling
  - REST
  - RPC
  - Routing
  - DoS: 👂 heard
  - DDoS: 👂 heard
  - XSS
  - Path traversal
  - CSRF
  - DNS: 👂 heard
  - SQL injection: 🎓 known
  - noDelay
  - keep-alive: 👂 heard
  - IP sticky sessions: 👂 heard
- Technique and tools
  - Native test runner: 🎓 known
  - Logging: 🎓 known
  - Application configuring: 🖐️ used
  - Testing: 🖐️ used
  - CI/CD: 🖐️ used
  - Readable: 👂 heard
  - Writable: 👂 heard
  - Transform
  - Back pressure
  - Buffer: 👂 heard
  - Console: 🖐️ used
  - Inspector
- Data access
  - Data access layer: 🎓 known
  - Repository: 👂 heard
  - Active record
  - Query builder
  - Object-Relational Mapping
  - CRUD: 🖐️ used
  - DTO: 👂 heard
- Error handling and debugging
  - `Error`: 🖐️ used
  - `error.cause`: 🎓 known
  - `error.code`: 🎓 known
  - `error.message`: 🖐️ used
  - `error.stack`: 🎓 known
  - `Error.captureStackTrace`: 🎓 known
  - How to avoid mixins
  - Uncaught exceptions: 🎓 known
  - Heap dump: 👂 heard
  - Debugging tools: 🎓 known
  - Flame graph
  - Memory leaks: 👂 heard
  - Resource leaks
  - Data race
- Integrations and bindings
  - Native addons
  - `C` and `C++` addons
  - `Rust` addons
  - `Zig` addons
  - NAN (Native Abstractions for Node.js)
  - Node-API (formerly N-API)
  - NAPI `C` and `C++`
  - NAPI `Rust`
  - NAPI `Zig`
  - Webassembly `WAT`
  - Webassembly `C` and `C++`
  - Webassembly `Rust`
  - Webassembly `Zig`
  - Webassembly `AssemblyScript`
  - Shared memory
  - V8 binary serialization
