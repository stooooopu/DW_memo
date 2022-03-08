## 참고 유트브

- https://youtu.be/6C1ayZh7S7I
- https://youtu.be/5DxMUShYHW8 (node위주)
- https://youtu.be/fXBZvpG_IUQ (스타트업 node이유)


## 참고 블로그

- https://doqtqu.tistory.com/284

## 기업 사례
- https://ichi.pro/ko/node-js-peuleim-wokeuleul-sayonghayeo-bildeu-doen-9-gaji-yumyeonghan-aepeullikeisyeon-137733197396695
- https://zdnet.co.kr/view/?no=20131128094356(paypal)
#### 런타임 : 프로그래밍 언어가 구동되는 환경

Node.js의 주요 특징

1. 자바스크립트 언어 사용

- 자바스크립트를 사용할 줄 아는 개발자들에게는 러닝커브가 낮다. 또한, 자바스크립트로 백엔드 로직까지 개발할 수 있다는 엄청난 장점으로 점유율이 높아지고 있다. 

2. 빠른 속도

- 구글에서 개발한 자바스크립트 엔진을 사용하기 때문에 빠른 속도를 자랑한다.

3. 이벤트 기반 비동기 방식 (Non-Blocking) 

- Node.js에서는 모든 API가 비동기 방식이므로, 호출 후 응답을 기다지리 않고 다른 API를 호출한다. 이전에 호출했던 API의 응답이 오면 이벤트 루프가 확인하여 처리한다.

4. 단일 쓰레드

- 복잡한 비동기 I/O 응용 프로그램을 싱글 스레드 JavaScript로 작성하여 결과물의 실행 속도와 개발 편의성 측면에서 좋다는 것이 Node.js의 근간을 이루는 개념이며, CPU의 높은 연산력을 요구하는 프로그램을 Node.js로 짜면 영 좋지 않은 성능이 나온다. (나무위키 발췌)

node.js 퍼포먼스 우수  
실제 기업들의 유지 케이스   
넷플릭스 : 자바->노드 => 프론트의 퍼포먼스가 올라감 페이지로딩시간이 몇배로 줄어듬
트렐로 : 동시에 일어나야하는 호출이 많음 실시간으로 스케줄 업데이트 -> nodejs사용
페이팔 : 서비스의 프로토타입을 둘로 나눔  
자바:5명 노드js:2명 자바팀에 퍼포먼스를 금방 따라잡음
퍼포먼스 : 생산성적인 측면에서 장점
개발속도 퍼포먼스 큰서비스를 운영하기에도 문제가 없음
Thread란?