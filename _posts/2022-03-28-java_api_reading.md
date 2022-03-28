# 자바 문서 api 보는 방법

[자바 API](https://docs.oracle.com/javase/7/docs/api/)



### <u>문서상에서 class안에 consturtors 가 존재하면 인스턴스 생성이 가능하다 </u>

```java
// new 는 인스턴스를 생성한다
Printwriter p1 = new PrintWriter("result.txt");

// 문서상 클래스안에 consturtors가 없으면 인스턴스 생성불가
// 인스턴스를 생성하면 재 사용면에서 편리하다

ex) 
    Printwriter.write("result1.txt","hello1");
	Printwriter.write("result2.txt","hello1");
	Printwriter.write("result3.txt","hello1");
	Printwriter.write("result4.txt","hello1");
						:
문제 : 내가 result4.txt파일 내용을 hello에서 hi로 바꾸고 싶다   
해결방안 Printwriter.write("result4.txt","hi"); 로 바꾸어야 된다
    
<인스턴스화 장점>    
하지만 인스턴스화를 하여 진행하면
Printwriter p1 = new PrintWriter("result4.txt");
인스턴스를 생성해 놓고
p1.write("hi"); 만 진행하면 편리하게 수정이 가능하다.
    
    
    
    
    
    
    


```









