## 김영훈 (Younghoon Kim)

Frontend Engineer | React Router / TanStack Query Contributor

Building React systems that preserve user context, keep data consistent, and make failures recoverable.

3 years of experience across EA Korea, NHN Injeinc, and PandoraTV.

[![Blog](https://img.shields.io/badge/Blog-000000?style=flat&logo=vercel&logoColor=white)](https://www.joseph0926.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joseph0926)

---

### Open Source

<details>
  <summary>
    <strong>11 merged PRs</strong> across React Router, TanStack Query, React Hook Form, TanStack Router, and Redux Toolkit
  </summary>
  <hr />
  <ul>
    <li>
      <strong>React Router</strong> (5 PRs)
      <ul>
        <li>Fix middleware <code>skipRevalidation</code> missing — <a href="https://github.com/remix-run/react-router/pull/14286">#14286</a></li>
        <li>Handle sessionStorage failure in restricted environments — <a href="https://github.com/remix-run/react-router/pull/14335">#14335</a></li>
        <li>Fix <code>fetcher.submit</code> JSON bug + SSR regression test — <a href="https://github.com/remix-run/react-router/pull/14534">#14534</a></li>
        <li>Fix <code>generatePath</code> suffix parameter regression — <a href="https://github.com/remix-run/react-router/pull/14269">#14269</a></li>
        <li>Add <code>crossOrigin</code> attribute to <code>&lt;Links /&gt;</code> for CDN CORS — <a href="https://github.com/remix-run/react-router/pull/14687">#14687</a></li>
      </ul>
    </li>
    <li>
      <strong>TanStack Query</strong> (3 PRs)
      <ul>
        <li>Optimize <code>useQueries</code> O(N²) → O(N) (~55% fewer function calls) — <a href="https://github.com/TanStack/query/pull/8641">#8641</a></li>
        <li>Fix persist + memoized combine bug — <a href="https://github.com/TanStack/query/pull/9592">#9592</a></li>
        <li>Fix CI timeout (Nx Cloud config) — <a href="https://github.com/TanStack/query/pull/9623">#9623</a></li>
      </ul>
    </li>
    <li>
      <strong>React Hook Form</strong> (1 PR)
      <ul>
        <li>Fix <code>useController</code> type regression + type tests — <a href="https://github.com/react-hook-form/react-hook-form/pull/13150">#13150</a></li>
      </ul>
    </li>
    <li>
      <strong>TanStack Router</strong> (1 PR)
      <ul>
        <li>Fix <code>params.parse</code> notFound() 500 → 404 — <a href="https://github.com/TanStack/router/pull/5864">#5864</a></li>
      </ul>
    </li>
    <li>
      <strong>Redux Toolkit</strong> (1 PR)
      <ul>
        <li>Prevent <code>onQueryStarted</code> from firing at end-of-list in RTK Query infinite queries + regression tests — <a href="https://github.com/reduxjs/redux-toolkit/pull/5182">#5182</a></li>
      </ul>
    </li>
  </ul>
</details>

---

### Featured Project

**[FirstTx](https://github.com/joseph0926/firsttx)** — Five npm packages for restoring CSR screen state on revisit and rolling back failed updates.

[Docs](https://www.firsttx.store) · [Playground](https://firsttx-playground.vercel.app) · [DevTools](https://chromewebstore.google.com/detail/firsttx-devtools/onpdifkipmmkajdhodmpphmlpbnopkdd)

---

### Tech Blog

- [I upgraded DOMPurify, so why did I end up fixing happy-dom?](https://www.joseph0926.com/post/2026-07-14-upgraded-dompurify-why-fix-happy-dom)
- [Why I separated data processing and UI responsibilities from React Query custom hooks](https://www.joseph0926.com/post/2026-07-21-react-query-custom-hook-responsibility-boundaries)
- [useRef holds values not needed for rendering, so why should you not read it during render?](https://www.joseph0926.com/post/2026-03-01-why-shouldnt-you-read-useref-during-render)
- [Why replacing window.confirm with a React Dialog is not just a UI swap](https://www.joseph0926.com/post/2026-07-09-window-confirm-react-dialog)

**Stack**: React, TypeScript, Next.js, React Router, TanStack Query, Zustand, Zod, Playwright, Vitest, Vite
