Hi, I'm JangHun Yuk 👋

Backend Engineer @ [Telos Inc.](https://www.thetelos.net/)
Building scalable systems with Java & Spring

🌱 I enjoy deep technical discussions with colleagues and am always eager to learn and apply new skills.

📫 Blog: https://yukmekim.github.io/

### About me

```java
package io.github.yukmekim.introduction;

public class AboutMe {
    Developer yuk = Developer.builder()
            .name("JangHun Yuk")
            .role("Backend Engineer @Telos")
            .languages("Java")
            .backend("Spring Boot", "JPA", "QueryDSL", "Gradle", "Junit5", "Mockito")
            .database("MySQL", "PostgreSQL", "Redis")
            .infra("Docker", "Github Actions")
            .interests("동시성 제어", "백엔드 아키텍처", "설명을 잘하는 개발자")
            .build();
}
```

### What I've worked on

- 다중 인스턴스 환경의 동시성 문제를 원인부터 확인하고 해결합니다
  - [Kubernetes 다중 파드 환경에서 ShedLock으로 스케줄러 중복 실행 막기](https://yukmekim.github.io/backend/2026/10/06/shedlock-scheduler-lock/)
- 사용하는 라이브러리의 취약점을 확인하고 대안을 검토합니다
  - [QueryDSL HQL Injection취약점(CVE-2024-49203)](https://yukmekim.github.io/backend/2025/08/02/querydsl-hql-injection/)
- 데이터 특성에 맞는 저장소를 고르고 성능을 측정합니다
  - [JWT Refresh Token을 Redis에서 관리하기](https://yukmekim.github.io/backend/2025/05/27/redis-migration/)
  - [[MySQL] 여러 컬럼으로 인덱스 구성](https://yukmekim.github.io/mysql/2024/04/11/index-optimize-2/)

---
💬 Open to discussions about backend aontrol!
