# 김영훈 | Frontend Engineer

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:joseph0926.dev@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joseph0926)
[![Blog](https://img.shields.io/badge/Blog-000000?style=flat&logo=vercel&logoColor=white)](https://www.joseph0926.com)

---

## 프로젝트

### [FirstTx](https://github.com/joseph0926/firsttx) — CSR 재방문 최적화 라이브러리
**CSR 앱의 재방문 빈 화면을 제거하고, IndexedDB ↔ React 동기화를 단순화합니다.**

- **Prepaint**: IndexedDB 스냅샷을 부트 스크립트(<2 KB)로 즉시 복원 → 재방문 빈 화면 **≈ 0 ms**
- **Local-First**: `useSyncExternalStore` + 메모리 캐시로 비동기 IndexedDB를 React와 동기 연결
- **Tx**: ViewTransition 통합 트랜잭션, 실패 시 자동 롤백

📦 **NPM**: [`@firsttx/prepaint`](https://www.npmjs.com/package/@firsttx/prepaint) / [`@firsttx/local-first`](https://www.npmjs.com/package/@firsttx/local-first) / [`@firsttx/tx`](https://www.npmjs.com/package/@firsttx/tx)  
🎮 **Demo**: [firsttx-playground.vercel.app](https://firsttx-playground.vercel.app/)  
📝 **블로그**: [기획 배경](https://www.joseph0926.com/post/2025-10-11-csr-ssr) / [Prepaint 구현](https://www.joseph0926.com/post/2025-10-12-csr-prepaint) / [Local-First 원리](https://www.joseph0926.com/post/2025-10-12-local-first-usesyncexternalstore-indexeddb-react)

---

## 오픈소스

### [React Query](https://github.com/TanStack/query)
- **55% 성능 개선**: 500개 동시 쿼리 시나리오에서 캐싱 최적화로 `findMatchingObservers` 호출 감소  
  → [PR #8641](https://github.com/TanStack/query/pull/8641) · [v5.66.3 릴리스](https://github.com/TanStack/query/releases/tag/v5.66.3)
- Suspense 모드 무한 리렌더링 방지  
  → [PR #9623](https://github.com/TanStack/query/pull/9623) · [v4.40.2 릴리스](https://github.com/TanStack/query/releases/tag/v4.40.2)
- persist 복원 후 combine 함수 실행 누락 수정  
  → [PR #9592](https://github.com/TanStack/query/pull/9592) · [v5.85.9 릴리스](https://github.com/TanStack/query/releases/tag/v5.85.9)

### [React Router](https://github.com/remix-run/react-router)
- `skipRevalidation` 플래그 전달 누락 버그 수정  
  → [PR #14286](https://github.com/remix-run/react-router/pull/14286) · [v7.9.0 릴리스](https://github.com/remix-run/react-router/releases/tag/react-router%407.9.0)
- 브라우저 스토리지 제한 환경 대응  
  → [PR #14335](https://github.com/remix-run/react-router/pull/14335) · [v7.9.2 릴리스](https://github.com/remix-run/react-router/releases/tag/react-router%407.9.2)

---

## 경력

- **EA Korea** · Frontend Engineer (계약직) · 2025.03 ~ 현재
- **NHN Injeinc** · Frontend Engineer (정규직) · 2024.05 ~ 2025.03
- **판도라TV** · Frontend Engineer (정규직) · 2023.07 ~ 2024.05

---

## 블로그 글

- [React Query 내부 동작 원리 - 선택적 리렌더링 최적화](https://www.joseph0926.com/post/2025-08-29-react-query-1)
- [React Query Issue 해결하기](https://www.joseph0926.com/post/2025-09-02-react-query-usequeries-combine-pr-merge)
- [왜 Suspense가 도입되었을까?](https://www.joseph0926.com/post/2025-07-13-learn-react-02-suspense-)
- [Next.js Cache: 빠른 속도와 정확한 데이터 사이에서](https://www.joseph0926.com/post/2025-08-24-nextjs-cache)

더 많은 글: [joseph0926.com](https://www.joseph0926.com)

---

## GitHub 통계

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=joseph0926&show_icons=true&theme=radical&hide_border=true)
