
https://dev.jek300.com/category/%5B3%EB%8B%A8%EA%B3%84%5D%20CS%20%EC%A7%88%EB%AC%B8%20%26%20%EB%8C%80%EB%8B%B5%20%EC%9A%94%EC%95%BD%20%EC%A0%95%EB%A6%AC%EC%A7%91

[프론트앤드]
https://velog.io/@okok0415/%EB%A9%B4%EC%A0%91%EB%8C%80%EB%B9%84-%EC%98%88%EC%83%81%EA%BC%AC%EB%A6%AC%EC%A7%88%EB%AC%B8-%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C-%EA%B0%9C%EB%B0%9C%EC%9E%90-%EC%B7%A8%EC%97%85-%EB%A9%B4%EC%A0%91-%EC%A7%88%EB%AC%B8-%EC%B4%9D%EC%A0%95%EB%A6%AC-%EC%9E%A5%EB%AC%B8-%EA%BC%AC%EB%A6%AC%EC%97%90%EA%BC%AC%EB%A6%AC%EB%A5%BC-%EB%AC%B4%EB%8A%94-%EC%A7%88%EB%AC%B8-%ED%8F%AC%ED%95%A8


https://naldo627.github.io/2019/06/03/techinterview-prepare-wm/

-   프로그래밍 지식 (소프트웨어 공학)
    -   가장 자신있는 언어
    -   특히 Java 의 데이터 타입(Array, ArrayList, LinkedList, Map, HashMap 등)과 그 외 전반적인 지식
    -   MVC 구조란?
    -   DTO, DAO, VO?
    -   Restful 이란?
    -   젠킨스란?
    -   재귀
    -   로우 레벨 지식
    -   OOP, AOP, FOP 등 프로그래밍 기법
    -   개발 방법론
-   운영체제
    -   멀티 스레드 지식 (환경 구성 시 신경써야 하는 부분 등)
    -   스레드와 프로세스 차이
    -   동기, 비동기, 블로킹, 넌블로킹 차이
    -   CPU 스케줄링
    -   프로세스 공간
-   데이터베이스
    -   쿼리 속도 및 효율 향상법
    -   정규화
    -   인덱스
    -   로우 레벨 지식
-   HTTP 등 웹과 통신 지식
    -   주소창에 URL을 치고 엔터를 치면 흐름이 어떻게 되는가
    -   HTTP/HTTPS 차이
    -   CORS 이슈
    -   OSI 7 계층 존재 이유
    -   로우 레벨 지식
-   컴퓨터 아키텍쳐
    -   32비트, 64비트 차이
-   디자인 패턴
-   개인 프로젝트 경험
    -   진행하면서 어려웠던 점이 뭐고, 어떻게 극복했는 지? 사례 포함
-   수업 경험
    -   가장 재밌었거나 기억나는 과목
-   그 밖에 꼬리물기 식 질문이 많음

이 이외에, 핵데이 당시 멘토님의 조언은 다음과 같다.

-   기본적인 것들을 착실히 공부해서 준비하라.
-   시간복잡도 등 알고리즘 효율 생각하라.
-   Hackday 신청 당시 제출했던 자소서 기반으로 면접 준비하라.
-   Hackday 당시 진행했던 프로젝트 경험, 느낀 점 및 부족했던 점 보완해라.
-   GIF 만들기 프로젝트였던 만큼, 이미지 지식을 보충해서 가라.

추가로, 후기에서 말하고 있거나, 개인적으로 느낀 면접 TIP으로는 다음과 같다.

-   당연한 말이지만, 위축되지 않고 당당한 자세
-   과장되지 않고, 솔직하게 답변
-   모르는 것은 모른다고 말하며, 면접관을 속이려 들지 말 것
-   꼬리물기 식 질문이 많다고 하니, 답변을 추상적으로 하지 말고 구체적으로 하며, 잘 아는 쪽으로 답변할 것 (즉, 질문 유도가 가능하다!)
-   면접관이 꼰대 개발자일 수 있다. 이에 맞춰서 준비할 것  
    (여기서 말하는 꼰대는 나쁜 뜻이 아니다. 자신의 개발 주관이 철저한 개발자를 뜻한다. 오히려 난 개발자는 꼰대여야 한다고 생각한다. 왜냐면 자신의 뚜렷한 주관없이 개발을 하게 된다면, 코드가 들쑥날쑥, 이랬다저랬다 할 수 있기 때문. 그렇다고 의사소통을 안하려 한다면 곤란하겠지만..)
-   여러개를 짧게 답하는 것보다, 하나를 깊게 답하는게 나을듯

https://github.com/ksundong/backend-interview-question



**내가 만든 이 시스템은 실제 장비에서**

-   어느 정도의 **부하** 를 견딜 수 있는가?
-   시스템(데이터베이스, 서버), 자원(cpu, disk, memory 등)에서 **병목** 이 생기진 않는가?
-   자원을 **효율적** 으로 사용하는가?
-   **메모리 누수, 오류, 오버플로우** 는 발생하지 않는가?
-   **최악의 상황** 에선 어떤 동작을 하는가? (예측하고 대비하기 위하여)
-   **장애 조치와 복구** 가 잘 동작을 하는가?