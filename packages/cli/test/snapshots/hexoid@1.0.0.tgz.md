# hexoid@1.0.0.tgz

```
$ attw hexoid@1.0.0.tgz


 ❗️ The types resolved at the package use `export default` where the implementation appears to use `module.exports =`.
   Node treats a default import of these constructs from an ES module differently, so these types will make TypeScript under the `node16` resolution mode think an extra `.default` property access is required, but that will likely fail at runtime in Node.
   These types should use `export =` instead of `export default`.

┌────────────────────┬───────────────────────────────────┐
│                    │ "hexoid"                          │
├────────────────────┼───────────────────────────────────┤
│ node10             │ 🟢                                │
├────────────────────┼───────────────────────────────────┤
│ node16 (from CJS)  │ 🟢 (CJS)                          │
├────────────────────┼───────────────────────────────────┤
│ node16 (from ESM)  │ ❗️ Incorrect default export      │
├────────────────────┼───────────────────────────────────┤
│ bundler            │ 🟢                                │
└────────────────────┴───────────────────────────────────┘


```

Exit code: 1