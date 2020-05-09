# ***String & Stringbuffer & StringBuilder***
## **String**
**String** 클래스의 객체는 불변하다. 한번 생성되면 , 할당된 메모리 공간이 변하지 않는다. 단순히 읽어가는 조회연산에서 빠르게 읽을 수 있다는 장점이 있다. String 클래스는 문자열 연산이 적고, 자주 참조(조회)하는 경우에 사용하는 것이 좋다. 
<Mult-thread>환경에서 신경쓸 것이 없어서 좋다. 

<br>

## **StringBuilder & Stringbuffer**

**StringBuffer** 는 멀티쓰레드 환경에서 Synchronized 키워드가 가능하므로 동기화가 가능하다. 하지만 **StringBuilder**는 동기화를 지원하지 않는다. 
StringBuffer는 동기화를 고려하지 않아, single - thread 환경에서 연산처리가 빠르다. 

<br>


* * * 
