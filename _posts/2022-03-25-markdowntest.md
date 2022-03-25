

마크 다운 문법 정리

// 링크정리 

[google](http://google.com)

Link: [Google][googleLink]  [googleLink]: https://www.google.com "Go google"





// 타이틀

# 제목

## 제목 2

### 제목 3

#### 제목4

##### 제목5

###### 제목 6





//  인용 문 (블럭)

> 첫번째 블록
>
> > > 두번째 블록
> > >
> > > > > > > 세번째 블록
> > > > > > >
> > > > > > > 



// 목록 - list

// 1. 2. 3. 이렇게 번호를 적어도 되지만, 순서대로 번호를 매겨서 표시됩니다.

1. 첫번째 아이템

   ​	1. 하위 아이템

   	4. 하위 아이템 

2. 두번재 아이템

1. 세번째 아이템





// 순서없는 목록
순서가 없는 목록은 기호(*, -, +)를 사용해 표시합니다. 각 기호를 혼합해서 사용해도 무방합니다. *(표시하는 방식은 Viewer 마다 차이가 있습니다)*

+ 첫번째 아이템

  -1-1  item

  -1-2 item2

  -1-3 item3

  

+ 두번째 아이템

​		-1-1  item

​		-1-2 item2

​		-1-3 item3



// 강조 - Emphasis

 '**','_','~'기호를 이용하며, 서로 중첩해 사용할 수 있다.*

본문에 특정 문자에 서식(볼드, 이텔릭, 밑줄, 취소선)을 적용해 강조할 수 있습니다.



*이텔릭체*

**볼드체**

__볼드체2__

***볼드+이텔릭체***

<u>밑줄</u>

~~취소선~~

**~~볼드+취소~~**





//  코드

```java
public class Main{

    public static void main(String[] args) throws Exception {
        for (int i = 0; i < 5; i++) {
            for (int j = 0; j <= i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}

```



// 이미지 파일 넣기( typora 툴을 이용하자)

![cat-6977096_1920](C:\Users\werz3\Downloads\cat-6977096_1920.jpg)