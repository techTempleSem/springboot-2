# annotation

- @RestControllerAdvice: 예외가 일어난 곳을 감지함
- @ExceptionHandler: 어떤 예외를 잡을지 설정함

컨트롤러에 @ExceptionHandler를 달면 먼저 처리됨. controllerAdvice로 전달되지 않음

@RestControllerAdvice(basePackages = "com.example.exception.controller") : 해당 패키지의 에러는 이 클래스에서 잡겠다.

basePackageClasses로 클래스 기준으로 잡을 수 있다.

annotation단위로도 가능하다.