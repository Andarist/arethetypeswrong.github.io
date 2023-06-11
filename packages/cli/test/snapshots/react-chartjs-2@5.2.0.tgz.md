# react-chartjs-2@5.2.0.tgz

```
$ attw react-chartjs-2@5.2.0.tgz


 👺 Imports of the package under the `node16` module resolution setting when the importing module is CJS (its extension is `.cts` or `.cjs`, or it has a `.ts` or `.js` extension and is in scope of a `package.json` that does not contain `"type": "module"`) resolved to ESM types, but CJS implementations.

 ⚠️ Imports of the package resolved to ES modules from a CJS importing module.
   CJS modules in Node will only be able to access this entrypoint with a dynamic import.

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