# 2022_Summer_School
git hub 원격지 저장 활용 시험
## git hub 원격지 저장 활용 시험
git hub test
### 2022.06.29.(Wen.)
github 실습


소속: 국립안동대학교, 지구환경과학과
===========================

1 여름 계절학기(공학커뮤니케이션)
===========================

#1.1 인공지능 개론
## 2.1  machine learning
### 3.1 Depp learning
#### 4.1 경사하강법
##### 5.1 선형회귀

2BlockQuote
> This is a first blockqute.
> > This is a second blockqute.
> > > This is a third blockqute.


순서가 있는 목록(번호 사용)
1. 첫번째
2. 두번째
3. 세번째

순서가 없는 목록(글머리 기호 사용: *, +, - 사용)

* Blue-1

   * Green-1
  
     * Red-1

+ Blue-1

  + Green-

    + Red

- Blue

  - Green

    - Red


List

순서가 없는 목록(혼합 사용)

* 1st Stage

  - 2nd Stage
  
    + 3rd Stage
     
      + 4th Stage

2022/06/21(화) 누리호 발사 성공

          세계에서 7번째 우주 강국
 
누리호 성공 축하!!!!

2022/06/21(화) 누리호 발사 성공
세계에서 7번째 우주 강국
누리호 성공 축하!!!! 


      e_tot=0
      e_tot=0
      for x in range(1, 101):
          if x % 2 ==0: e_tot += x
          else: o_tot += x
      print('1 - 100 까지 짝수 합 : {0}, 홀수 합 : {1}' .format(e_tot,o_tot)}


Code Block Method 1 
# 이용방법
  
    <pre>
    <code>
    class Car {
      private String modelName;
      private int modelYear;
      private String color;
      private int maxSpeed;
      private int currentSpeed;

      Car(String modelName, int modelYear, String color, int maxSpeed) {
        this.modelName = modelName;
        this.modelYear = modelYear;
        this.color = color;
        this.maxSpeed = maxSpeed;
        this.currentSpeed = 0;
      }
    }
   </code>
   </pre>


## “ ‘ ‘ ‘ “ 이용

       ```
       import React from 'react';

       function MyComponent(props) {
        if (props.isBar) {
         return <div>Bar</div>;
        }

        return <div>Foo</div>;
       }
      
       export default MyComponent;
       ```

### Code Block Method 3

     ``` js
     import React from 'react';

     function MyComponent(props) {
      if (props.isBar) {
       return <div>Bar</div>;
      }

      return <div>Foo</div>;
     }

    export default MyComponent;
    ```

#### Draw line

  * * *
  ***
  *****
  - - -
  ---------------


##### Link
--------------
*참조 링크

// examle

Google Link: [google][googlelink]

[googlelink]: https://google.co.uk "Let's Go Google"


*외부 링크

// examle

[Google](https://google.co.uk)

 
*자동 링크

// examle

Google Homepage: https://google.co.uk 

Naver Homepage: <https://naver.com>


7. Emphasis
-------------

// examle

이텔릭체 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용

두껍게는 ** 별표(asterisks)* 혹은 __언더바(underscore)__를 사용

**_이텔릭체_와 두껍게**를 같이 사용할 수 있음

취소선은 ~~물결표시(tilde)~~를 사용


8. Images
-------------

![alt text](image url "image Title")

// examle 1
![Street](aa.jpg "aa")

// examle 2
Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

크기 조절
// examle 3

<img src="aa.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<img src="aa.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>


9. Footnotes
-------------

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2]. 

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces. 
  This allows you to have a footnote with multiple lines. 
[^note]:
   Named footnotes will still render with numbers instead of the text but allow easier identification and linking. 
   This footnote also has been made with a different syntax using 4 spaces for new lines.


10. Table
-------------

// example 1

| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 | |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 | |
| `fixed` | 브라우저 창을 기준으로 배치 | |

// example 2

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


11. 줄바꿈

*일반 텍스트 문장: 문장 끝에 공백 2번(스페이스 2번)하면 줄 바꿈이 됨.
테이블 내에서나 일반적인 경우: <br> 사용

// example 1
예를 들어, 지금    
공백 2번 만들어서 지금과 공백 사이에서 줄 바꿈이 된다.

// example 2
안녕하세요. <br>반갑습니다. 줄이 바뀌었어요.


