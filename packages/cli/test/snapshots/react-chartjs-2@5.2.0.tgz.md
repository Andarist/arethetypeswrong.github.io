# react-chartjs-2@5.2.0.tgz

```
$ attw react-chartjs-2@5.2.0.tgz


👺 Import resolved to an ESM type declaration file, but a CommonJS JavaScript file.

⚠️ A require call resolved to an ESM JavaScript file, which is an error in Node and some bundlers. CommonJS consumers will need to use a dynamic import.


┌────────────────────┬───────────────────────────────────┐
│                    │ "react-chartjs-2"                 │
├────────────────────┼───────────────────────────────────┤
│ node10             │ 🟢                                │
├────────────────────┼───────────────────────────────────┤
│ node16 (from CJS)  │ 👺 Masquerading as ESM            │
│                    │ ⚠️ ESM (dynamic import only)      │
├────────────────────┼───────────────────────────────────┤
│ node16 (from ESM)  │ 🟢 (ESM)                          │
├────────────────────┼───────────────────────────────────┤
│ bundler            │ 🟢                                │
└────────────────────┴───────────────────────────────────┘


```

Exit code: 1