# 개인정보처리방침 — 또박또박

최종 업데이트: 2026-04-20

또박또박(Play Store 명: "또박또박 — 월세·공과금 알림", 패키지명 `com.utilitytrack.app`, 이하 "본 앱")은 자취생·1인 가구의 월세·공과금 납부 관리를 위한 Android 앱입니다. 본 방침은 본 앱이 수집·이용·보관하는 정보와 사용자의 권리를 설명합니다.

## 1. 수집하는 정보

### 1-1. 사용자가 직접 입력하는 정보 (로컬 저장)
- 고지서 정보: 이름, 카테고리, 예상 금액, 납부일, 반복 여부, 알림 N일 전 설정
- 납부 기록: 실제 납부 일시·금액·메모, 영수증 이미지(선택)
- 커스텀 카테고리: 사용자 정의 카테고리 이름·아이콘·색상
- 앱 설정: 알림 시각, 테마(라이트/다크/시스템)

위 정보는 모두 **사용자 기기 내부**(Android Room DB, SharedPreferences)에만 저장되며, 본 앱 서버 또는 제3자에게 전송되지 않습니다. 본 앱은 서버를 운영하지 않습니다.

### 1-2. 자동 수집 정보
현재 버전(0.1.0)은 자동 수집 정보가 **없습니다**. 이름·이메일·전화번호·위치·연락처·통화 기록 등 개인 식별 정보를 수집하지 않습니다.

향후 업데이트에 Google AdMob 광고가 포함될 예정이며, 해당 버전부터는 다음 정보가 자동 수집됩니다.

- **광고 ID (AAID)**: Google AdMob이 광고 게재·측정에 사용
- **광고 로그**: AdMob SDK가 광고 노출·클릭 이벤트를 Google에 전송

## 2. 사용하는 권한

| 권한 | 목적 | 필수/선택 |
|---|---|---|
| `POST_NOTIFICATIONS` (Android 13+) | 납부 예정일 알림 전송 | 선택 — 거부 시 알림만 비활성 |
| `RECEIVE_BOOT_COMPLETED` | 기기 재부팅 후 알림 재스케줄 | 필수 |
| `INTERNET` | AdMob 도입 버전에서 광고 로딩 | 선택 |

## 3. 정보 이용 목적

| 정보 | 목적 |
|---|---|
| 고지서·납부 기록 | 납부 예정일 계산, 월별/카테고리별 통계 표시, 알림 스케줄링 |
| 앱 설정 | 알림 시각·테마 적용 |
| 광고 ID (향후) | 맞춤형 광고 게재 |

## 4. 정보 공유·외부 전송

- 본 앱은 사용자가 직접 입력한 정보를 외부에 공유·전송하지 않습니다.
- 사용자가 "설정 → 백업/복원"에서 JSON 내보내기를 실행하는 경우에만, 사용자가 선택한 저장소·공유 대상으로 파일이 전달됩니다. 저장 위치와 공유 범위는 전적으로 사용자의 선택이며 개발자는 해당 파일에 접근할 수 없습니다.
- 향후 AdMob 도입 버전에서는 다음 제3자 SDK가 광고 기능을 제공합니다.
  - **Google AdMob**: https://policies.google.com/privacy
  - **Google 광고 기술**: https://policies.google.com/technologies/ads

## 5. 보관 기간

- 사용자 입력 정보: 사용자가 앱을 삭제하거나 저장공간을 비울 때까지 기기에 보관
- 광고 데이터(향후): Google의 정책에 따름

## 6. 사용자 권리

- 앱 내 모든 데이터는 시스템 설정 → 앱 → 또박또박 → 저장공간 비우기로 즉시 삭제 가능
- "설정 → 백업/복원"에서 JSON 내보내기로 데이터 사본 확보 가능
- Android 13 이상에서는 시스템 설정에서 알림 권한 철회 가능
- Android 시스템 설정에서 광고 ID 재설정 또는 광고 맞춤설정 거부 가능(AdMob 도입 후 적용)

## 7. 만 14세 미만 아동

본 앱은 자취생·1인 가구를 대상으로 하며 만 14세 미만 아동의 사용을 의도하지 않습니다.

## 8. 방침 변경

방침이 변경되면 본 페이지의 "최종 업데이트" 일자를 갱신합니다. 중요한 변경(AdMob 도입 등)은 앱 내 공지로 안내합니다.

## 9. 문의

이메일: nonamedproj@gmail.com

---

# Privacy Policy — 또박또박 (Ddobak Ddobak) (English)

Last updated: 2026-04-20

또박또박 (Play Store title: "또박또박 — 월세·공과금 알림"; package `com.utilitytrack.app`; "the App") helps single-household users in Korea manage rent and utility bill payments on Android. This policy explains what data the App collects, how it is used, and your rights.

## 1. Information We Collect

### 1-1. User-entered (stored locally)
- Bills: name, category, expected amount, due day, reminder lead-time, recurrence
- Payment records: paid date/amount, optional memo and receipt image
- Custom categories: user-defined name, icon, color
- App settings: reminder time, theme mode

All of the above is stored **only on your device** (Android Room DB, SharedPreferences). The App runs no server and transmits nothing off your device.

### 1-2. Automatically collected
The current version (0.1.0) collects **no** automatic data and gathers no personal identifiers.

A future release will introduce Google AdMob, after which the following will be collected automatically:

- **Advertising ID (AAID)**: used by Google AdMob for ad delivery and measurement
- **Ad event logs**: AdMob SDK sends impression/click events to Google

## 2. Permissions

| Permission | Purpose | Required? |
|---|---|---|
| `POST_NOTIFICATIONS` (Android 13+) | Deliver bill-due reminders | Optional — denial only disables alerts |
| `RECEIVE_BOOT_COMPLETED` | Re-schedule reminders after reboot | Required |
| `INTERNET` | Load ads in the AdMob release | Optional |

## 3. Purpose of Use

| Data | Purpose |
|---|---|
| Bills / payments | Compute due dates, show monthly and per-category stats, schedule alerts |
| App settings | Apply reminder time and theme |
| Advertising ID (future) | Personalized ads |

## 4. Sharing

- We do not share user-entered data with any third party.
- If you run "Settings → Backup/Restore → Export" the JSON file is written only to the destination you choose via the system picker. The developer cannot access the file.
- When AdMob ships, the following third-party SDK will apply under its own policies:
  - Google AdMob — https://policies.google.com/privacy
  - Google ads technologies — https://policies.google.com/technologies/ads

## 5. Retention

Locally entered data persists until you uninstall the app or clear its storage. Future ad data follows Google's policies.

## 6. Your Rights

- Delete all local data via system Settings → Apps → 또박또박 → Clear storage
- Export a JSON copy of your data via "Settings → Backup/Restore"
- Revoke notification permission in system settings (Android 13+)
- Reset the Advertising ID or opt out of personalization in Android system settings (after AdMob ships)

## 7. Children Under 14

The App targets single-household adults and is not intended for children under 14.

## 8. Changes

When this policy changes the "Last updated" date will be revised. Material changes (e.g. introduction of AdMob) will be announced inside the App.

## 9. Contact

Email: nonamedproj@gmail.com
