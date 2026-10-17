<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/name-burst-dark.svg?v=1">
  <img alt="이상진" src="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/name-burst-light.svg?v=1" width="100%">
</picture>

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/header-dark-m.svg?v=6">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/header-light-m.svg?v=6">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/header-dark.svg?v=6">
  <img alt="이상진" src="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/header-light.svg?v=6" width="100%">
</picture>

> [!NOTE]
> 지금은 혼자 만든 학식 리뷰 서비스 [모나와](https://www.monawa.site)를 운영하면서 가족 체력 서비스 우리가족 체력키움의 프론트엔드를 만들고 있습니다.

고등학교 때 문제 풀이로 코딩을 배우다가, 카카오톡 봇을 만들면서 직접 만드는 재미를 알았습니다. 학교 학식표를 긁어 오는 안드로이드 앱도 그때 만들었습니다. 대학에서는 웹 팀 프로젝트마다 서버와 배포를 주로 맡았고, 화면이 필요하면 화면도 만들었습니다.

## projects/

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/board-dark.svg?v=1">
  <img alt="출발" src="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/board-light.svg?v=1" width="100%">
</picture>

<details open>
<summary><kbd>2026</kbd>&ensp;<b>모나와</b>&ensp;학식 리뷰 서비스</summary>
<br>

<img src="assets/monawa.webp" alt="모나와 홈, 랭킹, 메뉴 상세, 검색 화면" width="100%">
<br><br>

학교 식단표에는 메뉴 이름만 있어서 먹어 봐야 맛을 알 수 있었습니다. 그래서 학생들이 남긴 사진과 별점을 보고 오늘 뭘 먹을지 고르는 서비스를 만들었습니다. 기획과 디자인, 개발, 운영을 모두 혼자 합니다.

메뉴에서 존맛, 먹을만, 노맛 중 하나를 고르고 별점 등록을 누르면 끝납니다. 매일 아침 7시에 GitHub Actions가 학교 학식 페이지를 읽어 와 식당과 코너, 가격을 정리하고, 같은 이름의 메뉴는 하나로 합쳐서 예전에 쌓인 리뷰가 그대로 이어집니다. 방학 동안 만들어 개강 전에 열었고, 학기 중에는 매주 리뷰 추첨 이벤트를 열면서 들어오는 제보를 하나씩 처리합니다.

```yaml
period: 2026.08~ (운영 중)
team:   혼자
role:   기획, 디자인, 프론트엔드, 백엔드, 인프라
stack:  Next.js, TypeScript, Tailwind CSS, PostgreSQL(RDS),
        S3, Amplify, GitHub Actions
```

[www.monawa.site](https://www.monawa.site)

</details>

<details>
<summary><kbd>2026</kbd>&ensp;<b>체력키움</b>&ensp;가족 체력 서비스</summary>
<br>

<img src="assets/kium.webp" alt="체력키움 아이 홈의 3D 섬, 부모 홈, 가족 리그, 오늘 운동 화면" width="100%">
<br><br>

우리가족 체력키움은 국민체력100 공공데이터로 아이 체력을 재고, 부모와 아이가 같이 운동을 이어 가게 만드는 서비스입니다. 국민대 알파프로젝트로 시작해 한국스포츠정책과학원 공공데이터 활용 경진대회에 냈고, 저는 프론트엔드 전체와 시연용 AWS 배포를 맡고 있습니다. 아이 홈은 three.js로 만든 3D 섬이고, 운동한 날마다 섬에 나무가 한 그루씩 자랍니다.

```yaml
period: 2026.09~ (개발 중)
team:   국민대 알파프로젝트
role:   프론트엔드, AWS 배포
stack:  Next.js, TypeScript, three.js, TanStack Query,
        Zustand, Tailwind CSS, Lightsail, CloudFront
```

[family-fitness/family-fitness-fe](https://github.com/family-fitness/family-fitness-fe)

</details>

<details>
<summary><kbd>2026</kbd>&ensp;<b>두띵</b>&ensp;동아리 굿즈 공동구매</summary>
<br>

<img src="assets/doothing.webp" alt="두띵 디자인 에디터" width="100%">
<br><br>

동아리들은 굿즈를 만들 때 구글폼으로 주문을 받고 단톡방에서 입금을 하나하나 확인했습니다. 두띵은 굿즈 디자인과 펀딩, 입금, 제작을 한곳에서 하도록 만든 사이트이고, 제가 가장 많은 시간을 들인 프로젝트입니다.

처음 보는 다른 학과 학생 세 명이 모였고, 코딩을 할 줄 아는 사람은 저 하나였습니다. 그래서 시작하기 전에 깃허브와 AI 도구 쓰는 법을 먼저 설명하고, 깃허브 가이드와 PR 템플릿, 한국어 자동 코드 리뷰를 만들었습니다. 굿즈의 앞, 뒤, 옆 면에 직접 디자인을 올리는 에디터를 만들었고, 서버에서는 무통장입금 펀딩 주문과 마감, 알림, 관리자 기능을 맡았습니다. 화면은 S3, API는 EC2로 나눠 CloudFront 뒤에 배포했습니다. 카드 결제와 실시간 채팅, 소셜 로그인은 팀원이 만들었습니다.

```yaml
period: 2026.04~06
team:   AWS 실전 프로젝트, 3명
role:   서버, 배포, 화면
stack:  Node.js, Express, TypeScript, PostgreSQL,
        EC2, S3, CloudFront, HTML/CSS/JS
```

[AWS-PORJECT-2/AWS_PROJECT_2](https://github.com/AWS-PORJECT-2/AWS_PROJECT_2)

</details>

<details>
<summary><kbd>2026</kbd>&ensp;<b>KDD</b>&ensp;학사 규정 챗봇</summary>
<br>

<img src="assets/kdd.webp" alt="KDD가 질문에 근거 문서와 출처를 붙여 답하는 화면" width="100%">
<br><br>

학칙이나 규정을 물어보면 실제 문서를 인용해서 출처와 함께 답하는 챗봇입니다. 교내 학생을 대상으로 오픈베타를 했습니다. 저는 문서와 FAQ, 통계를 다루는 Spring 백엔드를 맡았고, 매일 새벽 최근 질문을 모아 FAQ 후보를 만드는 스케줄러도 넣었습니다. 화면은 Next.js로, 답을 만드는 AI 서버와 벡터 검색은 팀원들이 만들었습니다.

```yaml
period: 2026.03~06 (교내 오픈베타)
team:   4명
role:   Spring 백엔드 (문서, AI 서버 연동, FAQ, 통계)
stack:  Java 17, Spring Boot 3.4, JPA, PostgreSQL, Flyway
```

[KDD-Kookmin-Digital-Doc](https://github.com/KDD-Kookmin-Digital-Doc)

</details>

<details>
<summary><kbd>2026</kbd>&ensp;<b>오늘어디</b>&ensp;반복 경로 출발 알림</summary>
<br>

<img src="assets/today.webp" alt="직접 만든 오늘어디 소개 사이트" width="100%">
<br><br>

자주 가는 길을 한 번 등록해 두면 그날 교통 상황으로 출발 시각을 계산해서 웹 푸시로 알려 줍니다. 캡스톤디자인 수업에서 네 명이 만들었고, 저는 경로와 장소 검색, 푸시를 맡은 백엔드와 DB 스키마를 만들었습니다. 경로는 ODsay 대중교통 경로와 TMAP 보행자 경로를 이어 붙여 하나로 만듭니다. 서비스를 알리는 손그림 콘셉트의 소개 사이트도 만들었습니다.

```yaml
period: 2026.03~06
team:   캡스톤디자인, 4명
role:   백엔드 (경로, 장소 검색, 푸시), DB 스키마, 프론트 일부
stack:  Spring Boot, MySQL, Web Push, React PWA,
        ODsay, TMAP, Kakao
```

[kookmin-sw/2026-capstone-53](https://github.com/kookmin-sw/2026-capstone-53)&ensp;[소개 사이트](https://kookmin-sw.github.io/2026-capstone-53/)

</details>

<details>
<summary><kbd>2025</kbd>&ensp;<b>Aivive</b>&ensp;LLM 식단 관리 앱</summary>
<br>

<img src="assets/aivive.webp" alt="Aivive 홈, 식단 관리, 프로필 화면" width="100%">
<br><br>

식사와 물, 운동을 한곳에 기록하고 Gemini에게 식단 조언을 받는 안드로이드 앱입니다. 모바일프로그래밍 수업에서 세 명이 만들었고, 저는 식단 관리와 캘린더, 프로필을 맡았습니다. 모델의 답을 화면의 숫자로 쓰려고 프롬프트로 답의 형식을 정하고, 받은 값은 정규식으로 한 번 더 확인했습니다. LLM 답을 코드에서 다뤄 본 첫 프로젝트입니다.

```yaml
period: 2025.10~11
team:   모바일프로그래밍 수업, 3명
role:   식단 관리, 캘린더, 프로필
stack:  Android(Java), Room, Google Gemini
```

[tldbs0420/Team_9-MobileProgramming_2025](https://github.com/tldbs0420/Team_9-MobileProgramming_2025)

</details>

<details>
<summary><kbd>2025</kbd>&ensp;<b>SECTION NULL</b>&ensp;좀비 생존 FPS</summary>
<br>

<img src="assets/section-null.webp" alt="SECTION NULL 플레이 화면" width="100%">
<br><br>

Unity로 만든 좀비 생존 FPS입니다. 게임소프트웨어 수업에서 네 명이 만들어 itch.io에 올렸고, 제 첫 Unity 작업이었습니다. 아이템 파밍과 거점, 오염구역, 총기 소리를 맡았고, 최종 빌드의 화면 UI는 전부 제가 만들었습니다.

```yaml
period: 2025.10~11
team:   게임소프트웨어 수업, 4명
role:   플레이어 스탯, 아이템 파밍, 거점, 오염구역,
        인게임 UI, 사운드
stack:  Unity 6, C#, ScriptableObject, New Input System
```

[tldbs0420/Team_6-GameSoftware_2025](https://github.com/tldbs0420/Team_6-GameSoftware_2025)&ensp;[itch.io](https://ssutte.itch.io/section-null)

</details>

## pg-reward-order-repository.ts

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/code-dark.svg?v=1">
  <img alt="pg-reward-order-repository.ts" src="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/code-light.svg?v=1" width="100%">
</picture>

## reel/

<p align="center">
<img src="assets/reel/burst.webp" alt="burst" width="49%">
<img src="assets/reel/fold.webp" alt="fold" width="49%">
<img src="assets/reel/wobbly.webp" alt="wobbly" width="49%">
<img src="assets/reel/ascii.webp" alt="ascii" width="49%">
<img src="assets/reel/shock.webp" alt="shock" width="49%">
<img src="assets/reel/01-kium.webp" alt="01-kium.md" width="49%">
<img src="assets/reel/03-doothing.webp" alt="03-doothing.md" width="49%">
<img src="assets/reel/04-kdd.webp" alt="04-kdd.md" width="49%">
<img src="assets/reel/05-today.webp" alt="05-today.md" width="49%">
<img src="assets/reel/06-aivive.webp" alt="06-aivive.md" width="49%">
<img src="assets/reel/07-section-null.webp" alt="07-section-null.md" width="49%">
</p>

## skills.json

```json
{
  "role":      "Full-stack Developer",
  "frontend":  ["Next.js", "React", "three.js", "Tailwind CSS", "TanStack Query"],
  "backend":   ["Spring Boot", "JPA", "Flyway", "Node.js", "Express"],
  "database":  ["PostgreSQL", "MySQL", "Room"],
  "cloud":     ["AWS EC2", "S3", "CloudFront", "RDS", "Amplify", "Lightsail", "GitHub Actions"],
  "languages": ["Java", "JavaScript", "TypeScript", "Python", "C++", "C#", "SQL"],
  "tools":     ["Git", "Docker", "Android", "Unity"],
  "ai_tools":  ["Claude Code", "Codex", "오픈클로", "Stable Diffusion(로컬)", "Gemini"],
  "certs":     ["AWS Cloud Practitioner", "SQLD", "리눅스마스터 2급", "정보처리기능사"]
}
```

## journey.log

```mermaid
%%{init: {"themeCSS": ".commit-label-bkg{fill:#8c959f;fill-opacity:.14;opacity:1}", "gitGraph": {"rotateCommitLabel": false}, "themeVariables": {"commitLabelFontSize": "13px", "git0": "#2c5ee8", "git1": "#7e98ba", "git2": "#7e98ba", "git3": "#7e98ba", "gitBranchLabel0": "#ffffff", "gitBranchLabel1": "#0d1117", "gitBranchLabel2": "#0d1117", "gitBranchLabel3": "#0d1117", "gitInv0": "#ffffff"}}}%%
gitGraph TB:
  commit id: "init 웹 파싱 봇과 학식 앱"
  commit id: "2019.07 리눅스마스터 2급"
  commit id: "2019.09 정보처리기능사"
  commit id: "2021.03 국민대학교 소프트웨어학부 입학"
  commit id: "2025.04 SQLD"
  branch team
  commit id: "2025.10 Aivive"
  commit id: "2025.10 SECTION NULL"
  checkout main
  merge team id: "2025.11 두 프로젝트 마무리"
  checkout team
  commit id: "2026.03 KDD"
  commit id: "2026.03 오늘어디"
  commit id: "2026.04 두띵"
  checkout main
  commit id: "2026.04 AWS Cloud Practitioner"
  merge team id: "2026.06 세 프로젝트 마무리"
  branch monawa
  commit id: "2026.08~ 모나와 운영"
  checkout main
  branch kium
  commit id: "2026.09~ 우리가족 체력키움"
```

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/output/snake-dark.svg">
  <img alt="잔디를 먹는 뱀" src="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/output/snake-light.svg" width="100%">
</picture>

## skyline.stl

```stl
solid skyline
facet normal 0 0 1
outer loop
vertex -6.82 -.72 1.05
vertex 6.83 -.72 1.05
vertex 6.83 1.43 1.05
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.82 -.72 1.05
vertex 6.83 1.43 1.05
vertex -6.82 1.43 1.05
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -7.17 -1.77 0
vertex 7.17 -1.77 0
vertex 6.83 -.72 1.05
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -7.17 -1.77 0
vertex 6.83 -.72 1.05
vertex -6.82 -.72 1.05
endloop
endfacet
facet normal .95 0 .32
outer loop
vertex 7.17 -1.77 0
vertex 7.17 1.77 0
vertex 6.83 1.43 1.05
endloop
endfacet
facet normal .95 0 .32
outer loop
vertex 7.17 -1.77 0
vertex 6.83 1.43 1.05
vertex 6.83 -.72 1.05
endloop
endfacet
facet normal 0 .95 .32
outer loop
vertex 7.17 1.77 0
vertex -7.17 1.77 0
vertex -6.82 1.43 1.05
endloop
endfacet
facet normal 0 .95 .32
outer loop
vertex 7.17 1.77 0
vertex -6.82 1.43 1.05
vertex 6.83 1.43 1.05
endloop
endfacet
facet normal -.95 0 .32
outer loop
vertex -7.17 1.77 0
vertex -7.17 -1.77 0
vertex -6.82 -.72 1.05
endloop
endfacet
facet normal -.95 0 .32
outer loop
vertex -7.17 1.77 0
vertex -6.82 -.72 1.05
vertex -6.82 1.43 1.05
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.17 -1.77 0
vertex -7.17 1.77 0
vertex 7.17 1.77 0
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.17 -1.77 0
vertex 7.17 1.77 0
vertex 7.17 -1.77 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.61 -.26 1.75
vertex -6.38 -.26 1.75
vertex -6.38 -.03 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.61 -.26 1.75
vertex -6.38 -.03 1.75
vertex -6.61 -.03 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.61 -.26 1.05
vertex -6.38 -.26 1.05
vertex -6.38 -.26 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.61 -.26 1.05
vertex -6.38 -.26 1.75
vertex -6.61 -.26 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -6.38 -.03 1.05
vertex -6.61 -.03 1.05
vertex -6.61 -.03 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -6.38 -.03 1.05
vertex -6.61 -.03 1.75
vertex -6.38 -.03 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.61 -.03 1.05
vertex -6.61 -.26 1.05
vertex -6.61 -.26 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.61 -.03 1.05
vertex -6.61 -.26 1.75
vertex -6.61 -.03 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.38 -.26 1.05
vertex -6.38 -.03 1.05
vertex -6.38 -.03 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.38 -.26 1.05
vertex -6.38 -.03 1.75
vertex -6.38 -.26 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.36 .74 1.53
vertex -6.13 .74 1.53
vertex -6.13 .97 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.36 .74 1.53
vertex -6.13 .97 1.53
vertex -6.36 .97 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.36 .74 1.05
vertex -6.13 .74 1.05
vertex -6.13 .74 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.36 .74 1.05
vertex -6.13 .74 1.53
vertex -6.36 .74 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -6.13 .97 1.05
vertex -6.36 .97 1.05
vertex -6.36 .97 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -6.13 .97 1.05
vertex -6.36 .97 1.53
vertex -6.13 .97 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.36 .97 1.05
vertex -6.36 .74 1.05
vertex -6.36 .74 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.36 .97 1.05
vertex -6.36 .74 1.53
vertex -6.36 .97 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.13 .74 1.05
vertex -6.13 .97 1.05
vertex -6.13 .97 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.13 .74 1.05
vertex -6.13 .97 1.53
vertex -6.13 .74 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.11 -.26 1.75
vertex -5.88 -.26 1.75
vertex -5.88 -.03 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -6.11 -.26 1.75
vertex -5.88 -.03 1.75
vertex -6.11 -.03 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.11 -.26 1.05
vertex -5.88 -.26 1.05
vertex -5.88 -.26 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -6.11 -.26 1.05
vertex -5.88 -.26 1.75
vertex -6.11 -.26 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -5.88 -.03 1.05
vertex -6.11 -.03 1.05
vertex -6.11 -.03 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -5.88 -.03 1.05
vertex -6.11 -.03 1.75
vertex -5.88 -.03 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.11 -.03 1.05
vertex -6.11 -.26 1.05
vertex -6.11 -.26 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.11 -.03 1.05
vertex -6.11 -.26 1.75
vertex -6.11 -.03 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.88 -.26 1.05
vertex -5.88 -.03 1.05
vertex -5.88 -.03 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.88 -.26 1.05
vertex -5.88 -.03 1.75
vertex -5.88 -.26 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.11 .74 1.53
vertex -3.88 .74 1.53
vertex -3.88 .97 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.11 .74 1.53
vertex -3.88 .97 1.53
vertex -4.11 .97 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.11 .74 1.05
vertex -3.88 .74 1.05
vertex -3.88 .74 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.11 .74 1.05
vertex -3.88 .74 1.53
vertex -4.11 .74 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.88 .97 1.05
vertex -4.11 .97 1.05
vertex -4.11 .97 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.88 .97 1.05
vertex -4.11 .97 1.53
vertex -3.88 .97 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.11 .97 1.05
vertex -4.11 .74 1.05
vertex -4.11 .74 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.11 .97 1.05
vertex -4.11 .74 1.53
vertex -4.11 .97 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.88 .74 1.05
vertex -3.88 .97 1.05
vertex -3.88 .97 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.88 .74 1.05
vertex -3.88 .97 1.53
vertex -3.88 .74 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.11 -.01 1.53
vertex -3.88 -.01 1.53
vertex -3.88 .22 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.11 -.01 1.53
vertex -3.88 .22 1.53
vertex -4.11 .22 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.11 -.01 1.05
vertex -3.88 -.01 1.05
vertex -3.88 -.01 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -4.11 -.01 1.05
vertex -3.88 -.01 1.53
vertex -4.11 -.01 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.88 .22 1.05
vertex -4.11 .22 1.05
vertex -4.11 .22 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.88 .22 1.05
vertex -4.11 .22 1.53
vertex -3.88 .22 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.11 .22 1.05
vertex -4.11 -.01 1.05
vertex -4.11 -.01 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.11 .22 1.05
vertex -4.11 -.01 1.53
vertex -4.11 .22 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.88 -.01 1.05
vertex -3.88 .22 1.05
vertex -3.88 .22 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.88 -.01 1.05
vertex -3.88 .22 1.53
vertex -3.88 -.01 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.86 .24 1.53
vertex -3.63 .24 1.53
vertex -3.63 .47 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.86 .24 1.53
vertex -3.63 .47 1.53
vertex -3.86 .47 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.86 .24 1.05
vertex -3.63 .24 1.05
vertex -3.63 .24 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.86 .24 1.05
vertex -3.63 .24 1.53
vertex -3.86 .24 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.63 .47 1.05
vertex -3.86 .47 1.05
vertex -3.86 .47 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.63 .47 1.05
vertex -3.86 .47 1.53
vertex -3.63 .47 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.86 .47 1.05
vertex -3.86 .24 1.05
vertex -3.86 .24 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.86 .47 1.05
vertex -3.86 .24 1.53
vertex -3.86 .47 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.63 .24 1.05
vertex -3.63 .47 1.05
vertex -3.63 .47 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.63 .24 1.05
vertex -3.63 .47 1.53
vertex -3.63 .24 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.86 -.01 2.17
vertex -3.63 -.01 2.17
vertex -3.63 .22 2.17
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.86 -.01 2.17
vertex -3.63 .22 2.17
vertex -3.86 .22 2.17
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.86 -.01 1.05
vertex -3.63 -.01 1.05
vertex -3.63 -.01 2.17
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.86 -.01 1.05
vertex -3.63 -.01 2.17
vertex -3.86 -.01 2.17
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.63 .22 1.05
vertex -3.86 .22 1.05
vertex -3.86 .22 2.17
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.63 .22 1.05
vertex -3.86 .22 2.17
vertex -3.63 .22 2.17
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.86 .22 1.05
vertex -3.86 -.01 1.05
vertex -3.86 -.01 2.17
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.86 .22 1.05
vertex -3.86 -.01 2.17
vertex -3.86 .22 2.17
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.63 -.01 1.05
vertex -3.63 .22 1.05
vertex -3.63 .22 2.17
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.63 -.01 1.05
vertex -3.63 .22 2.17
vertex -3.63 -.01 2.17
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.61 .74 2
vertex -3.38 .74 2
vertex -3.38 .97 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.61 .74 2
vertex -3.38 .97 2
vertex -3.61 .97 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.61 .74 1.05
vertex -3.38 .74 1.05
vertex -3.38 .74 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.61 .74 1.05
vertex -3.38 .74 2
vertex -3.61 .74 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.38 .97 1.05
vertex -3.61 .97 1.05
vertex -3.61 .97 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.38 .97 1.05
vertex -3.61 .97 2
vertex -3.38 .97 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.61 .97 1.05
vertex -3.61 .74 1.05
vertex -3.61 .74 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.61 .97 1.05
vertex -3.61 .74 2
vertex -3.61 .97 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.38 .74 1.05
vertex -3.38 .97 1.05
vertex -3.38 .97 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.38 .74 1.05
vertex -3.38 .97 2
vertex -3.38 .74 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.61 .49 1.93
vertex -3.38 .49 1.93
vertex -3.38 .72 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.61 .49 1.93
vertex -3.38 .72 1.93
vertex -3.61 .72 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.61 .49 1.05
vertex -3.38 .49 1.05
vertex -3.38 .49 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.61 .49 1.05
vertex -3.38 .49 1.93
vertex -3.61 .49 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.38 .72 1.05
vertex -3.61 .72 1.05
vertex -3.61 .72 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.38 .72 1.05
vertex -3.61 .72 1.93
vertex -3.38 .72 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.61 .72 1.05
vertex -3.61 .49 1.05
vertex -3.61 .49 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.61 .72 1.05
vertex -3.61 .49 1.93
vertex -3.61 .72 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.38 .49 1.05
vertex -3.38 .72 1.05
vertex -3.38 .72 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.38 .49 1.05
vertex -3.38 .72 1.93
vertex -3.38 .49 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.61 -.01 1.53
vertex -3.38 -.01 1.53
vertex -3.38 .22 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.61 -.01 1.53
vertex -3.38 .22 1.53
vertex -3.61 .22 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.61 -.01 1.05
vertex -3.38 -.01 1.05
vertex -3.38 -.01 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.61 -.01 1.05
vertex -3.38 -.01 1.53
vertex -3.61 -.01 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.38 .22 1.05
vertex -3.61 .22 1.05
vertex -3.61 .22 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.38 .22 1.05
vertex -3.61 .22 1.53
vertex -3.38 .22 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.61 .22 1.05
vertex -3.61 -.01 1.05
vertex -3.61 -.01 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.61 .22 1.05
vertex -3.61 -.01 1.53
vertex -3.61 .22 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.38 -.01 1.05
vertex -3.38 .22 1.05
vertex -3.38 .22 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.38 -.01 1.05
vertex -3.38 .22 1.53
vertex -3.38 -.01 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.36 .49 1.65
vertex -3.13 .49 1.65
vertex -3.13 .72 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.36 .49 1.65
vertex -3.13 .72 1.65
vertex -3.36 .72 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.36 .49 1.05
vertex -3.13 .49 1.05
vertex -3.13 .49 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.36 .49 1.05
vertex -3.13 .49 1.65
vertex -3.36 .49 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.13 .72 1.05
vertex -3.36 .72 1.05
vertex -3.36 .72 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.13 .72 1.05
vertex -3.36 .72 1.65
vertex -3.13 .72 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.36 .72 1.05
vertex -3.36 .49 1.05
vertex -3.36 .49 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.36 .72 1.05
vertex -3.36 .49 1.65
vertex -3.36 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.13 .49 1.05
vertex -3.13 .72 1.05
vertex -3.13 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.13 .49 1.05
vertex -3.13 .72 1.65
vertex -3.13 .49 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.36 -.01 1.65
vertex -3.13 -.01 1.65
vertex -3.13 .22 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.36 -.01 1.65
vertex -3.13 .22 1.65
vertex -3.36 .22 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.36 -.01 1.05
vertex -3.13 -.01 1.05
vertex -3.13 -.01 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.36 -.01 1.05
vertex -3.13 -.01 1.65
vertex -3.36 -.01 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.13 .22 1.05
vertex -3.36 .22 1.05
vertex -3.36 .22 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.13 .22 1.05
vertex -3.36 .22 1.65
vertex -3.13 .22 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.36 .22 1.05
vertex -3.36 -.01 1.05
vertex -3.36 -.01 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.36 .22 1.05
vertex -3.36 -.01 1.65
vertex -3.36 .22 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.13 -.01 1.05
vertex -3.13 .22 1.05
vertex -3.13 .22 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.13 -.01 1.05
vertex -3.13 .22 1.65
vertex -3.13 -.01 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.36 -.26 1.53
vertex -3.13 -.26 1.53
vertex -3.13 -.03 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.36 -.26 1.53
vertex -3.13 -.03 1.53
vertex -3.36 -.03 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.36 -.26 1.05
vertex -3.13 -.26 1.05
vertex -3.13 -.26 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.36 -.26 1.05
vertex -3.13 -.26 1.53
vertex -3.36 -.26 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.13 -.03 1.05
vertex -3.36 -.03 1.05
vertex -3.36 -.03 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -3.13 -.03 1.05
vertex -3.36 -.03 1.53
vertex -3.13 -.03 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.36 -.03 1.05
vertex -3.36 -.26 1.05
vertex -3.36 -.26 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.36 -.03 1.05
vertex -3.36 -.26 1.53
vertex -3.36 -.03 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.13 -.26 1.05
vertex -3.13 -.03 1.05
vertex -3.13 -.03 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.13 -.26 1.05
vertex -3.13 -.03 1.53
vertex -3.13 -.26 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.11 .49 1.65
vertex -2.88 .49 1.65
vertex -2.88 .72 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.11 .49 1.65
vertex -2.88 .72 1.65
vertex -3.11 .72 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.11 .49 1.05
vertex -2.88 .49 1.05
vertex -2.88 .49 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.11 .49 1.05
vertex -2.88 .49 1.65
vertex -3.11 .49 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.88 .72 1.05
vertex -3.11 .72 1.05
vertex -3.11 .72 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.88 .72 1.05
vertex -3.11 .72 1.65
vertex -2.88 .72 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.11 .72 1.05
vertex -3.11 .49 1.05
vertex -3.11 .49 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.11 .72 1.05
vertex -3.11 .49 1.65
vertex -3.11 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.88 .49 1.05
vertex -2.88 .72 1.05
vertex -2.88 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.88 .49 1.05
vertex -2.88 .72 1.65
vertex -2.88 .49 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.11 .24 1.75
vertex -2.88 .24 1.75
vertex -2.88 .47 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.11 .24 1.75
vertex -2.88 .47 1.75
vertex -3.11 .47 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.11 .24 1.05
vertex -2.88 .24 1.05
vertex -2.88 .24 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.11 .24 1.05
vertex -2.88 .24 1.75
vertex -3.11 .24 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.88 .47 1.05
vertex -3.11 .47 1.05
vertex -3.11 .47 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.88 .47 1.05
vertex -3.11 .47 1.75
vertex -2.88 .47 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.11 .47 1.05
vertex -3.11 .24 1.05
vertex -3.11 .24 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.11 .47 1.05
vertex -3.11 .24 1.75
vertex -3.11 .47 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.88 .24 1.05
vertex -2.88 .47 1.05
vertex -2.88 .47 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.88 .24 1.05
vertex -2.88 .47 1.75
vertex -2.88 .24 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.11 -.01 2
vertex -2.88 -.01 2
vertex -2.88 .22 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.11 -.01 2
vertex -2.88 .22 2
vertex -3.11 .22 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.11 -.01 1.05
vertex -2.88 -.01 1.05
vertex -2.88 -.01 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.11 -.01 1.05
vertex -2.88 -.01 2
vertex -3.11 -.01 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.88 .22 1.05
vertex -3.11 .22 1.05
vertex -3.11 .22 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.88 .22 1.05
vertex -3.11 .22 2
vertex -2.88 .22 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.11 .22 1.05
vertex -3.11 -.01 1.05
vertex -3.11 -.01 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.11 .22 1.05
vertex -3.11 -.01 2
vertex -3.11 .22 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.88 -.01 1.05
vertex -2.88 .22 1.05
vertex -2.88 .22 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.88 -.01 1.05
vertex -2.88 .22 2
vertex -2.88 -.01 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.11 -.26 1.53
vertex -2.88 -.26 1.53
vertex -2.88 -.03 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.11 -.26 1.53
vertex -2.88 -.03 1.53
vertex -3.11 -.03 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.11 -.26 1.05
vertex -2.88 -.26 1.05
vertex -2.88 -.26 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -3.11 -.26 1.05
vertex -2.88 -.26 1.53
vertex -3.11 -.26 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.88 -.03 1.05
vertex -3.11 -.03 1.05
vertex -3.11 -.03 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.88 -.03 1.05
vertex -3.11 -.03 1.53
vertex -2.88 -.03 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.11 -.03 1.05
vertex -3.11 -.26 1.05
vertex -3.11 -.26 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.11 -.03 1.05
vertex -3.11 -.26 1.53
vertex -3.11 -.03 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.88 -.26 1.05
vertex -2.88 -.03 1.05
vertex -2.88 -.03 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.88 -.26 1.05
vertex -2.88 -.03 1.53
vertex -2.88 -.26 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 .99 1.65
vertex -2.63 .99 1.65
vertex -2.63 1.22 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 .99 1.65
vertex -2.63 1.22 1.65
vertex -2.86 1.22 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 .99 1.05
vertex -2.63 .99 1.05
vertex -2.63 .99 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 .99 1.05
vertex -2.63 .99 1.65
vertex -2.86 .99 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 1.22 1.05
vertex -2.86 1.22 1.05
vertex -2.86 1.22 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 1.22 1.05
vertex -2.86 1.22 1.65
vertex -2.63 1.22 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 1.22 1.05
vertex -2.86 .99 1.05
vertex -2.86 .99 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 1.22 1.05
vertex -2.86 .99 1.65
vertex -2.86 1.22 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 .99 1.05
vertex -2.63 1.22 1.05
vertex -2.63 1.22 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 .99 1.05
vertex -2.63 1.22 1.65
vertex -2.63 .99 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 .74 1.75
vertex -2.63 .74 1.75
vertex -2.63 .97 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 .74 1.75
vertex -2.63 .97 1.75
vertex -2.86 .97 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 .74 1.05
vertex -2.63 .74 1.05
vertex -2.63 .74 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 .74 1.05
vertex -2.63 .74 1.75
vertex -2.86 .74 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 .97 1.05
vertex -2.86 .97 1.05
vertex -2.86 .97 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 .97 1.05
vertex -2.86 .97 1.75
vertex -2.63 .97 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 .97 1.05
vertex -2.86 .74 1.05
vertex -2.86 .74 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 .97 1.05
vertex -2.86 .74 1.75
vertex -2.86 .97 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 .74 1.05
vertex -2.63 .97 1.05
vertex -2.63 .97 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 .74 1.05
vertex -2.63 .97 1.75
vertex -2.63 .74 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 .24 1.75
vertex -2.63 .24 1.75
vertex -2.63 .47 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 .24 1.75
vertex -2.63 .47 1.75
vertex -2.86 .47 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 .24 1.05
vertex -2.63 .24 1.05
vertex -2.63 .24 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 .24 1.05
vertex -2.63 .24 1.75
vertex -2.86 .24 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 .47 1.05
vertex -2.86 .47 1.05
vertex -2.86 .47 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 .47 1.05
vertex -2.86 .47 1.75
vertex -2.63 .47 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 .47 1.05
vertex -2.86 .24 1.05
vertex -2.86 .24 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 .47 1.05
vertex -2.86 .24 1.75
vertex -2.86 .47 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 .24 1.05
vertex -2.63 .47 1.05
vertex -2.63 .47 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 .24 1.05
vertex -2.63 .47 1.75
vertex -2.63 .24 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 -.01 1.53
vertex -2.63 -.01 1.53
vertex -2.63 .22 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 -.01 1.53
vertex -2.63 .22 1.53
vertex -2.86 .22 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 -.01 1.05
vertex -2.63 -.01 1.05
vertex -2.63 -.01 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 -.01 1.05
vertex -2.63 -.01 1.53
vertex -2.86 -.01 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 .22 1.05
vertex -2.86 .22 1.05
vertex -2.86 .22 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 .22 1.05
vertex -2.86 .22 1.53
vertex -2.63 .22 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 .22 1.05
vertex -2.86 -.01 1.05
vertex -2.86 -.01 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 .22 1.05
vertex -2.86 -.01 1.53
vertex -2.86 .22 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 -.01 1.05
vertex -2.63 .22 1.05
vertex -2.63 .22 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 -.01 1.05
vertex -2.63 .22 1.53
vertex -2.63 -.01 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 -.26 1.75
vertex -2.63 -.26 1.75
vertex -2.63 -.03 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.86 -.26 1.75
vertex -2.63 -.03 1.75
vertex -2.86 -.03 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 -.26 1.05
vertex -2.63 -.26 1.05
vertex -2.63 -.26 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.86 -.26 1.05
vertex -2.63 -.26 1.75
vertex -2.86 -.26 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 -.03 1.05
vertex -2.86 -.03 1.05
vertex -2.86 -.03 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.63 -.03 1.05
vertex -2.86 -.03 1.75
vertex -2.63 -.03 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 -.03 1.05
vertex -2.86 -.26 1.05
vertex -2.86 -.26 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.86 -.03 1.05
vertex -2.86 -.26 1.75
vertex -2.86 -.03 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 -.26 1.05
vertex -2.63 -.03 1.05
vertex -2.63 -.03 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.63 -.26 1.05
vertex -2.63 -.03 1.75
vertex -2.63 -.26 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.61 .99 1.53
vertex -2.38 .99 1.53
vertex -2.38 1.22 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.61 .99 1.53
vertex -2.38 1.22 1.53
vertex -2.61 1.22 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.61 .99 1.05
vertex -2.38 .99 1.05
vertex -2.38 .99 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.61 .99 1.05
vertex -2.38 .99 1.53
vertex -2.61 .99 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.38 1.22 1.05
vertex -2.61 1.22 1.05
vertex -2.61 1.22 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.38 1.22 1.05
vertex -2.61 1.22 1.53
vertex -2.38 1.22 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.61 1.22 1.05
vertex -2.61 .99 1.05
vertex -2.61 .99 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.61 1.22 1.05
vertex -2.61 .99 1.53
vertex -2.61 1.22 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.38 .99 1.05
vertex -2.38 1.22 1.05
vertex -2.38 1.22 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.38 .99 1.05
vertex -2.38 1.22 1.53
vertex -2.38 .99 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.36 .49 1.53
vertex -2.13 .49 1.53
vertex -2.13 .72 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.36 .49 1.53
vertex -2.13 .72 1.53
vertex -2.36 .72 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.36 .49 1.05
vertex -2.13 .49 1.05
vertex -2.13 .49 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.36 .49 1.05
vertex -2.13 .49 1.53
vertex -2.36 .49 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.13 .72 1.05
vertex -2.36 .72 1.05
vertex -2.36 .72 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.13 .72 1.05
vertex -2.36 .72 1.53
vertex -2.13 .72 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.36 .72 1.05
vertex -2.36 .49 1.05
vertex -2.36 .49 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.36 .72 1.05
vertex -2.36 .49 1.53
vertex -2.36 .72 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.13 .49 1.05
vertex -2.13 .72 1.05
vertex -2.13 .72 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.13 .49 1.05
vertex -2.13 .72 1.53
vertex -2.13 .49 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.36 -.01 1.93
vertex -2.13 -.01 1.93
vertex -2.13 .22 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.36 -.01 1.93
vertex -2.13 .22 1.93
vertex -2.36 .22 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.36 -.01 1.05
vertex -2.13 -.01 1.05
vertex -2.13 -.01 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.36 -.01 1.05
vertex -2.13 -.01 1.93
vertex -2.36 -.01 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.13 .22 1.05
vertex -2.36 .22 1.05
vertex -2.36 .22 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.13 .22 1.05
vertex -2.36 .22 1.93
vertex -2.13 .22 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.36 .22 1.05
vertex -2.36 -.01 1.05
vertex -2.36 -.01 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.36 .22 1.05
vertex -2.36 -.01 1.93
vertex -2.36 .22 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.13 -.01 1.05
vertex -2.13 .22 1.05
vertex -2.13 .22 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.13 -.01 1.05
vertex -2.13 .22 1.93
vertex -2.13 -.01 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.36 -.51 1.53
vertex -2.13 -.51 1.53
vertex -2.13 -.28 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.36 -.51 1.53
vertex -2.13 -.28 1.53
vertex -2.36 -.28 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.36 -.51 1.05
vertex -2.13 -.51 1.05
vertex -2.13 -.51 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.36 -.51 1.05
vertex -2.13 -.51 1.53
vertex -2.36 -.51 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.13 -.28 1.05
vertex -2.36 -.28 1.05
vertex -2.36 -.28 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -2.13 -.28 1.05
vertex -2.36 -.28 1.53
vertex -2.13 -.28 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.36 -.28 1.05
vertex -2.36 -.51 1.05
vertex -2.36 -.51 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.36 -.28 1.05
vertex -2.36 -.51 1.53
vertex -2.36 -.28 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.13 -.51 1.05
vertex -2.13 -.28 1.05
vertex -2.13 -.28 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.13 -.51 1.05
vertex -2.13 -.28 1.53
vertex -2.13 -.51 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.11 .74 1.93
vertex -1.88 .74 1.93
vertex -1.88 .97 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.11 .74 1.93
vertex -1.88 .97 1.93
vertex -2.11 .97 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.11 .74 1.05
vertex -1.88 .74 1.05
vertex -1.88 .74 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.11 .74 1.05
vertex -1.88 .74 1.93
vertex -2.11 .74 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.88 .97 1.05
vertex -2.11 .97 1.05
vertex -2.11 .97 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.88 .97 1.05
vertex -2.11 .97 1.93
vertex -1.88 .97 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.11 .97 1.05
vertex -2.11 .74 1.05
vertex -2.11 .74 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.11 .97 1.05
vertex -2.11 .74 1.93
vertex -2.11 .97 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.88 .74 1.05
vertex -1.88 .97 1.05
vertex -1.88 .97 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.88 .74 1.05
vertex -1.88 .97 1.93
vertex -1.88 .74 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.11 -.01 2.12
vertex -1.88 -.01 2.12
vertex -1.88 .22 2.12
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.11 -.01 2.12
vertex -1.88 .22 2.12
vertex -2.11 .22 2.12
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.11 -.01 1.05
vertex -1.88 -.01 1.05
vertex -1.88 -.01 2.12
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.11 -.01 1.05
vertex -1.88 -.01 2.12
vertex -2.11 -.01 2.12
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.88 .22 1.05
vertex -2.11 .22 1.05
vertex -2.11 .22 2.12
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.88 .22 1.05
vertex -2.11 .22 2.12
vertex -1.88 .22 2.12
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.11 .22 1.05
vertex -2.11 -.01 1.05
vertex -2.11 -.01 2.12
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.11 .22 1.05
vertex -2.11 -.01 2.12
vertex -2.11 .22 2.12
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.88 -.01 1.05
vertex -1.88 .22 1.05
vertex -1.88 .22 2.12
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.88 -.01 1.05
vertex -1.88 .22 2.12
vertex -1.88 -.01 2.12
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.11 -.26 1.65
vertex -1.88 -.26 1.65
vertex -1.88 -.03 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.11 -.26 1.65
vertex -1.88 -.03 1.65
vertex -2.11 -.03 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.11 -.26 1.05
vertex -1.88 -.26 1.05
vertex -1.88 -.26 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -2.11 -.26 1.05
vertex -1.88 -.26 1.65
vertex -2.11 -.26 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.88 -.03 1.05
vertex -2.11 -.03 1.05
vertex -2.11 -.03 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.88 -.03 1.05
vertex -2.11 -.03 1.65
vertex -1.88 -.03 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.11 -.03 1.05
vertex -2.11 -.26 1.05
vertex -2.11 -.26 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.11 -.03 1.05
vertex -2.11 -.26 1.65
vertex -2.11 -.03 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.88 -.26 1.05
vertex -1.88 -.03 1.05
vertex -1.88 -.03 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.88 -.26 1.05
vertex -1.88 -.03 1.65
vertex -1.88 -.26 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 .74 1.75
vertex -1.63 .74 1.75
vertex -1.63 .97 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 .74 1.75
vertex -1.63 .97 1.75
vertex -1.86 .97 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 .74 1.05
vertex -1.63 .74 1.05
vertex -1.63 .74 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 .74 1.05
vertex -1.63 .74 1.75
vertex -1.86 .74 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 .97 1.05
vertex -1.86 .97 1.05
vertex -1.86 .97 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 .97 1.05
vertex -1.86 .97 1.75
vertex -1.63 .97 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 .97 1.05
vertex -1.86 .74 1.05
vertex -1.86 .74 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 .97 1.05
vertex -1.86 .74 1.75
vertex -1.86 .97 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 .74 1.05
vertex -1.63 .97 1.05
vertex -1.63 .97 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 .74 1.05
vertex -1.63 .97 1.75
vertex -1.63 .74 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 .49 2
vertex -1.63 .49 2
vertex -1.63 .72 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 .49 2
vertex -1.63 .72 2
vertex -1.86 .72 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 .49 1.05
vertex -1.63 .49 1.05
vertex -1.63 .49 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 .49 1.05
vertex -1.63 .49 2
vertex -1.86 .49 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 .72 1.05
vertex -1.86 .72 1.05
vertex -1.86 .72 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 .72 1.05
vertex -1.86 .72 2
vertex -1.63 .72 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 .72 1.05
vertex -1.86 .49 1.05
vertex -1.86 .49 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 .72 1.05
vertex -1.86 .49 2
vertex -1.86 .72 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 .49 1.05
vertex -1.63 .72 1.05
vertex -1.63 .72 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 .49 1.05
vertex -1.63 .72 2
vertex -1.63 .49 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 -.01 1.65
vertex -1.63 -.01 1.65
vertex -1.63 .22 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 -.01 1.65
vertex -1.63 .22 1.65
vertex -1.86 .22 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 -.01 1.05
vertex -1.63 -.01 1.05
vertex -1.63 -.01 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 -.01 1.05
vertex -1.63 -.01 1.65
vertex -1.86 -.01 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 .22 1.05
vertex -1.86 .22 1.05
vertex -1.86 .22 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 .22 1.05
vertex -1.86 .22 1.65
vertex -1.63 .22 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 .22 1.05
vertex -1.86 -.01 1.05
vertex -1.86 -.01 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 .22 1.05
vertex -1.86 -.01 1.65
vertex -1.86 .22 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 -.01 1.05
vertex -1.63 .22 1.05
vertex -1.63 .22 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 -.01 1.05
vertex -1.63 .22 1.65
vertex -1.63 -.01 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 -.26 2.05
vertex -1.63 -.26 2.05
vertex -1.63 -.03 2.05
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 -.26 2.05
vertex -1.63 -.03 2.05
vertex -1.86 -.03 2.05
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 -.26 1.05
vertex -1.63 -.26 1.05
vertex -1.63 -.26 2.05
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 -.26 1.05
vertex -1.63 -.26 2.05
vertex -1.86 -.26 2.05
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 -.03 1.05
vertex -1.86 -.03 1.05
vertex -1.86 -.03 2.05
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 -.03 1.05
vertex -1.86 -.03 2.05
vertex -1.63 -.03 2.05
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 -.03 1.05
vertex -1.86 -.26 1.05
vertex -1.86 -.26 2.05
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 -.03 1.05
vertex -1.86 -.26 2.05
vertex -1.86 -.03 2.05
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 -.26 1.05
vertex -1.63 -.03 1.05
vertex -1.63 -.03 2.05
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 -.26 1.05
vertex -1.63 -.03 2.05
vertex -1.63 -.26 2.05
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 -.51 1.53
vertex -1.63 -.51 1.53
vertex -1.63 -.28 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.86 -.51 1.53
vertex -1.63 -.28 1.53
vertex -1.86 -.28 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 -.51 1.05
vertex -1.63 -.51 1.05
vertex -1.63 -.51 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.86 -.51 1.05
vertex -1.63 -.51 1.53
vertex -1.86 -.51 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 -.28 1.05
vertex -1.86 -.28 1.05
vertex -1.86 -.28 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.63 -.28 1.05
vertex -1.86 -.28 1.53
vertex -1.63 -.28 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 -.28 1.05
vertex -1.86 -.51 1.05
vertex -1.86 -.51 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.86 -.28 1.05
vertex -1.86 -.51 1.53
vertex -1.86 -.28 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 -.51 1.05
vertex -1.63 -.28 1.05
vertex -1.63 -.28 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.63 -.51 1.05
vertex -1.63 -.28 1.53
vertex -1.63 -.51 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 .99 2
vertex -1.38 .99 2
vertex -1.38 1.22 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 .99 2
vertex -1.38 1.22 2
vertex -1.61 1.22 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 .99 1.05
vertex -1.38 .99 1.05
vertex -1.38 .99 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 .99 1.05
vertex -1.38 .99 2
vertex -1.61 .99 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 1.22 1.05
vertex -1.61 1.22 1.05
vertex -1.61 1.22 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 1.22 1.05
vertex -1.61 1.22 2
vertex -1.38 1.22 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 1.22 1.05
vertex -1.61 .99 1.05
vertex -1.61 .99 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 1.22 1.05
vertex -1.61 .99 2
vertex -1.61 1.22 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 .99 1.05
vertex -1.38 1.22 1.05
vertex -1.38 1.22 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 .99 1.05
vertex -1.38 1.22 2
vertex -1.38 .99 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 .74 1.53
vertex -1.38 .74 1.53
vertex -1.38 .97 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 .74 1.53
vertex -1.38 .97 1.53
vertex -1.61 .97 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 .74 1.05
vertex -1.38 .74 1.05
vertex -1.38 .74 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 .74 1.05
vertex -1.38 .74 1.53
vertex -1.61 .74 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 .97 1.05
vertex -1.61 .97 1.05
vertex -1.61 .97 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 .97 1.05
vertex -1.61 .97 1.53
vertex -1.38 .97 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 .97 1.05
vertex -1.61 .74 1.05
vertex -1.61 .74 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 .97 1.05
vertex -1.61 .74 1.53
vertex -1.61 .97 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 .74 1.05
vertex -1.38 .97 1.05
vertex -1.38 .97 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 .74 1.05
vertex -1.38 .97 1.53
vertex -1.38 .74 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 .49 2
vertex -1.38 .49 2
vertex -1.38 .72 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 .49 2
vertex -1.38 .72 2
vertex -1.61 .72 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 .49 1.05
vertex -1.38 .49 1.05
vertex -1.38 .49 2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 .49 1.05
vertex -1.38 .49 2
vertex -1.61 .49 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 .72 1.05
vertex -1.61 .72 1.05
vertex -1.61 .72 2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 .72 1.05
vertex -1.61 .72 2
vertex -1.38 .72 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 .72 1.05
vertex -1.61 .49 1.05
vertex -1.61 .49 2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 .72 1.05
vertex -1.61 .49 2
vertex -1.61 .72 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 .49 1.05
vertex -1.38 .72 1.05
vertex -1.38 .72 2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 .49 1.05
vertex -1.38 .72 2
vertex -1.38 .49 2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 -.01 1.93
vertex -1.38 -.01 1.93
vertex -1.38 .22 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 -.01 1.93
vertex -1.38 .22 1.93
vertex -1.61 .22 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 -.01 1.05
vertex -1.38 -.01 1.05
vertex -1.38 -.01 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 -.01 1.05
vertex -1.38 -.01 1.93
vertex -1.61 -.01 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 .22 1.05
vertex -1.61 .22 1.05
vertex -1.61 .22 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 .22 1.05
vertex -1.61 .22 1.93
vertex -1.38 .22 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 .22 1.05
vertex -1.61 -.01 1.05
vertex -1.61 -.01 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 .22 1.05
vertex -1.61 -.01 1.93
vertex -1.61 .22 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 -.01 1.05
vertex -1.38 .22 1.05
vertex -1.38 .22 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 -.01 1.05
vertex -1.38 .22 1.93
vertex -1.38 -.01 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 -.26 1.53
vertex -1.38 -.26 1.53
vertex -1.38 -.03 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.61 -.26 1.53
vertex -1.38 -.03 1.53
vertex -1.61 -.03 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 -.26 1.05
vertex -1.38 -.26 1.05
vertex -1.38 -.26 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.61 -.26 1.05
vertex -1.38 -.26 1.53
vertex -1.61 -.26 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 -.03 1.05
vertex -1.61 -.03 1.05
vertex -1.61 -.03 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.38 -.03 1.05
vertex -1.61 -.03 1.53
vertex -1.38 -.03 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 -.03 1.05
vertex -1.61 -.26 1.05
vertex -1.61 -.26 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.61 -.03 1.05
vertex -1.61 -.26 1.53
vertex -1.61 -.03 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 -.26 1.05
vertex -1.38 -.03 1.05
vertex -1.38 -.03 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.38 -.26 1.05
vertex -1.38 -.03 1.53
vertex -1.38 -.26 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.36 .49 1.93
vertex -1.13 .49 1.93
vertex -1.13 .72 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.36 .49 1.93
vertex -1.13 .72 1.93
vertex -1.36 .72 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.36 .49 1.05
vertex -1.13 .49 1.05
vertex -1.13 .49 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.36 .49 1.05
vertex -1.13 .49 1.93
vertex -1.36 .49 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.13 .72 1.05
vertex -1.36 .72 1.05
vertex -1.36 .72 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.13 .72 1.05
vertex -1.36 .72 1.93
vertex -1.13 .72 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.36 .72 1.05
vertex -1.36 .49 1.05
vertex -1.36 .49 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.36 .72 1.05
vertex -1.36 .49 1.93
vertex -1.36 .72 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.13 .49 1.05
vertex -1.13 .72 1.05
vertex -1.13 .72 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.13 .49 1.05
vertex -1.13 .72 1.93
vertex -1.13 .49 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.36 .24 1.93
vertex -1.13 .24 1.93
vertex -1.13 .47 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.36 .24 1.93
vertex -1.13 .47 1.93
vertex -1.36 .47 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.36 .24 1.05
vertex -1.13 .24 1.05
vertex -1.13 .24 1.93
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.36 .24 1.05
vertex -1.13 .24 1.93
vertex -1.36 .24 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.13 .47 1.05
vertex -1.36 .47 1.05
vertex -1.36 .47 1.93
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.13 .47 1.05
vertex -1.36 .47 1.93
vertex -1.13 .47 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.36 .47 1.05
vertex -1.36 .24 1.05
vertex -1.36 .24 1.93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.36 .47 1.05
vertex -1.36 .24 1.93
vertex -1.36 .47 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.13 .24 1.05
vertex -1.13 .47 1.05
vertex -1.13 .47 1.93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.13 .24 1.05
vertex -1.13 .47 1.93
vertex -1.13 .24 1.93
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.36 -.01 1.65
vertex -1.13 -.01 1.65
vertex -1.13 .22 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.36 -.01 1.65
vertex -1.13 .22 1.65
vertex -1.36 .22 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.36 -.01 1.05
vertex -1.13 -.01 1.05
vertex -1.13 -.01 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.36 -.01 1.05
vertex -1.13 -.01 1.65
vertex -1.36 -.01 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.13 .22 1.05
vertex -1.36 .22 1.05
vertex -1.36 .22 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.13 .22 1.05
vertex -1.36 .22 1.65
vertex -1.13 .22 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.36 .22 1.05
vertex -1.36 -.01 1.05
vertex -1.36 -.01 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.36 .22 1.05
vertex -1.36 -.01 1.65
vertex -1.36 .22 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.13 -.01 1.05
vertex -1.13 .22 1.05
vertex -1.13 .22 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.13 -.01 1.05
vertex -1.13 .22 1.65
vertex -1.13 -.01 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.36 -.26 1.75
vertex -1.13 -.26 1.75
vertex -1.13 -.03 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -1.36 -.26 1.75
vertex -1.13 -.03 1.75
vertex -1.36 -.03 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.36 -.26 1.05
vertex -1.13 -.26 1.05
vertex -1.13 -.26 1.75
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -1.36 -.26 1.05
vertex -1.13 -.26 1.75
vertex -1.36 -.26 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.13 -.03 1.05
vertex -1.36 -.03 1.05
vertex -1.36 -.03 1.75
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -1.13 -.03 1.05
vertex -1.36 -.03 1.75
vertex -1.13 -.03 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.36 -.03 1.05
vertex -1.36 -.26 1.05
vertex -1.36 -.26 1.75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.36 -.03 1.05
vertex -1.36 -.26 1.75
vertex -1.36 -.03 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.13 -.26 1.05
vertex -1.13 -.03 1.05
vertex -1.13 -.03 1.75
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.13 -.26 1.05
vertex -1.13 -.03 1.75
vertex -1.13 -.26 1.75
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -.61 .24 3.15
vertex -.38 .24 3.15
vertex -.38 .47 3.15
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -.61 .24 3.15
vertex -.38 .47 3.15
vertex -.61 .47 3.15
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -.61 .24 1.05
vertex -.38 .24 1.05
vertex -.38 .24 3.15
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -.61 .24 1.05
vertex -.38 .24 3.15
vertex -.61 .24 3.15
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -.38 .47 1.05
vertex -.61 .47 1.05
vertex -.61 .47 3.15
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -.38 .47 1.05
vertex -.61 .47 3.15
vertex -.38 .47 3.15
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -.61 .47 1.05
vertex -.61 .24 1.05
vertex -.61 .24 3.15
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -.61 .47 1.05
vertex -.61 .24 3.15
vertex -.61 .47 3.15
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -.38 .24 1.05
vertex -.38 .47 1.05
vertex -.38 .47 3.15
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -.38 .24 1.05
vertex -.38 .47 3.15
vertex -.38 .24 3.15
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -.61 -.01 5.05
vertex -.38 -.01 5.05
vertex -.38 .22 5.05
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -.61 -.01 5.05
vertex -.38 .22 5.05
vertex -.61 .22 5.05
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -.61 -.01 1.05
vertex -.38 -.01 1.05
vertex -.38 -.01 5.05
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -.61 -.01 1.05
vertex -.38 -.01 5.05
vertex -.61 -.01 5.05
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -.38 .22 1.05
vertex -.61 .22 1.05
vertex -.61 .22 5.05
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -.38 .22 1.05
vertex -.61 .22 5.05
vertex -.38 .22 5.05
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -.61 .22 1.05
vertex -.61 -.01 1.05
vertex -.61 -.01 5.05
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -.61 .22 1.05
vertex -.61 -.01 5.05
vertex -.61 .22 5.05
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -.38 -.01 1.05
vertex -.38 .22 1.05
vertex -.38 .22 5.05
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -.38 -.01 1.05
vertex -.38 .22 5.05
vertex -.38 -.01 5.05
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -.36 .49 1.65
vertex -.13 .49 1.65
vertex -.13 .72 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -.36 .49 1.65
vertex -.13 .72 1.65
vertex -.36 .72 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -.36 .49 1.05
vertex -.13 .49 1.05
vertex -.13 .49 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -.36 .49 1.05
vertex -.13 .49 1.65
vertex -.36 .49 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -.13 .72 1.05
vertex -.36 .72 1.05
vertex -.36 .72 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -.13 .72 1.05
vertex -.36 .72 1.65
vertex -.13 .72 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -.36 .72 1.05
vertex -.36 .49 1.05
vertex -.36 .49 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -.36 .72 1.05
vertex -.36 .49 1.65
vertex -.36 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -.13 .49 1.05
vertex -.13 .72 1.05
vertex -.13 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -.13 .49 1.05
vertex -.13 .72 1.65
vertex -.13 .49 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex .14 .24 1.53
vertex .37 .24 1.53
vertex .37 .47 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex .14 .24 1.53
vertex .37 .47 1.53
vertex .14 .47 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex .14 .24 1.05
vertex .37 .24 1.05
vertex .37 .24 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex .14 .24 1.05
vertex .37 .24 1.53
vertex .14 .24 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex .37 .47 1.05
vertex .14 .47 1.05
vertex .14 .47 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex .37 .47 1.05
vertex .14 .47 1.53
vertex .37 .47 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex .14 .47 1.05
vertex .14 .24 1.05
vertex .14 .24 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex .14 .47 1.05
vertex .14 .24 1.53
vertex .14 .47 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex .37 .24 1.05
vertex .37 .47 1.05
vertex .37 .47 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex .37 .24 1.05
vertex .37 .47 1.53
vertex .37 .24 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 1.39 .49 1.53
vertex 1.62 .49 1.53
vertex 1.62 .72 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 1.39 .49 1.53
vertex 1.62 .72 1.53
vertex 1.39 .72 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 1.39 .49 1.05
vertex 1.62 .49 1.05
vertex 1.62 .49 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 1.39 .49 1.05
vertex 1.62 .49 1.53
vertex 1.39 .49 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 1.62 .72 1.05
vertex 1.39 .72 1.05
vertex 1.39 .72 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 1.62 .72 1.05
vertex 1.39 .72 1.53
vertex 1.62 .72 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 1.39 .72 1.05
vertex 1.39 .49 1.05
vertex 1.39 .49 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 1.39 .72 1.05
vertex 1.39 .49 1.53
vertex 1.39 .72 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 1.62 .49 1.05
vertex 1.62 .72 1.05
vertex 1.62 .72 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 1.62 .49 1.05
vertex 1.62 .72 1.53
vertex 1.62 .49 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.14 .24 2.67
vertex 2.37 .24 2.67
vertex 2.37 .47 2.67
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.14 .24 2.67
vertex 2.37 .47 2.67
vertex 2.14 .47 2.67
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.14 .24 1.05
vertex 2.37 .24 1.05
vertex 2.37 .24 2.67
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.14 .24 1.05
vertex 2.37 .24 2.67
vertex 2.14 .24 2.67
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.37 .47 1.05
vertex 2.14 .47 1.05
vertex 2.14 .47 2.67
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.37 .47 1.05
vertex 2.14 .47 2.67
vertex 2.37 .47 2.67
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.14 .47 1.05
vertex 2.14 .24 1.05
vertex 2.14 .24 2.67
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.14 .47 1.05
vertex 2.14 .24 2.67
vertex 2.14 .47 2.67
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.37 .24 1.05
vertex 2.37 .47 1.05
vertex 2.37 .47 2.67
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.37 .24 1.05
vertex 2.37 .47 2.67
vertex 2.37 .24 2.67
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.39 .49 2.23
vertex 2.62 .49 2.23
vertex 2.62 .72 2.23
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.39 .49 2.23
vertex 2.62 .72 2.23
vertex 2.39 .72 2.23
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.39 .49 1.05
vertex 2.62 .49 1.05
vertex 2.62 .49 2.23
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.39 .49 1.05
vertex 2.62 .49 2.23
vertex 2.39 .49 2.23
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.62 .72 1.05
vertex 2.39 .72 1.05
vertex 2.39 .72 2.23
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.62 .72 1.05
vertex 2.39 .72 2.23
vertex 2.62 .72 2.23
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.39 .72 1.05
vertex 2.39 .49 1.05
vertex 2.39 .49 2.23
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.39 .72 1.05
vertex 2.39 .49 2.23
vertex 2.39 .72 2.23
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.62 .49 1.05
vertex 2.62 .72 1.05
vertex 2.62 .72 2.23
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.62 .49 1.05
vertex 2.62 .72 2.23
vertex 2.62 .49 2.23
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.64 .74 1.53
vertex 2.87 .74 1.53
vertex 2.87 .97 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.64 .74 1.53
vertex 2.87 .97 1.53
vertex 2.64 .97 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.64 .74 1.05
vertex 2.87 .74 1.05
vertex 2.87 .74 1.53
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.64 .74 1.05
vertex 2.87 .74 1.53
vertex 2.64 .74 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.87 .97 1.05
vertex 2.64 .97 1.05
vertex 2.64 .97 1.53
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.87 .97 1.05
vertex 2.64 .97 1.53
vertex 2.87 .97 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.64 .97 1.05
vertex 2.64 .74 1.05
vertex 2.64 .74 1.53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.64 .97 1.05
vertex 2.64 .74 1.53
vertex 2.64 .97 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.87 .74 1.05
vertex 2.87 .97 1.05
vertex 2.87 .97 1.53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.87 .74 1.05
vertex 2.87 .97 1.53
vertex 2.87 .74 1.53
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.64 .49 1.65
vertex 2.87 .49 1.65
vertex 2.87 .72 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.64 .49 1.65
vertex 2.87 .72 1.65
vertex 2.64 .72 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.64 .49 1.05
vertex 2.87 .49 1.05
vertex 2.87 .49 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.64 .49 1.05
vertex 2.87 .49 1.65
vertex 2.64 .49 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.87 .72 1.05
vertex 2.64 .72 1.05
vertex 2.64 .72 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.87 .72 1.05
vertex 2.64 .72 1.65
vertex 2.87 .72 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.64 .72 1.05
vertex 2.64 .49 1.05
vertex 2.64 .49 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.64 .72 1.05
vertex 2.64 .49 1.65
vertex 2.64 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.87 .49 1.05
vertex 2.87 .72 1.05
vertex 2.87 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.87 .49 1.05
vertex 2.87 .72 1.65
vertex 2.87 .49 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.64 .24 1.65
vertex 2.87 .24 1.65
vertex 2.87 .47 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.64 .24 1.65
vertex 2.87 .47 1.65
vertex 2.64 .47 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.64 .24 1.05
vertex 2.87 .24 1.05
vertex 2.87 .24 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.64 .24 1.05
vertex 2.87 .24 1.65
vertex 2.64 .24 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.87 .47 1.05
vertex 2.64 .47 1.05
vertex 2.64 .47 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 2.87 .47 1.05
vertex 2.64 .47 1.65
vertex 2.87 .47 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.64 .47 1.05
vertex 2.64 .24 1.05
vertex 2.64 .24 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.64 .47 1.05
vertex 2.64 .24 1.65
vertex 2.64 .47 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.87 .24 1.05
vertex 2.87 .47 1.05
vertex 2.87 .47 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 2.87 .24 1.05
vertex 2.87 .47 1.65
vertex 2.87 .24 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.89 .49 1.65
vertex 3.12 .49 1.65
vertex 3.12 .72 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.89 .49 1.65
vertex 3.12 .72 1.65
vertex 2.89 .72 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.89 .49 1.05
vertex 3.12 .49 1.05
vertex 3.12 .49 1.65
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.89 .49 1.05
vertex 3.12 .49 1.65
vertex 2.89 .49 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.12 .72 1.05
vertex 2.89 .72 1.05
vertex 2.89 .72 1.65
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.12 .72 1.05
vertex 2.89 .72 1.65
vertex 3.12 .72 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.89 .72 1.05
vertex 2.89 .49 1.05
vertex 2.89 .49 1.65
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.89 .72 1.05
vertex 2.89 .49 1.65
vertex 2.89 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.12 .49 1.05
vertex 3.12 .72 1.05
vertex 3.12 .72 1.65
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.12 .49 1.05
vertex 3.12 .72 1.65
vertex 3.12 .49 1.65
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.89 .24 3.1
vertex 3.12 .24 3.1
vertex 3.12 .47 3.1
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.89 .24 3.1
vertex 3.12 .47 3.1
vertex 2.89 .47 3.1
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.89 .24 1.05
vertex 3.12 .24 1.05
vertex 3.12 .24 3.1
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.89 .24 1.05
vertex 3.12 .24 3.1
vertex 2.89 .24 3.1
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.12 .47 1.05
vertex 2.89 .47 1.05
vertex 2.89 .47 3.1
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.12 .47 1.05
vertex 2.89 .47 3.1
vertex 3.12 .47 3.1
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.89 .47 1.05
vertex 2.89 .24 1.05
vertex 2.89 .24 3.1
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.89 .47 1.05
vertex 2.89 .24 3.1
vertex 2.89 .47 3.1
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.12 .24 1.05
vertex 3.12 .47 1.05
vertex 3.12 .47 3.1
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.12 .24 1.05
vertex 3.12 .47 3.1
vertex 3.12 .24 3.1
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.89 -.01 2.55
vertex 3.12 -.01 2.55
vertex 3.12 .22 2.55
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.89 -.01 2.55
vertex 3.12 .22 2.55
vertex 2.89 .22 2.55
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.89 -.01 1.05
vertex 3.12 -.01 1.05
vertex 3.12 -.01 2.55
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.89 -.01 1.05
vertex 3.12 -.01 2.55
vertex 2.89 -.01 2.55
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.12 .22 1.05
vertex 2.89 .22 1.05
vertex 2.89 .22 2.55
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.12 .22 1.05
vertex 2.89 .22 2.55
vertex 3.12 .22 2.55
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.89 .22 1.05
vertex 2.89 -.01 1.05
vertex 2.89 -.01 2.55
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.89 .22 1.05
vertex 2.89 -.01 2.55
vertex 2.89 .22 2.55
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.12 -.01 1.05
vertex 3.12 .22 1.05
vertex 3.12 .22 2.55
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.12 -.01 1.05
vertex 3.12 .22 2.55
vertex 3.12 -.01 2.55
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.89 -.26 3.08
vertex 3.12 -.26 3.08
vertex 3.12 -.03 3.08
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 2.89 -.26 3.08
vertex 3.12 -.03 3.08
vertex 2.89 -.03 3.08
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.89 -.26 1.05
vertex 3.12 -.26 1.05
vertex 3.12 -.26 3.08
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 2.89 -.26 1.05
vertex 3.12 -.26 3.08
vertex 2.89 -.26 3.08
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.12 -.03 1.05
vertex 2.89 -.03 1.05
vertex 2.89 -.03 3.08
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.12 -.03 1.05
vertex 2.89 -.03 3.08
vertex 3.12 -.03 3.08
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.89 -.03 1.05
vertex 2.89 -.26 1.05
vertex 2.89 -.26 3.08
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 2.89 -.03 1.05
vertex 2.89 -.26 3.08
vertex 2.89 -.03 3.08
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.12 -.26 1.05
vertex 3.12 -.03 1.05
vertex 3.12 -.03 3.08
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.12 -.26 1.05
vertex 3.12 -.03 3.08
vertex 3.12 -.26 3.08
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.14 .74 2.05
vertex 3.37 .74 2.05
vertex 3.37 .97 2.05
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.14 .74 2.05
vertex 3.37 .97 2.05
vertex 3.14 .97 2.05
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.14 .74 1.05
vertex 3.37 .74 1.05
vertex 3.37 .74 2.05
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.14 .74 1.05
vertex 3.37 .74 2.05
vertex 3.14 .74 2.05
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.37 .97 1.05
vertex 3.14 .97 1.05
vertex 3.14 .97 2.05
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.37 .97 1.05
vertex 3.14 .97 2.05
vertex 3.37 .97 2.05
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 3.14 .97 1.05
vertex 3.14 .74 1.05
vertex 3.14 .74 2.05
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 3.14 .97 1.05
vertex 3.14 .74 2.05
vertex 3.14 .97 2.05
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.37 .74 1.05
vertex 3.37 .97 1.05
vertex 3.37 .97 2.05
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.37 .74 1.05
vertex 3.37 .97 2.05
vertex 3.37 .74 2.05
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.14 .49 2.42
vertex 3.37 .49 2.42
vertex 3.37 .72 2.42
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.14 .49 2.42
vertex 3.37 .72 2.42
vertex 3.14 .72 2.42
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.14 .49 1.05
vertex 3.37 .49 1.05
vertex 3.37 .49 2.42
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.14 .49 1.05
vertex 3.37 .49 2.42
vertex 3.14 .49 2.42
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.37 .72 1.05
vertex 3.14 .72 1.05
vertex 3.14 .72 2.42
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.37 .72 1.05
vertex 3.14 .72 2.42
vertex 3.37 .72 2.42
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 3.14 .72 1.05
vertex 3.14 .49 1.05
vertex 3.14 .49 2.42
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 3.14 .72 1.05
vertex 3.14 .49 2.42
vertex 3.14 .72 2.42
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.37 .49 1.05
vertex 3.37 .72 1.05
vertex 3.37 .72 2.42
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.37 .49 1.05
vertex 3.37 .72 2.42
vertex 3.37 .49 2.42
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.14 .24 2.23
vertex 3.37 .24 2.23
vertex 3.37 .47 2.23
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.14 .24 2.23
vertex 3.37 .47 2.23
vertex 3.14 .47 2.23
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.14 .24 1.05
vertex 3.37 .24 1.05
vertex 3.37 .24 2.23
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.14 .24 1.05
vertex 3.37 .24 2.23
vertex 3.14 .24 2.23
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.37 .47 1.05
vertex 3.14 .47 1.05
vertex 3.14 .47 2.23
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.37 .47 1.05
vertex 3.14 .47 2.23
vertex 3.37 .47 2.23
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 3.14 .47 1.05
vertex 3.14 .24 1.05
vertex 3.14 .24 2.23
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 3.14 .47 1.05
vertex 3.14 .24 2.23
vertex 3.14 .47 2.23
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.37 .24 1.05
vertex 3.37 .47 1.05
vertex 3.37 .47 2.23
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.37 .24 1.05
vertex 3.37 .47 2.23
vertex 3.37 .24 2.23
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.64 -.51 2.12
vertex 3.87 -.51 2.12
vertex 3.87 -.28 2.12
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.64 -.51 2.12
vertex 3.87 -.28 2.12
vertex 3.64 -.28 2.12
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.64 -.51 1.05
vertex 3.87 -.51 1.05
vertex 3.87 -.51 2.12
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.64 -.51 1.05
vertex 3.87 -.51 2.12
vertex 3.64 -.51 2.12
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.87 -.28 1.05
vertex 3.64 -.28 1.05
vertex 3.64 -.28 2.12
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.87 -.28 1.05
vertex 3.64 -.28 2.12
vertex 3.87 -.28 2.12
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 3.64 -.28 1.05
vertex 3.64 -.51 1.05
vertex 3.64 -.51 2.12
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 3.64 -.28 1.05
vertex 3.64 -.51 2.12
vertex 3.64 -.28 2.12
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.87 -.51 1.05
vertex 3.87 -.28 1.05
vertex 3.87 -.28 2.12
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.87 -.51 1.05
vertex 3.87 -.28 2.12
vertex 3.87 -.51 2.12
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.2 -1.5 .53
vertex -6.57 -1.5 .53
vertex -6.57 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.46 -1.08 .94
vertex -6.08 -1.08 .94
vertex -6.08 -1 1.02
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.2 -1.5 .53
vertex -6.57 -1.58 .44
vertex -6.16 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.2 -1.5 .53
vertex -6.16 -1.58 .44
vertex -6.08 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.2 -1.5 .53
vertex -6.08 -1.52 .5
vertex -6.08 -1.3 .72
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.2 -1.33 .69
vertex -6.2 -1.5 .53
vertex -6.08 -1.3 .72
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.2 -1.33 .69
vertex -6.08 -1.3 .72
vertex -6.16 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.2 -1.33 .69
vertex -6.16 -1.25 .78
vertex -6.46 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.49 -1.33 .69
vertex -6.2 -1.33 .69
vertex -6.46 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.57 -1.27 .75
vertex -6.49 -1.33 .69
vertex -6.46 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.57 -1.06 .97
vertex -6.57 -1.27 .75
vertex -6.46 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.57 -1.06 .97
vertex -6.46 -1.25 .78
vertex -6.46 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.49 -1 1.02
vertex -6.57 -1.06 .97
vertex -6.46 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -6.46 -1.08 .94
vertex -6.08 -1 1.02
vertex -6.49 -1 1.02
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -6.57 -1.46 .32
vertex -6.16 -1.46 .32
vertex -6.16 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -6.57 -1.46 .32
vertex -6.16 -1.58 .44
vertex -6.57 -1.58 .44
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex -6.16 -1.46 .32
vertex -6.08 -1.4 .38
vertex -6.08 -1.52 .5
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex -6.16 -1.46 .32
vertex -6.08 -1.52 .5
vertex -6.16 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.08 -1.4 .38
vertex -6.08 -1.18 .59
vertex -6.08 -1.3 .72
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.08 -1.4 .38
vertex -6.08 -1.3 .72
vertex -6.08 -1.52 .5
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -6.08 -1.18 .59
vertex -6.16 -1.12 .65
vertex -6.16 -1.25 .78
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -6.08 -1.18 .59
vertex -6.16 -1.25 .78
vertex -6.08 -1.3 .72
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -6.16 -1.12 .65
vertex -6.46 -1.12 .65
vertex -6.46 -1.25 .78
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -6.16 -1.12 .65
vertex -6.46 -1.25 .78
vertex -6.16 -1.25 .78
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.46 -1.12 .65
vertex -6.46 -.96 .82
vertex -6.46 -1.08 .94
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.46 -1.12 .65
vertex -6.46 -1.08 .94
vertex -6.46 -1.25 .78
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -6.46 -.96 .82
vertex -6.08 -.96 .82
vertex -6.08 -1.08 .94
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -6.46 -.96 .82
vertex -6.08 -1.08 .94
vertex -6.46 -1.08 .94
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.08 -.96 .82
vertex -6.08 -.87 .9
vertex -6.08 -1 1.02
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -6.08 -.96 .82
vertex -6.08 -1 1.02
vertex -6.08 -1.08 .94
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -6.08 -.87 .9
vertex -6.49 -.87 .9
vertex -6.49 -1 1.02
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -6.08 -.87 .9
vertex -6.49 -1 1.02
vertex -6.08 -1 1.02
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex -6.49 -.87 .9
vertex -6.57 -.93 .84
vertex -6.57 -1.06 .97
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex -6.49 -.87 .9
vertex -6.57 -1.06 .97
vertex -6.49 -1 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.57 -.93 .84
vertex -6.57 -1.15 .62
vertex -6.57 -1.27 .75
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.57 -.93 .84
vertex -6.57 -1.27 .75
vertex -6.57 -1.06 .97
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex -6.57 -1.15 .62
vertex -6.49 -1.21 .57
vertex -6.49 -1.33 .69
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex -6.57 -1.15 .62
vertex -6.49 -1.33 .69
vertex -6.57 -1.27 .75
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -6.49 -1.21 .57
vertex -6.2 -1.21 .57
vertex -6.2 -1.33 .69
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -6.49 -1.21 .57
vertex -6.2 -1.33 .69
vertex -6.49 -1.33 .69
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.2 -1.21 .57
vertex -6.2 -1.37 .4
vertex -6.2 -1.5 .53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.2 -1.21 .57
vertex -6.2 -1.5 .53
vertex -6.2 -1.33 .69
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -6.2 -1.37 .4
vertex -6.57 -1.37 .4
vertex -6.57 -1.5 .53
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -6.2 -1.37 .4
vertex -6.57 -1.5 .53
vertex -6.2 -1.5 .53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.57 -1.37 .4
vertex -6.57 -1.46 .32
vertex -6.57 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -6.57 -1.37 .4
vertex -6.57 -1.58 .44
vertex -6.57 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.86 -1.41 .61
vertex -5.62 -1.41 .61
vertex -5.62 -1.33 .69
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.86 -1.41 .61
vertex -5.62 -1.33 .69
vertex -5.9 -1.33 .69
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.86 -1.41 .61
vertex -5.9 -1.33 .69
vertex -5.98 -1.39 .64
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.86 -1.41 .61
vertex -5.98 -1.39 .64
vertex -5.98 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.86 -1.5 .53
vertex -5.86 -1.41 .61
vertex -5.98 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.86 -1.5 .53
vertex -5.98 -1.52 .5
vertex -5.9 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.62 -1.5 .53
vertex -5.86 -1.5 .53
vertex -5.9 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.62 -1.5 .53
vertex -5.9 -1.58 .44
vertex -5.5 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.98 -1.15 .87
vertex -5.98 -1.24 .79
vertex -5.62 -1.24 .79
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.58 -1.15 .87
vertex -5.98 -1.15 .87
vertex -5.62 -1.24 .79
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.5 -1.21 .81
vertex -5.58 -1.15 .87
vertex -5.62 -1.24 .79
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.5 -1.21 .81
vertex -5.62 -1.24 .79
vertex -5.62 -1.33 .69
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.5 -1.58 .44
vertex -5.5 -1.21 .81
vertex -5.62 -1.33 .69
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.62 -1.41 .61
vertex -5.62 -1.5 .53
vertex -5.5 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.5 -1.58 .44
vertex -5.62 -1.33 .69
vertex -5.62 -1.41 .61
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.9 -1.46 .32
vertex -5.5 -1.46 .32
vertex -5.5 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.9 -1.46 .32
vertex -5.5 -1.58 .44
vertex -5.9 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.5 -1.46 .32
vertex -5.5 -1.08 .69
vertex -5.5 -1.21 .81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.5 -1.46 .32
vertex -5.5 -1.21 .81
vertex -5.5 -1.58 .44
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -5.5 -1.08 .69
vertex -5.58 -1.03 .75
vertex -5.58 -1.15 .87
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -5.5 -1.08 .69
vertex -5.58 -1.15 .87
vertex -5.5 -1.21 .81
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -5.58 -1.03 .75
vertex -5.98 -1.03 .75
vertex -5.98 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -5.58 -1.03 .75
vertex -5.98 -1.15 .87
vertex -5.58 -1.15 .87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.98 -1.03 .75
vertex -5.98 -1.11 .66
vertex -5.98 -1.24 .79
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.98 -1.03 .75
vertex -5.98 -1.24 .79
vertex -5.98 -1.15 .87
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.98 -1.11 .66
vertex -5.62 -1.11 .66
vertex -5.62 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.98 -1.11 .66
vertex -5.62 -1.24 .79
vertex -5.98 -1.24 .79
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.62 -1.11 .66
vertex -5.62 -1.2 .57
vertex -5.62 -1.33 .69
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.62 -1.11 .66
vertex -5.62 -1.33 .69
vertex -5.62 -1.24 .79
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -5.62 -1.2 .57
vertex -5.9 -1.2 .57
vertex -5.9 -1.33 .69
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -5.62 -1.2 .57
vertex -5.9 -1.33 .69
vertex -5.62 -1.33 .69
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex -5.9 -1.2 .57
vertex -5.98 -1.26 .51
vertex -5.98 -1.39 .64
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex -5.9 -1.2 .57
vertex -5.98 -1.39 .64
vertex -5.9 -1.33 .69
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.98 -1.26 .51
vertex -5.98 -1.4 .38
vertex -5.98 -1.52 .5
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.98 -1.26 .51
vertex -5.98 -1.52 .5
vertex -5.98 -1.39 .64
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex -5.98 -1.4 .38
vertex -5.9 -1.46 .32
vertex -5.9 -1.58 .44
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex -5.98 -1.4 .38
vertex -5.9 -1.58 .44
vertex -5.98 -1.52 .5
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.86 -1.29 .49
vertex -5.62 -1.29 .49
vertex -5.62 -1.41 .61
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.86 -1.29 .49
vertex -5.62 -1.41 .61
vertex -5.86 -1.41 .61
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.62 -1.29 .49
vertex -5.62 -1.37 .4
vertex -5.62 -1.5 .53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.62 -1.29 .49
vertex -5.62 -1.5 .53
vertex -5.62 -1.41 .61
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -5.62 -1.37 .4
vertex -5.86 -1.37 .4
vertex -5.86 -1.5 .53
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -5.62 -1.37 .4
vertex -5.86 -1.5 .53
vertex -5.62 -1.5 .53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.86 -1.37 .4
vertex -5.86 -1.29 .49
vertex -5.86 -1.41 .61
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.86 -1.37 .4
vertex -5.86 -1.41 .61
vertex -5.86 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.4 -1.58 .44
vertex -5.28 -1.58 .44
vertex -5.28 -1.24 .79
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.04 -1.24 .79
vertex -5.04 -1.58 .44
vertex -4.92 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.04 -1.24 .79
vertex -4.92 -1.58 .44
vertex -4.92 -1.21 .81
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.04 -1.24 .79
vertex -4.92 -1.21 .81
vertex -5.01 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.28 -1.24 .79
vertex -5.04 -1.24 .79
vertex -5.01 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.28 -1.24 .79
vertex -5.01 -1.15 .87
vertex -5.4 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -5.4 -1.58 .44
vertex -5.28 -1.24 .79
vertex -5.4 -1.15 .87
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.4 -1.46 .32
vertex -5.28 -1.46 .32
vertex -5.28 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.4 -1.46 .32
vertex -5.28 -1.58 .44
vertex -5.4 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.28 -1.46 .32
vertex -5.28 -1.11 .66
vertex -5.28 -1.24 .79
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.28 -1.46 .32
vertex -5.28 -1.24 .79
vertex -5.28 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.28 -1.11 .66
vertex -5.04 -1.11 .66
vertex -5.04 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.28 -1.11 .66
vertex -5.04 -1.24 .79
vertex -5.28 -1.24 .79
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.04 -1.11 .66
vertex -5.04 -1.46 .32
vertex -5.04 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.04 -1.11 .66
vertex -5.04 -1.58 .44
vertex -5.04 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.04 -1.46 .32
vertex -4.92 -1.46 .32
vertex -4.92 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -5.04 -1.46 .32
vertex -4.92 -1.58 .44
vertex -5.04 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -4.92 -1.46 .32
vertex -4.92 -1.08 .69
vertex -4.92 -1.21 .81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -4.92 -1.46 .32
vertex -4.92 -1.21 .81
vertex -4.92 -1.58 .44
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -4.92 -1.08 .69
vertex -5.01 -1.03 .75
vertex -5.01 -1.15 .87
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -4.92 -1.08 .69
vertex -5.01 -1.15 .87
vertex -4.92 -1.21 .81
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -5.01 -1.03 .75
vertex -5.4 -1.03 .75
vertex -5.4 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -5.01 -1.03 .75
vertex -5.4 -1.15 .87
vertex -5.01 -1.15 .87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.4 -1.03 .75
vertex -5.4 -1.46 .32
vertex -5.4 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -5.4 -1.03 .75
vertex -5.4 -1.58 .44
vertex -5.4 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.47 -1.24 .79
vertex -4.35 -1.15 .87
vertex -4.75 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.71 -1.24 .79
vertex -4.47 -1.24 .79
vertex -4.75 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.71 -1.24 .79
vertex -4.75 -1.15 .87
vertex -4.83 -1.21 .81
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.47 -1.67 .36
vertex -4.83 -1.67 .36
vertex -4.83 -1.75 .27
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.47 -1.67 .36
vertex -4.83 -1.75 .27
vertex -4.43 -1.75 .27
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.47 -1.67 .36
vertex -4.43 -1.75 .27
vertex -4.35 -1.69 .33
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.47 -1.58 .44
vertex -4.47 -1.67 .36
vertex -4.35 -1.69 .33
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.71 -1.24 .79
vertex -4.83 -1.21 .81
vertex -4.83 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.71 -1.5 .53
vertex -4.71 -1.24 .79
vertex -4.83 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.71 -1.5 .53
vertex -4.83 -1.52 .5
vertex -4.75 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.71 -1.5 .53
vertex -4.75 -1.58 .44
vertex -4.47 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.47 -1.5 .53
vertex -4.71 -1.5 .53
vertex -4.47 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.35 -1.15 .87
vertex -4.47 -1.24 .79
vertex -4.47 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.47 -1.5 .53
vertex -4.47 -1.58 .44
vertex -4.35 -1.69 .33
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.35 -1.69 .33
vertex -4.35 -1.15 .87
vertex -4.47 -1.5 .53
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.83 -1.63 .15
vertex -4.43 -1.63 .15
vertex -4.43 -1.75 .27
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.83 -1.63 .15
vertex -4.43 -1.75 .27
vertex -4.83 -1.75 .27
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex -4.43 -1.63 .15
vertex -4.35 -1.57 .21
vertex -4.35 -1.69 .33
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex -4.43 -1.63 .15
vertex -4.35 -1.69 .33
vertex -4.43 -1.75 .27
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -4.35 -1.57 .21
vertex -4.35 -1.03 .75
vertex -4.35 -1.15 .87
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -4.35 -1.57 .21
vertex -4.35 -1.15 .87
vertex -4.35 -1.69 .33
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -4.35 -1.03 .75
vertex -4.75 -1.03 .75
vertex -4.75 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -4.35 -1.03 .75
vertex -4.75 -1.15 .87
vertex -4.35 -1.15 .87
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex -4.75 -1.03 .75
vertex -4.83 -1.08 .69
vertex -4.83 -1.21 .81
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex -4.75 -1.03 .75
vertex -4.83 -1.21 .81
vertex -4.75 -1.15 .87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.83 -1.08 .69
vertex -4.83 -1.4 .38
vertex -4.83 -1.52 .5
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.83 -1.08 .69
vertex -4.83 -1.52 .5
vertex -4.83 -1.21 .81
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex -4.83 -1.4 .38
vertex -4.75 -1.46 .32
vertex -4.75 -1.58 .44
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex -4.83 -1.4 .38
vertex -4.75 -1.58 .44
vertex -4.83 -1.52 .5
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.75 -1.46 .32
vertex -4.47 -1.46 .32
vertex -4.47 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.75 -1.46 .32
vertex -4.47 -1.58 .44
vertex -4.75 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.47 -1.46 .32
vertex -4.47 -1.54 .23
vertex -4.47 -1.67 .36
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.47 -1.46 .32
vertex -4.47 -1.67 .36
vertex -4.47 -1.58 .44
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -4.47 -1.54 .23
vertex -4.83 -1.54 .23
vertex -4.83 -1.67 .36
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -4.47 -1.54 .23
vertex -4.83 -1.67 .36
vertex -4.47 -1.67 .36
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.83 -1.54 .23
vertex -4.83 -1.63 .15
vertex -4.83 -1.75 .27
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.83 -1.54 .23
vertex -4.83 -1.75 .27
vertex -4.83 -1.67 .36
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.71 -1.11 .66
vertex -4.47 -1.11 .66
vertex -4.47 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.71 -1.11 .66
vertex -4.47 -1.24 .79
vertex -4.71 -1.24 .79
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.47 -1.11 .66
vertex -4.47 -1.37 .4
vertex -4.47 -1.5 .53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.47 -1.11 .66
vertex -4.47 -1.5 .53
vertex -4.47 -1.24 .79
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -4.47 -1.37 .4
vertex -4.71 -1.37 .4
vertex -4.71 -1.5 .53
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -4.47 -1.37 .4
vertex -4.71 -1.5 .53
vertex -4.47 -1.5 .53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -4.71 -1.37 .4
vertex -4.71 -1.11 .66
vertex -4.71 -1.24 .79
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -4.71 -1.37 .4
vertex -4.71 -1.24 .79
vertex -4.71 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.09 -1.67 .36
vertex -4.25 -1.67 .36
vertex -4.25 -1.75 .27
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.09 -1.67 .36
vertex -4.25 -1.75 .27
vertex -4.05 -1.75 .27
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.09 -1.67 .36
vertex -4.05 -1.75 .27
vertex -3.97 -1.69 .33
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.97 -1.15 .87
vertex -4.09 -1.15 .87
vertex -4.09 -1.67 .36
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.97 -1.69 .33
vertex -3.97 -1.15 .87
vertex -4.09 -1.67 .36
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.25 -1.63 .15
vertex -4.05 -1.63 .15
vertex -4.05 -1.75 .27
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.25 -1.63 .15
vertex -4.05 -1.75 .27
vertex -4.25 -1.75 .27
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex -4.05 -1.63 .15
vertex -3.97 -1.57 .21
vertex -3.97 -1.69 .33
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex -4.05 -1.63 .15
vertex -3.97 -1.69 .33
vertex -4.05 -1.75 .27
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.97 -1.57 .21
vertex -3.97 -1.03 .75
vertex -3.97 -1.15 .87
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.97 -1.57 .21
vertex -3.97 -1.15 .87
vertex -3.97 -1.69 .33
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.97 -1.03 .75
vertex -4.09 -1.03 .75
vertex -4.09 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.97 -1.03 .75
vertex -4.09 -1.15 .87
vertex -3.97 -1.15 .87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.09 -1.03 .75
vertex -4.09 -1.54 .23
vertex -4.09 -1.67 .36
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.09 -1.03 .75
vertex -4.09 -1.67 .36
vertex -4.09 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -4.09 -1.54 .23
vertex -4.25 -1.54 .23
vertex -4.25 -1.67 .36
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -4.09 -1.54 .23
vertex -4.25 -1.67 .36
vertex -4.09 -1.67 .36
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.25 -1.54 .23
vertex -4.25 -1.63 .15
vertex -4.25 -1.75 .27
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.25 -1.54 .23
vertex -4.25 -1.75 .27
vertex -4.25 -1.67 .36
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -4.09 -1.01 1.02
vertex -4.09 -1.09 .93
vertex -3.97 -1.09 .93
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.97 -1.09 .93
vertex -3.97 -1.01 1.02
vertex -4.09 -1.01 1.02
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.09 -.97 .81
vertex -3.97 -.97 .81
vertex -3.97 -1.09 .93
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -4.09 -.97 .81
vertex -3.97 -1.09 .93
vertex -4.09 -1.09 .93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.97 -.97 .81
vertex -3.97 -.88 .89
vertex -3.97 -1.01 1.02
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.97 -.97 .81
vertex -3.97 -1.01 1.02
vertex -3.97 -1.09 .93
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.97 -.88 .89
vertex -4.09 -.88 .89
vertex -4.09 -1.01 1.02
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.97 -.88 .89
vertex -4.09 -1.01 1.02
vertex -3.97 -1.01 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.09 -.88 .89
vertex -4.09 -.97 .81
vertex -4.09 -1.09 .93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -4.09 -.88 .89
vertex -4.09 -1.09 .93
vertex -4.09 -1.01 1.02
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.87 -1.15 .87
vertex -3.87 -1.58 .44
vertex -3.75 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.75 -1.58 .44
vertex -3.75 -1.15 .87
vertex -3.87 -1.15 .87
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.87 -1.46 .32
vertex -3.75 -1.46 .32
vertex -3.75 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.87 -1.46 .32
vertex -3.75 -1.58 .44
vertex -3.87 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.75 -1.46 .32
vertex -3.75 -1.03 .75
vertex -3.75 -1.15 .87
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.75 -1.46 .32
vertex -3.75 -1.15 .87
vertex -3.75 -1.58 .44
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.75 -1.03 .75
vertex -3.87 -1.03 .75
vertex -3.87 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.75 -1.03 .75
vertex -3.87 -1.15 .87
vertex -3.75 -1.15 .87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.87 -1.03 .75
vertex -3.87 -1.46 .32
vertex -3.87 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.87 -1.03 .75
vertex -3.87 -1.58 .44
vertex -3.87 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.87 -1.01 1.02
vertex -3.87 -1.09 .93
vertex -3.75 -1.09 .93
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.75 -1.09 .93
vertex -3.75 -1.01 1.02
vertex -3.87 -1.01 1.02
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.87 -.97 .81
vertex -3.75 -.97 .81
vertex -3.75 -1.09 .93
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.87 -.97 .81
vertex -3.75 -1.09 .93
vertex -3.87 -1.09 .93
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.75 -.97 .81
vertex -3.75 -.88 .89
vertex -3.75 -1.01 1.02
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.75 -.97 .81
vertex -3.75 -1.01 1.02
vertex -3.75 -1.09 .93
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.75 -.88 .89
vertex -3.87 -.88 .89
vertex -3.87 -1.01 1.02
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.75 -.88 .89
vertex -3.87 -1.01 1.02
vertex -3.75 -1.01 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.87 -.88 .89
vertex -3.87 -.97 .81
vertex -3.87 -1.09 .93
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.87 -.88 .89
vertex -3.87 -1.09 .93
vertex -3.87 -1.01 1.02
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.65 -1.58 .44
vertex -3.54 -1.58 .44
vertex -3.54 -1.24 .79
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.3 -1.24 .79
vertex -3.3 -1.58 .44
vertex -3.18 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.3 -1.24 .79
vertex -3.18 -1.58 .44
vertex -3.18 -1.21 .81
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.3 -1.24 .79
vertex -3.18 -1.21 .81
vertex -3.26 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.54 -1.24 .79
vertex -3.3 -1.24 .79
vertex -3.26 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.54 -1.24 .79
vertex -3.26 -1.15 .87
vertex -3.65 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.65 -1.58 .44
vertex -3.54 -1.24 .79
vertex -3.65 -1.15 .87
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.65 -1.46 .32
vertex -3.54 -1.46 .32
vertex -3.54 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.65 -1.46 .32
vertex -3.54 -1.58 .44
vertex -3.65 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.54 -1.46 .32
vertex -3.54 -1.11 .66
vertex -3.54 -1.24 .79
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.54 -1.46 .32
vertex -3.54 -1.24 .79
vertex -3.54 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.54 -1.11 .66
vertex -3.3 -1.11 .66
vertex -3.3 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.54 -1.11 .66
vertex -3.3 -1.24 .79
vertex -3.54 -1.24 .79
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.3 -1.11 .66
vertex -3.3 -1.46 .32
vertex -3.3 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.3 -1.11 .66
vertex -3.3 -1.58 .44
vertex -3.3 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.3 -1.46 .32
vertex -3.18 -1.46 .32
vertex -3.18 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.3 -1.46 .32
vertex -3.18 -1.58 .44
vertex -3.3 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.18 -1.46 .32
vertex -3.18 -1.08 .69
vertex -3.18 -1.21 .81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -3.18 -1.46 .32
vertex -3.18 -1.21 .81
vertex -3.18 -1.58 .44
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -3.18 -1.08 .69
vertex -3.26 -1.03 .75
vertex -3.26 -1.15 .87
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -3.18 -1.08 .69
vertex -3.26 -1.15 .87
vertex -3.18 -1.21 .81
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.26 -1.03 .75
vertex -3.65 -1.03 .75
vertex -3.65 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -3.26 -1.03 .75
vertex -3.65 -1.15 .87
vertex -3.26 -1.15 .87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.65 -1.03 .75
vertex -3.65 -1.46 .32
vertex -3.65 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.65 -1.03 .75
vertex -3.65 -1.58 .44
vertex -3.65 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -3.08 -1.32 .7
vertex -3.08 -1.41 .61
vertex -2.8 -1.41 .61
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.8 -1.41 .61
vertex -2.8 -1.32 .7
vertex -3.08 -1.32 .7
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.08 -1.28 .49
vertex -2.8 -1.28 .49
vertex -2.8 -1.41 .61
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -3.08 -1.28 .49
vertex -2.8 -1.41 .61
vertex -3.08 -1.41 .61
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.8 -1.28 .49
vertex -2.8 -1.2 .57
vertex -2.8 -1.32 .7
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.8 -1.28 .49
vertex -2.8 -1.32 .7
vertex -2.8 -1.41 .61
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -2.8 -1.2 .57
vertex -3.08 -1.2 .57
vertex -3.08 -1.32 .7
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -2.8 -1.2 .57
vertex -3.08 -1.32 .7
vertex -2.8 -1.32 .7
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.08 -1.2 .57
vertex -3.08 -1.28 .49
vertex -3.08 -1.41 .61
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -3.08 -1.2 .57
vertex -3.08 -1.41 .61
vertex -3.08 -1.32 .7
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.7 -1 1.02
vertex -2.7 -1.58 .44
vertex -2.58 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.58 -1.58 .44
vertex -2.58 -1 1.02
vertex -2.7 -1 1.02
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.7 -1.46 .32
vertex -2.58 -1.46 .32
vertex -2.58 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.7 -1.46 .32
vertex -2.58 -1.58 .44
vertex -2.7 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.58 -1.46 .32
vertex -2.58 -.87 .9
vertex -2.58 -1 1.02
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.58 -1.46 .32
vertex -2.58 -1 1.02
vertex -2.58 -1.58 .44
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -2.58 -.87 .9
vertex -2.7 -.87 .9
vertex -2.7 -1 1.02
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -2.58 -.87 .9
vertex -2.7 -1 1.02
vertex -2.58 -1 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.7 -.87 .9
vertex -2.7 -1.46 .32
vertex -2.7 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.7 -.87 .9
vertex -2.7 -1.58 .44
vertex -2.7 -1 1.02
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.58 -1.48 .54
vertex -2.24 -1.15 .87
vertex -2.38 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.7 -1.48 .54
vertex -2.58 -1.48 .54
vertex -2.38 -1.15 .87
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.7 -1.36 .42
vertex -2.58 -1.36 .42
vertex -2.58 -1.48 .54
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.7 -1.36 .42
vertex -2.58 -1.48 .54
vertex -2.7 -1.48 .54
endloop
endfacet
facet normal .81 -.41 -.41
outer loop
vertex -2.58 -1.36 .42
vertex -2.24 -1.03 .75
vertex -2.24 -1.15 .87
endloop
endfacet
facet normal .81 -.41 -.41
outer loop
vertex -2.58 -1.36 .42
vertex -2.24 -1.15 .87
vertex -2.58 -1.48 .54
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -2.24 -1.03 .75
vertex -2.38 -1.03 .75
vertex -2.38 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -2.24 -1.03 .75
vertex -2.38 -1.15 .87
vertex -2.24 -1.15 .87
endloop
endfacet
facet normal -.83 .4 .4
outer loop
vertex -2.38 -1.03 .75
vertex -2.7 -1.36 .42
vertex -2.7 -1.48 .54
endloop
endfacet
facet normal -.83 .4 .4
outer loop
vertex -2.38 -1.03 .75
vertex -2.7 -1.48 .54
vertex -2.38 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.38 -1.58 .44
vertex -2.24 -1.58 .44
vertex -2.43 -1.32 .7
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.53 -1.38 .64
vertex -2.38 -1.58 .44
vertex -2.43 -1.32 .7
endloop
endfacet
facet normal -.89 -.32 -.32
outer loop
vertex -2.53 -1.26 .52
vertex -2.38 -1.46 .32
vertex -2.38 -1.58 .44
endloop
endfacet
facet normal -.89 -.32 -.32
outer loop
vertex -2.53 -1.26 .52
vertex -2.38 -1.58 .44
vertex -2.53 -1.38 .64
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.38 -1.46 .32
vertex -2.24 -1.46 .32
vertex -2.24 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.38 -1.46 .32
vertex -2.24 -1.58 .44
vertex -2.38 -1.58 .44
endloop
endfacet
facet normal .89 .32 .32
outer loop
vertex -2.24 -1.46 .32
vertex -2.43 -1.2 .58
vertex -2.43 -1.32 .7
endloop
endfacet
facet normal .89 .32 .32
outer loop
vertex -2.24 -1.46 .32
vertex -2.43 -1.32 .7
vertex -2.24 -1.58 .44
endloop
endfacet
facet normal -.66 .53 .53
outer loop
vertex -2.43 -1.2 .58
vertex -2.53 -1.26 .52
vertex -2.53 -1.38 .64
endloop
endfacet
facet normal -.66 .53 .53
outer loop
vertex -2.43 -1.2 .58
vertex -2.53 -1.38 .64
vertex -2.43 -1.32 .7
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.15 -1.58 .44
vertex -2.03 -1.58 .44
vertex -2.03 -1.24 .79
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.85 -1.24 .79
vertex -1.85 -1.58 .44
vertex -1.73 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.85 -1.24 .79
vertex -1.73 -1.58 .44
vertex -1.73 -1.24 .79
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.55 -1.24 .79
vertex -1.55 -1.58 .44
vertex -1.43 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.55 -1.24 .79
vertex -1.43 -1.58 .44
vertex -1.43 -1.21 .81
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.55 -1.24 .79
vertex -1.43 -1.21 .81
vertex -1.51 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.73 -1.24 .79
vertex -1.55 -1.24 .79
vertex -1.51 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.73 -1.24 .79
vertex -1.51 -1.15 .87
vertex -2.15 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.15 -1.15 .87
vertex -2.15 -1.58 .44
vertex -2.03 -1.24 .79
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -2.15 -1.15 .87
vertex -2.03 -1.24 .79
vertex -1.85 -1.24 .79
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.85 -1.24 .79
vertex -1.73 -1.24 .79
vertex -2.15 -1.15 .87
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.15 -1.46 .32
vertex -2.03 -1.46 .32
vertex -2.03 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.15 -1.46 .32
vertex -2.03 -1.58 .44
vertex -2.15 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.03 -1.46 .32
vertex -2.03 -1.11 .66
vertex -2.03 -1.24 .79
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -2.03 -1.46 .32
vertex -2.03 -1.24 .79
vertex -2.03 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.03 -1.11 .66
vertex -1.85 -1.11 .66
vertex -1.85 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -2.03 -1.11 .66
vertex -1.85 -1.24 .79
vertex -2.03 -1.24 .79
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.85 -1.11 .66
vertex -1.85 -1.46 .32
vertex -1.85 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.85 -1.11 .66
vertex -1.85 -1.58 .44
vertex -1.85 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -1.85 -1.46 .32
vertex -1.73 -1.46 .32
vertex -1.73 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -1.85 -1.46 .32
vertex -1.73 -1.58 .44
vertex -1.85 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.73 -1.46 .32
vertex -1.73 -1.11 .66
vertex -1.73 -1.24 .79
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.73 -1.46 .32
vertex -1.73 -1.24 .79
vertex -1.73 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -1.73 -1.11 .66
vertex -1.55 -1.11 .66
vertex -1.55 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -1.73 -1.11 .66
vertex -1.55 -1.24 .79
vertex -1.73 -1.24 .79
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.55 -1.11 .66
vertex -1.55 -1.46 .32
vertex -1.55 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.55 -1.11 .66
vertex -1.55 -1.58 .44
vertex -1.55 -1.24 .79
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -1.55 -1.46 .32
vertex -1.43 -1.46 .32
vertex -1.43 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -1.55 -1.46 .32
vertex -1.43 -1.58 .44
vertex -1.55 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.43 -1.46 .32
vertex -1.43 -1.08 .69
vertex -1.43 -1.21 .81
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.43 -1.46 .32
vertex -1.43 -1.21 .81
vertex -1.43 -1.58 .44
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -1.43 -1.08 .69
vertex -1.51 -1.03 .75
vertex -1.51 -1.15 .87
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex -1.43 -1.08 .69
vertex -1.51 -1.15 .87
vertex -1.43 -1.21 .81
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -1.51 -1.03 .75
vertex -2.15 -1.03 .75
vertex -2.15 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -1.51 -1.03 .75
vertex -2.15 -1.15 .87
vertex -1.51 -1.15 .87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.15 -1.03 .75
vertex -2.15 -1.46 .32
vertex -2.15 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -2.15 -1.03 .75
vertex -2.15 -1.58 .44
vertex -2.15 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -.85 -1.15 .87
vertex -.97 -1.15 .87
vertex -.97 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.21 -1.5 .53
vertex -1.21 -1.15 .87
vertex -1.33 -1.15 .87
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.21 -1.5 .53
vertex -1.33 -1.15 .87
vertex -1.33 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -1.21 -1.5 .53
vertex -1.33 -1.52 .5
vertex -1.25 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -.97 -1.5 .53
vertex -1.21 -1.5 .53
vertex -1.25 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -.97 -1.5 .53
vertex -1.25 -1.58 .44
vertex -.85 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex -.85 -1.58 .44
vertex -.85 -1.15 .87
vertex -.97 -1.5 .53
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -1.25 -1.46 .32
vertex -.85 -1.46 .32
vertex -.85 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex -1.25 -1.46 .32
vertex -.85 -1.58 .44
vertex -1.25 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -.85 -1.46 .32
vertex -.85 -1.03 .75
vertex -.85 -1.15 .87
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -.85 -1.46 .32
vertex -.85 -1.15 .87
vertex -.85 -1.58 .44
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -.85 -1.03 .75
vertex -.97 -1.03 .75
vertex -.97 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -.85 -1.03 .75
vertex -.97 -1.15 .87
vertex -.85 -1.15 .87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -.97 -1.03 .75
vertex -.97 -1.37 .4
vertex -.97 -1.5 .53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -.97 -1.03 .75
vertex -.97 -1.5 .53
vertex -.97 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -.97 -1.37 .4
vertex -1.21 -1.37 .4
vertex -1.21 -1.5 .53
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -.97 -1.37 .4
vertex -1.21 -1.5 .53
vertex -.97 -1.5 .53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.21 -1.37 .4
vertex -1.21 -1.03 .75
vertex -1.21 -1.15 .87
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -1.21 -1.37 .4
vertex -1.21 -1.15 .87
vertex -1.21 -1.5 .53
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -1.21 -1.03 .75
vertex -1.33 -1.03 .75
vertex -1.33 -1.15 .87
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex -1.21 -1.03 .75
vertex -1.33 -1.15 .87
vertex -1.21 -1.15 .87
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.33 -1.03 .75
vertex -1.33 -1.4 .38
vertex -1.33 -1.52 .5
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -1.33 -1.03 .75
vertex -1.33 -1.52 .5
vertex -1.33 -1.15 .87
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex -1.33 -1.4 .38
vertex -1.25 -1.46 .32
vertex -1.25 -1.58 .44
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex -1.33 -1.4 .38
vertex -1.25 -1.58 .44
vertex -1.33 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.78 -1.58 .44
vertex 4.78 -1.5 .53
vertex 4.4 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.28 -1 1.02
vertex 4.28 -1.08 .94
vertex 4.66 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.7 -1 1.02
vertex 4.28 -1 1.02
vertex 4.66 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.78 -1.06 .97
vertex 4.7 -1 1.02
vertex 4.66 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.78 -1.27 .75
vertex 4.78 -1.06 .97
vertex 4.66 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.78 -1.27 .75
vertex 4.66 -1.08 .94
vertex 4.66 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.7 -1.33 .69
vertex 4.78 -1.27 .75
vertex 4.66 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.4 -1.33 .69
vertex 4.7 -1.33 .69
vertex 4.66 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.4 -1.33 .69
vertex 4.66 -1.25 .78
vertex 4.37 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.4 -1.33 .69
vertex 4.37 -1.25 .78
vertex 4.28 -1.3 .72
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.4 -1.5 .53
vertex 4.4 -1.33 .69
vertex 4.28 -1.3 .72
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.4 -1.5 .53
vertex 4.28 -1.3 .72
vertex 4.28 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 4.28 -1.58 .44
vertex 4.78 -1.58 .44
vertex 4.4 -1.5 .53
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 4.28 -1.46 .32
vertex 4.78 -1.46 .32
vertex 4.78 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 4.28 -1.46 .32
vertex 4.78 -1.58 .44
vertex 4.28 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.78 -1.46 .32
vertex 4.78 -1.37 .4
vertex 4.78 -1.5 .53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.78 -1.46 .32
vertex 4.78 -1.5 .53
vertex 4.78 -1.58 .44
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 4.78 -1.37 .4
vertex 4.4 -1.37 .4
vertex 4.4 -1.5 .53
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 4.78 -1.37 .4
vertex 4.4 -1.5 .53
vertex 4.78 -1.5 .53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.4 -1.37 .4
vertex 4.4 -1.21 .57
vertex 4.4 -1.33 .69
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.4 -1.37 .4
vertex 4.4 -1.33 .69
vertex 4.4 -1.5 .53
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 4.4 -1.21 .57
vertex 4.7 -1.21 .57
vertex 4.7 -1.33 .69
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 4.4 -1.21 .57
vertex 4.7 -1.33 .69
vertex 4.4 -1.33 .69
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex 4.7 -1.21 .57
vertex 4.78 -1.15 .62
vertex 4.78 -1.27 .75
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex 4.7 -1.21 .57
vertex 4.78 -1.27 .75
vertex 4.7 -1.33 .69
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.78 -1.15 .62
vertex 4.78 -.93 .84
vertex 4.78 -1.06 .97
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 4.78 -1.15 .62
vertex 4.78 -1.06 .97
vertex 4.78 -1.27 .75
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex 4.78 -.93 .84
vertex 4.7 -.87 .9
vertex 4.7 -1 1.02
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex 4.78 -.93 .84
vertex 4.7 -1 1.02
vertex 4.78 -1.06 .97
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 4.7 -.87 .9
vertex 4.28 -.87 .9
vertex 4.28 -1 1.02
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 4.7 -.87 .9
vertex 4.28 -1 1.02
vertex 4.7 -1 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.28 -.87 .9
vertex 4.28 -.96 .82
vertex 4.28 -1.08 .94
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.28 -.87 .9
vertex 4.28 -1.08 .94
vertex 4.28 -1 1.02
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 4.28 -.96 .82
vertex 4.66 -.96 .82
vertex 4.66 -1.08 .94
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 4.28 -.96 .82
vertex 4.66 -1.08 .94
vertex 4.28 -1.08 .94
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.66 -.96 .82
vertex 4.66 -1.12 .65
vertex 4.66 -1.25 .78
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.66 -.96 .82
vertex 4.66 -1.25 .78
vertex 4.66 -1.08 .94
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 4.66 -1.12 .65
vertex 4.37 -1.12 .65
vertex 4.37 -1.25 .78
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 4.66 -1.12 .65
vertex 4.37 -1.25 .78
vertex 4.66 -1.25 .78
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex 4.37 -1.12 .65
vertex 4.28 -1.18 .59
vertex 4.28 -1.3 .72
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex 4.37 -1.12 .65
vertex 4.28 -1.3 .72
vertex 4.37 -1.25 .78
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.28 -1.18 .59
vertex 4.28 -1.46 .32
vertex 4.28 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.28 -1.18 .59
vertex 4.28 -1.58 .44
vertex 4.28 -1.3 .72
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.26 -1.08 .94
vertex 5.38 -1.06 .97
vertex 5.3 -1 1.02
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.26 -1.08 .94
vertex 5.3 -1 1.02
vertex 4.96 -1 1.02
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5 -1.08 .94
vertex 5.26 -1.08 .94
vertex 4.96 -1 1.02
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5 -1.08 .94
vertex 4.96 -1 1.02
vertex 4.88 -1.06 .97
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5 -1.08 .94
vertex 4.88 -1.06 .97
vertex 4.88 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.38 -1.52 .5
vertex 5.38 -1.06 .97
vertex 5.26 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5 -1.5 .53
vertex 5 -1.08 .94
vertex 4.88 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5 -1.5 .53
vertex 4.88 -1.52 .5
vertex 4.96 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5 -1.5 .53
vertex 4.96 -1.58 .44
vertex 5.3 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.26 -1.5 .53
vertex 5 -1.5 .53
vertex 5.3 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.26 -1.5 .53
vertex 5.3 -1.58 .44
vertex 5.38 -1.52 .5
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.38 -1.52 .5
vertex 5.26 -1.08 .94
vertex 5.26 -1.5 .53
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 4.96 -1.46 .32
vertex 5.3 -1.46 .32
vertex 5.3 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 4.96 -1.46 .32
vertex 5.3 -1.58 .44
vertex 4.96 -1.58 .44
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex 5.3 -1.46 .32
vertex 5.38 -1.4 .38
vertex 5.38 -1.52 .5
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex 5.3 -1.46 .32
vertex 5.38 -1.52 .5
vertex 5.3 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.38 -1.4 .38
vertex 5.38 -.93 .84
vertex 5.38 -1.06 .97
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.38 -1.4 .38
vertex 5.38 -1.06 .97
vertex 5.38 -1.52 .5
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex 5.38 -.93 .84
vertex 5.3 -.87 .9
vertex 5.3 -1 1.02
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex 5.38 -.93 .84
vertex 5.3 -1 1.02
vertex 5.38 -1.06 .97
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.3 -.87 .9
vertex 4.96 -.87 .9
vertex 4.96 -1 1.02
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.3 -.87 .9
vertex 4.96 -1 1.02
vertex 5.3 -1 1.02
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex 4.96 -.87 .9
vertex 4.88 -.93 .84
vertex 4.88 -1.06 .97
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex 4.96 -.87 .9
vertex 4.88 -1.06 .97
vertex 4.96 -1 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.88 -.93 .84
vertex 4.88 -1.4 .38
vertex 4.88 -1.52 .5
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 4.88 -.93 .84
vertex 4.88 -1.52 .5
vertex 4.88 -1.06 .97
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex 4.88 -1.4 .38
vertex 4.96 -1.46 .32
vertex 4.96 -1.58 .44
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex 4.88 -1.4 .38
vertex 4.96 -1.58 .44
vertex 4.88 -1.52 .5
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 5 -.96 .82
vertex 5.26 -.96 .82
vertex 5.26 -1.08 .94
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 5 -.96 .82
vertex 5.26 -1.08 .94
vertex 5 -1.08 .94
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.26 -.96 .82
vertex 5.26 -1.37 .4
vertex 5.26 -1.5 .53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.26 -.96 .82
vertex 5.26 -1.5 .53
vertex 5.26 -1.08 .94
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.26 -1.37 .4
vertex 5 -1.37 .4
vertex 5 -1.5 .53
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.26 -1.37 .4
vertex 5 -1.5 .53
vertex 5.26 -1.5 .53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5 -1.37 .4
vertex 5 -.96 .82
vertex 5 -1.08 .94
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5 -1.37 .4
vertex 5 -1.08 .94
vertex 5 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.98 -1.58 .44
vertex 5.98 -1.5 .53
vertex 5.6 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.48 -1 1.02
vertex 5.48 -1.08 .94
vertex 5.86 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.9 -1 1.02
vertex 5.48 -1 1.02
vertex 5.86 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.98 -1.06 .97
vertex 5.9 -1 1.02
vertex 5.86 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.98 -1.27 .75
vertex 5.98 -1.06 .97
vertex 5.86 -1.08 .94
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.98 -1.27 .75
vertex 5.86 -1.08 .94
vertex 5.86 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.9 -1.33 .69
vertex 5.98 -1.27 .75
vertex 5.86 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.6 -1.33 .69
vertex 5.9 -1.33 .69
vertex 5.86 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.6 -1.33 .69
vertex 5.86 -1.25 .78
vertex 5.56 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.6 -1.33 .69
vertex 5.56 -1.25 .78
vertex 5.48 -1.3 .72
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.6 -1.5 .53
vertex 5.6 -1.33 .69
vertex 5.48 -1.3 .72
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.6 -1.5 .53
vertex 5.48 -1.3 .72
vertex 5.48 -1.58 .44
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 5.48 -1.58 .44
vertex 5.98 -1.58 .44
vertex 5.6 -1.5 .53
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 5.48 -1.46 .32
vertex 5.98 -1.46 .32
vertex 5.98 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 5.48 -1.46 .32
vertex 5.98 -1.58 .44
vertex 5.48 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.98 -1.46 .32
vertex 5.98 -1.37 .4
vertex 5.98 -1.5 .53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.98 -1.46 .32
vertex 5.98 -1.5 .53
vertex 5.98 -1.58 .44
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.98 -1.37 .4
vertex 5.6 -1.37 .4
vertex 5.6 -1.5 .53
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.98 -1.37 .4
vertex 5.6 -1.5 .53
vertex 5.98 -1.5 .53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.6 -1.37 .4
vertex 5.6 -1.21 .57
vertex 5.6 -1.33 .69
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.6 -1.37 .4
vertex 5.6 -1.33 .69
vertex 5.6 -1.5 .53
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 5.6 -1.21 .57
vertex 5.9 -1.21 .57
vertex 5.9 -1.33 .69
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 5.6 -1.21 .57
vertex 5.9 -1.33 .69
vertex 5.6 -1.33 .69
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex 5.9 -1.21 .57
vertex 5.98 -1.15 .62
vertex 5.98 -1.27 .75
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex 5.9 -1.21 .57
vertex 5.98 -1.27 .75
vertex 5.9 -1.33 .69
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.98 -1.15 .62
vertex 5.98 -.93 .84
vertex 5.98 -1.06 .97
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.98 -1.15 .62
vertex 5.98 -1.06 .97
vertex 5.98 -1.27 .75
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex 5.98 -.93 .84
vertex 5.9 -.87 .9
vertex 5.9 -1 1.02
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex 5.98 -.93 .84
vertex 5.9 -1 1.02
vertex 5.98 -1.06 .97
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.9 -.87 .9
vertex 5.48 -.87 .9
vertex 5.48 -1 1.02
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.9 -.87 .9
vertex 5.48 -1 1.02
vertex 5.9 -1 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.48 -.87 .9
vertex 5.48 -.96 .82
vertex 5.48 -1.08 .94
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.48 -.87 .9
vertex 5.48 -1.08 .94
vertex 5.48 -1 1.02
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 5.48 -.96 .82
vertex 5.86 -.96 .82
vertex 5.86 -1.08 .94
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 5.48 -.96 .82
vertex 5.86 -1.08 .94
vertex 5.48 -1.08 .94
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.86 -.96 .82
vertex 5.86 -1.12 .65
vertex 5.86 -1.25 .78
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.86 -.96 .82
vertex 5.86 -1.25 .78
vertex 5.86 -1.08 .94
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.86 -1.12 .65
vertex 5.56 -1.12 .65
vertex 5.56 -1.25 .78
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 5.86 -1.12 .65
vertex 5.56 -1.25 .78
vertex 5.86 -1.25 .78
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex 5.56 -1.12 .65
vertex 5.48 -1.18 .59
vertex 5.48 -1.3 .72
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex 5.56 -1.12 .65
vertex 5.48 -1.3 .72
vertex 5.56 -1.25 .78
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.48 -1.18 .59
vertex 5.48 -1.46 .32
vertex 5.48 -1.58 .44
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 5.48 -1.18 .59
vertex 5.48 -1.58 .44
vertex 5.48 -1.3 .72
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.46 -1.33 .69
vertex 6.58 -1.3 .72
vertex 6.49 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.46 -1.33 .69
vertex 6.49 -1.25 .78
vertex 6.2 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.2 -1.33 .69
vertex 6.46 -1.33 .69
vertex 6.2 -1.25 .78
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.58 -1.52 .5
vertex 6.58 -1.3 .72
vertex 6.46 -1.33 .69
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.58 -1.52 .5
vertex 6.46 -1.33 .69
vertex 6.46 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.49 -1.58 .44
vertex 6.58 -1.52 .5
vertex 6.46 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.16 -1.58 .44
vertex 6.49 -1.58 .44
vertex 6.46 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.16 -1.58 .44
vertex 6.46 -1.5 .53
vertex 6.2 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.08 -1.52 .5
vertex 6.16 -1.58 .44
vertex 6.2 -1.5 .53
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.08 -1.52 .5
vertex 6.2 -1.5 .53
vertex 6.2 -1.33 .69
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.2 -1.08 .94
vertex 6.58 -1.08 .94
vertex 6.58 -1 1.02
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.2 -1.08 .94
vertex 6.58 -1 1.02
vertex 6.16 -1 1.02
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.2 -1.08 .94
vertex 6.16 -1 1.02
vertex 6.08 -1.06 .97
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.2 -1.25 .78
vertex 6.2 -1.08 .94
vertex 6.08 -1.06 .97
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.08 -1.06 .97
vertex 6.08 -1.52 .5
vertex 6.2 -1.33 .69
endloop
endfacet
facet normal 0 -.71 .71
outer loop
vertex 6.2 -1.33 .69
vertex 6.2 -1.25 .78
vertex 6.08 -1.06 .97
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 6.16 -1.46 .32
vertex 6.49 -1.46 .32
vertex 6.49 -1.58 .44
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 6.16 -1.46 .32
vertex 6.49 -1.58 .44
vertex 6.16 -1.58 .44
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex 6.49 -1.46 .32
vertex 6.58 -1.4 .38
vertex 6.58 -1.52 .5
endloop
endfacet
facet normal .71 -.5 -.5
outer loop
vertex 6.49 -1.46 .32
vertex 6.58 -1.52 .5
vertex 6.49 -1.58 .44
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.58 -1.4 .38
vertex 6.58 -1.18 .59
vertex 6.58 -1.3 .72
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.58 -1.4 .38
vertex 6.58 -1.3 .72
vertex 6.58 -1.52 .5
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex 6.58 -1.18 .59
vertex 6.49 -1.12 .65
vertex 6.49 -1.25 .78
endloop
endfacet
facet normal .71 .5 .5
outer loop
vertex 6.58 -1.18 .59
vertex 6.49 -1.25 .78
vertex 6.58 -1.3 .72
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 6.49 -1.12 .65
vertex 6.2 -1.12 .65
vertex 6.2 -1.25 .78
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 6.49 -1.12 .65
vertex 6.2 -1.25 .78
vertex 6.49 -1.25 .78
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.2 -1.12 .65
vertex 6.2 -.96 .82
vertex 6.2 -1.08 .94
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.2 -1.12 .65
vertex 6.2 -1.08 .94
vertex 6.2 -1.25 .78
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 6.2 -.96 .82
vertex 6.58 -.96 .82
vertex 6.58 -1.08 .94
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 6.2 -.96 .82
vertex 6.58 -1.08 .94
vertex 6.2 -1.08 .94
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.58 -.96 .82
vertex 6.58 -.87 .9
vertex 6.58 -1 1.02
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.58 -.96 .82
vertex 6.58 -1 1.02
vertex 6.58 -1.08 .94
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 6.58 -.87 .9
vertex 6.16 -.87 .9
vertex 6.16 -1 1.02
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 6.58 -.87 .9
vertex 6.16 -1 1.02
vertex 6.58 -1 1.02
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex 6.16 -.87 .9
vertex 6.08 -.93 .84
vertex 6.08 -1.06 .97
endloop
endfacet
facet normal -.71 .5 .5
outer loop
vertex 6.16 -.87 .9
vertex 6.08 -1.06 .97
vertex 6.16 -1 1.02
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 6.08 -.93 .84
vertex 6.08 -1.4 .38
vertex 6.08 -1.52 .5
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 6.08 -.93 .84
vertex 6.08 -1.52 .5
vertex 6.08 -1.06 .97
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex 6.08 -1.4 .38
vertex 6.16 -1.46 .32
vertex 6.16 -1.58 .44
endloop
endfacet
facet normal -.71 -.5 -.5
outer loop
vertex 6.08 -1.4 .38
vertex 6.16 -1.58 .44
vertex 6.08 -1.52 .5
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 6.2 -1.21 .57
vertex 6.46 -1.21 .57
vertex 6.46 -1.33 .69
endloop
endfacet
facet normal 0 -.71 -.71
outer loop
vertex 6.2 -1.21 .57
vertex 6.46 -1.33 .69
vertex 6.2 -1.33 .69
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 6.46 -1.21 .57
vertex 6.46 -1.37 .4
vertex 6.46 -1.5 .53
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 6.46 -1.21 .57
vertex 6.46 -1.5 .53
vertex 6.46 -1.33 .69
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 6.46 -1.37 .4
vertex 6.2 -1.37 .4
vertex 6.2 -1.5 .53
endloop
endfacet
facet normal 0 .71 .71
outer loop
vertex 6.46 -1.37 .4
vertex 6.2 -1.5 .53
vertex 6.46 -1.5 .53
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.2 -1.37 .4
vertex 6.2 -1.21 .57
vertex 6.2 -1.33 .69
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 6.2 -1.37 .4
vertex 6.2 -1.33 .69
vertex 6.2 -1.5 .53
endloop
endfacet
endsolid skyline
```

## kookmin.geojson

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "name": "국민대학교",
        "description": "소프트웨어학부, 2021.03 입학"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          126.997,
          37.6106
        ]
      }
    },
    {
      "type": "Feature",
      "properties": {
        "stroke": "#2c5ee8",
        "stroke-width": 2
      },
      "geometry": {
        "type": "LineString",
        "coordinates": [
          [
            127.000969,
            37.6106
          ],
          [
            127.000935,
            37.611013
          ],
          [
            127.000834,
            37.611419
          ],
          [
            127.000667,
            37.611812
          ],
          [
            127.000437,
            37.612183
          ],
          [
            127.000149,
            37.612528
          ],
          [
            126.999806,
            37.612839
          ],
          [
            126.999416,
            37.613112
          ],
          [
            126.998984,
            37.613342
          ],
          [
            126.998519,
            37.613525
          ],
          [
            126.998027,
            37.613658
          ],
          [
            126.997518,
            37.613739
          ],
          [
            126.997,
            37.613766
          ],
          [
            126.996482,
            37.613739
          ],
          [
            126.995973,
            37.613658
          ],
          [
            126.995481,
            37.613525
          ],
          [
            126.995016,
            37.613342
          ],
          [
            126.994584,
            37.613112
          ],
          [
            126.994194,
            37.612839
          ],
          [
            126.993851,
            37.612528
          ],
          [
            126.993563,
            37.612183
          ],
          [
            126.993333,
            37.611812
          ],
          [
            126.993166,
            37.611419
          ],
          [
            126.993065,
            37.611013
          ],
          [
            126.993031,
            37.6106
          ],
          [
            126.993065,
            37.610187
          ],
          [
            126.993166,
            37.609781
          ],
          [
            126.993333,
            37.609388
          ],
          [
            126.993563,
            37.609017
          ],
          [
            126.993851,
            37.608672
          ],
          [
            126.994194,
            37.608361
          ],
          [
            126.994584,
            37.608088
          ],
          [
            126.995016,
            37.607858
          ],
          [
            126.995481,
            37.607675
          ],
          [
            126.995973,
            37.607542
          ],
          [
            126.996482,
            37.607461
          ],
          [
            126.997,
            37.607434
          ],
          [
            126.997518,
            37.607461
          ],
          [
            126.998027,
            37.607542
          ],
          [
            126.998519,
            37.607675
          ],
          [
            126.998984,
            37.607858
          ],
          [
            126.999416,
            37.608088
          ],
          [
            126.999806,
            37.608361
          ],
          [
            127.000149,
            37.608672
          ],
          [
            127.000437,
            37.609017
          ],
          [
            127.000667,
            37.609388
          ],
          [
            127.000834,
            37.609781
          ],
          [
            127.000935,
            37.610187
          ],
          [
            127.000969,
            37.6106
          ]
        ]
      }
    }
  ]
}
```

## contact.sh

[leesangjin128@gmail.com](mailto:leesangjin128@gmail.com)

