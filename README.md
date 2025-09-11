# ☕ KT_APR-B_FullStack_Project2 (Team)

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
- Recommendation Service ⛔️ : 나영 구현 아직 안 함 + Azure 배포 완료

[심화 구현]
- 전체 front-end ➡️ : 현지가 frontend git repository 파고 + 화면설계/flow 기획 + Next.js로 코드 구현까지 진행 중
- Azure AI Foundry_OpenAI ➡️ : 활용한 익명 닉네임 생성기 ➡️ : 나영 구현 중

[목표]
- Appointment, Guest, Feedback, Notification: 구현 완료  
- Recommendation: 구현 시작

### 9/11 (목)
- FE-BE 연결 중 ➡️ : 나영
- Appointment, Guest, Feedback, Notification, Recommendation ➡️ : Azure 배포 및 트러블슈팅  
- Recommendation: 구현 완료  

### 9/12 (금)
- Azure 배포 완료  
- 시연 영상 제작  
- 보고 문서 정리  
- 발표 자료 작성  
- 최종 발표  

---

## 🚀 프로덕트 소개
- **사내 커피챗 장려를 위한 커피타임 요청 서비스**

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
   - 사용자 맞춤 약속 추천 서비스  
   - [리포지토리 바로가기](https://github.com/nymvmt/RecommendationService)
  
---

6. **FrontEnd**
   - 프론트엔드 통합 관리
   - https://github.com/jennnif/koffeekonnect-frontend.git
   - main 브랜치가 최종 브랜치
  
---
+. **Feedback Service**
   - 모임 피드백 CRUD 서비스  
   - [리포지토리 바로가기](https://github.com/nymvmt/FeedbackService)

++. **Notification Service**
   - 게스트 도착 예정 시각 알림(호스트 페이지 팝업 표시)  
   - [리포지토리 바로가기](https://github.com/nymvmt/NotificationService)

---

## 📊 아키텍처 & 협업 문서
- **MSA 보드**: [Miro 링크](https://miro.com/app/board/uXjVJPRLAtY=/?share_link_id=41447987665)  
- **프로젝트 노트**: [Notion 링크](https://www.notion.so/2616156a6141802cb94acf498b0e5df8?source=copy_link)

---

## 👥 역할 분담
- **Appointment & Guest**  
- **Feedback**  
- **Notification**  
- **Recommendation**  
- (+ 추가 기능: 대화 서비스 *Conversation* → 시간 여유 시 도전)

---
