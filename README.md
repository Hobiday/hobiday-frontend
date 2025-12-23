# Hobiday
> **스위프(SWYP) 7기 최우수 프로젝트🎉** </br>
> **개발기간: (mvp) 2024.11 ~ 2024.12 / (고도화) 2025.01 ~ 2025.04** </br>

<img src="https://github.com/user-attachments/assets/161e426b-0568-431e-9230-d8d30f3d5d4c" alt="hobiday_cover" width="1200" height="950" />

  <details>
      <summary>1위 상장 보기</summary>
      <img width="801" alt="상장 7기" src="https://github.com/user-attachments/assets/67d4e697-06dc-4d7a-92f2-3e92f3d337cc" />
  </details>

#### 개발인원
- 기획자 1명, 디자이너 1명, 프론트엔드 2명, 백엔드 2명

#### 도메인
> hobiday 홈페이지(운영 종료): http://hobiday.site   </br>
> 본 프로젝트는 **2025년 4월 기준으로 운영이 종료**되었습니다.
  
## ※ 주요 기능
| 구분 | 기능 설명 |
|------|-----------|
| 온보딩 & 프로필 | 닉네임 및 관심 장르 설정, 프로필 편집 |
| 공연/전시 탐색 | 마감 임박 공연, 장르별 목록, 키워드 검색, 추천 검색어 |
| 공연 상세 | 공연 및 시설 정보 확인 |
| 피드 | 이미지 업로드, 해시태그·카테고리 설정, 게시글 작성·수정·삭제, 댓글 및 좋아요 |
| 위시리스트 | 관심 공연 저장 및 장르별 위시리스트 관리 |
| 소셜 | 팔로우·팔로잉, 다른 사용자 피드 탐색 |
| 로그인 | 카카오 OAuth 연동, 토큰 갱신 처리 |


![회원가입](https://github.com/user-attachments/assets/1469a167-ffe6-4a66-8f34-25a1baf200e5)
![홈](https://github.com/user-attachments/assets/8b17efd2-bd97-4582-9df7-0fb5a6c250c7)
![피드](https://github.com/user-attachments/assets/769c8a81-31aa-4a50-9a55-3a7323967da4)
![위시](https://github.com/user-attachments/assets/33872ea2-e4dd-4464-a9df-4e33be0aac0e)
![마이페이지](https://github.com/user-attachments/assets/55a39c51-8df4-4803-bffa-e882361a4fb5)


</br> 
</br> 

## ※ 기술 스택
### 💡 Core
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=Next.js&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"/>

- **Next.js 14 (App Router)**  
  서버 컴포넌트와 라우팅 구조를 활용한 SEO 및 초기 렌더링 성능 중심의 애플리케이션 구성
- **React 18**  
  컴포넌트 기반 UI 설계를 통한 재사용성과 유지보수성 확보
- **TypeScript**  
  도메인 중심 타입 설계로 런타임 오류 최소화 및 코드 안정성 강화

---

### 💡 State & Data
<img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=React%20Query&logoColor=white"/> <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white"/> <img src="https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=Zustand&logoColor=white"/>

- **TanStack Query**  
  서버 상태와 클라이언트 상태 분리, 캐싱·로딩·에러 처리의 일관성 유지
- **Axios**  
  API 통신 로직 공통화 및 인터셉터 기반 인증·에러 처리 구조
- **Zustand**  
  인증 정보와 전역 UI 상태를 단순하고 예측 가능하게 관리

---

### 💡 UI & Interaction
<img src="https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=Tailwind%20CSS&logoColor=white"/> <img src="https://img.shields.io/badge/Framer%20Motion-0055FF?style=for-the-badge&logo=Framer&logoColor=white"/> <img src="https://img.shields.io/badge/Swiper-007AFF?style=for-the-badge&logo=Swiper&logoColor=white"/>

- **Tailwind CSS**  
  유틸리티 기반 스타일링을 통한 빠른 UI 구현과 디자인 일관성 유지
- **Framer Motion**  
  사용자 흐름을 고려한 자연스러운 애니메이션과 인터랙션 구현
- **Swiper**  
  터치 친화적인 슬라이드 UI를 안정적으로 구성

---

### 💡 Testing & Quality
<img src="https://img.shields.io/badge/Storybook-FD5750?style=for-the-badge&logo=Storybook&logoColor=white"/> <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=Jest&logoColor=white"/> <img src="https://img.shields.io/badge/Testing%20Library-E33332?style=for-the-badge&logo=Testing%20Library&logoColor=white"/> <img src="https://img.shields.io/badge/Playwright-000000?style=for-the-badge&logo=Playwright&logoColor=white"/>

- **Storybook**  
  공통 컴포넌트의 독립적 개발과 시각적 검증
- **Jest + Testing Library**  
  핵심 로직 및 컴포넌트 동작에 대한 단위 테스트 구성
- **Playwright**  
  로그인·온보딩 등 주요 사용자 플로우의 E2E 테스트 검증

---

### 💡 Monitoring
<img src="https://img.shields.io/badge/Sentry-341E37?style=for-the-badge&logo=Sentry&logoColor=white"/>

- **Sentry**  
  운영 환경 오류 추적 및 원인 분석을 위한 모니터링 도구


</br> 

## ※ 프로젝트 구조
```
src/
  app/            # 라우트 (App Router)
    apis/           # API 클라이언트/엔드포인트
    hooks/          # React hooks (쿼리/유틸)
    contexts/       # 전역 컨텍스트 (모달, 바텀시트 등)
    stores/         # 전역 변수 설정 (Zustand)
    types/          # 타입 정의
    utils/          # 공용 유틸
    assets/         # 아이콘/이미지/폰트
tests/            # Playwright E2E
.storybook/       # Storybook 설정
```


<details>
<summary><strong>전체 구조 보기</strong></summary>

<br />

```txt
src/
  app/
    layout.tsx
    globals.css
    global-error.tsx
    not-found.tsx
    (main)/
      page.tsx
      feed/
        page.tsx
        upload/
        comments/
        [feedId]/
        search/[performanceId]/
      performance/[performanceId]/
      search/
        page.tsx
        add-info/
      wishlist/
        page.tsx
        _components/
      my/
        page.tsx
        edit/
        followers/
        following/
        setting/
      onboarding/
        page.tsx
        _components/
    login/
      page.tsx
      _component/
    registration-form/
    terms/
      page.tsx
      privacy-policy/
  components/
    commons/       # button, checkbox, chip, text-field, toast, spinner, funnel 등
    layout/        # main/section/step/search layout
    header/
    navigation-bar/
    feed/
    comment/
    search/
    card/
    modal/
    bottom-sheet/
  apis/
    index.ts
    end-points.ts
    performance-api.ts
    feed-api.ts
    user-api.ts
    wishlist-api.ts
    comment-api.ts
  hooks/
    performance/
    feed/
    wishlist/
    user/
    comment/
    queries/
  contexts/
    providers/
    modal.context.tsx
    bottom-sheet.context.tsx
  stores/
  types/
    performance/
      adapter/
      client.ts
      server.ts
    feed/
    wishlist/
    user/
    comment/
  utils/
  assets/
    icons/
    svgr-icons/
    images/
  styles/
    fonts/
    gradients/
public/
  img/
  favicon.ico
tests/
  onboarding.spec.ts
  storage/
```
</details> 

</br> 

## ※ 담당 역할 (Frontend)

#### 임현석
- **온보딩(퍼널 포함)**: 온보딩 단계 전환 구조 설계 및 프로필/카테고리/완료 플로우 구현
- **홈 UI**: 메인 화면 UI 구성 및 탐색 진입 흐름 연결
- **공연 상세 페이지**: 공연/전시 상세 정보 화면 구현 및 탐색 → 상세 전환 연결
- **공통 컴포넌트**: 버튼/폼/토스트/스피너 등 공통 UI 구성 및 재사용 구조 정리
- **검색**: 검색 UI 및 결과 흐름 구성(추천 검색어/키워드 탐색 흐름 포함)
- **위시리스트**: 장르 탭 기반 위시리스트 조회/관리 화면 구현

#### 이가영
- **피드**: 공연·전시 관람 후기를 중심으로 한 피드 목록 및 아이템 구성, 최신/인기 기준의 컨텐츠 흐름 구현
- **피드 댓글**: 관람 후기 피드에 대한 댓글 작성·조회 기능
- **피드 등록**: 관람 후기를 이미지와 함께 기록할 수 있는 피드 작성·수정 플로우 구현
- **로그인 페이지**: 카카오 OAuth 기반 소셜 로그인 진입 UI 및 인증
- **마이페이지**: 프로필 정보, 작성한 관람 후기, 팔로우 관계, 설정 등 개인 기록을 관리하는 마이페이지 전반 구현

