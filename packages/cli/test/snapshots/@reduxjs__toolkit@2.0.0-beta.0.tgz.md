# @reduxjs__toolkit@2.0.0-beta.0.tgz

```
$ attw @reduxjs__toolkit@2.0.0-beta.0.tgz


🎭 Import resolved to a CommonJS type declaration file, but an ESM JavaScript file.

🥴 Import found in a type declaration file failed to resolve. Either this indicates that runtime resolution errors will occur, or (more likely) the types misrepresent the contents of the JavaScript files.


┌────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┐
│                    │ "@reduxjs/toolkit/package.json"   │ "@reduxjs/toolkit"                │ "@reduxjs/toolkit/react"          │ "@reduxjs/toolkit/query"          │ "@reduxjs/toolkit/query/react"    │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node10             │ 🟢 (JSON)                         │ 🟢                                │ 🟢                                │ 🟢                                │ 🟢                                │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from CJS)  │ 🟢 (JSON)                         │ 🟢 (CJS)                          │ 🥴 Internal resolution error      │ 🟢 (CJS)                          │ 🥴 Internal resolution error      │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from ESM)  │ 🟢 (JSON)                         │ 🎭 Masquerading as CJS            │ 🎭 Masquerading as CJS            │ 🎭 Masquerading as CJS            │ 🎭 Masquerading as CJS            │
│                    │                                   │                                   │ 🥴 Internal resolution error      │                                   │ 🥴 Internal resolution error      │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ bundler            │ 🟢 (JSON)                         │ 🟢                                │ 🥴 Internal resolution error      │ 🟢                                │ 🥴 Internal resolution error      │
└────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┘


```

Exit code: 1