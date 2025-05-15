# SmartBakeChain 🍪

스마트한 쿠키 제조 공정과 ERP 시스템 통합을 목표로 한 **MES+ERP 웹 통합 시스템**입니다.  
Spring Boot 기반으로 제조 공정을 디지털화하고, 관리자 중심의 기능을 실시간 시각화하며 효율적인 업무를 지원합니다.

---

## 📆 프로젝트 기간
2025.01.23 ~ 2025.02.26 (총 5인 팀 프로젝트)

## 👩‍💻 담당 역할
- 팀 리더 및 프론트엔드 전담
- 고객관리/주문관리/마케팅/원재료/제품/판매관리 모듈 전체 기여
- UI 설계, DB 모델링, 업무 흐름 도식화

---

## 🛠 기술 스택

| 구분        | 기술 |
|-------------|------|
| **Frontend** | HTML5, CSS3, JavaScript, JSP, jQuery, Bootstrap, Ajax, FullCalendar, Chart.js |
| **Backend**  | Java 17, Spring Boot, Spring MVC, MyBatis |
| **Database** | Oracle 11g, DBeaver, eXERD |
| **Server**   | Apache Tomcat 9 |
| **기타**     | WebSocket, Axios, Vue.js (일부 화면), VSCode, STS |

---

## ✨ 주요 기능

- **입출고 일정 시각화**: FullCalendar로 월간/주간/일간 입출고 일정 관리
- **원재료 및 제품 CRUD**: 등록, 조회, 수정, 삭제 / 조건 검색 / 상세 정보 조회
- **고객·주문 관리**: 권한 기반 접근 제어, 세션 기반 로그인 처리
- **실시간 채팅**: WebSocket 기반 채팅 기능 구현
- **판매 데이터 시각화**: Chart.js로 월별 제품 판매 현황 선형 그래프 출력
- **다국어 처리**: 한국어, 영어, 중국어 다국어 UI 제공
- **권한 체계 분리**: 사원 등급 및 부서에 따른 기능 접근 제한

---

## ✅ 테스트 및 운영

- 단위 테스트 & 통합 테스트 2회 수행
- 권한별 시나리오 기반 기능 검증 완료
- 주요 이슈: DB 복잡도에 따른 테이블 분리 및 조건 처리 로직 개선

---

## 📺 시연 영상 & 저장소

- [팀 프로젝트 시연 영상 (Full ver.)](https://www.youtube.com/watch?v=UkU1IFAy-KM)
- [개인 시연 영상](https://youtu.be/l8u1crKlwt4)
- [GitHub 저장소](https://github.com/songyiseok/SmartBakeChain)

---

## 🧠 회고 & 배운 점

- 일정 시각화 및 실시간 데이터 처리 기능 구현을 통해 **사용자 중심의 기능 설계** 경험
- 웹 MVC 구조를 체계적으로 적용하며 유지보수성과 재사용성을 확보
- 역할 조정, 회의록 관리, 코드 리뷰 등 **팀 리딩 경험**을 통해 소통과 협업의 중요성 체득