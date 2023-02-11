- ### JVM의 메모리 구조 

  - 응용 프로그램이 실행 되면, JVM은 시스템으로부터 프로그램을 수행하는데 필요한 메모리를 할당 받는다

  - JVM은 메모리를 용도에 따라 나눈다.

    1. 메서드 영역(Method Area : 메서드 영역인데 클래스가 저장됨)

       - 프로그램 실행 중 어떤 클래스가 사용되면, 그 클래스에 대한 정보(클래스 데이터)를 이 곳에 저장한다. 
       - 해당 클래스의 클래스 변수도 이 영역에 생성된다. 

    2. 힙 영역(heap)

       - 프로그램 실행 중 생성되는 인스턴스가 생성되는 공간이다.
       - 인스턴스 변수도 이곳에서 생성된다. 

    3. 호출 스택 (call stack / execution stack)

       - 메서드의 작업에 필요한 메모리 공간이다.
       - 메서드가 호출될 때, 그 메서드에 대한 메모리 공간이 생성된다.
       - 호출된 메서드가 작업을 수행하는 동안 호출 스택에서 호출된 메서드의 지역변수들과 연산의 중간결과 등을 저장한다.

        

------

출처 : [자바의 정석](https://book.interpark.com/product/BookDisplay.do?_method=detail&amp;sc.prdNo=249927409&amp;gclid=Cj0KCQiA8t2eBhDeARIsAAVEga0wHKonUHZDG3WiedMCF_l7_V41JOwONiRYfFdaTGasByaYdOhwLV0aAmyrEALw_wcB)

