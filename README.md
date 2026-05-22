# Backend Developer 전남혁

> Java/Spring 기반 백엔드 개발자 · 레거시 현대화와 서비스 안정화에 강점

---

## 👋 About

약 5년 차 백엔드 개발자입니다.
기능 구현을 넘어 운영·장애 대응·성능 개선까지, 서비스의 전체 생명주기를 책임지는 개발을 지향합니다.

- 🔄 **레거시 현대화**: ASP→PHP, PHP→Java 마이그레이션 주도
- ☁️ **클라우드 전환**: 온프레미스 → AWS (RDS, S3, CloudFront)
- 📊 **운영 안정화**: DB 성능 최적화(CloudWatch 기준 CPU 약 50% 개선), 모니터링·알림 체계 구축
- 🛒 **커머스 도메인**: 결제·예약·정산 등 핵심 도메인 다수 경험

---

## 🚀 Key Projects

### 0. 골프존 굿샵 (팀 리딩 · JPA 운영 첫 도입)
- 역할: 팀 리딩 + 백엔드 아키텍처/DB 설계
- 기술: Java, Spring Boot, JPA
- 핵심: 운영 환경 JPA 첫 도입, 컬렉션 페이징 중복 이슈 해결, 모의해킹 점검 이슈 0건 통과
- 결과: 삼성물산 직원 복지몰로 안정적 런칭 및 운영

👉 [자세히 보기](./projects/goodshop.md)

---

### 1. OMS PHP → Java 마이그레이션 (대형 프로젝트)
- 역할: 레거시(PHP+Java 혼용) 시스템의 Java 통합 및 사이트 리뉴얼 주도
- 기술: Java, Spring Boot
- 핵심: 프론트·기획자와 3인 협업(Swagger 기반 API 소통), 크롤링 안정화 및 연동 로그 추적성 확보

👉 [자세히 보기](./projects/oms-migration.md)

---

### 2. AWS RDS 무중단 이관
- 기술: AWS DMS, HikariCP
- 결과: CloudWatch 기준 DB CPU 35%→18% (약 50% 개선), 무중단 이관 완료

👉 [자세히 보기](./projects/rds-migration.md)

---

### 3. AWS S3 + CloudFront 이미지 서버 (Kotlin Coroutine)
- 기술: Kotlin(Coroutine), Java, Spring Boot, AWS S3/CloudFront
- 핵심: 동시 다발 업로드 환경에서 논블로킹 비동기 처리로 I/O 부하 대응
- 결과: 이미지 로딩 속도 약 2배 개선(실측), 인프라 비용 절감

👉 [자세히 보기](./projects/s3-image-server.md)

---

### 4. 모니터링 · 알림 체계 구축
- 기술: Prometheus, Grafana, Sentry
- 핵심: 에러 레벨·발생주기 튜닝, 운영/개발 처리 영역별 알림 라우팅(Google Chat / Discord)
- 결과: 장애 탐지·대응 속도 단축, 실시간 대응 체계 확립

👉 [자세히 보기](./projects/monitoring-system.md)

---

### 5. 정산 데이터 크롤링 안정화
- 기술: Python(Selenium), PHP
- 핵심: 메모리 누수·불필요 프로세스 리팩토링으로 크롤링 오류 0건, 연동 구간 로그 추적성 확보
- 결과: 취소 누락 매출 손실 방지 (개선 전 최대 약 천만 원 손실 → 이후 재발 없음)

👉 [자세히 보기](./projects/crawling-system.md)

---

## 🧠 Core Experience

👉 [에이치투오코리아: 레거시 개선 / 신규 개발 / Kotlin 서버 구축](./experience/h2o-tech.md)

---

## 🏢 SI / 기타 Projects (WebBiz)

- 골프존 굿샵 → 삼성물산 복지몰 (JPA, 팀 리딩)
- 해외 뷰티 쇼핑몰(theBeautyzon) → 글로벌 결제/물류/세금 API 직접 연동(Stripe, PayPal, Shippo, Avalara)
- 공임나라 → ASP→PHP 마이그레이션, MSSQL→MariaDB 무중단 DB 이관(회원 80만+)
- Celuvu → DB 설계·캐싱, 현재까지 운영 중(celuvu.com)
- 통계청 대표 홈페이지 → 검색엔진 형태소 분석 개선 (백엔드 단독 담당)
- 이건창호 현장 업무 관리 → 공공데이터 API 연동 단기 날씨 예보 구축

👉 [상세 보기](./projects/si-projects.md)

---

## 🛠 Tech Stack

**Backend** Java · Spring Boot · Spring Data JPA · QueryDSL · MyBatis
**Database** MySQL · MariaDB · Oracle · PostgreSQL · Redis
**Infra** AWS (RDS, S3, CloudFront, DMS) · Docker · Prometheus · Grafana · Sentry · Linux
**Etc** PHP · Python · Kotlin · JavaScript

---

## 📄 Career

👉 [경력 상세 보기](./career.md)

---

## 🔗 Links

- GitHub: https://github.com/wjsskagur
- Blog: https://dev-log.tistory.com/
