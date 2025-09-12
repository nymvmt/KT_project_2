# ☕ KT_APR-B_FullStack_Project2 (Team 1)
사내 커피챗을 쉽고 즐겁게 ! 
- 재밌는 자기소개부터 약속 예약, 즐거운 정산까지
- 참여자 모두의 행복과 더 나아가 사내 소통 활성화를 위한 가장 완벽한 서비스
---
## ⭐️ 개요
### ✅ 프로젝트 비전/ 목표
**AI 기반 사내 커피챗을 통해 열린 사내 문화 형성을 위한 즐거운 경험을 제공한다.**


### ✅ 서비스 도출 배경
사회학 고전 연구에 따르면 새로운 정보, 기회 확산의 핵심 통로는 '**약한 연결**' 

조직 내 우연한 교류를 쉽고 편리하게 지지하는 커피챗을 통해 사내 교류를 확산하고자 함

**1) 사내 커뮤니케이션 허들**  
- 같은 부서, 동기, 동호회 등이 아니면 새로운 관계를 맺기 힘듦
- 업무 상 궁금한 점이 있더라도 쉽게 문의할 사람이 없음
  
⭐️ 익명 기반 서비스와 편리한 이용을 위한 자동 닉네임 생성으로 소통 장벽 완화

**2) 불편한 상대와의 만남과 귀찮은 정산 요청** 
- 부서 내 막내 혹은 최고 결정권자들은 다른 사람과 교류하고 싶어도 선뜻 나서지 못함
- 오프라인 모임을 가진 이후 계산/송금 요청을 해야할 시, 피로감을 불러 일으킴
  
⭐️ 장소 기반, 취미 기반 매칭으로 누구나 만날 수 있는 서비스이자 영수증 인식 기능을 통한 랜덤 정산 서비스로 편리함과 재미 모두 확보 

---
### ✅ 주요 기능 
👤 사용자 경험(UX)
- 🪪 익명/별칭 닉네임 자동 생성
   대화 장벽↓, 심리적 안전감↑.
  
- 🗓️ 원클릭 약속 생성/참가/초대
   제목·설명·시간·장소 선택 후 약속 생성
   약속 리스트에서 참가 버튼 클릭 시 원클릭 참여 가능 

- 📍 장소 기반 매칭 
   지사별 선택 & 층 선택 가능 

🧑‍🤝‍🧑 게스트 & 도착 관리
- ⏱️ 게스트 ETA 등록
참가자가 도착 예정 시각(ETA) 입력
- 🔔 호스트 알림 팝업
약속 후 게스트의 참여 여부 확인 가능 

🧾 정산·놀이화
- 🧮 영수증 OCR 업로드 → 자동 아이템 추출
상호·일자·메뉴·금액 라인 추출
- 🎲 랜덤 정산/룰 기반 분배
인원수에 맞춰 무작위/규칙 혼합 분배
- 📤 정산 결과 공유
링크 복사·스크린샷 배포 가능 

🎨 그 외 AI 재미 요소
- 🧑‍🎤 익명 닉네임 제너레이터
팀/취향 태그 기반 재밌는 별칭 자동 추천
- 🖼️ 약속 포스터/배너 이미지 자동 생성(선택)
모임 분위기·키워드로 약속을 잘 나타내는 한 장 이미지 생성

---
## 👥 서비스 담당자 
- **User&Location&nickname-python&Front(연결)** : 김나영  
- **Appointment&Front(연결)** : 임태규  
- **Guest&image-python** : 김혜지  
- **Recommendation&Frontend** : 황현지
---
## 📌 집계 리포지토리
- [KT Project 2](https://github.com/nymvmt/KT_project_2.git)

---
## 🗓️ 작업 계획
### 9/8 (월)
- 개발 환경 세팅 완료 ✅ : 각자 로컬에서 git clone 받아온 각 서비스 repository 내에서 하면 됨. Docker, Azure Web App, Azure MySQL Flexible Server도 초기 설정 완료됨.
- Azure 서비스 스택 선정 ✅ : pivot -> 기획 큰 틀 잡음. Document Understanding(OCR), Video Understanding 사용 시도할 예정임.
- DB SQL 초기데이터 등록 ✅ : 혜지가 init-db.sql 파일 구성.
- 역할 분담 ✅ : 각자 맡아서 개발할 Service 나눴고, 각자 맡은 Service 개발 착수함.
- User, Location Service 간단 구현 ➡️ : 나영이 남아서 진행 중이었고, User 됐고, Location까지 내일 아침까지 구현 완료 예정.
- API 명세서 최종 확인, 오타 확인 ➡️ : 현지가 남아서 진행 중이었고, 내일 아침까지 확인 완료 예정.
- Appointment Service 간단 구현 ➡️ : 태규가 남아서 진행 중이었고, 내일까지 구현 완료 예정.

### 9/9 (화)
- DB 구조 최종 수정 및 픽스 ✅ : 오전 팀 회의
- API 명세서 최종 수정 및 픽스 ✅ : 오전 팀 회의
- Azure server & web app 환경변수 설정 최종 ✅ : 나영
- CI/CD 환경변수와 docker profile, github secrets 설정 ✅ : 나영

[기본 구현 + 배포]
- User Service ✅ : 나영 구현 완료 + Azure 배포 완료

### 9/10 (수)
[기본 구현 + 배포]
- Location Service ✅ : 나영 구현 완료 + 태규가 Azure 배포 완료
- Appointment Service ✅ : 태규 구현 진행 중 + Azure 배포 완료
- Guest Service ✅ : 혜지 구현 완료 + Azure 배포 완료
- Notification Service ✅ : 현지 구현 완료 + Azure 배포 완료
- Recommendation Service ✅ : 나영 구현 아직 안 함 + Azure 배포 완료

[심화 구현]
- 전체 front-end ✅ : 현지가 frontend git repository 파고 + 화면설계/flow 기획 + Next.js로 코드 초안 구현 완료
- Azure AI Foundry_OpenAI ➡️ : 활용한 익명 닉네임 생성기 ➡️ : 나영 구현 중

[목표]
- Appointment, Guest, Feedback, Notification: 구현 완료  
- Recommendation: 구현 시작

### 9/11 (목)
- Appointment, Guest, User, Location :
   - Azure 배포 ✅ 전체
   - FE 와 BE 연결 ✅ 나영 
   - 트러블슈팅 ➡️ 전체
- Recommendation:
  - Azure 웹앱 배포 / DB 연결 및 환경 변수 설정 완료 ✅ 나영
  -  Azure Document Understanding(OCR) 환경 변수 설정 및 기능 구현 완료 ✅ 현지
  -  테스트용 별개의 프론트엔드 로컬 구동까지 완료 ✅
  -  서비스 로직 정돈 및 FE 연결 필요 ➡️
-    Azure AI Foundry 활용한 그림일기 서비스 환경 변수 설정 및 기능 구현 완료 ✅ 혜지
-    스케줄러를 통한 통신 공부 및 구현 설계 ✅ 태규

### 9/12 (금)
#아침부터 시작된 프론트엔드 처음부터 다시 짜서 백엔드랑 연결하기 ✅✅✅✅✅✅✅✅✅✅✅
- 시연 영상 제작 ✅
- 보고 문서 / 발표 자료 정리 ✅ 
- 최종 발표 ✅ :) 
---

## 🔧 주요 기능 & 서비스별 리포지토리
1. **User Service**
   - 사용자 등록 서비스  
   - [리포지토리 바로가기](https://github.com/nymvmt/UserService)

2. **Appointment Service**
   - 약속 CRUD 서비스  
   - [리포지토리 바로가기](https://github.com/nymvmt/AppointmentService)

3. **Guest Service**
   - 참가자 CRUD 및 상태 관리 서비스  
   - [리포지토리 바로가기](https://github.com/nymvmt/GuestService)

4. **Location Service**
   - 만남 장소 조회 서비스  
   - [리포지토리 바로가기](https://github.com/nymvmt/LocationService)

5. **Recommendation Service**
   - 영수증 분석 및 랜덤 정산 서비스 
   - [리포지토리 바로가기](https://github.com/nymvmt/RecommendationService)
  
---

6. **FrontEnd**
   - 프론트엔드 통합 관리
   - https://github.com/jennnif/koffeekonnect-frontend.git
   - main 브랜치가 최종 브랜치
  
7. **Recommendation frontend**
  - recommendation 프론트엔드
  - https://github.com/jennnif/koffeekonnect-frontend.git
  - feature/file-upload-only 브랜치 
  
---
+. **Feedback Service**
   - 모임 피드백 CRUD 서비스
   - 중간 기획 변경으로 인해 삭제 
   - [리포지토리 바로가기](https://github.com/nymvmt/FeedbackService)

++. **Notification Service**
   - 게스트 도착 예정 시각 알림(호스트 페이지 팝업 표시)
   - 구현 완료, BUT 중간 기획 변경으로 인한 appointment service로의 통합
   - [리포지토리 바로가기](https://github.com/nymvmt/NotificationService)

---

## 📊 아키텍처 & 협업 문서
- **MSA 보드**: [Miro 링크](https://miro.com/app/board/uXjVJPRLAtY=/?share_link_id=41447987665)  
- **프로젝트 노트**: [Notion 링크](https://www.notion.so/2616156a6141802cb94acf498b0e5df8?source=copy_link)

---
