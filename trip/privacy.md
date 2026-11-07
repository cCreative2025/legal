# 출장갈때 개인정보처리방침

**시행일**: 2026년 11월 8일

**라운지스(Loungees)**(대표자: 김대현, 이하 "운영자")는 출장·여행 관리 앱 **"출장갈때"**(이하 "서비스")를 운영합니다. 출장갈때는 **회원가입·로그인이 없는 앱**이며, 이용자가 기록한 출장·일정·바우처·장소·지출은 **이용자의 기기 안에만 저장**됩니다.

- **상호**: 라운지스(Loungees)
- **대표자**: 김대현
- **이메일**: support@loungees.net

---

## 1. 기기에만 저장되는 정보

출장 이름·기간, 일정, 바우처(사진·PDF), 장소 링크, 지갑·지출 기록, 영수증 사진은 모두 이용자의 기기 안에 저장되며 운영자에게 전송되지 않습니다. **앱을 삭제하면 함께 삭제**되며 되살릴 수 없습니다.

## 2. 운영자 서버가 처리하는 정보

| 항목 | 목적 | 보관 |
|---|---|---|
| 기기 식별값(iOS 공급업체 식별자 IDFV) | AI 분석 하루 사용 횟수·광고 보상 횟수 계산 | 사용 횟수와 함께 보관, 이름·연락처와 연결하지 않음 |
| AI 사용 횟수·날짜, 광고로 받은 남은 횟수 | 하루 이용 한도 관리 | 위와 같음 |

운영자는 이름·전화번호·이메일·위치 등 이용자를 직접 알아볼 수 있는 정보를 수집하지 않습니다.

## 3. AI 분석 (이용자가 요청할 때만)

이용자가 **'AI로 등록'(바우처)** 또는 **'영수증으로 채우기'**를 누르면, 해당 이미지·PDF가 운영자 서버를 거쳐 **Google LLC의 Gemini API**로 전송되어 일정·장소·금액 등을 읽어냅니다.

- 바우처·영수증에는 이름, 예약번호, 결제 금액 등이 포함될 수 있습니다.
- 운영자 서버는 분석 결과를 앱에 돌려줄 뿐 **이미지와 결과를 저장하지 않습니다.**
- Google은 Gemini API 이용약관에 따라 요청을 처리합니다. ([Google 개인정보처리방침](https://policies.google.com/privacy))
- AI 분석을 쓰지 않으면 어떤 파일도 기기 밖으로 나가지 않습니다.

## 4. 광고 (Google AdMob)

이용자가 **'광고 보고 10회 받기'**를 누를 때 Google AdMob 보상형 광고가 표시됩니다. AdMob은 광고 제공과 측정을 위해 광고 식별자(IDFA, 이용자가 추적을 허용한 경우), 기기 정보, 대략적인 위치(IP 기반) 등을 수집할 수 있습니다. 앱은 처음 광고를 볼 때 iOS의 '앱 추적 투명성' 동의를 묻으며, 거부해도 광고와 앱을 그대로 이용할 수 있습니다. ([Google 광고 정책](https://policies.google.com/technologies/ads))

## 5. 기기 권한 사용

| 권한 | 사용 목적 |
|---|---|
| 카메라 | 영수증을 찍어 지출에 붙임 |
| 사진 보관함 | 바우처·영수증 사진을 골라 앱에 저장 |
| 알림 | 이용자가 켠 일정 알림(기기 안에서 예약) |
| 추적(ATT) | 맞춤 광고 — 거부 가능 |

다른 앱(메일·파일)에서 '출장갈때'로 공유한 파일은 앱 안의 바우처로만 저장됩니다.

## 6. 제3자 제공 및 처리 위탁

| 받는 곳 | 내용 | 목적 |
|---|---|---|
| Google LLC (Gemini API) | 이용자가 분석을 요청한 이미지·PDF | AI 분석 |
| Google LLC (AdMob) | 광고 관련 기기 정보 | 보상형 광고 |
| Supabase Inc. | 기기 식별값·사용 횟수 | 서버 운영(데이터 저장) |

## 7. 보관 및 삭제

- 서버의 사용 횟수 기록은 서비스 운영 기간 동안 보관하며, 이용자가 삭제를 요청하면 지체 없이 삭제합니다. 요청 시 앱의 설정 대신 아래 이메일로 연락해 주세요.
- 기기 안의 데이터는 앱 안에서 항목별로 지우거나 앱을 삭제해 지울 수 있습니다.

## 8. 아동의 개인정보

출장갈때는 만 14세 미만 아동을 대상으로 하지 않으며, 아동의 개인정보를 알면서 수집하지 않습니다.

## 9. 방침 변경

iCloud 백업, 유료 결제 등 새 기능으로 처리 항목이 바뀌면 시행 전에 본 방침을 개정하고 이 페이지에서 알립니다.

## 10. 문의

개인정보 관련 문의는 support@loungees.net 으로 보내 주세요.

---

# BizTrip ("출장갈때") Privacy Policy (English summary)

- No sign-up. Trips, schedules, vouchers, places, expenses and receipt photos are stored **only on your device**.
- Our server stores only a device identifier (IDFV) with AI-usage counts to enforce daily limits.
- When you tap **AI analysis** (voucher or receipt), the image/PDF is sent through our server to **Google Gemini API** for extraction; we do not store the file or result.
- **Google AdMob** rewarded ads are shown only when you choose to watch one; tracking is asked via App Tracking Transparency and can be declined.
- Contact: support@loungees.net
