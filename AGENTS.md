# AGENTS.md

This file provides guidance to coding agents when working with code in this repository.

Teaching material from a front-end course for the 2023 intern cohort at TÜBİTAK BİLGEM
YTE: plain JavaScript examples, then React and the Next.js 13.4 App Router. React 18, TypeScript,
MUI 5, npm (`package-lock.json`). The repo is archived on GitHub.

## Commands

```bash
npm run dev      # http://localhost:3000
npm run build
npm run lint     # next lint
```

No tests.

## Layout

- `non-next examples/` (the folder name has a space): plain HTML, CSS and JS exercises.
- `src/app/page.tsx` renders the React examples (`FormExample`, `ContextExample`,
  `ChildrenExample`, `UseEffectExample`) on one page; they live as flat files in `src/app/`.
- Route folders each demonstrate one App Router feature: `apple` (layout, `[slug]`), `banana`,
  `loadingExample` (`loading.tsx`), `errorExample` (`error.tsx`), `mui`.
- Commit history maps to the course days (`2. gun`, `3. gun`, ...). Commit messages are Turkish.

## Imports

Import paths must match file name casing exactly (`./ThemeContext`, not `./themeContext`). macOS
and Windows ignore case, so a mismatch only fails on Linux and in Linux CI.

## Notes

- Keep examples at the level they were taught; don't add libraries or abstractions.
- Every dependency, including `@types/*`, `eslint` and `typescript`, sits under `dependencies`.
