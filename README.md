# github-practice-2025spring
# Git 원격 작업 연습
준회원 교육 실습용 리포지토리입니다.

## 복제(clone)하기
이 레포를 `git clone`으로 복제해 보세요. 로컬 환경의 새 디렉토리 안에 GitHub에서 보는 것과 똑같은
Git 리포지토리가 생긴 것을 확인할 수 있습니다.

`git status` 명령으로 현재 브랜치 이름이 `main`임을 확인할 수 있습니다. `git init`을 사용하면
기본으로 `master` 브랜치를 만들어 주지만, 꼭 기본 브랜치 이름이 `master`일 필요는 없어요. GitHub은
기본 브랜치 이름으로 `main`을 사용합니다.

## 새 브랜치 만들기
다른 사람과 겹치지 않을 만한 이름으로 브랜치를 만들고[^1], 해당 브랜치로 전환하세요.
브랜치 이름으로는 자신의 유저네임을 쓰는 걸 추천합니다 (그러면 안 겹칠
테니까).

## 커밋 만들기
1. 디렉토리 안에 자신의 유저네임을 이름으로 갖는 파일을 만드세요. 
2. 수업에서 배운 마크다운으로 간단한 자기소개 글을 작성하고 저장하세요.
3. 새로 만든 파일을 커밋하세요.  

## 브랜치 푸시하기
이제 커밋을 만들었으니, 새 커밋을 가리키는 브랜치를 GitHub으로 업로드할 차례입니다. 이 과정을
푸시(push)라고 합니다. 브랜치 푸시에는 `git push` 명령어를 사용합니다.

## 풀 리퀘스트 만들기
위의 [Pull requests] 탭을 누르면 현재 진행 중인 풀 리퀘스트 목록을 보고, 또 새 풀 리퀘스트를 만들 수
있습니다. [New pull request]를 눌러 방금 푸시한 브랜치로 풀 리퀘스트를 만들어 보세요.

[Pull requests]: https://github.com/bacchus-snu/github-practice-2025spring/pulls
[New pull request]: https://github.com/bacchus-snu/github-practice-2025spring/compare

---

여기까지 완료하는 것이 실습입니다. 이 과정을 통해 GitHub을 사용한 대략적인 작업 과정을 확인해 볼 수
있습니다.

[^1]: 사실 복제 전에 Fork를 하면 이름이 겹칠 걱정을 안 해도 되는데, 지금 당장은 다루지 않도록
  하겠습니다.
