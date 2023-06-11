# axios@1.4.0.tgz

```
$ attw axios@1.4.0.tgz


 ❓ Wildcards cannot yet be analyzed by this tool.

 💀 Imports of multiple entrypoints under the `node10` module resolution setting failed to resolve.

 🚫 Imports of multiple entrypoints under the `node16` module resolution setting when the importing module is CJS (its extension is `.cts` or `.cjs`, or it has a `.ts` or `.js` extension and is in scope of a `package.json` that does not contain `"type": "module"`) resolved to JavaScript files, but no types.
 🚫 Imports of multiple entrypoints under the `node16` module resolution setting when the importing module is ESM (its extension is `.mts` or `.mjs`, or it has a `.ts` or `.js` extension and is in scope of a `package.json` that contains `"type": "module"`) resolved to JavaScript files, but no types.
 🚫 Imports of multiple entrypoints under the `bundler` module resolution setting resolved to JavaScript files, but no types.

 ⚠️ Imports of multiple entrypoints resolved to ES modules from a CJS importing module.
   CJS modules in Node will only be able to access this entrypoint with a dynamic import.

┌────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┐
│                    │ "axios"                           │ "axios/unsafe/*"                  │ "axios/unsafe/core/settle.js"     │ "axios/unsafe/core/buildFullPath… │ "axios/unsafe/helpers/isAbsolute… │ "axios/unsafe/helpers/buildURL.j… │ "axios/unsafe/helpers/combineURL… │ "axios/unsafe/adapters/http.js"   │ "axios/unsafe/adapters/xhr.js"    │ "axios/unsafe/utils.js"           │ "axios/package.json"              │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node10             │ 🟢                                │ ❓ Unable to check                │ 💀 Failed to resolve              │ 💀 Failed to resolve              │ 💀 Failed to resolve              │ 💀 Failed to resolve              │ 💀 Failed to resolve              │ 💀 Failed to resolve              │ 💀 Failed to resolve              │ 💀 Failed to resolve              │ 🟢 (JSON)                         │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from CJS)  │ 🟢 (CJS)                          │ ❓ Unable to check                │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🟢 (JSON)                         │
│                    │                                   │                                   │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │                                   │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from ESM)  │ 🟢 (ESM)                          │ ❓ Unable to check                │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🚫 No types                       │ 🟢 (JSON)                         │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────�

```

Exit code: 1