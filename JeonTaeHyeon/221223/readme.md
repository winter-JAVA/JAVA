### 221222

리터럴 : 프로그래밍 언어에서 미리 정의해놓은 값의 형태

---
pakage : class를 묶는 폴더 개념
>com.sec01.literal 과 같은 형식으로 말들면 하위 폴더 생성됨
>
>패키지 작성 요령 com(회사 성격).greedy(회사명),variable(프로젝트 이름) 과 가팅 보통 3level 이상으로 작성함.
---

```java
package com.sec1.literal;

public class Application2 {

	public static void main(String[] args) {
		//1-1 숫자와 숫자 연산
		System.out.println(123+456);
		
		//1-2 실수와 실수 연산
		System.out.println(1.23+1.34);
		
		//1-3 정수와 실수 연산
		//정수와 실수의 연산결과는 실수
		System.out.println(123+0.5);
		
		//2-1 문자의 연산
		System.out.println('a'+'b');
		
		//2-2 문자와 정수의 연산
		System.out.println('a'+1);
		//2-3 문자와 실수의 연산
		System.out.println('a'+0.5);
		
		//3 문자열
		// 문자열은 +연산만 사용 가능
		System.out.println("hello"+"world");
		System.out.println("hello"+123);
		
		//4 논리값 연산은 안됩니다.
		
	}

}
```
