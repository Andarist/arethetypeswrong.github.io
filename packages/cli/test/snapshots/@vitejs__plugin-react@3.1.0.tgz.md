# @vitejs__plugin-react@3.1.0.tgz

```
$ attw /Users/andrew/Developer/arethetypeswrong.github.io/packages/core/test/fixtures/@vitejs__plugin-react@3.1.0.tgz


 🎭 Imports of the package under the `node16` module resolution setting when the importing module is ESM (its extension is `.mts` or `.mjs`, or it has a `.ts` or `.js` extension and is in scope of a `package.json` that contains `"type": "module"`) resolved to CJS types, but ESM implementations.

┌────────────────────┬───────────────────────────────────┐
│                    │ "@vitejs/plugin-react"            │
├────────────────────┼───────────────────────────────────┤
│ node10             │ 🟢                                │
├────────────────────┼───────────────────────────────────┤
│ node16 (from CJS)  │ 🟢 (CJS)                          │
├────────────────────┼───────────────────────────────────┤
│ node16 (from ESM)  │ 🎭 Masquerading as CJS            │
├────────────────────┼───────────────────────────────────┤
│ bundler            │ 🟢                                │
└────────────────────┴───────────────────────────────────┘


```

Exit code: 1