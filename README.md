## 김영훈 (Younghoon Kim)

Frontend Engineer | React Router / TanStack Query Contributor

3 years of experience across EA Korea, NHN Injeinc, and PandoraTV.

[![Blog](https://img.shields.io/badge/Blog-000000?style=flat&logo=rss&logoColor=white)](https://www.joseph0926.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joseph0926)

---

### Open Source

**11 merged PRs** across React Router, TanStack Query, React Hook Form, TanStack Router, and Redux Toolkit

**React Router** (5 PRs)

- Fix missing `skipRevalidation` in middleware — [#14286](https://github.com/remix-run/react-router/pull/14286)
- Handle sessionStorage failure in restricted environments — [#14335](https://github.com/remix-run/react-router/pull/14335)
- Fix `fetcher.submit` misdetecting plain objects as HTML elements + browser regression test — [#14534](https://github.com/remix-run/react-router/pull/14534)
- Fix `generatePath` suffix parameter regression — [#14269](https://github.com/remix-run/react-router/pull/14269)
- Add `crossOrigin` attribute to `<Links />` for CDN CORS — [#14687](https://github.com/remix-run/react-router/pull/14687)

**TanStack Query** (3 PRs)

- Optimize `useQueries` O(N²) → O(N) (~55% fewer function calls) — [#8641](https://github.com/TanStack/query/pull/8641)
- Fix persist + memoized combine bug — [#9592](https://github.com/TanStack/query/pull/9592)
- Fix CI timeout (Nx Cloud config) — [#9623](https://github.com/TanStack/query/pull/9623)

**React Hook Form** (1 PR)

- Fix `useController` type regression + type tests — [#13150](https://github.com/react-hook-form/react-hook-form/pull/13150)

**TanStack Router** (1 PR)

- Fix `params.parse` notFound() 500 → 404 — [#5864](https://github.com/TanStack/router/pull/5864)

**Redux Toolkit** (1 PR)

- Prevent `onQueryStarted` from firing at end-of-list in RTK Query infinite queries + regression tests — [#5182](https://github.com/reduxjs/redux-toolkit/pull/5182)

---

### Featured Project

**[FirstTx](https://github.com/joseph0926/firsttx)** — Restores CSR screen state on revisit and rolls back failed optimistic updates, shipped as 5 npm packages.

[Docs](https://www.firsttx.store) | [Playground](https://firsttx-playground.vercel.app) | [DevTools](https://chromewebstore.google.com/detail/firsttx-devtools/onpdifkipmmkajdhodmpphmlpbnopkdd)

---

### Tech Blog

- [I upgraded DOMPurify, so why did I end up fixing happy-dom?](https://www.joseph0926.com/post/2026-07-14-upgraded-dompurify-why-fix-happy-dom)
- [Why I separated data processing and UI responsibilities from React Query custom hooks](https://www.joseph0926.com/post/2026-07-21-react-query-custom-hook-responsibility-boundaries)
- [React Query useQueries combine function bug fix: From PR to Merge](https://www.joseph0926.com/post/2025-09-02-react-query-usequeries-combine-pr-merge)
- [What makes a test failure trustworthy?](https://www.joseph0926.com/post/2026-03-27-what-makes-a-test-failure-trustworthy)
