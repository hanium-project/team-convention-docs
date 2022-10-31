## Commit message Convention
- Message Type List
    ![image](https://user-images.githubusercontent.com/96467030/198984702-a7dfecfa-f123-4cde-aaeb-97a74f0ecfec.png)
    - 코드를 수정한 경우 Modify Type 사용
    - Github issue 번호에 따라 다음과 같은 규칙으로 작성한다.
        - issue number 26 → [Type]: #[issue number] [commit message]
    - Type은 현재 시제로 작성하도록 한다.
    - Message는 무엇을 했으며 왜 했는지 적어준다.
        - 다만 우리는 ‘왜’에 대해서는 깃허브에 커밋 시 작성하지 않도록 한다.
        - 이에 대해서는 코드 테스트 완료 후 PR에 작성하도록 할 것
    - **기능 구현 단위로 commit** 하도록 하고, 기능 구현이 완료되면 **반드시 PR 및 코드 리뷰**를 받도록 한다.
    - [https://seolahchloe.tistory.com/entry/GitHub-깃-커밋-메세지-컨벤션-Git-Commit-Message-Convention](https://seolahchloe.tistory.com/entry/GitHub-%EA%B9%83-%EC%BB%A4%EB%B0%8B-%EB%A9%94%EC%84%B8%EC%A7%80-%EC%BB%A8%EB%B2%A4%EC%85%98-Git-Commit-Message-Convention)

## Code Convention
### Frontend
### Backend
- 캠퍼스 핵데이 java 코딩 컨벤션
    - [https://naver.github.io/hackday-conventions-java/](https://naver.github.io/hackday-conventions-java/)
- 좋은 코드를 위한 자바 변수명 / 메소드 네이밍
    - [https://tecoble.techcourse.co.kr/post/2020-04-24-variable_naming/](https://tecoble.techcourse.co.kr/post/2020-04-24-variable_naming/)
    - [https://tecoble.techcourse.co.kr/post/2020-04-26-Method-Naming/](https://tecoble.techcourse.co.kr/post/2020-04-26-Method-Naming/)

## Github Issue Convention
- 각 스프린트에 맞게 이슈를 발급한다
- 완료, 진행중, 오류 3개의 라벨을 달아 현재 스프린트의 상태를 표시한다.
- 완료된 이슈는 PR 확인 후 Close 한다.
![image](https://user-images.githubusercontent.com/96467030/198984745-f80becbd-07f4-483c-b810-bb9b41c7364c.png)
## Github Branch Convention

- branch 생성 시에도 커밋 메시지와 같은 방식으로 작성한다.
- #[issue number] [branch name]
- 브랜치 이름에는 띄어쓰기 대신 -를 사용한다.
- 왠만하면 이슈 제목과 일치시키는 것이 좋다.

## PR 및 Branch 생성 시 주의 사항

```
1. 머지 시 메인 브랜치와 충돌 날 우려가 있기 때문에 자신이 한 부분만 올려주세요.
	ex) 만약 내가 A를 했다면, 머지 전 메인브랜치를 받은 후 해당 코드를 넣거나 모두 삭제하고
			자신이 구현한 부분만 넣을 것
  ** 만약 메인 코드에서 수정된 부분이 있다면 알려주세요
2. 코드 리뷰 확인 후 머지 승인 시 머지 후 이슈를 닫아주세요.
3. 이슈번호와 브랜치번호를 일치시켜주세요.
4. 커밋 컨벤션을 지키고, 브랜치 번호를 일치시켜주세요. 브랜치 번호에 따라 이슈에
   커밋 메시지가 기록됩니다. 잘못된 번호가 기록되지 않게 주의하세요.
5. 만약 문제가 있다는 코멘트를 받으면, PR을 닫고 수정 후 다시 PR 날려주세요.
```

- 해당 컨벤션 문서와 관련하여 **다른 팀과의 공유를 금지**함