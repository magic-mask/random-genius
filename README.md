# ⚛︎ random-genius

본 repository는 떠오르는 영감을 문서화하여, 미래의 구현 시점에서 겪을 인지적 비용을 최소화합니다.

<br><br>

---

## 문서화 표준 지침

For Human Eyes Only

### 디렉토리 네이밍

| 항목 | 규칙 | 예시 |
| :--- | :--- | :--- |
| **케이스** | kebab-case (소문자 + 대시) | `cloud-computing` |
| **정렬** | 숫자 접두사 활용 | `10-docker`, `20-kubernetes` |
| **언어** | 가급적 영어 (한글은 인코딩 이슈 발생 가능) | `database` (O), `데이터베이스` (△) |
| **구분자** | 단어 사이는 `-` 사용 | `java-performance-tuning` |

### 디렉토리 구조

```text
root/
├── 00-computer-science/
│   ├── network/
│   └── operating-system/
├── 01-frontend/
│   ├── react/
│   └── typescript/
├── 02-backend/
│   ├── node-js/
│   └── spring-boot/
└── images/           <-- 문서에 쓰이는 이미지 모음
```
