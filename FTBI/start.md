### Builder.io 를 이용해서 Figma로 만든 페이지 code로 변환

#### 절차

1. Figma에 Builder.io Plugin 설치
![](https://github.com/teemo75/sw_black/blob/master/FTBI/image/2025-04-10%2017%2058%2034.png)

2. Figma Contents를 Export
   ![](https://github.com/teemo75/sw_black/blob/master/FTBI/image/2025-04-10%2017%2058%2058.png)

3. Converting
   ![](https://github.com/teemo75/sw_black/blob/master/FTBI/image/2025-04-10%2017%2059%2012.png)

4. 잘 된 것 선정
   ![](https://github.com/teemo75/sw_black/blob/master/FTBI/image/2025-04-10%2018%2000%2051.png)

5. View Code in Builder
    ![](https://github.com/teemo75/sw_black/blob/master/FTBI/image/2025-04-10%2018%2001%2009.png)

6. Generated Code
    ![](https://github.com/teemo75/sw_black/blob/master/FTBI/image/2025-04-10%2018%2001%2043.png)

7. Profit!!


#### 장점
- 클릭 몇번으로 피그마 화면을 코드로 그럴싸하게 만들어줌
- 테스트 코드도 작성해줌
![](https://github.com/teemo75/sw_black/blob/master/FTBI/image/2025-04-10%2019%2042%2019.png)
- 코드를 만든 이후에 추가 질의를 통해서 코드 변경이 가능함
  - 처음에 Option API Component로 되어 있는 것을 Composition API Component로 변경(react 생각하고 함수형으로 바꿔달라고 그랬는데 철썩같이 알아들은 LLM...)
![](https://github.com/teemo75/sw_black/blob/master/FTBI/image/2025-04-10%2019%2041%2023.png)

#### 못해본거
- Code Output을 설정할수 있는데 Quality로 하면 뭐 많이 좋아진다고는 하는데 공짜로 쓰는거라 그런지 화면이 너무 복잡하다고 안해줌
![](https://github.com/teemo75/sw_black/blob/master/FTBI/image/2025-04-10%2019%2041%2041.png)


#### 단점
- 그래도 그냥 쓸수는 없고 확인과 수정이 필요함
- 외부 LLM 연계인거라서 개발에 쓰기는....
  - Figma는 외부에서 접속이 가능해서 한번 해볼까 했지만 차마....
