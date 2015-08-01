방송평점서비스 만들기
=====

- 루비 온 레일즈 기초 지식을 활용해 간단한 평점 서비스를 만들어 봅시다

## 커리큘럼 목적

- 루비 온 레일즈 기본기를 다지기 위한 커리큘럼입니다
- 서비스 하나를 간단하게 처음부터 끝까지 만들어봅니다
- 이러한 토이 프로젝트 개발을 반복하다보면 루비 온 레일즈에 자신감이 붙게 됩니다

## 다루는 내용

- 부트스트랩을 활용하여 웹 페이지 꾸미기
- Devise Gem을 활용한 로그인 기능 구현
- DB에 방송 정보 쓰기
- 별점 및 코멘트 기능 구현

## 항상 머리 속에 있어야 할 틀

![웹 프레임 워크의 구조 - MVC](https://s3-ap-northeast-1.amazonaws.com/cycorld/webframework)

## 이 커리큘럼의 응용

- 맛집 평가 서비스 (구글 맵 API 활용)
- 강의 평가 서비스 (크롤링/파싱을 통한 강의 정보 수집 필요)

## 참고자료

- [부트스트랩](http://getbootstrap.com/)
- [부트스트랩 테마(부츠와치)](https://bootswatch.com/)
- [Devise](https://github.com/plataformatec/devise)
- [별점 관련 블로그](http://rog.ie/blog/css-star-rater)

## 수업 중 참고할 git 명령어

- git 현황 확인 : git status
- 수정하던 내용 되돌리기 : git reset --hard
- Untracked File 지우기 : git clean -f -d
- 특정 상태로 옮겨가기 : git checkout [TAG NAME]

## git으로 진도 따라가기

- **수업 시작하기!! : git checkout init**
- git reset --hard 와 git clean -f -d 로 자신의 작업 날려버린 후
- 홈 디자인까지 : git checkout design
- 디테일 페이지 디자인까지 : git checkout detail
- 업로드 페이지 디자인까지 : git checkout upload
- 시드 파일까지 : git checkout seed
