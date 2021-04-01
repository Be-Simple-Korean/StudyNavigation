# StudyNavigation
* 1. 프래그먼트 생성
* 2. 네비게이션 폴더 및 파일 생성
* 3. 네비게이션 파일에 프래그먼트 가져오기
## 화면 전환
* 1. 네비게이션에서 연결
   * 네비게이션 리소스 파일에서 마우스로 드래그해서 프래그먼트끼리 연결 후
   * 화면 전환 될 부분에 코드 넣기
   ``` NavHostFragment.findNavController(현재 클래스명.this).navigate(드래그로 이벤트처리 된 이벤트id값);```
* 2. 코드로 연결
    * NavController 객체 생성
    ```NavController navController= Navigation.findNavController(this,NavHostFragmet 위젯 아이디값);```
    * 화면 전환 될 부분에 코드 넣기
     ```navController.navigate(네비게이션에 추가된 프래그먼트 id값); ```
