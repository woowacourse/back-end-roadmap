# Logback

공식 사이트 : http://logback.qos.ch/

### 1) 개념 다지기

#### 📖 추천 도서

#### 📖 참고 자료

- [(Spring Boot)Logging과 Profile 전략](https://meetup.toast.com/posts/149)

#### 🎥 참고영상

- [스프링 부트 2.0 Day 11. 스프링 프로파일과 스프링 부트 기본 로깅](https://www.youtube.com/watch?v=h_VoxXhhNH0)

- [스프링 부트 2.0 Day 12. 커스텀 로그 설정 제공하기와 logback에서 스프링 프로파일 사용하기](https://www.youtube.com/watch?v=uVR2iBEb474)

- [스프링캠프 2015[A-3]: 스프링부트와 로깅](https://www.youtube.com/watch?v=o2-JaRD9qQE)

---

### 2) 면접 질문

---

### 3) 실습해보기

준비물

- 본인의 spring boot Project
  - 만약 없다면 아래의 url을 clone하여 테스트 진행부탁드립니다.
  - https://github.com/vsh123/springboot-study

#### Step1 : logback.xml 등록하기

- resources 하위에 `logback.xml`파일을 만들어 주세요.
  - 콘솔에 찍을 수 있는 `ConsoleAppender`를 만들어주세요. (이름은 자유입니다.)
  - 위의 appender를 이용한 logger를 만들어주세요.

#### Step2 : logback을 이용하여 logging찍어보기

- 본인이 만들 logger를 이용하여 아무 클래스에나 Logging을 설정해 주세요.

- 해당 메서드를 지나가면서 콘솔에 로그가 찍히는지 확인해주세요,

#### Step3 : Logger 분리 및 파일로 저장하기

- logger의 역할에 따라 다양하게 나누는 작업을 진행합니다.
  - RollingFileAppender를 이용한 appender 및 Logger를 생성해 주세요.
  - 해당 파일의 저장 위치를 설정하고 파일에 로깅이 잘 남는지 확인해주세요.

#### Step4 : appender 파일 분리하기

- console-appender와 file-appender를 분리하고 이를 include하는 형식으로 변경해 보세요.

```
위 모든 과정은 https://github.com/vsh123/springboot-study/tree/logback 에서 확인 가능합니다.

```
