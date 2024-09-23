# 우아한테크코스 6기 백엔드 도라 기록

## Level 1 (24.02.13~24.04.05)

### 학습 목표
- 자바 프로그래밍 언어에 대한 핵심 개념을 익혀 프로그래밍하는 경험
- 읽기 좋은 코드를 구현하는 것이 왜 중요한지와 코드를 개선해 읽기 좋은 코드로 변경해 보는 경험
- 자신이 구현한 코드에 대해 단위 테스트와 리팩토링하는 경험
- 데이터베이스를 활용한 콘솔 애플리케이션을 개발하는 경험

| 프로젝트 | 기간 | PR |
| - | - | - |
| 1️⃣ 자동차 경주 - 단위 테스트 | `24.02.13` ~ `24.02.19` | [1단계 - 자동차 경주 (페어 프로그래밍) 🔗](https://github.com/woowacourse/java-racingcar/pull/679) |
| | | [2단계 - 자동차 경주 리팩터링 🔗](https://github.com/woowacourse/java-racingcar/pull/801) |
| 2️⃣ 사다리 타기 - TDD | `24.02.20` ~ `24.03.04` | [1단계 - 사다리 생성 (페어 프로그래밍) 🔗](https://github.com/woowacourse/java-ladder/pull/315) |
| | | [2단계 - 사다리 게임 실행 🔗](https://github.com/woowacourse/java-ladder/pull/399) |
| 3️⃣ 블랙잭 - Clean Code | `24.03.05` ~ `24.03.18` | [1단계 - 블랙잭 게임 실행 (페어 프로그래밍) 🔗](https://github.com/woowacourse/java-blackjack/pull/612) |
| | | [2단계 - 블랙잭 베팅 🔗](https://github.com/woowacourse/java-blackjack/pull/752) |
| 4️⃣ 체스 - OOP,DB | `24.03.19` ~ `24.04.01` | [1~2단계 - 체스판 초기화, 말 이동 (페어 프로그래밍) 🔗](https://github.com/woowacourse/java-chess/pull/646) |
| | | [3단계 - 승패 및 점수 🔗](https://github.com/woowacourse/java-chess/pull/771) |
| | | [4단계 - DB 적용 🔗](https://github.com/woowacourse/java-chess/pull/816) |


### 기술 포스팅
- [Abstract class vs Interface (Virtual function vs Abstract method, Dynamic Method Dispatch)](https://choo.oopy.io/84026815-5393-46cf-994c-d8b3d2fb1ce0)
- [레벨 1 기간동안 생긴 나의 개발 철학과 기준 총정리 (Java, OOP)](https://choo.oopy.io/1a5e6970-fa9e-471c-8cc1-b4bdbcc03ff8)
- [Inheritance vs Composition](https://choo.oopy.io/36293e4a-f4ab-4b74-ba62-e70a2d4eaad3)

### 소프트스킬 포스팅
- [우아한테크코스는 내게 어떤 곳인가: 토론으로 성장하기](https://choo.oopy.io/ca580009-e345-4974-8d7c-59d256552994)

## Level 2 (24.04.16~24.06.14)

### 학습 목표
- 주어진 요구사항에 맞춰 기능을 추가/변경하며 애플리케이션을 발전시켜 나가는 경험
- 클라우드 환경에 배포 하여 사용자에게 서비스할 수 있는 최소한의 상태로 만드는 경험
- 효과적으로 새로운 기술을 익힐 수 있는 본인만의 학습 방법을 찾는 시도
- 웹 프로그래밍 과정에서도 읽기 좋은 코드, 유지보수하기 좋은 코드를 작성하는 경험

| 프로젝트 | 기간 | PR |
| - | - | - |
| 1️⃣ 방탈출 예약 관리 | `24.04.16` ~ `24.04.29` | [1~3단계 - 홈 화면, 예약 조회, 예약 추가/취소 (페어 프로그래밍) 🔗](https://github.com/woowacourse/spring-roomescape-admin/pull/63) |
| | | [4~9단계 - DB 적용, 시간 관리, 계층화 리팩터링 🔗](https://github.com/woowacourse/spring-roomescape-admin/pull/148) |
| | | [10단계 - 콘솔 UI 지원 (선택) 🔗](https://github.com/woowacourse/spring-roomescape-admin/pull/191) |
| 2️⃣ 방탈출 사용자 예약 | `24.04.30` ~ `24.05.13` | [1~3단계 - 예외 처리와 응답, 테마 추가, 사용자 기능 (페어 프로그래밍) 🔗](https://github.com/woowacourse/spring-roomescape-member/pull/12) |
| | | [4~6단계 - 사용자 로그인, 로그인 리팩터링, 관리자 기능 🔗](https://github.com/woowacourse/spring-roomescape-member/pull/144) |
| 3️⃣ 방탈출 예약 대기 | `24.05.14` ~ `24.05.27` | [1~2단계 - JPA 전환, 내 예약 목록 조회 기능 (페어 프로그래밍) 🔗](https://github.com/woowacourse/spring-roomescape-waiting/pull/20) |
| | | [3~4단계 - 예약 대기 기능, 예약 대기 관리 🔗](https://github.com/woowacourse/spring-roomescape-waiting/pull/156) |
| 4️⃣ 방탈출 결제/배포 | `24.05.28` ~ `24.06.10` | [1단계 - 예약 시 결제단계 추가 (페어 프로그래밍) 🔗](https://github.com/woowacourse/spring-roomescape-payment/pull/25) |
| | | [2~4단계 - 내 예약 페이지 변경, 배포, 문서화 🔗](https://github.com/woowacourse/spring-roomescape-payment/pull/146) |


### 기술 포스팅

### 소프트스킬 포스팅
