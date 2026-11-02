# YTE Internship 2023

Examples from the front-end lectures I gave to the 2023 intern cohort at TÜBİTAK BİLGEM YTE. The course went from plain JavaScript to React and the Next.js App Router, and the commits follow the days of the course.

## What's inside

**Plain JavaScript** (`non-next examples/`), the first part of the course:

- `exercise-1`: DOM events and `fetch` with promise chains
- `exercise-2`: loops, arrays and `fetch` with `async`/`await`

**React** (`src/app/`), shown together on the home page:

- `FormExample`, `FormElement`: forms and controlled inputs
- `ContextExample`, `ThemeContext`: sharing state with Context
- `ChildrenExample`: composition with `children`
- `UseEffectExample`: side effects with `useEffect`

**Next.js App Router** (routes):

| Route            | Topic                                                   |
| ---------------- | ------------------------------------------------------- |
| `/apple`         | Nested layout and a dynamic `[slug]` route              |
| `/banana`        | A plain second route, for navigating between pages      |
| `/loadingExample`| An async Server Component with `loading.tsx`            |
| `/errorExample`  | Error boundaries with `error.tsx`                       |
| `/mui`           | Using Material UI in a Next.js app                      |

## Running

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000). The plain JavaScript examples open directly in a browser.

Built with Next.js 13.4, React 18, TypeScript and MUI 5.
