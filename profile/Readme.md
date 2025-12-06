<div align="center">

# CarsCommunity  
### 자동차 커뮤니티 사이트

</div>

---


## 1. 프로젝트 개요

### 프로젝트명  
** CarsCommunity— 자동차 커뮤니티 & 튜닝 이미지 관리 플랫폼

### 프로젝트 기간  
2025년 11월 ~ 2025년 ing

### 프로젝트 목표
- 차량 관련 정보를 공유하고 소통할 수 있는 커뮤니티 제공
- 자동차 튜닝 이미지(2D/3D) 저장 및 관리 기능 제공 
- 사용자 간 댓글, 좋아요 등 상호작용 기능 제공  
- 파일 업로드·조회·관리 가능한 안정적인 백엔드 제공  

### 주요 타겟 사용자
- 자동차 튜닝을 좋아하는 일반 사용자  
- 자신의 차량 커스터마이징 이미지를 저장하고 싶은 사용자
- 차량 정보/팁/노하우를 공유하고 싶은 커뮤니티 유저 

---

## 2. 프로젝트 소개

### 프로젝트 배경
자동차 튜닝 유저들은 다양한 2D/3D 이미지, 차량 데이터, 파츠 정보를 저장하고 공유하려는 니즈가 높습니다. 하지만 이를 체계적으로 저장하거나 다른 사람들과 소통할 수 있는 환경은 부족했습니다.

#### 문제 상황
- 허위·과대 건강 제품 광고 증가  
- SNS·인플루언서 중심의 검증되지 않은 광고 확산  
- AI 기반 가짜 의사 영상·조작된 인터뷰 등 신종 광고 기법 증가  
- 건강기능식품 관련 오해 및 소비자 금전적 피해 증가  

#### 기존 서비스의 한계
- 광고 문구에 대한 AI 검증 기능 부재  
- 성분/효능 정보를 연계해 해석해주는 서비스 부족  
- 과대광고 판단 기준을 사용자가 직접 찾아 비교해야 함  
- 단순 정보 제공 앱은 존재하지만 “판단 + 근거 제공” 기능은 부족  

### 목표 정리
CarsCommunity는 다음 방향으로 개발되었습니다.
- AI 기반 허위·과장 가능성 자동 판단  
- MFDS 고시·개별인정 원료 기반 근거 중심 분석  
- 제품 성분과 기능성 정보의 자동 매핑  
- 사용자에게 신뢰성 있는 결과와 해석 제공  
- 모바일에서도 간편하고 빠른 검증 흐름 제공  

---

## 3. 기능 명세서 
<img src="./assets/기능흐름도.png" width="700">
<a href="https://www.notion.so/2a985bcdbd268049a3e5f97a80b1d204" 
   style="display:inline-block;padding:10px 20px;background:#007bff;color:white;border-radius:8px;text-decoration:none;font-weight:bold;">
    기능 명세서 보러가기
</a>

---

## 4. API 명세서

<a href="https://www.notion.so/1cb85bcdbd2680de96f0d3d09d546766" 
   style="display:inline-block;padding:10px 20px;background:#007bff;color:white;border-radius:8px;text-decoration:none;font-weight:bold;">
   API 명세서 보러가기
</a>

---

## 5. DB 명세서 
<img src="./assets/ERD.PNG" width="700">

---

## 6. 시스템 아키텍처 
<img src="./assets/시스템아키텍처(어플리케이션).png" width="700">

<img src="./assets/시스템아키텍처(CI , CD).png" width="700">

<img src="./assets/시스템아키텍처(nks).png" width="700">

---

## 7. 팀원 소개

| 이름 | 담당 |
|------|------|
| **김현수** | Backend Post, Email, user, jwt , file ,TestCode|
| **조현우** | Backend Car , Comment, Exception |

---

## 8. 기술 스택

| 영역                    | 기술                                                                                                                 |
| --------------------- | ------------------------------------------------------------------------------------------------------------------ |
| **Backend**           | Java 21, Spring Boot 3.4, Spring MVC, Spring Security, JWT, JPA, Validation, QueryDSL                              |
| **Database**          | MySQL 8, Redis(Set 기반 좋아요 관리 / 캐싱)                                                                                 |
| **File / Media**      | MultipartFile, UrlResource(2D/3D 파일 로드), FileProperties 경로 매핑                                                      |
| **Development Tools** | IntelliJ IDEA, Postman, Git & GitHub , Jenkins , Mook                                                       |




---

## 9. 문서 자료
[문서 보기](./assets/F_F%20제품%20소개서.pdf)

---

<div align="center">

🚗 CarsCommunity
“자동차 유저들이 서로 소통하고 튜닝을 즐기는 공간을 만듭니다.”

</div>
