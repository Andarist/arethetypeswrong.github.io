# vue@3.3.4.tgz

```
$ attw vue@3.3.4.tgz


 🎭 Imports of multiple entrypoints under the `node16` module resolution setting when the importing module is ESM (its extension is `.mts` or `.mjs`, or it has a `.ts` or `.js` extension and is in scope of a `package.json` that contains `"type": "module"`) resolved to CJS types, but ESM implementations.

 💀 Imports of `"vue/jsx-dev-runtime"` under the `node10` module resolution setting failed to resolve.

 🚭 The implementation resolved at multiple entrypoints uses ESM syntax, but the detected module kind is CJS.
   This will be an error in Node (and potentially other runtimes and bundlers).
   The module kind was decided based on the nearest package.json’s lack of a `"type": "module"` field.
 🚭 The implementation resolved at multiple entrypoints uses ESM syntax, but the detected module kind is CJS.
   This will be an error in Node (and potentially other runtimes and bundlers).
   The module kind was decided based on the nearest package.json’s lack of a `"type": "module"` field.

 ❓ Wildcards cannot yet be analyzed by this tool.

┌────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┐
│                    │ "vue"                             │ "vue/server-renderer"             │ "vue/compiler-sfc"                │ "vue/jsx-runtime"                 │ "vue/jsx-dev-runtime"             │ "vue/jsx"                         │ "vue/dist/*"                      │ "vue/package.json"                │ "vue/macros"                      │ "vue/macros-global"               │ "vue/ref-macros"                  │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node10             │ 🟢                                │ 🟢                                │ 🟢                                │ 🟢                                │ 💀 Failed to resolve              │ 🟢                                │ ❓ Unable to check                │ 🟢 (JSON)                         │ 🟢                                │ 🟢                                │ 🟢                                │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from CJS)  │ 🟢 (CJS)                          │ 🟢 (CJS)                          │ 🟢 (CJS)                          │ 🟢 (CJS)                          │ 🟢 (CJS)                          │ 🚭 Unexpected ESM syntax          │ ❓ Unable to check                │ 🟢 (JSON)                         │ 🚭 Unexpected ESM syntax          │ 🚭 Unexpected ESM syntax          │ 🚭 Unexpected ESM syntax          │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from ESM)  │ 🟢 (ESM)                          │ 🟢 (ESM)                          │ 🟢 (ESM)                          │ 🎭 Masquerading as CJS            │ 🎭 Masquerading as CJS            │ 🚭 Unexpected ESM syntax          │ ❓ Unable to check                │ 🟢 (JSON)                         │ 🚭 Unexpected ESM syntax          │ 🚭 Unexpected ESM syntax          │ 🚭 Unexpected ESM syntax          │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ bundler            │ 🟢                                │ 🟢   

```

Exit code: 1