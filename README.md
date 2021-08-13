
## 글쓰기
1. `content/posts` 아래 `mdx` 포멧의 파일 추가해서 글쓰기
2. 완성 전에는 `main` branch 관리
3. 배포 시 `yarn deploy` 실행


## 가이드라인
- 글의 포멧(format)을 먼저 설정한다.
    - 포멧의 의미?
        - 전달하고자 하는 정보를 담는 그릇의 형태
        - 전달하고자 하는 정보에 따라 최적의 포멧이 있다.
    - 가능한 포멧의 종류는?
        - 학습일지 `format:diary` 📓
            - 관찰: 무엇을 보았는가?
            - 질문: 어떤 궁금증이 떠올랐는가?
            - 이해/추론: 어떤 방식으로 이해하고 추론했는가?
        - 에세지 `format:essay` 🖌
            - 주제: 무엇에 대해 이야기 하는가?
            - 근거: 왜 그렇게 생각하는가?
        - 튜토리얼 `format:tutorial` 🚩
            - 목표: 목표는 무엇인가?
            - 절차: 어떤 순서로 진행하는가?
        - 문제해결 `format:problem-solve`
            - 문제의식: 무엇을 문제라고 생각하는가?
            - 과정: 문제 해결책을 고민하는 과정은 어떻게 되나?
            - 해결책: 최종 해결책은 어떻게 되는가?
- 글의 타입(ctype)을 결정한다.
    - 가능한 타입의 종류는?
        - 블럭 `ctype:block`
            - 재사용 가능한 기본 단위
        - 팩 `ctype:pack`
            - 블럭을 조합한 단위
            - 일반적으로 블로그 글에 대응
        - 패키지 `ctype:package`
            - 팩을 조합한 단위
            - 시리즈 혹은 여러 챕터로 구성된 강의에 대응
- 글의 타겟(target)을 설정한다.
    - 타겟의 의미?
        - 예상 독자를 의미
    - 타겟의 종류?
        - ⬜️ 흰띠 (코딩학당 등급 기준: 1)
        - 🟨 노란띠 (코딩학당 등급 기준: 2)
        - 🟦 파란띠 (코딩학당 등급 기준: 3)
        - 🟥 빨간띠 (코딩학당 등급 기준: 4)
        - ⬛️ 검정띠 (코딩학당 등급 기준: >=5)