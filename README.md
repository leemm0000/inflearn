
![인프런](https://github.com/user-attachments/assets/011c9ea4-f53a-4950-a0f6-77e1822d1d07)

# 🍃Inflearn 리디자인 퍼블리싱 프로젝트
기존 인프런(Inflearn) 웹사이트를 기반으로, 개인의 시각에서 디자인을 재해석하고 퍼블리싱 구조를 재구성한 클론 프로젝트입니다.
</div>

## 작업자 : 
이민
<br><br>

## 📅 제작기간 :(5일)
<br><br>

 ## ✨ 도메인

```

📦 #inflearn
├─ css/                 # 컴파일된 CSS 파일들이 저장되는 폴더
├─ html/                # HTML 관련 파일들이 들어있는 폴더
├─ images/              # 프로젝트에 사용되는 이미지 파일들이 저장된 폴더
├─ include/             # 공통으로 포함되는 파일들이 저장된 폴더(header, footer) 
├─ script/              # 자바스크립트 파일들이 저장된 폴더(custom,swiper) 
├─ fonts.scss           # 웹 폰트 관련 Sass 파일
├─ index.html           # 메인 HTML 파일
├─ reset.scss           # CSS 초기화 스타일을 정의한 Sass 파일
├─ responsive-mobile.scss # 모바일 반응형 스타일용 Sass 파일
├─ responsive-tablet.scss # 태블릿 반응형 스타일용 Sass 파일
├─ style.scss           # 메인 스타일 시트(Sass)
├─ variables.scss       # Sass 변수들이 정의된 파일


```
 
<br><br><br>



## ⭐️ 프로젝트 목적
실무 중심의 퍼블리싱 연습을 위해 실존 사이트의 구조와 인터랙션을 분석하고 구현
반응형 레이아웃, 모듈화된 컴포넌트, 접근성 등을 고려한 웹 구조 설계
HTML, CSS, JavaScript 기반의 정적 웹사이트 구현 경험 강화
<br><br>

### 리뉴얼 방향과 디자인 기획
인프런의 전반적인 UI/UX를 개인 스타일로 재디자인
헤더/푸터 모듈화 (include 방식 적용)
Swiper.js, 모달, 드롭다운, 아코디언 등 다양한 인터랙션 구현
반응형 웹 구현 (PC / 모바일 대응)


<br><br>

 

 
<br><br><br>

# 📝 페이지 구성
![인프런 00](https://github.com/user-attachments/assets/4e5f2aa3-838d-4b09-9c45-978e747150c4)
![인프런모바일01](https://github.com/user-attachments/assets/7455ef60-5b6e-484e-a8ad-a69b3ed6e68c)

## Header  
페이지 상단에 위치한 영역으로, 로고, 내비게이션 메뉴, 검색 아이콘 등이 포함되어 있습니다.  
사용자가 사이트를 탐색하는 데 필요한 주요 링크들을 제공합니다.  

### 헤더 반응형  
화면 너비가 768px 미만일 경우, 내비게이션 메뉴는 사라지고 햄버거 아이콘으로 대체됩니다.  
아이콘 클릭 시 측면 내비게이션 메뉴가 나타나도록 구성되어 있습니다.

---

## Footer  
페이지 하단 영역으로, 뚜레쥬르의 부가적인 서비스 정보를 확인할 수 있으며,  
제휴 사이트로 이동할 수 있는 링크도 포함되어 있습니다.

---
![인프런 01](https://github.com/user-attachments/assets/8a8690f6-04fa-43f2-9faa-a156d4c5eaae)

## 이벤트 배너  
접속 시 가장 상단에 노출되는 배너 이미지입니다.  
현재 진행 중인 이벤트나 공지사항 등을 사용자에게 알리는 용도로 활용됩니다.

---
![인프런 02 모달](https://github.com/user-attachments/assets/3d8b612d-7914-4aca-9a0f-98855a0bd4a0)

## 로그인 페이지 (모달)  
로그인 기능을 위한 모달창으로, 클릭 시 회원 로그인 페이지가 표시됩니다.

---

# 메인 페이지

## Section 1 - 메인 비주얼  
페이지에서 가장 먼저 보이는 슬라이드 영역입니다.  
현재 진행 중인 이벤트 배너를 배치하여 사용자가 빠르게 접근할 수 있도록 구성했습니다.

**반응형 디자인**  
화면 크기에 따라 슬라이드 구조와 배너의 배치가 조정됩니다.

---
![인프런 03](https://github.com/user-attachments/assets/a2bf596b-2552-4fdd-8290-59a3fa2e7526)

## Section 2 - 카테고리  
강의 카테고리별로 콘텐츠를 확인할 수 있는 섹션입니다.


---

## Section 3 - 강의 안내 슬라이드  
뚜레쥬르의 다양한 메뉴(강의 콘텐츠)를 소개하는 영역입니다.  
카테고리 탭 클릭 시 해당 콘텐츠 목록이 나타나며,  
오른쪽 메뉴 버튼 클릭 시 해당 정보가 왼쪽 영역에 표시됩니다.

---

## Section 4 - 베스트 강의 소개  
사용자가 특정 영역을 클릭하면 해당 콘텐츠가 확대되고, 나머지는 축소됩니다.  
시각적 흥미를 유도하며, 콘텐츠 집중도를 높입니다.



---

## Section 5 - 얼리버드 안내  
카운트다운 타이머와 안내 배너가 포함된 영역입니다.  
카운트다운은 실제로 동작하며, 얼리버드 이벤트 정보를 효과적으로 전달합니다.

---

## Section 6 - 블로그 글  
관련 블로그 글들이 카드 형태로 배치되어 있어  
사용자가 흥미 있는 콘텐츠를 탐색할 수 있습니다.

---

## Section 7 - 뉴스 기사  
뚜레쥬르 관련 뉴스 및 기사들이 모여 있는 섹션입니다.  
브랜드 소식이나 업데이트 정보를 전달합니다.

---

# 서브 페이지
![인프런 서브페이지 1](https://github.com/user-attachments/assets/cee98ab6-9bb5-4b8f-94fb-11e0683915b0)

## 강의 상세 페이지  
강의 커리큘럼, 상세 설명, 후기, 장바구니, 가격 비교 등  
사용자에게 필요한 모든 정보를 제공하는 상세 콘텐츠 페이지입니다.

---
![인프런 서브페이지 2](https://github.com/user-attachments/assets/7923257b-c913-4db0-bc29-b6b0478e5f79)

## 카테고리 메인 페이지  
전체 강의 리스트를 확인할 수 있는 페이지입니다.  
카테고리별로 필터링하거나 원하는 강의를 탐색할 수 있습니다.

  

## ⚙️ 개발 환경  
- 사용 프로그램 : <img src="https://img.shields.io/badge/Vs code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/> <img src="https://img.shields.io/badge/figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>  
- 사용된 기술 :  
  <img src="https://img.shields.io/badge/html5-E34F26?style=flat-square&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/scss-1572B6?style=flat-square&logo=scss&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"> <img src="https://img.shields.io/badge/Swiper-6332F6?style=flat-square&logo=Swiper&logoColor=white">  <img src="https://img.shields.io/badge/Aos-1572B6?style=flat-square&logo=Aos&logoColor=white">

 
