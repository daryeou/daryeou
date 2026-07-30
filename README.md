<div align="center">

# Kwak Wonjo

### Android App Developer

Kotlin과 Jetpack Compose를 중심으로, 안정적으로 운영할 수 있는 모바일 제품을 만듭니다.

[![Blog](https://img.shields.io/badge/Tech_Blog-181717?style=flat-square&logo=tistory&logoColor=white)](https://daryeou.tistory.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:daryeou@gmail.com)

</div>

## About

실시간으로 변하는 금융 서비스부터 **100만+ 다운로드, MAU 30만+ 규모의 게임 리워드 플랫폼**까지 경험한 5년 차 Android 개발자입니다.

기능 구현에 그치지 않고 아키텍처 설계, Jetpack Compose 전환, 성능 측정과 최적화, 배포 및 운영 이슈 대응까지 제품의 전체 생명주기를 다룹니다. 사용자가 체감하는 안정성과 팀이 오래 유지보수할 수 있는 구조를 함께 만드는 것을 중요하게 생각합니다.

## Experience Highlights

### [Playio](https://play.google.com/store/apps/details?id=com.gna.playio) · GNA Company

`2023.06 — 2026.02` · 게임 리워드 플랫폼

- 파티, 퀘스트, 오퍼월, 보상 등 핵심 기능의 설계부터 출시와 운영까지 담당
- Clean Architecture 기반 10개 이상의 core 모듈과 20개 이상의 공통 Compose 컴포넌트 구축
- View 기반 화면의 Compose 전환과 Firebase Performance 기반 성능 측정 체계 도입
- MessagePack과 Zstandard를 활용한 이미지 업로드 파이프라인 최적화
- Android 프로세스 생명주기와 관련된 서드파티 SDK 결함을 분석·제보하여 패치에 기여

### [A-Bee](https://play.google.com/store/apps/details?id=com.app.abee) · The A-Bee

`2022.04 — 2023.05` · 지역 상인 광고 서비스

- Java 코드를 Kotlin으로 전환하고 MVVM, Clean Architecture, Flow, Hilt를 도입
- Foreground Service 기반 오버레이 광고와 WYSIWYG 광고 편집·결제 흐름 개발
- Firebase Crashlytics를 활용한 운영 안정성 개선

### [Korbit](https://play.google.com/store/apps/details?id=com.korbit.exchange)

`2021.07 — 2021.12` · 가상자산 거래소

- 실시간 시세와 보유 자산을 제공하는 Android 홈 화면 위젯 개발
- Foreground Service와 BroadcastReceiver를 활용한 백그라운드 업데이트 구현

## Selected Projects

### [Greenie — On-device AI Noise Analyzer](https://github.com/Greenie-crew/greenie-android)

생활 소음을 녹음하고 온디바이스 AI로 소음원을 분석하는 Android 앱입니다. 2023 서울시 새싹톤에서 인기상을 수상했습니다.

- Kotlin, Jetpack Compose, TensorFlow Lite, Room, Retrofit, Hilt
- AudioRecord 기반 PCM 수집 및 WAV 변환, YAMNet 기반 소음 분류
- 장시간 녹음 시 발생하던 메모리 문제를 파일 스트리밍 방식으로 개선
- Foreground Service를 활용한 백그라운드 녹음과 트래킹 구현

### [Image Search & Collection](https://github.com/daryeou/kakao-assignment)

이미지와 동영상 검색 결과를 시간순으로 통합하고 로컬 보관함을 제공하는 Compose 기반 Android 앱입니다.

- Kotlin, Jetpack Compose, Retrofit, Coroutines, Hilt
- 멀티 모듈 구조와 Secrets Gradle Plugin을 활용한 API 키 분리
- 서로 다른 두 API의 페이지네이션 결과를 시간 기준으로 병합

## Technical Focus

| Area | Technologies |
| --- | --- |
| Android | Kotlin, Java, Jetpack Compose, Coroutines, Flow, Navigation, Paging 3 |
| Architecture | Clean Architecture, MVVM, MVI, Multi-module, Dependency Injection |
| Data & Network | Retrofit, OkHttp, Room, DataStore, SQLite, MessagePack, Zstandard |
| Quality & Operations | Firebase Performance, Crashlytics, Remote Config, FCM, GitHub Actions |

## Technical Writing

- [Android 동적 로딩 — DexClassLoader, PathClassLoader, InMemoryDexClassLoader](https://daryeou.tistory.com/408)
- [Foreground Service가 서드파티 SDK 초기화에 미치는 문제](https://daryeou.tistory.com/396)
- [Playio Android 개발자 2년 9개월 회고](https://daryeou.tistory.com/401)

---

새로운 기술을 빠르게 적용하는 것보다, 문제의 원인을 끝까지 추적하고 제품과 팀에 남는 형태로 해결하는 개발자를 지향합니다.

---

<!-- 
<img src="https://cr-ss-service.azurewebsites.net/api/ScreenShot?widget=activity&username=daryeou&labels=true"/>
-->

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fharusiku0610&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com) <img src="https://img.shields.io/static/v1?label=🔭&message=Lets Dev&color=<COLOR>"/>
<!-- PM Status Table
Dev 일정|Ticket Name|Status
---|:----:|---:
2022.02.14 ~ </br>2022|Cryptocurrency Trading App|Open -->


<!--
**daryeou/daryeou** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

simple Icon: https://simpleicons.org/

custom Icon: https://shields.io/

github-readme-stats: https://github.com/anuraghazra/github-readme-stats/blob/master/docs/readme_kr.md

Jira는 이슈의 ‘상태(Status)’를 통해 진행상황을 전체 구성원에게 공유합니다. 그리고 ‘상태(Status)’값은 다음과 같이 정의할 수 있습니다.

열기(Open): 스프린트 내 이슈를 인지한 단계를 의미합니다. 해당 상태에서 SM과 PO는 협의를 거쳐 진행할 필요가 없는 이슈는 취소(Cancel) 상태로 변경합니다.
할 일(To-do): 실제로 수행해야할 이슈로 인지한 단계를 의미합니다. 이슈(보통은 스토리 형태이나 작업일수도 있음)를 진행하기 위한 실질적인 준비상태입니다.
진행중(In Progress): 수행해야할 이슈들이 실제로 개발 단계에 들어섰음을 의미합니다. 개발과 단위테스트를 진행하게되며 물리적으로 가장 오랜 시간을 차지합니다.
해결됨(Resolved): 진행 중 상태였던 이슈를 개발자(디자이너)가 1차 완료했음을 의미합니다. 해당 단계에서 SM이 2차 단위테스트(확인)을 진행하고 수행이 마무리됐다고 판단하면 PO, SM, 개발자가 함께 참여해 이슈의 완료 상태를 점검하는 ‘리뷰’를 진행합니다. ‘리뷰’는 PO, SM, 개발자가 일정을 협의해 일정 장소에 모여 이슈 상태를 확인합니다.
완료됨(Done): 해결된 이슈를 ‘리뷰’를 통해 완벽하게 마무리됐음을 확인했됐음을 의미합니다. 개발팀 전체의 합의에 의해 부여되는 상태이므로 ‘리뷰’ 세션에서 PO, SM, 개발자가 함께하는 가운데 이슈 상태를 완료로 넘기는 것을 추천합니다.
닫힘(Closed): 완료된 이슈나 취소된 이슈를 완전히 종결된 상태로 전환했음을 의미합니다. 불필요하다고 생각될 경우 프로젝트 구성원들의 협의에 의해 프로젝트에서 사용하는 상태 값에서 제외할 수 있습니다.
다시열기(Reopened): 취소했던 이슈가 재검토를 통해 필요하다고 판단될 경우 다시 할 일 단계로 되돌리는 것을 의미합니다. 협의는 보통 SM과 PO가 하게됩니다.
빌드(Build): 완료된 이슈를 통해 개발된 물량(화면, 소스 등)을 배포 완료했음을 의미합니다. 마찬가지로 협의에 의해 제외하고 별도의 시스템(Jenkins 등)을 통해 관리하는 것도 가능합니다.
빌드 실패(Build Failure): 말그대로 빌드가 실패했을 의미합니다.
취소(Cancel): 특정 상태(열기 등)에서 이슈가 수행할 필요가 없다고 판단된 경우를 의미합니다. 보통 SM과 PO가 협의를 거쳐 취소 여부를 결정합니다.


Feat 새로운 기능을 추가할 경우 
Fix 버그를 고친 경우 
Design CSS 등 사용자 UI 디자인 변경 
!BREAKING CHANGE 커다란 API 변경의 경우 
!HOTFIX 급하게 치명적인 버그를 고쳐야하는 경우 
Style 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우 
Refactor 프로덕션 코드 리팩토링 
Comment 필요한 주석 추가 및 변경 
Docs 문서를 수정한 경우 
Test 테스트 추가, 테스트 리팩토링(프로덕션 코드 변경 X) 
Chore 빌드 태스트 업데이트, 패키지 매니저를 설정하는 경우(프로덕션 코드 변경 X)
Rename 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우 Remove 파일을 삭제하는 작업만 수행한 경우

-->
