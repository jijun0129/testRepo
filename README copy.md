# 멀티모달 임베딩을 활용한 이미지 속 객체 특성 식별 및 텍스트 프롬프트 생성 

**경북대학교 2024 하반기 종합설계프로젝트1 with 스피어AX**

## 🚩 참여 조원

| [<img src="https://github.com/jijun0129.png" width="100px">](https://github.com/jijun0129) | [<img src="https://github.com/machi2001.png" width="100px">](https://github.com/machi2001) | [<img src="https://github.com/rrak99.png" width="100px">](https://github.com/rrak99) | [<img src="https://github.com/gagi132.png" width="100px">](https://github.com/gagi132) |
| :------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: |
|                         [jijun0129](https://github.com/jijun0129)                          |                         [machi2001](https://github.com/machi2001)                          |                         [rrak99](https://github.com/rrak99)                          |                         [gagi132](https://github.com/gagi132)                          |

## 👩‍🔧 과제 추진 배경 및 목적

> [!NOTE]
- 생성형 AI의 등장으로 양질의 데이터셋 부족 문제가 부각되고 있습니다. 이를 해결하기 위한 방법으로 멀티모달 임베딩 기술이 주목받고 있는데, 이는 다양한 데이터 소스를 하나의 임베딩 공간에 통합해서 분석하는 기술입니다.
- 이러한 멀티모달 모델을 활용해 데이터를 분석하고 필요한 정보를 추출할 수 있으며, 텍스트 프롬프트의 정확성을 판별하는 페이지를 개발할 계획입니다.



### 📌 규칙

###  아래 커밋 컨벤션을 지키며 commit을 진행합니다.


```bash
<type>(<scope>): <short summary>
```

1. `<type>` 에 들어갈 수 있는 항목들
   > 어떤 작업을 했는지 기록하는 용도입니다.

**사용 커밋 컨벤션**

- Feat: 새로운 기능 추가
- Fix: 버그 수정
- Docs: 문서 관련
- Style: 스타일 변경 (포매팅 수정, 들여쓰기 추가, …)
- Refactor: 코드 리팩토링
- Chore: 그 외 자잘한 수정
- Comment: 주석 관련 작업
- Backend: 백엔드 관련 작업
- Frontend: 프론트엔드 관련 작
- Test: 테스트 관련

2. `<scope>` 에 들어갈 수 있는 항목들
   > 어디가 변경되었는지 기록하는 용도입니다.

예를 들어 로그인 관련 코드를 추가했을 경우

```bash
Feat(login): 카카오 소셜 로그인 기능 구현
```

> [!TIP]
>
> **알고리즘 문제 풀이시에는 scope 부분을 생략해도 좋습니다.**

### 4️⃣ 본인 branch 에서 작업 한 후 main branch로 Pull Request를 진행합니다.

- PR의 Assignees 부분에 본인을 추가합니다.
- 적절한 Label을 추가합니다.
- main branch로 `Squash and merge`를 진행합니다.
