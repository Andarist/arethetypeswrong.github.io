# astring@1.8.6.tgz

```
$ attw astring@1.8.6.tgz


🎭 Import resolved to a CommonJS type declaration file, but an ESM JavaScript file. https://github.com/arethetypeswrong/arethetypeswrong.github.io/blob/main/docs/problems/FalseCJS.md


┌────────────────────┬───────────────────────────────────┐
│                    │ "astring"                         │
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