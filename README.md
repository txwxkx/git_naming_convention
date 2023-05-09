# git 저장소 이름 규칙(git naming convention)

일관적이고, 색인이 간편한 Git 저장소 명명 규칙을 정합니다. 프로젝트를 생성하거나 기존에 작성된 프로젝트를 참고하고자 할 떄, 일관되지 않은 규칙으로 작성된 저장소 이름으로 인해 어려움을 겪는 것을 방지하고자 함에 목적이 있습니다.

## 기본적인 명명 규칙(default naming convention)

1. 특수문자, CamelCase 금지
2. 소문자 사용
3. 대시 사용
4. 명확하게 작성
5. 일관성있게 작성
6. '프로젝트 이름-개발 환경-프로젝트 목적' 형태로 구성

### 이름(Name)

이 Keyword는 프로젝트의 이름을 나타내는 Keyword입니다.

- 웹 사이트의 경우 특별히 명명한 프로젝트 명이 없을 경우 도메인(Domaion) 자체가 프로젝트 명이 될 수 있습니다.
  - http://domain.com ➔ domain.com
  - http://sub.domain.com ➔ sub.domain.com

### 개발 환경(development enviroment)

이 Keyword는 프로젝트의 개발 환경을 나타내는 Keyword입니다.

- 개발 환경은 언어, 사용된 개발 도구, 운영 체제 등을 포함합니다.
- 특정 개발 환경에서만 프로젝트가 작동되는 경우 그 Keyword를 우선적으로 작성합니다.

| 이름(Name) | 설명(Description)                |
| ---------- | -------------------------------- |
| angular    |                                  |
| cpp        |                                  |
| dotnet     |                                  |
| java       |                                  |
| javascript |                                  |
| nodejs     |                                  |
| windows    |                                  |
| ...        | 그 외 개발 환경 잘 설명하는 단어 |

### 용도(Purpose)

이 Keyword는 프로젝트가 어떠한 용도로 사용되는 지를 나타내는 Keyword입니다.

| 이름(Name) | 설명(Description)             |
| ---------- | ----------------------------- |
| backend    |                               |
| cli        |                               |
| client     |                               |
| core       |                               |
| documents  |                               |
| extention  |                               |
| frontend   |                               |
| gui        |                               |
| interface  |                               |
| lib        |                               |
| references |                               |
| samples    |                               |
| sdk        |                               |
| server     |                               |
| tools      |                               |
| util       |                               |
| ...        | 그 외 용도를 잘 설명하는 단어 |
