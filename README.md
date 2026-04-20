# policies

개인 개발 안드로이드 앱의 **개인정보처리방침** 및 법적 문서를 호스팅하는 public 저장소. 앱 코드는 각 앱 별도 저장소에서 관리됩니다.

## 호스팅된 문서

- **ShiftSleep** — <https://heegyeong.github.io/policies/shiftsleep/>
- **PlantCare** — <https://heegyeong.github.io/policies/plantcare/>
- **또박또박** (UtilityTrack) — <https://heegyeong.github.io/policies/utilitytrack/>

## 레포 구조

```
policies/
├── _config.yml           # Jekyll 사이트 설정 (minimal 테마)
├── index.md              # 앱 목록 랜딩 페이지
├── README.md             # 본 문서
├── shiftsleep/
│   └── index.md          # ShiftSleep 개인정보처리방침 (ko + en)
├── plantcare/
│   └── index.md          # PlantCare 개인정보처리방침 (ko + en)
└── utilitytrack/
    └── index.md          # 또박또박 개인정보처리방침 (ko + en)
```

앱을 추가할 때는 새 폴더 (`{app}/index.md`) 만 추가하면 됩니다. `_config.yml`이나 루트 `index.md`에 링크를 한 줄 추가하는 것이 좋습니다.

## 배포

- GitHub Pages: `Settings → Pages → Deploy from a branch → main / (root)`
- 빌드: Jekyll 자동 (별도 workflow 불필요)

## 업데이트 이력

- **2026-04-20** — UtilityTrack 정책 추가 → Play Store 브랜드 "또박또박 — 월세·공과금 알림"으로 변경
- **2026-04-19** — PlantCare 정책 추가, 기존 shiftsleep-legal 레포 내용을 하위 패키지 `shiftsleep/`로 통합
