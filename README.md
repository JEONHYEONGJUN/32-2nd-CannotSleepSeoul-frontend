# 잠못자 서울 프로젝트 Front-end 소개

- 숙박 업소 예약 사이트 [마이리얼트립](https://www.myrealtrip.com/) 클론 프로젝트
- 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.
- 저는 메인페이지와, 예약페이지 전체를 담당했습니다. 


## 메인, 예약 담당이유

- 메인페이지에서는 라이브러리 slick slider를 이용한 carousel을 구현해보고 싶었고,
- 예약페이지에서는 카카오톡 api를 통해 정보를 전달받는 과정과, 모달창을 구현해보고 싶었습니다. 

## 적용 기술 및 구현 기능

### [유튜브 링크](https://www.youtube.com/watch?v=KUcVnyKOoY8)

### 적용 기술

#### Front-End

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![styled-components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)


### 구현 기능

- Main

   ![01-main](https://user-images.githubusercontent.com/73154157/169675198-cd531c6c-dd87-4dec-90ec-9834c03a7070.gif)

  라이브러리 slick slider를 이용하여 캐러셀기능을 구현했습니다. 각각의 캐러셀마다 측면에 블러기능을 추가했고, 맨 첫 페이지와 마지막페이지에서는 끝부분에 블러가 풀리게 처리했습니다.
 
- Reservation

   ![07-reservation](https://user-images.githubusercontent.com/73154157/169675212-436ead24-8c58-4590-95eb-46639fc34e29.gif)
  
  position : stickey 기능을 통해, 우측에 결제정보를 스크롤에 따라 내려오도록 고정시켰습니다. 결제하기 버튼을 누르면, 모달창이 뜨면서 결제정보를 입력하게 하였습니다.

## Reference

이 프로젝트는 마이리얼트립 사이트를 참조하여 학습목적으로 만들었습니다.
실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
