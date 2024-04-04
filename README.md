# <span id='top'>엑셀함수 문제풀이 시뮬레이터 프로젝트 EFSS <img src = "![susu](https://github.com/24-gitTest/demo-repository/assets/99867931/238c60c2-72d5-43ba-a52a-d2fb0513b7f3)"/></span>

![image](https://github.com/an1413/excelQuiz/assets/87430624/972743e8-efb7-4c9f-ad1b-3c232814281a)


> 📎 <a href=''>배포 URL</a> <br/>
>
> <br/>

<br/>

## 📃 목차 (클릭 시 해당 목차로 이동합니다.)
- [🎨 프로젝트 소개](#1-프로젝트-소개)
  
- [🛠 개발 환경 및 기술 스택](#2-개발-환경-및-기술-스택)

- [📃 페이지 캡쳐](#4-페이지-캡쳐--제목-클릭-시-해당-기능-상세-설명으로-이동됩니다-)

- [🗂 프로젝트 구조](#5-프로젝트-구조)

  <br/>
  <br/>

## 1.🎨 프로젝트 소개

** EFSS는 시뮬레이터를 이용한 엑셀 함수 문제 풀이 웹사이트입니다. **

#### 기획 의도

- 엑셀함수 문제풀이를 위한 많은 방법 중에서 개인의 스타일에 맞는 것을 찾기위한 시간의 비용을 절약한. <br/>
- 어떤 기능이 있으면 좋을지 미래의 사용자들에게 고려중인 기능 중 어떤 기능들이 선호도가 높은지 확인해 보았다.  <br/>
- 엑셀 시뮬레이터, 엑셀 함수 관련 문제 풀기, 엑셀의 기본적인 기능 설명이 높은 선호도를 보였다. <br/>
![image](https://github.com/an1413/excelQuiz/assets/87430624/0e4da30d-acba-4df8-b6e3-9d8597ceaef9)
![image](https://github.com/an1413/excelQuiz/assets/87430624/e210ceed-c017-4c41-9860-ebb1453fdd56)

<br/>

<p align="right"><a href="#top">TOP 🔼</a></p>

<br/>

## 2.🛠 개발 환경 및 기술 스택

### 3-1. 개발 환경

- IDE : Visual Studio Code 1.74.2
- OS : Windows 10

<br/>

![image](https://github.com/an1413/excelQuiz/assets/87430624/69b1ba4d-5a51-4e15-8a2d-92bae4580f8c)                                                                                                                                                                    
<p align="right"><a href="#top">TOP 🔼</a></p>

<br/>

## 3.📆 개발 일정

#### 🔥 2023-09-21 ~ 2023-12-10

<br/>

<p align="right"><a href="#top">TOP 🔼</a></p>
<br/>


## 4.📃 페이지 캡쳐 ( 제목 클릭 시 해당 기능 상세 설명으로 이동됩니다. )

![image](https://github.com/an1413/excelQuiz/assets/87430624/66c82ce7-b3b1-4ec8-98cb-9fada3e4a740)
![image](https://github.com/an1413/excelQuiz/assets/87430624/3837f0d9-0ad2-426d-8948-30f896c97edd)
![image](https://github.com/an1413/excelQuiz/assets/87430624/d30a3480-4247-4da5-82c0-88d941c51e6b)
![image](https://github.com/an1413/excelQuiz/assets/87430624/7224d299-c733-4c84-8ec9-e8c4c09f8a9f)
![image](https://github.com/an1413/excelQuiz/assets/87430624/28f30595-dc89-4ebb-a22c-c144fbc8e320)
![image](https://github.com/an1413/excelQuiz/assets/87430624/feefc1ea-37ae-42e4-b2b7-a7dd992cbf0c)

<p align="right"><a href="#top">TOP 🔼</a></p>

<br/>


## 5.🗂 프로젝트 구조
- `src/components/` : 서비스에서 사용하는 컴포넌트 (공통 컴포넌트, 공통 레이아웃)
- `src/commons/` : 공통컴포넌트 중 UI와 관련된 파일
- `src/context/` : 전역 데이터를 공유하기 위해 정의한 Context 파일
- `src/hooks/` : 재사용을 위해 분리한 Custom Hook
- `src/img/` : 서비스에서 사용하는 에셋 파일 (폰트, 아이콘, 이미지)
- `src/library/` : 사용을 편리하게 하거나 재사용을 줄이기 위해 만든 함수
- `src/pages/` : 컴포넌트를 조합하여 만든 페이지
- `src/routes/` : 페이지 라우팅을 위한 파일

```
📦susuMarket
 ┣ 📂public
   ┗ 📜index.html
 ┣ 📂src
   ┣ 📂components
   ┃ ┣ 📂commons
   ┃ ┃ ┣ 📂Back
   ┃ ┃ ┣ 📂Button
   ┃ ┃ ┣ 📂DataInput
   ┃ ┃ ┣ 📂ErrorMessage
   ┃ ┃ ┣ 📂Footer
   ┃ ┃ ┣ 📂Hint
   ┃ ┃ ┣ 📂HomeButton
   ┃ ┃ ┣ 📂Level
   ┃ ┃ ┣ 📂List
   ┃ ┃ ┣ 📂NextProb
   ┃ ┃ ┣ 📂PrevProb
   ┃ ┃ ┣ 📂Reset
   ┃ ┗ ┗ 📂UserInput
   ┣ 📂context
   ┣ 📂db
   ┣ 📂hook
   ┣ 📂img
   ┣ 📂library
   ┃ ┣ 📜checkWebpSupport.js
   ┃ ┣ 📜customAxios.js
   ┃ ┣ 📜imgCompression.js
   ┃ ┗ 📜imgValidation.js
   ┣ 📂pages
   ┃ ┣ 📂Beginer
   ┃ ┣ 📂Dictionary
   ┃ ┣ 📂Expert
   ┃ ┣ 📂FunctionKnow
   ┃ ┣ 📂FunctionProblem
   ┃ ┣ 📂HomeFeed
   ┃ ┣ 📂Intern
   ┃ ┣ 📂Login
   ┃ ┣ 📂Signup
   ┣ 📂routes
   ┣ .prettierrc.json 
   ┣ 📜App.js
   ┣ 📜GlobalStyle.js
   ┗ 📜index.js
```

<br/>
<p align="right"><a href="#top">TOP 🔼</a></p>
<br/>
