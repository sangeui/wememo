# wememo
- [ ] 아키텍처 구성
  - 레이어드 아키텍처 채택
    - 가장 보편적이며 누구나 이해 가능한 수준의 아키텍처
- [ ] 컴파일 단위로 패키지 구성
- [ ] 스토리지 구성
  - [ ] 디바이스 (필수)
  - [ ] 클라우드킷 (필수)
  - [ ] 그 외 원격 저장소 (선택)

---
- 레이어
  - 코디네이터
  - 유저 인터페이스
    - 뷰, 뷰 스트림
  - 앱 종속 비즈니스
  - 서비스
  - 퍼시스턴스
- 각 레이어의 독립적인 모델 구성
  - 상위 레이어의 어떤 구성요소에서 불필요한 **import** (또는 의존)을 방지
