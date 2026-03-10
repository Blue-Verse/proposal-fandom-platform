# React Native 기반 글로벌 팬덤 플랫폼 개발 — 제안 분석 로그

> 생성일: 2026-03-11
> 공고 URL: https://www.wishket.com/project/153378/

## 1. 공고 파싱 결과

```yaml
job:
  title: "React Native 기반 팬덤 플랫폼 개발"
  category: "개발 / 웹·안드로이드·iOS / 커뮤니티·SNS, 게임·리워드"
  budget_range: "30,000,000원"
  duration: "90일"
  tech_stack:
    - React Native
    - Expo
    - Firebase (Firestore, Auth, Functions)
    - Health API (걸음 수)
    - YouTube IFrame API
    - Google AdMob
    - IAP (인앱 결제)
  description: "차세대 글로벌 팬덤 플랫폼 MVP 구축 — 시네마틱 & Non-Verbal UI"
  requirements:
    - Galaxy 3D 뷰 (아티스트별 행성 렌더링, FPI 연동)
    - POP 토큰 이코노미 (걷기 + YouTube 스밍 → POP 획득)
    - 이클립스 이벤트 (팬덤 단결 방어전)
    - 크라우드 펀딩 (자동 환불)
    - 현상금 Q&A 게시판
    - 진화형 디지털 ID 카드
    - AdMob 리워드 광고 + IAP 구독
    - 마케팅용 읽기 전용 모바일 웹
  client_questions:
    - "유사한 프로젝트를 수행한 경험이 있다면 무엇입니까?"
  deadline: "2026-03-23"
  job_post_url: "https://www.wishket.com/project/153378/"
  urls: []
  images: []
```

## 2. URL/이미지 분석

참고 URL/이미지 없음. 공고 본문에 별도 레퍼런스 링크나 이미지 첨부 없음.

클라이언트가 보유한 자료 (미팅 시 제공 예정):
- 상세 PRD (10개 이상 섹션)
- React/Tailwind 기반 디자인 코드
- 3D 개발 소스

## 3. 실현 가능성 분석 (내부용)

### 프로젝트 유형
- **모바일 앱 (React Native)**: 조건부 가능, +20% 버퍼
- **복잡한 실시간 시스템**: 주의, +25% 버퍼
- **종합**: 모바일 + 실시간 + 3D + 센서 → **버퍼 +25% 적용**

### 기본 공수 (AI 보조 없이)

| 작업 영역 | M/D |
|-----------|-----|
| 기획/설계 (PRD 검토·보완) | 8 |
| FE — Galaxy 3D + 이클립스 | 28 |
| FE — Home (퀘스트, 만보기, YouTube) | 19 |
| FE — Archive + K-Inside | 16 |
| FE — My Page + 인증 + 마케팅웹 + 알림 | 27 |
| BE — POP 경제 + 이클립스 | 14 |
| BE — 펀딩 + YouTube + Health | 18 |
| BE — AdMob + IAP + Auth + 알림 | 16 |
| QA/배포 | 15 |
| **합계** | **161 M/D** |

### AI 절감 적용
- 기본 공수: 161 M/D
- AI 절감률 (50%): → 80.5 M/D
- 모바일+실시간 버퍼 (+25%): → **~101 M/D**
- 달력 일수 (×1.4 주말 보정): → **~141일**

### 클라이언트 예상 vs 산정
- 클라이언트 예상: 90일
- 내부 산정: ~141일
- 차이: +51일 (57% 초과)
- **판정: 20% 초과 → 새 기간 제안 필요**

### 최종 결정
- **옵션 B 채택**: 90일 MVP + 30일 확장 = 120일
- Phase 1 (90일): Galaxy, Home, My Page 핵심 3탭 MVP
- Phase 2 (30일): Archive, K-Inside, 수익화, 마케팅 웹

### 참고: 클라이언트 유리 요인
- 상세 PRD 존재 → 기획 공수 대폭 절감
- React/Tailwind 디자인 코드 → RN 변환만 필요
- 3D 소스 보유 → 3D 개발 시간 단축
- 내부 PM + 디자이너 → 커뮤니케이션 효율

## 4. 포트폴리오 매칭

| 프로젝트 | 매칭 점수 | 주요 매칭 근거 |
|---------|----------|--------------|
| **DayStarter** | ★★★★★ | 센서 기반 활동 트래킹, 토큰 이코노미, 게이미피케이션, AdMob |
| **Fortune App** | ★★★★☆ | Firebase 풀스택, 포인트/리워드, 광고 수익화, 3개월 딜리버리 |
| **Pilates App** | ★★★★☆ | React Native 직접 경험, 커뮤니티, 멀티플랫폼, 빠른 납기 |

## 5. 최종 제안 요약

- **지원 금액**: 27,000,000원 (VAT 별도)
- **지원 기간**: 120일 (Phase 1 MVP 90일 + Phase 2 확장 30일)
- **핵심 제안 포인트**:
  1. 센서 기반 게이미피케이션 + 토큰 이코노미 직접 구축 경험 (DayStarter)
  2. Firebase 풀스택 + 광고 수익화 3개월 딜리버리 경험 (Fortune App)
  3. React Native 크로스플랫폼 실전 경험 (Pilates App)
  4. 2단계 납품으로 90일 시점 시장 검증 가능

## 6. 최종 산출물

(8단계 완료 후 추가 예정)
