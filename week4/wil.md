## github flow vs git flow
### github flow
단순하고 언제든지 수시로 배포 가능한 브랜치 네이밍 방식
#### 구성요소
* main
* feature
### git flow
배포 주기가 어느정도 정해져 있고, github flow에 비해 브랜치 구분 및 사용이 엄격함
#### 구성요소
* main
* develop
* feature
* release
* hotfix

## commit convention
커밋 메세지를 사용할 때 적용하는 **규칙(관례)**. 예를 들면 메세지 앞에 "fix:", "docs:" 등과 같은 헤더를 붙이는 식이다. 어떤 규칙을 사용할지는 사용자마다, 프로젝트마다 다를 수 있으며, 이 메세지를 통해 커밋의 변경사항을 쉽게 알아볼 수 있다.   
[자주 사용되는 commit convention 더 알아보기](https://velog.io/@archivvonjang/Git-Commit-Message-Convention)
## PR template
pull request를 전송할 때 적는 메세지의 구조를 매번 적기 귀찮을 때, 레포지토리 내에 .github 폴더 내에 pull_request_template.md 파일에 미리 양식을 작성해두면 pull request 메세지를 작성할 때 자동으로 양식이 불러와진다.

코드블럭 헤딩 볼드 리스트 링크 포함