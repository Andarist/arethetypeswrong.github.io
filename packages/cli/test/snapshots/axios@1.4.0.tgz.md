# axios@1.4.0.tgz

```
$ attw axios@1.4.0.tgz


❓ Wildcard subpaths cannot yet be analyzed by this tool. https://github.com/arethetypeswrong/arethetypeswrong.github.io/issues/40

💀 Import failed to resolve to type declarations or JavaScript files. https://github.com/arethetypeswrong/arethetypeswrong.github.io/blob/main/docs/problems/NoResolution.md

❌ Import resolved to JavaScript files, but no type declarations were found. https://github.com/arethetypeswrong/arethetypeswrong.github.io/blob/main/docs/problems/UntypedResolution.md

⚠️ A require call resolved to an ESM JavaScript file, which is an error in Node and some bundlers. CommonJS consumers will need to use a dynamic import. https://github.com/arethetypeswrong/arethetypeswrong.github.io/blob/main/docs/problems/CJSResolvesToESM.md


┌────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┬───────────────────────────────────┐
│                    │ "axios"                           │ "axios/unsafe/*"                  │ "axios/unsafe/core/settle.js"     │ "axios/unsafe/core/buildFullPath… │ "axios/unsafe/helpers/isAbsolute… │ "axios/unsafe/helpers/buildURL.j… │ "axios/unsafe/helpers/combineURL… │ "axios/unsafe/adapters/http.js"   │ "axios/unsafe/adapters/xhr.js"    │ "axios/unsafe/utils.js"           │ "axios/package.json"              │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node10             │ 🟢                                │ ❓ Unable to check                │ 💀 Resolution failed              │ 💀 Resolution failed              │ 💀 Resolution failed              │ 💀 Resolution failed              │ 💀 Resolution failed              │ 💀 Resolution failed              │ 💀 Resolution failed              │ 💀 Resolution failed              │ 🟢 (JSON)                         │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from CJS)  │ 🟢 (CJS)                          │ ❓ Unable to check                │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ 🟢 (JSON)                         │
│                    │                                   │                                   │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │ ⚠️ ESM (dynamic import only)      │                                   │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ node16 (from ESM)  │ 🟢 (ESM)                          │ ❓ Unable to check                │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ 🟢 (JSON)                         │
├────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┼───────────────────────────────────┤
│ bundler            │ 🟢                                │ ❓ Unable to check                │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ ❌ No types                       │ 🟢 (JSON)                         │
└────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┴───────────────────────────────────┘


```

Exit code: 1