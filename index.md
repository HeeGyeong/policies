# HeeGyeong — App Policies

개인 개발 안드로이드 앱의 **개인정보처리방침** 및 법적 문서를 호스팅하는 저장소입니다.

## 앱 목록

- **[ShiftSleep](shiftsleep/)** — 교대근무자 대상 수면 관리 앱
- **[PlantCare](plantcare/)** — 식집사 입문자 대상 물주기·성장 일기 앱
- **[UtilityTrack](utilitytrack/)** — 자취생·1인 가구 대상 공과금·월세 납부 관리 앱

## 구조

각 앱은 하위 폴더(패키지)로 분리되어 있으며, 폴더 내 `index.md`가 해당 앱의 기본 정책 문서입니다.

```
policies/
├── shiftsleep/      → /shiftsleep/
├── plantcare/       → /plantcare/
└── utilitytrack/    → /utilitytrack/
```

## 업데이트 방법

각 앱 폴더의 `index.md`를 수정하고 `main`에 push하면 GitHub Pages가 자동으로 재배포합니다.
