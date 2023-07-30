# 부산로봇경진대회 로봇공성전용 뽑기 파일
공성전 뽑기 바로가기:
https://kbj2934.github.io/robotSiege/
PC에서 화면이 잘려나올 시 Ctrl + '-' 키를 눌러 화면을 축소시키면 됩니다.

이 페이지는 로봇경진대회 로봇공성전용 뽑기 파일입니다.
기본적인 프론트엔드 개발 지식을 가진 개발자가 chatGPT의 코딩 기능을 이용해서 개발했습니다.
개발 언어는 CSS, HTML, 자바스크립트입니다.

## 첫 번째 요구:
> HTML을 이용해서 화면을 div로 분할하는 걸 만들거야.
> 먼저 화면 상단의 높이 50%, 폭 100%를 차지하도록 top을 만들어.
> 화면 하단의 높이 50%는 각각 폭 30%, 30%, 40%를 차지하도록 3개로 나눠서 순서대로 left, center, right로 이름붙여줘.
> 위 코드의 구역마다 그림파일을 넣을거야. 그림파일은 화면 크기가 달라지면 자동으로 크기가 달라지도록 해줘


## 두 번째 요구:
> top구역에는 main.png가 출력될거야. bottom에는 s01.png, s02.png, s03.png, s04.png 파일이 0.2초 간격으로 바뀌도록 해줘.
> center구역에는 d01.png, d02.png 파일이 0.3초 간격으로 바뀌도록 해줘. right구역에는 c01.png, c02.png, c03.png, c04.png파일이 0.4초 간격으로 바뀌도록 해줘.
> 처음에는 그림이 멈춰 있다가 스페이스바를 누르거나 main.png파일을 누르면 그림이 바뀌도록 토글하는 기능을 자바스크립트로 구현해줘.

## 세 번째 요구:
> 위 화면을 PC에서는 그대로 보이게 하고, 모바일에서는 top, bottom, center, right이 각각 25%의 높이를 갖도록 반응형으로 해줘
> 모바일과 PC화면이 다르게 보이도록 뷰포트 태그도 넣어줘.
