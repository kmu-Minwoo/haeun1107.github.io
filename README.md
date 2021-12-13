## repoitory 생성

Github에 새 저장소인 repository(haeun1107.github.io)를 생성했습니다.

## Local-Remote repository 연동

git clone을 통해 Remote repository의 주소를 복사하여 Local-Remote repository를 연동했습니다.

## index.html 작성

예시 파일인 index.html를 작성한 후 git add, git commit, git push를 통해 원격 저장소에 반영하려 했지만 실패했습니다.

## Personal Access Token(PAT) 생성

github의 Setting에서 Developer settings, Generate new token을 선택하고 Note(토큰 메모), Expiration(유효기간), Scope(권한 범위) 결정한 후 토큰을 생성했습니다.

## git push로 원격 저장소에 반영

Password에 PAT을 입력하여 git push를 성공했습니다.

## Github Page에서 주소(haeun1107.github.io)로 접속 확인

주소(haeun1107.github.io)로 접속했더니 index.html 문서가 떴고,  Github Page 설정을 성공했습니다.

## Jekyll 설치

bundle exec jekyll serve 실행 후, localhost:4000에 접속했습니다. 기본 테마로 된 Jekyll 사이트가 생성되었습니다.

## _config.yml 수정

대부분의 블로그 속성을 관리하는 _config.yml 파일을 제 블로그의 컨셉에 맞게 수정하였습니다.

## Post Upload

_posts 폴더에 새로운 문서(2021-11-17-haeun1107-story.md)를 생성하여 Markdown 형식을 통해 내용을 작성하였습니다. Local에 commit으로 반영한 후, Remote로 push했습니다.

## Jekyll 테마 적용

다양한 목적에 맞는 템플릿들 중에 jekyll-theme-yat라는 테마를 선택했습니다. 선택한 테마의 원격 저장소를 나의 원격 저장소로 fork해온 후 저장소의 이름을 haeun1107.github.io로 변경했습니다. git clone을 통해 받아온 후, 작업을 계속했습니다.

## Customize blog

댓글 기능을 추가하기 위해 Disqus 홈페이지에서 Disqus에 가입을 하고 세팅했습니다.

## Blog에 Disqus 반영 (댁글 기능 추가)

_config.yml 파일에 key-value를 추가했습니다. disqus 홈페이지에서 Universal Code를 복사한 후, _includes/extensions/comments/disqus.html 파일을 페이지에 맞게 수정했습니다. 주석 해제 후, PAGE_URL과 PAGE_IDENTIFIER를 설정하고 s.src가 잘 지정되어있는지 확인했고, 댓글을 허용하고 싶은 곳인 2021-11-17-haeun1107-story.md와 2021-11-26-Git.md, 2021-12-01-markdown.md 에 comments: True로 지정했습니다.

## favicon 기능 추가

웹페이지 접속 시 상단 탭에 국민대학교 로고 아이콘이 보여질 수 있도록 favicon을 추가해주었습니다. 먼저 kookmin.ico라는 파비콘 파일을 만들고 head.html에서 <head> 부분에 코드를 추가했습니다.

## Google Analytics 기능 추가

웹페이지 방문자의 유입 경로, 오래 본 페이지 등을 확인할 수 있는 Google Analytics 기능을 추가했습니다. 먼저 Google Analytics에 접속하여 로그인했고, tracking ID를 찾아 그에 맞게 _config.yml을 수정하였습니다. 그리고 head.html에 에널리틱스 태그를 추가했습니다. 기능을 추가한 과정을 post로 작성하였습니다.

## 나만의 Blog 완성!

나의 Blog 분위기에 맞게 내용을 수정하여 나만의 Blog를 완성했습니다!