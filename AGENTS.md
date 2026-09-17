# AGENTS.md - Taskly / ai-cli

## Declared Intent (from README.md)
Taskly is a simple React Native app for managing daily tasks.
Core features: create, complete, edit, and delete daily tasks.

Declared setup:
```bash
git clone https://github.com/example/taskly.git
cd taskly
npm install
# prerequisiti: Node LTS, Watchman (macOS), Android Studio / Xcode
```

Declared run:
```bash
npx react-native start
npx react-native run-android
npx react-native run-ios
```

## Actual Repo State (ai-cli/)
Static web scaffold, currently empty. No React Native code present.
Do not assume `npm install` / `npx react-native run-android` work here.

```
ai-cli/
├── AGENTS.md
├── README.md
├── index.html (0 lines, empty)
├── css/style.css (empty)
├── js/app.js (empty)
├── img/ (empty)
└── .git/
```

## Agent Rules
1. Source of truth for intent: `README.md`. Source of truth for code: actual files.
2. If task requires React Native Taskly features, flag the mismatch before scaffolding.
3. For web tasks: use `index.html` + `css/style.css` + `js/app.js`, vanilla only, no build step unless user asks.
4. Keep changes minimal and consistent with existing structure.
5. Contributing: PRs welcome, open issue first for major changes, update tests as appropriate.
6. License: MIT - https://choosealicense.com/licenses/mit/
