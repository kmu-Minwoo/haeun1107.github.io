---
layout: post
title:  "Google Analytics"
date:   2021-11-26 02:28:13 +0900
categories: story
comments: true
---

## __Google Analytics__

- __Google Analytics란__

구글 애널리틱스(Google Analytics)는 현재 구글 마케팅 플랫폼 브랜드 내의 플랫폼으로서, 웹사이트 트래픽을 추적하고 보고하는 구글이 제공하는 웹 애널리틱스 서비스이다.

무료이며, 복잡한 설치과정 없이 페이지에 코드 하나만 삽입하면 누구나 운영 중인 서비스에 유입하는 사용자들의 행동을 추적하여 분석할 수 있다.

## __Google Analytics를 추가한 과정__

- __Google Analytics 접속__

https://analytics.google.com/에 접속하여 애널리틱스 게정을 생성합니다.


- __속성 설정__

블로그 주소, 카테고리, 보고시간대 선택 후 만들기를 클릭합니다.

- __tracking ID 찾기__

Analystics의 가장 하단에 있는 관리에서 데이터 스트림 버튼을 클릭합니다. 스트림 목록에서 현재의 Github Blog 주소를 클릭하면, 우측 상단에서 tracking ID를 찾을 수 있습니다.

- ___config.yml 수정하기__

코드를 복사해와서 _config.yml 파일에 tracking id값을 붙여넣습니다.


- __연결 확인__

재접속 후 방문자 수가 카운팅 되는 것을 확인합니다. 일자마다 그래프가 생성되고 현재 실시간으로 보고있는 인원 또한 볼 수 있습니다.
