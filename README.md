# 안녕하세요, 프론트엔드 개발자 김영훈입니다

프론트엔드 엔지니어 | React Query 컨트리뷰터

## 경력

- EA Korea (Freelancer): 2025.03 ~
- NHN Injeinc: 2024.05 ~ 2025.03
- Pandora.TV: 2023.07 ~ 2024.05


## 오픈소스 기여

### React Query

**성능 최적화** | [PR #8641](https://github.com/TanStack/query/pull/8641) → [v5.66.3 릴리스](https://github.com/TanStack/query/releases/tag/v5.66.3)

- 문제: useQueries O(N²) 복잡도로 100개 쿼리 시 약 10,000번 연산 발생
- 해결: observerMatches 캐싱 전략 도입, 처리 시간 55% 단축
- 검증: 메인테이너와 협업, 10,000개 쿼리 극한 테스트

**useQueries combine 함수 버그 수정** | [PR #9592](https://github.com/TanStack/query/pull/9592) → [v5.85.9 릴리스](https://github.com/TanStack/query/releases/tag/v5.85.9)

- 문제: StoragePersister 사용 시 combine 함수가 호출되지 않는 이슈
- 해결: shallowEqualObjects 비교로 메타데이터 변경 감지 개선
- 검증: 메인테이너 리뷰 반영, 테스트 케이스 추가 및 최적화
- 관련 글: [Blog](https://www.joseph0926.com/post/2025-09-02-react-query-usequeries-combine-pr-merge)

**SSR Hydration 개선** | [PR #9572](https://github.com/TanStack/query/pull/9572) (Review 진행중)

- Next.js App Router hydration mismatch 근본 원인 분석 및 해결
- getServerSnapshot 구현으로 서버-클라이언트 상태 일치

**기타**

- React Query: Suspense 처리 버그 수정 ([PR #9584](https://github.com/TanStack/query/pull/9584)), combine 함수 캐시 버그 수정 ([PR #**9618**](https://github.com/TanStack/query/pull/9618)), hydration 타이밍 이슈 수정 ([PR #9617](https://github.com/TanStack/query/pull/9617))
- React Router: unstable_middleware 버그 수정 ([PR #14286](https://github.com/remix-run/react-router/pull/14286)), relative() 헬퍼 절대경로 버그 수정 ([PR #14156](https://github.com/remix-run/react-router/pull/14156))
- SWR: useSWRInfinite 사용시 전역 mutate로 데이터 갱신이 안되는 현상 수정 ([PR #4167](https://github.com/vercel/swr/pull/4167))

## 주요 프로젝트

- Blog: [개인 블로그](https://github.com/joseph0926/blog)

## 기술 스택

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=flat&logo=tailwindcss&logoColor=white)

## 연락처

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:joseph0926.dev@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joseph0926)
[![Blog | Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://www.joseph0926.com)

## 최근 블로그 글

- [React Query 내부 동작 원리 - 선택적 리렌더링 최적화](https://www.joseph0926.com/post/2025-08-29-react-query-1)
- [왜 Suspense가 도입되었을까?](https://www.joseph0926.com/post/2025-07-13-learn-react-02-suspense-)
- [React Query Issue 해결하기](https://www.joseph0926.com/post/2025-09-02-react-query-usequeries-combine-pr-merge)
- [React는 예측 가능성을 높여줍니다](https://www.joseph0926.com/post/2025-06-22-react-react-component)
- [Next.js Cache 캐싱의 두 얼굴: 빠른 속도와 정확한 데이터 사이에서](https://www.joseph0926.com/post/2025-08-24-nextjs-cache)

## GitHub 통계

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=joseph0926&show_icons=true&theme=radical)

