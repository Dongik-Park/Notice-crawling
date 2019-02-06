# Website crawling chatbot


## Getting Started

### 크롤링(Crawling)

웹 크롤링이란 인터넷에 있는 웹페이지를 방문해서 자료를 수집하는 일을 말한다. 

 Reference : [wiki - Web crawler](https://en.wikipedia.org/wiki/Web_crawler)

### Prerequisites & Installing

* Flask

    플라스크(Flask)는 파이썬으로 작성된 마이크로 웹 프레임워크의 하나로, Werkzeug 툴킷과 Jinja2 템플릿 엔진에 기반을 둔다. BSD 라이선스이다.

    플라스크의 최신 안정판은 2017년 5월 기준으로 0.12.2이다. 플라스크 프레임워크를 사용하는 애플리케이션에는 핀터레스트, 링크드인, 플라스크 자체를 위한 공동체 웹 페이지를 포함한다.

    플라스크는 특별한 도구나 라이브러리가 필요 없기 때문에 마이크로 프레임워크라 부른다. 데이터베이스 추상화 계층, 양식 유효성 확인, 기타 기존의 서드파티 라이브러리가 공통 기능을 제공하는 구성 요소가 없다. 그러나 플라스크는 플라스 자체에서 구현된 것처럼 애플리케이션 기능을 추가할 수 있는 확장 기능을 지원한다. 확장 기능은 객체 관계 매퍼, 양식 유효성 확인, 업로드 관리, 다양한 개방형 인증 기술, 여러 공통 프레임워크 관련 도구들을 위해 존재한다. 확장 기능들은 코어 플라스크 프로그램에 비해 훨씬 더 정기적으로 업데이트된다.

    Reference : [wiki - Flask](https://en.wikipedia.org/wiki/Flask_(web_framework))

* Selenium

    Selenium은 웹 응용 프로그램을 테스트 하기 위한 이식 가능한 프레임 워크이다 . Selenium은 테스트 스크립트 언어(Selenium IDE) 를 배울 필요없이 기능 테스트를 작성하기 위한 재생 도구를 제공한다.

    Reference : [wiki - Selenium](https://en.wikipedia.org/wiki/Selenium_(software))

* DialogFlow

    Dialogflow는 웹사이트, 모바일 애플리케이션, 널리 사용되는 메시지 플랫폼, IoT 기기의 대화 인터페이스를 구축할 수 있는 엔드 투 엔드 개발 도구로, 한번 구축하면 어느 곳에나 배포할 수 있습니다. 이를 통해 사용자와 기업 간의 자연스러우면서 다양한 상호작용이 가능한 인터페이스(예: 채팅봇, 대화형 IVR)를 구축할 수 있습니다. Dialogflow Enterprise 버전 사용자는 Google Cloud 지원을 이용할 수 있으며 프로덕션 배포에 서비스수준계약(SLA)이 적용됩니다.

    Reference : https://cloud.google.com/dialogflow-enterprise/?hl=ko
    
## Running the tests
