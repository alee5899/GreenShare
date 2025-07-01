# 🌱 GreenShare 프로젝트  
**IoT 기기 연동 & 웹·앱 식물 커뮤니티 풀스택 개발**  
*(Python, Java/Spring, React, React Native)*  

---

## 📌 프로젝트 개요  

안녕하세요! GreenShare 프로젝트는 **스마트한 식물 관리와 커뮤니티를 위한 IoT 기반 풀스택 플랫폼**입니다.  
**식물 재배부터 사용자 간 소통까지** 모두 가능한 서비스를 구현했습니다.  

본 프로젝트는 IoT 기기를 통해 환경 데이터를 수집·제어하고,  
이를 웹과 모바일 앱에서 실시간으로 모니터링하며 사용자 간 커뮤니티 기능을 제공합니다.  
👉 **IoT 기기 제어는 팀원이 구현**하였으며, **웹/앱 연동 및 커뮤니티 기능은 제가 주도적으로 개발**했습니다.

- 🌡️ **IoT 기기 자동제어 시스템** (Python, Raspberry Pi – 팀원 구현)  
- 🖥️ **API 서버** (Java/Spring + MariaDB)  
- 🌐 **웹 커뮤니티** (React)  
- 📱 **모바일 앱** (React Native)  

---

## 🔗 레포지토리  

| 구분        | 기술 스택                  | 링크                                                        |
|-------------|---------------------------|-------------------------------------------------------------|
| 📱 App       | React Native               | [greenShareApp](https://github.com/PangJin97/greenShareApp) |
| 🌐 Frontend  | React                      | [greenShareFront](https://github.com/PangJin97/greenShareFront) |
| 🖥️ Backend   | Java/Spring + MariaDB       | [greenShareBack](https://github.com/PangJin97/greenShareBack) |

---

## 🌿 주요 기능  

## 🌿 주요 기능  

### 🌐 웹 (React) — **제가 주도적으로 개발한 부분**  
- 공지사항 게시판 CRUD 및 권한 처리  
- 공지사항 UI/UX 디자인  
- Q&A 게시판 CRUD 및 권한 처리  
- Q&A 게시판 UI/UX 디자인  
- 게시글 등록 시 React-Quill 에디터 적용  

### 📱 모바일 앱 (React Native) — **제가 주도적으로 개발한 부분**  
- 커뮤니티 페이지 제작 및 UI/UX 구성  
- 이미지 URL 추출 기능 (정규식 적용)  
- 좋아요, 팔로우 기능 구현  

### 🌡️ IoT (Python, Raspberry Pi) — **팀원 구현**  
- 센서 데이터 수집 및 자동제어 시스템  

---

![image](https://github.com/user-attachments/assets/ccce3154-7bf7-4bb3-aa0e-75c2b13f49a9)  
![image](https://github.com/user-attachments/assets/ec0100eb-cbb8-4a7e-a18c-c8fd0a76cef6)

---

## 💻 프로젝트 결과  

| 기능 설명 | 미리보기 |
|-----------|-----------|
| **공지사항 게시판 조회/권한 처리** | ![Image](https://github.com/user-attachments/assets/071c4eb1-f318-46cb-8a3c-fac7a713a1b0) |
| 공지사항 게시판 댓글 CRUD 및 권한 처리 | ![Image](https://github.com/user-attachments/assets/7093d580-1cdb-4a85-b376-0603e147c080) |
| QNA 게시판 조회 | ![Image](https://github.com/user-attachments/assets/e3ea5fd1-deee-46de-b678-461a9c7f27f1) |
| QNA 게시판 상세 조회 | ![Image](https://github.com/user-attachments/assets/605b1c2e-b4a9-44d7-8ed0-7e61c11a70b4) |
| QNA 댓글 등록/삭제/상세/권한 처리 | ![Image](https://github.com/user-attachments/assets/a25ad99b-16d3-4a62-bd3c-bf9f6fa8cabc) |
| 게시글 등록 (에디터) | ![Image](https://github.com/user-attachments/assets/2335c5e8-1779-4705-91ac-4662e1595b2a) |

---

## 📱 앱 시연  

| 기능 | GIF |
|-------|------|
| 🌿 이미지 URL 추출 기능 | ![Image](https://github.com/user-attachments/assets/e8662926-95b6-43a4-bc4c-9ebd0e58f7c8) |
| 💬 팔로우 기능 | ![Image](https://github.com/user-attachments/assets/5687d66d-249e-4496-911a-6c9bf01d9949) |
| 🌱 좋아요 기능 | ![Image](https://github.com/user-attachments/assets/4a89ddf5-62f0-45cc-a2a1-a9a0197fef08) |

---

## 🛠️ 사용 기술  

| 분야         | 기술 스택                                      |
|--------------|-------------------------------------------------|
| **IoT 제어** | Python, Raspberry Pi *(팀원 구현)*              |
| **백엔드**   | Java, Spring Boot, MariaDB, REST API            |
| **프론트엔드** | React, React Native, Axios                      |
| **협업 도구** | GitHub, Notion                                   |

---

## 🔍 프로젝트 특징  

### 🌐 웹  
- 공지사항 및 Q&A 게시판, 댓글 CRUD 기능 구현  
- 사용자 권한에 따른 접근 제어 로직 개발  
- React-Quill 에디터를 적용한 게시글 작성 기능 구현  
- 공지/Q&A 댓글 관련 DB 설계 및 백엔드 API 일부 직접 개발  

### 📱 앱  
- 커뮤니티 페이지 UI/UX 설계 및 개발  
- 정규식을 활용한 이미지 URL 추출 기능 구현  
- 좋아요 및 팔로우 기능 구현

---

## 💡 느낀 점  

이 프로젝트를 통해 **프론트엔드.백엔드 개발 웹/앱/서버 연동 및 시스템 전체 설계**를 경험할 수 있었습니다.  
특히 **IoT 기기 연동은 팀원이 구현**하였지만, 이를 웹과 앱에 연동하는 과정에서  
**실시간 데이터 흐름, 시스템 구조, 사용자 경험을 고려한 설계의 중요성**을 배울 수 있었습니다.  

프로젝트의 부분적인 프론트엔드와 백엔드를 직접 담당하며, 문제 해결 능력과 협업 커뮤니케이션,  
그리고 개발 역량과 경험을 키울 수 있었습니다
