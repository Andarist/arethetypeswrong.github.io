# commander@10.0.1.tgz

```
$ attw commander@10.0.1.tgz


 🎭 Imports of `"commander"` under the `node16` module resolution setting when the importing module is ESM (its extension is `.mts` or `.mjs`, or it has a `.ts` or `.js` extension and is in scope of a `package.json` that contains `"type": "module"`) resolved to CJS types, but ESM implementations.

 🚫 Imports of `"commander/esm.mjs"` under all module resolution settings resolved to JavaScript files, but no types.

 ⚠️ Imports of `"commander/esm.mjs"` resolved to ES modules from a CJS importing module.
   CJS modules in Node will only be able to access this entrypoint with a dynamic import.

┌────────────────────┬───────────────────────────────────┬───────────────────────────────────┐
│                    │ "commander"                       │ "commander/esm.mjs"               │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node10             │ 🟢                                │ 🚫 No types                       │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from CJS)  │ 🟢 (CJS)                          │ 🚫 No types                       │
│                    │                                   │ ⚠️ ESM (dynamic import only)      │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from ESM)  │ 🎭 Masquerading as CJS            │ 🚫 No types                       │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ bundler            │ 🟢                                │ 🚫 No types                       │
└────────────────────┴───────────────────────────────────┴───────────────────────────────────┘


```

Exit code: 1