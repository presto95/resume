# 안녕하세요, 이한결입니다.

iOS 앱 개발자로 소프트웨어 개발자 커리어를 시작한 지 2년이 지났습니다. 사람이 보기에 좋은 코드를 작성하는 것이 개인과 팀의 생산성을 높여준다고 믿고, 저부터 사람이 읽기 좋은 코드를 작성하기 위해 노력합니다. 주요한 업무 외에도 개선할 점을 찾아 고치는 것을 좋아합니다. 팀원들과 쉽고 빠르게 커뮤니케이션하며 일할 수 있는 환경을 좋아합니다. 온화한 커뮤니케이션을 위해 노력하면서도, 사실을 바탕으로 하는 대화에서는 최대한 단언하는 표현을 사용하여 효율적으로 커뮤니케이션하려고 합니다.

# Work Experience

## Coupang

- Mobile Engineer | 2020.2. ~ 2022.3.
- Sr. Mobile Engineer | 2022.4. ~ 현재

쿠팡 iOS 앱의 개발 및 유지보수를 담당합니다.

### Platform

iOS와 관련된 기능 개선 및 유지보수 업무를 진행했습니다.

**Push Notification 수신 로깅 구현**

- Notification Service Extension을 경유해 들어오는 Push Notification의 경우 앱이 종료된 상태에서도 코드를 실행시킬 수 있다는 것을 활용, 이러한 Push Notification의 수신 여부를 로깅하는 것을 구현함
- 현재 시스템에서 로깅에 필요한 값을 App Extension에 공유하여 App Extension에서 로깅하는 것에 문제 없게 함
- Push Notification 관련 서비스의 안정성을 확인할 수 있는 데이터를 수집할 수 있게 됨
- 연구 내용을 사내 다른 iOS 개발팀에도 공유함

### RDS

Rocket Design System의 줄임말로, 쿠팡의 디자인 시스템을 구축하는 프로젝트에 참여했습니다. iOS 엔지니어로서 iOS 환경에서 사용할 수 있는 UI 라이브러리를 만들고 유지보수하며, 쿠팡 iOS 애플리케이션에 적용했습니다.

**리스트에서 상품을 보여주는 컴포넌트 개발 및 마이그레이션**

- 기존에 리스트에서 상품을 보여주는 컴포넌트는 공통화되지 않았고, 오랜 기간 동안 규칙 없이 다양한 요구사항을 만족하기 위해 유지보수되면서 코드의 양과 복잡도가 증가함
- 컴포넌트의 불변 영역과 가변 영역을 UX 팀과 사전에 정의하여, 유연성과 개발 난이도 간 트레이드오프를 고려한 설계를 진행함
- 비즈니스에 깊게 관여하지만, 비즈니스 코드에 의존하지 않게 개발하여 공통 UI 컴포넌트로서 기능할 수 있게 함
- 정의된 규칙 안에서 요구사항을 구현할 수 있게 되어, 피쳐 개발을 위해 수정해야 하는 지점을 쉽게 알 수 있게 되는 등, 엔지니어의 생산성을 높임

**샘플 앱 개발에 특화된 DSL 개발 및 적용**

- UI 개발이 주를 이루는 작업의 특성을 고려하여 UI를 선언적으로 작성할 수 있게 하는 DSL을 개발함
- iOS 엔지니어에게 친숙한 인터페이스를 제공하기 위해 SwiftUI의 API와 Swift의 Result Builder와 같은 최신 기능을 참고하여 작성함
- 코드가 선언형 UI의 이점을 갖게 되어 더 이해하기 쉬운 코드 구조를 가지면서도 더 효율적인 개발 및 유지보수가 가능해짐

**RDS를 사용하는 사내 개발자와의 커뮤니케이션 및 서포트**

- 프로젝트의 메인 PoC 역할을 주도적으로 수행함
- 관련 문의를 신속하게 처리하여 엔지니어들의 생산성 향상에 기여함
- 온보딩 세션을 진행하고 관련 자료를 만들어 러닝 커브를 최소화함

### Full Stack Project

AB 테스트를 통해 피쳐 개발 및 이터레이션을 진행합니다. iOS 엔지니어로서 쿠팡 iOS 앱에 해당 작업을 진행했습니다.

**Contribution**

- 배송 피드백 팝업 리뉴얼
- 리뷰 작성시 별점 입력을 더 빠르게 할 수 있게 함

# Skill

## Communication

- 말뿐만 아니라 글, 그림 등을 활용하여 생각하는 것을 명확하게 표현하기 위해 노력합니다.
- 단언할 수 있는 상황이라면, 모호한 표현을 피하고 단언하는 표현을 사용합니다.
- 투명하게 커뮤니케이션하기 위해 노력합니다. 잘한 것은 잘했다고, 잘못한 것은 잘못했다고 열린 공간에 공유합니다.

## Swift

- Swift를 사용하여 생각하는 것을 막힘 없이 작성합니다.
- Swift Style Guidelines를 준수하여 코드를 작성합니다.
- Generics, Protocol Oriented Programming 등을 이해하고 있습니다.
- ARC를 이해하고, Reference Cycle을 피하는 코드를 작성할 수 있습니다.
- Swift가 내부적으로 어떻게 동작하는지 이해하고 있고, Memory Debugger 및 Swift Intermediate Language를 통해 직접 확인해 보았습니다.

## iOS

- UIKit을 사용하여 다양한 커스텀 뷰를 개발할 수 있습니다.
- SnapKit, FSPagerView 등 UI 개발에 도움을 주는 다양한 라이브러리를 사용한 경험이 있으며, 기반 기술도 이해하고 있습니다.
- MVC, MVVM, ReactorKit 등의 아키텍쳐 패턴을 이해하고, 사용한 경험이 있습니다.
- Reactive Programming을 이해하고, RxSwift나 ReactiveSwift와 같은 라이브러리를 사용한 경험이 있습니다. 
- SwiftUI, Combine 등을 적용하여 애플리케이션을 개발한 경험이 있습니다.

## Tool

- Xcode에 친숙하며, Instruments를 사용한 Profiling을 통해 성능 개선점을 찾을 수 있습니다.
- Terminal과 Sourcetree를 사용하여 Git을 활용합니다.
- GitHub를 활용한 Pull Request 및 Code Review에 익숙합니다.
- Slack, Zoom, Confluence, Jira 등의 툴에 익숙합니다.

# Contact

- [Email](mailto:yoohan95@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/한결-이-463750152/)
- [GitHub](https://github.com/presto95)
