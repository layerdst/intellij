## 단축키
- 자동 구문 선택
  - **Ctrl+w**
  ```java
  String dd = "|dd";
  ```
  - 한번 입력시 **dd** 선택
  - 두번 입력시 **"dd"** 선택
  - 세번 입력시 **String dd = "dd"** 선택
    
- 자동 타입 변수명 생성
  - **Ctrl + Alt + V**
  ```java
  "dd"
  String dd = "dd
  ```
 
- **세미콜론 자동 생성**
  - **Ctrl + Shift + Enter**
  ```java
  String ddd = "dd"
  String ddd = "dd";
  
  for()
  for(; ; ;)
  ```
- **생성자, 메소드, 오버라이드 Generator**
  - **Alt + i**
  ```java
  public class C{
    String dd;
  }
  
  public C(String dd){
    this.dd = dd;
  }
  
  public String getDd(){
    return dd;
  }
  
  ```
- **다중커서**
  - **각 줄마다 공통 구문 선택시 : Alt + j ... j** 
    - 각 줄마다 공통 구문 앞뒤에서 다중커서를 하고 싶을때 사용하는 방법임
    ```java
    System.out.|println(); // println의 문구에 커서가 위치할때 Alt + j 누르면 println 이 선택 
    System.out.|println(); // j 를 추가로 입력시 아랫줄 println
    System.out.|println(); // j 를 추가로 입력시 아랫줄 println
    System.out.|println(); // j 를 추가로 입력시 아랫줄 println 
    ```
  - **각 줄마다 상이한 구문에 다중커서를 적용할때 : Alt + Shift + Mouse<left>**
    - 각 줄마다 원하는 위치에 해당 단축키를 누르면 됨
    ```java
    |System.out.println(); 
    System.out.|println(); 
    ```
