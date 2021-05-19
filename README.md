  # Introduction
  부트스트랩을 이용한 반응형 웹 페이지 제작

  <br />

  # Stack
  - HTML5
  - CSS3
  - Bootstrap

  <br />

  # 구현 기능
  - 반응형 웹 페이지 구현
  - carousel (이미지 슬라이드) 기능 구현
  - 부트스트랩 그리드 시스템을 이용하여, 각 디바이스 크기에 따라 한 행에 보이는 개수 조절

  <br />

  # > 기억하고 싶은 코드
  - margin 값을 auto로 설정하면 웹 브라우저가 자동으로 설정한다.

  - 수직 가운데 정렬 <br />
    info 요소를 수직으로 가운데 정렬하기 위해, 바로 앞에 빈 div 박스를 만들고 아래 스타일을 지정해준다.
    ```html
    <div class="container">
      <div class="helper"></div><div class="info">
        <h3>title</h3>
        <p>description</p>
      </div>
    </div>
    ```
    ```css
    .helper {
      display: inline-block;
      height: 100%;
      vertical-align: middle;
    }

    .info {
      display: inline-block;
      vertical-align: middle;
    }
    ```
    
  - 부트스트랩 그리드 시스템 ⭐️한 행이 12개의 열로 나누어짐⭐️<br />
  small size 일때는 한 행에 1개, medium 일때는 한 행에 2개, large size 일때는 한 행에 3개, extra large size 일때는 한 행에 4개가 보이게 하고 싶다면
    ```html
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-6 col-lg-4 col-xl-3"></div>
      </div>
    </div>
    ```

  <br />

  # Reference
  해당 프로젝트는 코드잇 강좌 프로그램에 있는 실습 과제입니다.