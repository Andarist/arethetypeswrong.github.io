# node-html-parser@6.1.5.tgz

```
$ attw node-html-parser@6.1.5.tgz


 🤨 The CJS module resolved at the package under contains a simulated `export default` with an `__esModule` marker, but no top-level `module.exports`.
   Node does not respect the `__esModule` marker, so accessing the intended default export will require a `.default` property access in Node from an ES module.

┌────────────────────┬───────────────────────────────────┐
│                    │ "node-html-parser"                │
├────────────────────┼───────────────────────────────────┤
│ node10             │ 🟢                                │
├────────────────────┼───────────────────────────────────┤
│ node16 (from CJS)  │ 🟢 (CJS)                          │
├────────────────────┼───────────────────────────────────┤
│ node16 (from ESM)  │ 🤨 CJS default export             │
├────────────────────┼───────────────────────────────────┤
│ bundler            │ 🟢                                │
└────────────────────┴───────────────────────────────────┘


```

Exit code: 1