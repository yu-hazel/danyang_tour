# 🌳 단양관광 공식 홈페이지 리디자인

기존 단양관광 홈페이지 UI/UX의 정적인 분위기를 개선하고자 기획하였습니다. <br>
처음으로 API를 활용한 프로젝트이며, 기본 퍼블리싱을 포함하여 반복적인 하드 코딩을 최소화하는 데 목적을 둔 서브 페이지를 함께 구현하였습니다. <br>
필요에 의해 JSON을 직접 만들어 사용해 보는 경험과 함께 같은 레이아웃에 다른 내용이 들어가는 페이지 구현 로직을 이해하게 되었습니다.

<br>

## ✋🏻 개요

- 프로젝트 기간 : 2024.05.14 ~ 2024.06.16
- 기여도 : 100% (개인 프로젝트
- [배포 주소](https://yu-hazel.github.io/portfolio/tour/html/danyang_tour.html)

<br>

## 🥞 사용 기술

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

<br>

## 🪼 라이브러리

- Swiper

<br>

## 📟 사용 API

- 충북관광 API
- 한국관광공사 API

<br>

## 🖌️ 와이어프레임 (Figma 디자인보드)

![image](https://github.com/user-attachments/assets/08546e7f-2bb1-4190-ab89-18f997b2e260)

<br>

## 📺 미리 보기

![dan01](https://github.com/user-attachments/assets/05af7b7c-505b-43e1-ba77-0a22662b2cdb) | ![dan02](https://github.com/user-attachments/assets/2920b6b9-5f08-4862-afec-a4bc6aa5bf83)
--- | --- |


![dan03](https://github.com/user-attachments/assets/460d4e96-ecc7-463e-bb7e-818ada27b566) | ![dan04](https://github.com/user-attachments/assets/f4053d21-9975-4ef6-aca8-cf9a2f7f984e)
--- | --- |


![dan_sub01](https://github.com/user-attachments/assets/ae9b30a6-7e30-4115-a479-a3dfc649032a) | ![dan_sub02](https://github.com/user-attachments/assets/1ac7bbb1-28b7-4b9d-8d4a-5cecc9044a76) | ![dan_sub03](https://github.com/user-attachments/assets/4bd5dabe-33d4-4aa0-9373-be57447b59be)
--- | --- | --- |

<br>

## 🗒️ 구현 페이지

- [메인 페이지](https://yu-hazel.github.io/portfolio/tour/html/danyang_tour.html)
  - [단양팔경](https://yu-hazel.github.io/portfolio/tour/html/danyang_sub.html?fetch=81)
  - [문화재](https://yu-hazel.github.io/portfolio/tour/html/danyang_sub.html?fetch=he1)
  - [관광지](https://yu-hazel.github.io/portfolio/tour/html/danyang_sub.html?fetch=h3)
  - [체험마을](https://yu-hazel.github.io/portfolio/tour/html/danyang_sub.html?fetch=a1)


### ✔️ 서브페이지 구현 방식

메인 페이지(danyang_tour.html)에서 서브 페이지(danyang_sub.html)로 이동할 때, url에 `쿼리 파라미터`가 붙어 이동하게 코드를 작성하였습니다. <br>
쿼리 파라미터에 따라 보여주는 상세 페이지가 달라지지만, 레이아웃이 같은 32개의 페이지를 전부 하드코딩하는 방식이 아닌 반복문으로 처리하여 코드 작업의 공수를 줄이고 전체 파일의 크기를 줄이게 되었습니다.

<br>

## 🖼️ 디바이스별 반응형 UI

<div>
  <img src="https://github.com/user-attachments/assets/cf6f1b4f-ef73-4059-961b-0e1f5637a40f" width="40%" align="top">
  <img src="https://github.com/user-attachments/assets/f8abf5da-3694-4231-8050-996367ab3529" width="33%" align="top">
  <img src="https://github.com/user-attachments/assets/684aea78-ecdf-4138-bd95-8169e45e2424" width="25%" align="top">
</div>
<br>
<div>
  <img src="https://github.com/user-attachments/assets/600aee35-251c-433d-b1c5-bd89065683ac" width="40%" align="top">
  <img src="https://github.com/user-attachments/assets/e0d83711-d63e-4058-b81d-a54e8ae3b692" width="33%" align="top">
  <img src="https://github.com/user-attachments/assets/4f83ba5e-d00b-48dd-81e7-87a27141e0ef" width="25%" align="top">
</div>








