# layout_3 - 반응형 웹 레이아웃 유형 1
## * 웹 사이트의 크기에 따라 색깔과 글이 변경된다.

### 기본
![1](https://user-images.githubusercontent.com/37132897/166245443-43739a9c-2559-4373-b276-cb40b8818077.JPG)

### /* 화면 너비가 0 ~ 1280px : 데스크탑 */
![2](https://user-images.githubusercontent.com/37132897/166245453-d5c4e461-bbfb-4939-9464-65071d2f2e16.JPG)

### /* 화면 너비가 0 ~ 1024px : 데스크탑 */
![3](https://user-images.githubusercontent.com/37132897/166245460-02c3d1e9-5373-434a-bddf-48777227a868.JPG)

### /* 화면 너비가 0 ~ 960px : 노트북 */
![4](https://user-images.githubusercontent.com/37132897/166245468-6547cfe5-60a0-485d-8a78-117bd8d900ce.JPG)

### /* 화면 너비가 0 ~ 768px : 타블렛 */
![5](https://user-images.githubusercontent.com/37132897/166245475-b891afe3-d96f-4f40-bb35-7f8ec8e0c479.JPG)

### /* 화면 너비가 0 ~ 576px : 모바일 */
![6](https://user-images.githubusercontent.com/37132897/166245484-88a02957-e697-467e-834a-b8cd170674f5.JPG)


### 미디어 쿼리 반응형 설명
미디어 쿼리 : 화면 크기에 따른 각각의 속성 값을 지정하여, 여러가지 화면을 구성하는 기술
미디어 쿼리 쓰는법 : @media only all and (조건문) {실행문}
- @media : 미디어 쿼리가 시작됨을 표시
- only : 미디어 쿼리 구문을 해석하라는 명령어 (생략가능)
- all : 미디어 쿼리를 해석해야 할 대상을 나타냄 (생략가능)
  - all : 모든 미디어 유형에서 사용할 CSS를 정의
  - print : 인쇄 장치에서 사용할 CSS를 정의
  - screen : 컴퓨터 스크린에서 사용할 CSS를 정의
  - aural : 화면을 읽어 소리로 출력해주는 장치에서 사용할 CSS를 정의
  - tv : TV에서 사용할 CSS를 정의
  - handheld : 손에 들고 다니는 장치를 사용할 CSS를 정의
  - projection : 프로젝트를 위해 사용할 CSS를 정의
