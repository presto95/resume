# 안녕하세요, 이한결입니다.

iOS 앱 개발자로 소프트웨어 개발자 커리어를 시작한 지 벌써 4년이 지났습니다.

사람이 보기에 좋은 코드를 작성하는 것이 팀과 개인의 업무 효율성을 높여준다고 믿습니다.

주요한 업무 외에도 개선할 점을 찾아 고치는 것을 좋아합니다.

팀원들과 빠르고 쉽게 커뮤니케이션하며 일할 수 있는 환경을 좋아합니다.

# Work Experience

## Coupang

- Sr. Mobile Engineer | 2022.4. ~ 현재
- Mobile Engineer | 2020.2. ~ 2022.3.

쿠팡 iOS 애플리케이션의 기능 개발 및 유지보수를 담당합니다.

### Platform

iOS와 관련된 기능 개선 및 유지보수 업무를 진행했습니다.

**앱 시작 시간 개선**

- 쿠팡 앱의 시작 시간이 경쟁사 대비 오래 걸리는 것으로 조사되어 개선 작업을 진행함
- Instruments를 사용하여 앱 실행부터 초기 화면이 노출되기까지 실행되는 코드들의 실행 시간을 파악, 오래 걸리는 코드들을 개선함
- 도메인 레벨에서 모듈화된 모듈들을 Dynamic Framework에서 Static Library로 전환함. 이 때 xib와 같은 리소스를 포함하는 경우 리소스 제거 작업도 함께 함
- 앱 시작 시간에 0.x초를 줄임

**리스트 스크롤 성능 개선**

- 사내 성능 측정 툴을 통해 특정 페이지에서 리스트 스크롤 성능이 매우 좋지 않음을 발견함
- Instruments를 통해 메인 쓰레드를 많이 사용하는 지점을 찾아냄
- 메인 쓰레드를 사용하지 않아도 되는 지점에서 백그라운드 쓰레드를 사용하게 하는 것으로 스크롤 성능을 크게 개선함

**Push Notification 수신 로깅 구현**

- Notification Service Extension을 경유해 들어오는 Push Notification의 경우 앱이 종료된 상태에서도 코드를 실행시킬 수 있다는 것을 활용, 이러한 Push Notification의 수신 여부를 로깅하는 기능을 구현함
- 현재 시스템에서 로깅에 필요한 값을 App Extension에 공유하여 App Extension에서 로깅하는 것에 문제가 없게 함
- Push Notification 관련 서비스의 안정성을 확인할 수 있는 데이터를 수집할 수 있게 됨
- 연구 내용을 사내 다른 iOS 개발팀에도 공유함

### Design System

초기 디자인 시스템 구축 프로젝트에 참여하여 iOS 환경에서 사용할 수 있는 UI 라이브러리를 만들고 유지보수 하였으며, 쿠팡 iOS 애플리케이션에 적용했습니다.

**리스트에서 상품을 보여주는 컴포넌트 개발 및 마이그레이션**

- 기존에 리스트에서 상품을 보여주는 컴포넌트는 공통화되지 않았고, 오랜 기간 동안 규칙 없이 다양한 요구사항을 만족하기 위해 유지보수되면서 코드의 양과 복잡도가 증가함
- 컴포넌트의 불변 영역과 가변 영역을 UX 팀과 사전에 정의하여, 유연성과 개발 난이도 간 트레이드오프를 고려하여 디자인함
- 기존에 비즈니스와 연관된 기능일지라도 비즈니스 코드에 의존하지 않게 개발하여 공통 UI 컴포넌트로서 기능할 수 있게 함
- 정의된 규칙 안에서 요구사항을 구현할 수 있게 되어, 피쳐 개발을 위해 수정해야 하는 지점을 쉽게 알 수 있게 되는 등, 엔지니어의 생산성을 높임

**샘플 앱 개발에 특화된 DSL 개발 및 적용**

- UI 개발이 주를 이루는 작업의 특성을 고려하여 UI를 선언적으로 작성할 수 있게 하는 DSL을 도입하려고 함
- SwiftUI의 API와 Swift의 Result Builder와 같은 기능을 적용하여 iOS 엔지니어에게 친숙한 인터페이스를 제공함
- 선언형 UI의 이점을 갖게 되어 더 이해하기 쉬운 코드 구조를 가지면서도 더 효율적인 개발 및 유지보수가 가능해짐

**디자인 시스템 클라이언트들과의 커뮤니케이션 및 지원**

- 주요한 PoC 역할을 주도적으로 수행함
- 관련 문의를 기민하게 처리하여 엔지니어들의 생산성 향상에 기여함
- 온보딩 세션을 진행하고 위키를 만들어 러닝 커브를 최소화하고 성공적인 온보딩에 기여함

## LINE Financial Plus

- 인턴 | 2019.4. ~ 2019.5.

LINE 가계부 서비스의 API를 사용하여 위치 기반 가계부 애플리케이션을 만드는 과제를 수행했습니다.

- 수입 및 지출을 기록하는 가계부 기능 개발
- 지출이 발생한 위치를 기록하여 지도상에서 '소비 지도'를 볼 수 있는 기능 개발
- SDK를 래핑하여 Swift스러운 코드로 필요한 기능만 사용할 수 있도록 함
- Profiling을 통해 메모리 누수 문제 해결

# Skill

## Communication

- 메신저를 사용하는 것보다 얼굴을 맞대고 대화하는 것을 선호합니다.
- 메모장을 곁에 두고 그림 등을 활용하여 생각하는 것을 명확하게 표현하기 위해 노력합니다.
- 모르는 것이 있으면 완벽하게 알 때까지 파고들며, 알게 된 것을 잘 정리하여 공유합니다.
- 단언할 수 있는 상황이라면 모호한 표현을 피하고 단언하는 표현을 사용합니다. '~인 것 같다'라고 말했다면 '~이다'라고 바꾸어 말합니다.
- 투명하게 커뮤니케이션합니다. DM보다는 모두가 함께 있는 채널에서 커뮤니케이션합니다. 잘한 것은 잘했다고, 잘못한 것은 잘못했다고 솔직하게 말합니다.

## Swift

- Swift를 사용하여 생각하는 것을 막힘 없이 작성합니다.
- Swift Style Guidelines를 준수하여 코드를 작성합니다.
- Generics, Protocol Oriented Programming 등을 이해하고 있습니다.
- ARC를 이해하고, Reference Cycle을 피하는 코드를 작성할 수 있습니다.
- Swift의 업데이트 소식을 따라잡기 위해 노력합니다.
- Swift가 내부적으로 어떻게 동작하는지 이해하고 있고, Memory Debugger 및 Swift Intermediate Language를 통해 직접 확인해 보았습니다.

## iOS

- UIKit을 사용하여 다양한 커스텀 뷰를 개발할 수 있습니다.
- SnapKit, FSPagerView 등 UI 개발에 도움을 주는 다양한 라이브러리를 사용한 경험이 있으며, 기반 기술도 이해하고 있습니다.
- MVC, MVVM, ReactorKit 등의 아키텍쳐 패턴을 사용한 경험이 있으며, 기반 기술도 이해하고 있습니다.
- Reactive Programming을 이해하고, RxSwift나 ReactiveSwift와 같은 라이브러리를 사용한 경험이 있습니다. 
- SwiftUI, Combine 등을 적용하여 애플리케이션을 개발한 경험이 있습니다.

## Tool

- Instruments를 사용한 Profiling을 통해 성능 개선점을 찾고 해결할 수 있습니다.
- Terminal과 Sourcetree를 사용하여 Git을 활용합니다.
- GitHub를 활용한 Pull Request 및 Code Review에 익숙합니다.
- Slack, Zoom, Jira 등의 툴에 익숙합니다.

# Contact

- [Email](mailto:yoohan95@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/한결-이-463750152/)
- [GitHub](https://github.com/presto95)
