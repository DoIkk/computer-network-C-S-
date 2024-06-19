# 사칙연산 서버-클라이언트 시스템

## 클라이언트
1. 사용자로부터 사칙연산 수식을 텍스트로 입력받는다.
2. 입력된 수식을 서버로 전송한다.
3. 서버로부터 전송된 연산 결과를 출력한다.
4. 만약 서버로부터 에러 메시지가 전송된 경우, 이를 출력한다.

## 서버
1. 클라이언트로부터 수식을 텍스트로 수신한다.
2. 수식을 해석하여 연산을 수행한다.
   - 수식의 형식이 올바르지 않은 경우, 에러 메시지를 생성한다.
3. 연산 결과 또는 에러 메시지를 클라이언트로 전송한다.

## 예시 시나리오

### 클라이언트 입력
