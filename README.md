<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/header-dark-m.svg?v=4">
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/header-light-m.svg?v=4">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/header-dark.svg?v=4">
  <img alt="이상진" src="https://raw.githubusercontent.com/Sangjin-kmu/Sangjin-kmu/main/assets/header-light.svg?v=4" width="100%">
</picture>

> [!NOTE]
> 지금은 혼자 만든 학식 리뷰 서비스 [모나와](https://www.monawa.site)를 운영하면서 가족 체력 서비스 우리가족 체력키움의 프론트엔드를 만들고 있습니다.

고등학교 때 문제 풀이로 코딩을 배우다가, 카카오톡 봇을 만들면서 직접 만드는 재미를 알았습니다. 학교 학식표를 긁어 오는 안드로이드 앱도 그때 만들었습니다. 대학에서는 웹 팀 프로젝트마다 서버와 배포를 주로 맡았고, 화면이 필요하면 화면도 만들었습니다.

## projects/

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

## nameplate.stl

```stl
solid nameplate
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 37.63 -25.3 4
vertex 38.8 -25.14 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 38.8 -25.14 0
vertex 37.63 -25.3 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 38.8 -25.14 4
vertex 39.88 -24.69 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 39.88 -24.69 0
vertex 38.8 -25.14 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 39.88 -24.69 4
vertex 40.81 -23.98 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 40.81 -23.98 0
vertex 39.88 -24.69 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 40.81 -23.98 4
vertex 41.53 -23.05 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 41.53 -23.05 0
vertex 40.81 -23.98 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 41.53 -23.05 4
vertex 41.98 -21.96 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 41.98 -21.96 0
vertex 41.53 -23.05 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 41.98 -21.96 4
vertex 42.13 -20.8 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 42.13 -20.8 0
vertex 41.98 -21.96 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 42.13 -20.8 4
vertex 42.13 20.8 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 42.13 20.8 0
vertex 42.13 -20.8 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 42.13 20.8 4
vertex 41.98 21.96 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 41.98 21.96 0
vertex 42.13 20.8 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 41.98 21.96 4
vertex 41.53 23.05 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 41.53 23.05 0
vertex 41.98 21.96 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 41.53 23.05 4
vertex 40.81 23.98 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 40.81 23.98 0
vertex 41.53 23.05 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 40.81 23.98 4
vertex 39.88 24.69 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 39.88 24.69 0
vertex 40.81 23.98 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 39.88 24.69 4
vertex 38.8 25.14 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 38.8 25.14 0
vertex 39.88 24.69 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 38.8 25.14 4
vertex 37.63 25.3 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex 37.63 25.3 0
vertex 38.8 25.14 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex 37.63 25.3 4
vertex -37.63 25.3 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -37.63 25.3 0
vertex 37.63 25.3 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -37.63 25.3 4
vertex -38.8 25.14 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -38.8 25.14 0
vertex -37.63 25.3 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -38.8 25.14 4
vertex -39.88 24.69 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -39.88 24.69 0
vertex -38.8 25.14 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -39.88 24.69 4
vertex -40.81 23.98 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -40.81 23.98 0
vertex -39.88 24.69 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -40.81 23.98 4
vertex -41.53 23.05 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -41.53 23.05 0
vertex -40.81 23.98 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -41.53 23.05 4
vertex -41.98 21.96 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -41.98 21.96 0
vertex -41.53 23.05 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -41.98 21.96 4
vertex -42.13 20.8 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -42.13 20.8 0
vertex -41.98 21.96 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -42.13 20.8 4
vertex -42.13 -20.8 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -42.13 -20.8 0
vertex -42.13 20.8 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -42.13 -20.8 4
vertex -41.98 -21.96 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -41.98 -21.96 0
vertex -42.13 -20.8 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -41.98 -21.96 4
vertex -41.53 -23.05 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -41.53 -23.05 0
vertex -41.98 -21.96 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -41.53 -23.05 4
vertex -40.81 -23.98 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -40.81 -23.98 0
vertex -41.53 -23.05 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.63 -25.3 4
vertex -40.81 -23.98 4
vertex -39.88 -24.69 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.63 -25.3 0
vertex -39.88 -24.69 0
vertex -40.81 -23.98 0
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -39.88 -24.69 4
vertex -38.8 -25.14 4
vertex -37.63 -25.3 4
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -39.88 -24.69 0
vertex -37.63 -25.3 0
vertex -38.8 -25.14 0
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex 37.63 -25.3 0
vertex 38.8 -25.14 0
vertex 38.8 -25.14 4
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex 37.63 -25.3 0
vertex 38.8 -25.14 4
vertex 37.63 -25.3 4
endloop
endfacet
facet normal 0.38 0.92 0
outer loop
vertex 38.8 -25.14 0
vertex 39.88 -24.69 0
vertex 39.88 -24.69 4
endloop
endfacet
facet normal 0.38 0.92 0
outer loop
vertex 38.8 -25.14 0
vertex 39.88 -24.69 4
vertex 38.8 -25.14 4
endloop
endfacet
facet normal 0.61 0.79 0
outer loop
vertex 39.88 -24.69 0
vertex 40.81 -23.98 0
vertex 40.81 -23.98 4
endloop
endfacet
facet normal 0.61 0.79 0
outer loop
vertex 39.88 -24.69 0
vertex 40.81 -23.98 4
vertex 39.88 -24.69 4
endloop
endfacet
facet normal 0.79 0.61 0
outer loop
vertex 40.81 -23.98 0
vertex 41.53 -23.05 0
vertex 41.53 -23.05 4
endloop
endfacet
facet normal 0.79 0.61 0
outer loop
vertex 40.81 -23.98 0
vertex 41.53 -23.05 4
vertex 40.81 -23.98 4
endloop
endfacet
facet normal 0.92 0.38 0
outer loop
vertex 41.53 -23.05 0
vertex 41.98 -21.96 0
vertex 41.98 -21.96 4
endloop
endfacet
facet normal 0.92 0.38 0
outer loop
vertex 41.53 -23.05 0
vertex 41.98 -21.96 4
vertex 41.53 -23.05 4
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex 41.98 -21.96 0
vertex 42.13 -20.8 0
vertex 42.13 -20.8 4
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex 41.98 -21.96 0
vertex 42.13 -20.8 4
vertex 41.98 -21.96 4
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 42.13 -20.8 0
vertex 42.13 20.8 0
vertex 42.13 20.8 4
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 42.13 -20.8 0
vertex 42.13 20.8 4
vertex 42.13 -20.8 4
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex 42.13 20.8 0
vertex 41.98 21.96 0
vertex 41.98 21.96 4
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex 42.13 20.8 0
vertex 41.98 21.96 4
vertex 42.13 20.8 4
endloop
endfacet
facet normal 0.92 0.38 0
outer loop
vertex 41.98 21.96 0
vertex 41.53 23.05 0
vertex 41.53 23.05 4
endloop
endfacet
facet normal 0.92 0.38 0
outer loop
vertex 41.98 21.96 0
vertex 41.53 23.05 4
vertex 41.98 21.96 4
endloop
endfacet
facet normal 0.79 0.61 0
outer loop
vertex 41.53 23.05 0
vertex 40.81 23.98 0
vertex 40.81 23.98 4
endloop
endfacet
facet normal 0.79 0.61 0
outer loop
vertex 41.53 23.05 0
vertex 40.81 23.98 4
vertex 41.53 23.05 4
endloop
endfacet
facet normal 0.61 0.79 0
outer loop
vertex 40.81 23.98 0
vertex 39.88 24.69 0
vertex 39.88 24.69 4
endloop
endfacet
facet normal 0.61 0.79 0
outer loop
vertex 40.81 23.98 0
vertex 39.88 24.69 4
vertex 40.81 23.98 4
endloop
endfacet
facet normal 0.38 0.92 0
outer loop
vertex 39.88 24.69 0
vertex 38.8 25.14 0
vertex 38.8 25.14 4
endloop
endfacet
facet normal 0.38 0.92 0
outer loop
vertex 39.88 24.69 0
vertex 38.8 25.14 4
vertex 39.88 24.69 4
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex 38.8 25.14 0
vertex 37.63 25.3 0
vertex 37.63 25.3 4
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex 38.8 25.14 0
vertex 37.63 25.3 4
vertex 38.8 25.14 4
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 37.63 25.3 0
vertex -37.63 25.3 0
vertex -37.63 25.3 4
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 37.63 25.3 0
vertex -37.63 25.3 4
vertex 37.63 25.3 4
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex -37.63 25.3 0
vertex -38.8 25.14 0
vertex -38.8 25.14 4
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex -37.63 25.3 0
vertex -38.8 25.14 4
vertex -37.63 25.3 4
endloop
endfacet
facet normal 0.38 0.92 0
outer loop
vertex -38.8 25.14 0
vertex -39.88 24.69 0
vertex -39.88 24.69 4
endloop
endfacet
facet normal 0.38 0.92 0
outer loop
vertex -38.8 25.14 0
vertex -39.88 24.69 4
vertex -38.8 25.14 4
endloop
endfacet
facet normal 0.61 0.79 0
outer loop
vertex -39.88 24.69 0
vertex -40.81 23.98 0
vertex -40.81 23.98 4
endloop
endfacet
facet normal 0.61 0.79 0
outer loop
vertex -39.88 24.69 0
vertex -40.81 23.98 4
vertex -39.88 24.69 4
endloop
endfacet
facet normal 0.79 0.61 0
outer loop
vertex -40.81 23.98 0
vertex -41.53 23.05 0
vertex -41.53 23.05 4
endloop
endfacet
facet normal 0.79 0.61 0
outer loop
vertex -40.81 23.98 0
vertex -41.53 23.05 4
vertex -40.81 23.98 4
endloop
endfacet
facet normal 0.92 0.38 0
outer loop
vertex -41.53 23.05 0
vertex -41.98 21.96 0
vertex -41.98 21.96 4
endloop
endfacet
facet normal 0.92 0.38 0
outer loop
vertex -41.53 23.05 0
vertex -41.98 21.96 4
vertex -41.53 23.05 4
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -41.98 21.96 0
vertex -42.13 20.8 0
vertex -42.13 20.8 4
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -41.98 21.96 0
vertex -42.13 20.8 4
vertex -41.98 21.96 4
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -42.13 20.8 0
vertex -42.13 -20.8 0
vertex -42.13 -20.8 4
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -42.13 20.8 0
vertex -42.13 -20.8 4
vertex -42.13 20.8 4
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -42.13 -20.8 0
vertex -41.98 -21.96 0
vertex -41.98 -21.96 4
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -42.13 -20.8 0
vertex -41.98 -21.96 4
vertex -42.13 -20.8 4
endloop
endfacet
facet normal 0.92 0.38 0
outer loop
vertex -41.98 -21.96 0
vertex -41.53 -23.05 0
vertex -41.53 -23.05 4
endloop
endfacet
facet normal 0.92 0.38 0
outer loop
vertex -41.98 -21.96 0
vertex -41.53 -23.05 4
vertex -41.98 -21.96 4
endloop
endfacet
facet normal 0.79 0.61 0
outer loop
vertex -41.53 -23.05 0
vertex -40.81 -23.98 0
vertex -40.81 -23.98 4
endloop
endfacet
facet normal 0.79 0.61 0
outer loop
vertex -41.53 -23.05 0
vertex -40.81 -23.98 4
vertex -41.53 -23.05 4
endloop
endfacet
facet normal 0.61 0.79 0
outer loop
vertex -40.81 -23.98 0
vertex -39.88 -24.69 0
vertex -39.88 -24.69 4
endloop
endfacet
facet normal 0.61 0.79 0
outer loop
vertex -40.81 -23.98 0
vertex -39.88 -24.69 4
vertex -40.81 -23.98 4
endloop
endfacet
facet normal 0.38 0.92 0
outer loop
vertex -39.88 -24.69 0
vertex -38.8 -25.14 0
vertex -38.8 -25.14 4
endloop
endfacet
facet normal 0.38 0.92 0
outer loop
vertex -39.88 -24.69 0
vertex -38.8 -25.14 4
vertex -39.88 -24.69 4
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex -38.8 -25.14 0
vertex -37.63 -25.3 0
vertex -37.63 -25.3 4
endloop
endfacet
facet normal 0.13 0.99 0
outer loop
vertex -38.8 -25.14 0
vertex -37.63 -25.3 4
vertex -38.8 -25.14 4
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -37.63 -25.3 0
vertex 37.63 -25.3 0
vertex 37.63 -25.3 4
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -37.63 -25.3 0
vertex 37.63 -25.3 4
vertex -37.63 -25.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 37.73 16.3 5.2
vertex 38.57 16.46 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex 38.57 16.46 4
vertex 37.73 16.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 38.57 16.46 5.2
vertex 39.29 16.94 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex 39.29 16.94 4
vertex 38.57 16.46 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 39.29 16.94 5.2
vertex 39.76 17.65 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex 39.76 17.65 4
vertex 39.29 16.94 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 39.76 17.65 5.2
vertex 39.93 18.5 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex 39.93 18.5 4
vertex 39.76 17.65 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 39.93 18.5 5.2
vertex 39.93 20.9 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex 39.93 20.9 4
vertex 39.93 18.5 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 39.93 20.9 5.2
vertex 39.76 21.74 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex 39.76 21.74 4
vertex 39.93 20.9 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 39.76 21.74 5.2
vertex 39.29 22.45 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex 39.29 22.45 4
vertex 39.76 21.74 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 39.29 22.45 5.2
vertex 38.57 22.93 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex 38.57 22.93 4
vertex 39.29 22.45 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 38.57 22.93 5.2
vertex 37.73 23.1 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex 37.73 23.1 4
vertex 38.57 22.93 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex 37.73 23.1 5.2
vertex -37.73 23.1 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex -37.73 23.1 4
vertex 37.73 23.1 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex -37.73 23.1 5.2
vertex -38.57 22.93 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex -38.57 22.93 4
vertex -37.73 23.1 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex -38.57 22.93 5.2
vertex -39.29 22.45 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex -39.29 22.45 4
vertex -38.57 22.93 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex -39.29 22.45 5.2
vertex -39.76 21.74 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex -39.76 21.74 4
vertex -39.29 22.45 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex -39.76 21.74 5.2
vertex -39.93 20.9 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex -39.93 20.9 4
vertex -39.76 21.74 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex -39.93 20.9 5.2
vertex -39.93 18.5 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex -39.93 18.5 4
vertex -39.93 20.9 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex -39.93 18.5 5.2
vertex -39.76 17.65 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex -39.76 17.65 4
vertex -39.93 18.5 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -37.73 16.3 5.2
vertex -39.76 17.65 5.2
vertex -39.29 16.94 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -37.73 16.3 4
vertex -39.29 16.94 4
vertex -39.76 17.65 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -39.29 16.94 5.2
vertex -38.57 16.46 5.2
vertex -37.73 16.3 5.2
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -39.29 16.94 4
vertex -37.73 16.3 4
vertex -38.57 16.46 4
endloop
endfacet
facet normal 0.2 0.98 0
outer loop
vertex 37.73 16.3 4
vertex 38.57 16.46 4
vertex 38.57 16.46 5.2
endloop
endfacet
facet normal 0.2 0.98 0
outer loop
vertex 37.73 16.3 4
vertex 38.57 16.46 5.2
vertex 37.73 16.3 5.2
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex 38.57 16.46 4
vertex 39.29 16.94 4
vertex 39.29 16.94 5.2
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex 38.57 16.46 4
vertex 39.29 16.94 5.2
vertex 38.57 16.46 5.2
endloop
endfacet
facet normal 0.83 0.56 0
outer loop
vertex 39.29 16.94 4
vertex 39.76 17.65 4
vertex 39.76 17.65 5.2
endloop
endfacet
facet normal 0.83 0.56 0
outer loop
vertex 39.29 16.94 4
vertex 39.76 17.65 5.2
vertex 39.29 16.94 5.2
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex 39.76 17.65 4
vertex 39.93 18.5 4
vertex 39.93 18.5 5.2
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex 39.76 17.65 4
vertex 39.93 18.5 5.2
vertex 39.76 17.65 5.2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 39.93 18.5 4
vertex 39.93 20.9 4
vertex 39.93 20.9 5.2
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 39.93 18.5 4
vertex 39.93 20.9 5.2
vertex 39.93 18.5 5.2
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex 39.93 20.9 4
vertex 39.76 21.74 4
vertex 39.76 21.74 5.2
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex 39.93 20.9 4
vertex 39.76 21.74 5.2
vertex 39.93 20.9 5.2
endloop
endfacet
facet normal 0.83 0.56 0
outer loop
vertex 39.76 21.74 4
vertex 39.29 22.45 4
vertex 39.29 22.45 5.2
endloop
endfacet
facet normal 0.83 0.56 0
outer loop
vertex 39.76 21.74 4
vertex 39.29 22.45 5.2
vertex 39.76 21.74 5.2
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex 39.29 22.45 4
vertex 38.57 22.93 4
vertex 38.57 22.93 5.2
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex 39.29 22.45 4
vertex 38.57 22.93 5.2
vertex 39.29 22.45 5.2
endloop
endfacet
facet normal 0.2 0.98 0
outer loop
vertex 38.57 22.93 4
vertex 37.73 23.1 4
vertex 37.73 23.1 5.2
endloop
endfacet
facet normal 0.2 0.98 0
outer loop
vertex 38.57 22.93 4
vertex 37.73 23.1 5.2
vertex 38.57 22.93 5.2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 37.73 23.1 4
vertex -37.73 23.1 4
vertex -37.73 23.1 5.2
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 37.73 23.1 4
vertex -37.73 23.1 5.2
vertex 37.73 23.1 5.2
endloop
endfacet
facet normal 0.2 0.98 0
outer loop
vertex -37.73 23.1 4
vertex -38.57 22.93 4
vertex -38.57 22.93 5.2
endloop
endfacet
facet normal 0.2 0.98 0
outer loop
vertex -37.73 23.1 4
vertex -38.57 22.93 5.2
vertex -37.73 23.1 5.2
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex -38.57 22.93 4
vertex -39.29 22.45 4
vertex -39.29 22.45 5.2
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex -38.57 22.93 4
vertex -39.29 22.45 5.2
vertex -38.57 22.93 5.2
endloop
endfacet
facet normal 0.83 0.56 0
outer loop
vertex -39.29 22.45 4
vertex -39.76 21.74 4
vertex -39.76 21.74 5.2
endloop
endfacet
facet normal 0.83 0.56 0
outer loop
vertex -39.29 22.45 4
vertex -39.76 21.74 5.2
vertex -39.29 22.45 5.2
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex -39.76 21.74 4
vertex -39.93 20.9 4
vertex -39.93 20.9 5.2
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex -39.76 21.74 4
vertex -39.93 20.9 5.2
vertex -39.76 21.74 5.2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -39.93 20.9 4
vertex -39.93 18.5 4
vertex -39.93 18.5 5.2
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -39.93 20.9 4
vertex -39.93 18.5 5.2
vertex -39.93 20.9 5.2
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex -39.93 18.5 4
vertex -39.76 17.65 4
vertex -39.76 17.65 5.2
endloop
endfacet
facet normal 0.98 0.2 0
outer loop
vertex -39.93 18.5 4
vertex -39.76 17.65 5.2
vertex -39.93 18.5 5.2
endloop
endfacet
facet normal 0.83 0.56 0
outer loop
vertex -39.76 17.65 4
vertex -39.29 16.94 4
vertex -39.29 16.94 5.2
endloop
endfacet
facet normal 0.83 0.56 0
outer loop
vertex -39.76 17.65 4
vertex -39.29 16.94 5.2
vertex -39.76 17.65 5.2
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex -39.29 16.94 4
vertex -38.57 16.46 4
vertex -38.57 16.46 5.2
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex -39.29 16.94 4
vertex -38.57 16.46 5.2
vertex -39.29 16.94 5.2
endloop
endfacet
facet normal 0.2 0.98 0
outer loop
vertex -38.57 16.46 4
vertex -37.73 16.3 4
vertex -37.73 16.3 5.2
endloop
endfacet
facet normal 0.2 0.98 0
outer loop
vertex -38.57 16.46 4
vertex -37.73 16.3 5.2
vertex -38.57 16.46 5.2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -37.73 16.3 4
vertex 37.73 16.3 4
vertex 37.73 16.3 5.2
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -37.73 16.3 4
vertex 37.73 16.3 5.2
vertex -37.73 16.3 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -33.88 19.7 6.3
vertex -34.02 20.33 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -34.02 20.33 5.2
vertex -33.88 19.7 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -34.02 20.33 6.3
vertex -34.43 20.83 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -34.43 20.83 5.2
vertex -34.02 20.33 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -34.43 20.83 6.3
vertex -35.01 21.11 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -35.01 21.11 5.2
vertex -34.43 20.83 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -35.01 21.11 6.3
vertex -35.65 21.11 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -35.65 21.11 5.2
vertex -35.01 21.11 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -35.65 21.11 6.3
vertex -36.23 20.83 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -36.23 20.83 5.2
vertex -35.65 21.11 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -36.23 20.83 6.3
vertex -36.64 20.33 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -36.64 20.33 5.2
vertex -36.23 20.83 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -36.64 20.33 6.3
vertex -36.78 19.7 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -36.78 19.7 5.2
vertex -36.64 20.33 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -36.78 19.7 6.3
vertex -36.64 19.07 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -36.64 19.07 5.2
vertex -36.78 19.7 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -36.64 19.07 6.3
vertex -36.23 18.56 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -36.23 18.56 5.2
vertex -36.64 19.07 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -36.23 18.56 6.3
vertex -35.65 18.28 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -35.65 18.28 5.2
vertex -36.23 18.56 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -34.02 19.07 6.3
vertex -35.65 18.28 6.3
vertex -35.01 18.28 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -34.02 19.07 5.2
vertex -35.01 18.28 5.2
vertex -35.65 18.28 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -35.01 18.28 6.3
vertex -34.43 18.56 6.3
vertex -34.02 19.07 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -35.01 18.28 5.2
vertex -34.02 19.07 5.2
vertex -34.43 18.56 5.2
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -33.88 19.7 5.2
vertex -34.02 20.33 5.2
vertex -34.02 20.33 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -33.88 19.7 5.2
vertex -34.02 20.33 6.3
vertex -33.88 19.7 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -34.02 20.33 5.2
vertex -34.43 20.83 5.2
vertex -34.43 20.83 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -34.02 20.33 5.2
vertex -34.43 20.83 6.3
vertex -34.02 20.33 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -34.43 20.83 5.2
vertex -35.01 21.11 5.2
vertex -35.01 21.11 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -34.43 20.83 5.2
vertex -35.01 21.11 6.3
vertex -34.43 20.83 6.3
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -35.01 21.11 5.2
vertex -35.65 21.11 5.2
vertex -35.65 21.11 6.3
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -35.01 21.11 5.2
vertex -35.65 21.11 6.3
vertex -35.01 21.11 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -35.65 21.11 5.2
vertex -36.23 20.83 5.2
vertex -36.23 20.83 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -35.65 21.11 5.2
vertex -36.23 20.83 6.3
vertex -35.65 21.11 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -36.23 20.83 5.2
vertex -36.64 20.33 5.2
vertex -36.64 20.33 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -36.23 20.83 5.2
vertex -36.64 20.33 6.3
vertex -36.23 20.83 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -36.64 20.33 5.2
vertex -36.78 19.7 5.2
vertex -36.78 19.7 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -36.64 20.33 5.2
vertex -36.78 19.7 6.3
vertex -36.64 20.33 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -36.78 19.7 5.2
vertex -36.64 19.07 5.2
vertex -36.64 19.07 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -36.78 19.7 5.2
vertex -36.64 19.07 6.3
vertex -36.78 19.7 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -36.64 19.07 5.2
vertex -36.23 18.56 5.2
vertex -36.23 18.56 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -36.64 19.07 5.2
vertex -36.23 18.56 6.3
vertex -36.64 19.07 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -36.23 18.56 5.2
vertex -35.65 18.28 5.2
vertex -35.65 18.28 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -36.23 18.56 5.2
vertex -35.65 18.28 6.3
vertex -36.23 18.56 6.3
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -35.65 18.28 5.2
vertex -35.01 18.28 5.2
vertex -35.01 18.28 6.3
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -35.65 18.28 5.2
vertex -35.01 18.28 6.3
vertex -35.65 18.28 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -35.01 18.28 5.2
vertex -34.43 18.56 5.2
vertex -34.43 18.56 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -35.01 18.28 5.2
vertex -34.43 18.56 6.3
vertex -35.01 18.28 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -34.43 18.56 5.2
vertex -34.02 19.07 5.2
vertex -34.02 19.07 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -34.43 18.56 5.2
vertex -34.02 19.07 6.3
vertex -34.43 18.56 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -34.02 19.07 5.2
vertex -33.88 19.7 5.2
vertex -33.88 19.7 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -34.02 19.07 5.2
vertex -33.88 19.7 6.3
vertex -34.02 19.07 6.3
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -28.88 19.7 6.3
vertex -29.02 20.33 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -29.02 20.33 5.2
vertex -28.88 19.7 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -29.02 20.33 6.3
vertex -29.43 20.83 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -29.43 20.83 5.2
vertex -29.02 20.33 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -29.43 20.83 6.3
vertex -30.01 21.11 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -30.01 21.11 5.2
vertex -29.43 20.83 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -30.01 21.11 6.3
vertex -30.65 21.11 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -30.65 21.11 5.2
vertex -30.01 21.11 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -30.65 21.11 6.3
vertex -31.23 20.83 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -31.23 20.83 5.2
vertex -30.65 21.11 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -31.23 20.83 6.3
vertex -31.64 20.33 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -31.64 20.33 5.2
vertex -31.23 20.83 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -31.64 20.33 6.3
vertex -31.78 19.7 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -31.78 19.7 5.2
vertex -31.64 20.33 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -31.78 19.7 6.3
vertex -31.64 19.07 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -31.64 19.07 5.2
vertex -31.78 19.7 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -31.64 19.07 6.3
vertex -31.23 18.56 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -31.23 18.56 5.2
vertex -31.64 19.07 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -31.23 18.56 6.3
vertex -30.65 18.28 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -30.65 18.28 5.2
vertex -31.23 18.56 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.02 19.07 6.3
vertex -30.65 18.28 6.3
vertex -30.01 18.28 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.02 19.07 5.2
vertex -30.01 18.28 5.2
vertex -30.65 18.28 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -30.01 18.28 6.3
vertex -29.43 18.56 6.3
vertex -29.02 19.07 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -30.01 18.28 5.2
vertex -29.02 19.07 5.2
vertex -29.43 18.56 5.2
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -28.88 19.7 5.2
vertex -29.02 20.33 5.2
vertex -29.02 20.33 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -28.88 19.7 5.2
vertex -29.02 20.33 6.3
vertex -28.88 19.7 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -29.02 20.33 5.2
vertex -29.43 20.83 5.2
vertex -29.43 20.83 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -29.02 20.33 5.2
vertex -29.43 20.83 6.3
vertex -29.02 20.33 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -29.43 20.83 5.2
vertex -30.01 21.11 5.2
vertex -30.01 21.11 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -29.43 20.83 5.2
vertex -30.01 21.11 6.3
vertex -29.43 20.83 6.3
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -30.01 21.11 5.2
vertex -30.65 21.11 5.2
vertex -30.65 21.11 6.3
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -30.01 21.11 5.2
vertex -30.65 21.11 6.3
vertex -30.01 21.11 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -30.65 21.11 5.2
vertex -31.23 20.83 5.2
vertex -31.23 20.83 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -30.65 21.11 5.2
vertex -31.23 20.83 6.3
vertex -30.65 21.11 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -31.23 20.83 5.2
vertex -31.64 20.33 5.2
vertex -31.64 20.33 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -31.23 20.83 5.2
vertex -31.64 20.33 6.3
vertex -31.23 20.83 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -31.64 20.33 5.2
vertex -31.78 19.7 5.2
vertex -31.78 19.7 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -31.64 20.33 5.2
vertex -31.78 19.7 6.3
vertex -31.64 20.33 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -31.78 19.7 5.2
vertex -31.64 19.07 5.2
vertex -31.64 19.07 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -31.78 19.7 5.2
vertex -31.64 19.07 6.3
vertex -31.78 19.7 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -31.64 19.07 5.2
vertex -31.23 18.56 5.2
vertex -31.23 18.56 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -31.64 19.07 5.2
vertex -31.23 18.56 6.3
vertex -31.64 19.07 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -31.23 18.56 5.2
vertex -30.65 18.28 5.2
vertex -30.65 18.28 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -31.23 18.56 5.2
vertex -30.65 18.28 6.3
vertex -31.23 18.56 6.3
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -30.65 18.28 5.2
vertex -30.01 18.28 5.2
vertex -30.01 18.28 6.3
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -30.65 18.28 5.2
vertex -30.01 18.28 6.3
vertex -30.65 18.28 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -30.01 18.28 5.2
vertex -29.43 18.56 5.2
vertex -29.43 18.56 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -30.01 18.28 5.2
vertex -29.43 18.56 6.3
vertex -30.01 18.28 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -29.43 18.56 5.2
vertex -29.02 19.07 5.2
vertex -29.02 19.07 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -29.43 18.56 5.2
vertex -29.02 19.07 6.3
vertex -29.43 18.56 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -29.02 19.07 5.2
vertex -28.88 19.7 5.2
vertex -28.88 19.7 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -29.02 19.07 5.2
vertex -28.88 19.7 6.3
vertex -29.02 19.07 6.3
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -23.88 19.7 6.3
vertex -24.02 20.33 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -24.02 20.33 5.2
vertex -23.88 19.7 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -24.02 20.33 6.3
vertex -24.43 20.83 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -24.43 20.83 5.2
vertex -24.02 20.33 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -24.43 20.83 6.3
vertex -25.01 21.11 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -25.01 21.11 5.2
vertex -24.43 20.83 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -25.01 21.11 6.3
vertex -25.65 21.11 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -25.65 21.11 5.2
vertex -25.01 21.11 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -25.65 21.11 6.3
vertex -26.23 20.83 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -26.23 20.83 5.2
vertex -25.65 21.11 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -26.23 20.83 6.3
vertex -26.64 20.33 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -26.64 20.33 5.2
vertex -26.23 20.83 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -26.64 20.33 6.3
vertex -26.78 19.7 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -26.78 19.7 5.2
vertex -26.64 20.33 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -26.78 19.7 6.3
vertex -26.64 19.07 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -26.64 19.07 5.2
vertex -26.78 19.7 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -26.64 19.07 6.3
vertex -26.23 18.56 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -26.23 18.56 5.2
vertex -26.64 19.07 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -26.23 18.56 6.3
vertex -25.65 18.28 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -25.65 18.28 5.2
vertex -26.23 18.56 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.02 19.07 6.3
vertex -25.65 18.28 6.3
vertex -25.01 18.28 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.02 19.07 5.2
vertex -25.01 18.28 5.2
vertex -25.65 18.28 5.2
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -25.01 18.28 6.3
vertex -24.43 18.56 6.3
vertex -24.02 19.07 6.3
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -25.01 18.28 5.2
vertex -24.02 19.07 5.2
vertex -24.43 18.56 5.2
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -23.88 19.7 5.2
vertex -24.02 20.33 5.2
vertex -24.02 20.33 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -23.88 19.7 5.2
vertex -24.02 20.33 6.3
vertex -23.88 19.7 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -24.02 20.33 5.2
vertex -24.43 20.83 5.2
vertex -24.43 20.83 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -24.02 20.33 5.2
vertex -24.43 20.83 6.3
vertex -24.02 20.33 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -24.43 20.83 5.2
vertex -25.01 21.11 5.2
vertex -25.01 21.11 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -24.43 20.83 5.2
vertex -25.01 21.11 6.3
vertex -24.43 20.83 6.3
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -25.01 21.11 5.2
vertex -25.65 21.11 5.2
vertex -25.65 21.11 6.3
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -25.01 21.11 5.2
vertex -25.65 21.11 6.3
vertex -25.01 21.11 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -25.65 21.11 5.2
vertex -26.23 20.83 5.2
vertex -26.23 20.83 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -25.65 21.11 5.2
vertex -26.23 20.83 6.3
vertex -25.65 21.11 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -26.23 20.83 5.2
vertex -26.64 20.33 5.2
vertex -26.64 20.33 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -26.23 20.83 5.2
vertex -26.64 20.33 6.3
vertex -26.23 20.83 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -26.64 20.33 5.2
vertex -26.78 19.7 5.2
vertex -26.78 19.7 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -26.64 20.33 5.2
vertex -26.78 19.7 6.3
vertex -26.64 20.33 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -26.78 19.7 5.2
vertex -26.64 19.07 5.2
vertex -26.64 19.07 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -26.78 19.7 5.2
vertex -26.64 19.07 6.3
vertex -26.78 19.7 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -26.64 19.07 5.2
vertex -26.23 18.56 5.2
vertex -26.23 18.56 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -26.64 19.07 5.2
vertex -26.23 18.56 6.3
vertex -26.64 19.07 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -26.23 18.56 5.2
vertex -25.65 18.28 5.2
vertex -25.65 18.28 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -26.23 18.56 5.2
vertex -25.65 18.28 6.3
vertex -26.23 18.56 6.3
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -25.65 18.28 5.2
vertex -25.01 18.28 5.2
vertex -25.01 18.28 6.3
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -25.65 18.28 5.2
vertex -25.01 18.28 6.3
vertex -25.65 18.28 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -25.01 18.28 5.2
vertex -24.43 18.56 5.2
vertex -24.43 18.56 6.3
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex -25.01 18.28 5.2
vertex -24.43 18.56 6.3
vertex -25.01 18.28 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -24.43 18.56 5.2
vertex -24.02 19.07 5.2
vertex -24.02 19.07 6.3
endloop
endfacet
facet normal 0.78 0.62 0
outer loop
vertex -24.43 18.56 5.2
vertex -24.02 19.07 6.3
vertex -24.43 18.56 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -24.02 19.07 5.2
vertex -23.88 19.7 5.2
vertex -23.88 19.7 6.3
endloop
endfacet
facet normal 0.97 0.22 0
outer loop
vertex -24.02 19.07 5.2
vertex -23.88 19.7 6.3
vertex -24.02 19.07 6.3
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -14.18 -14.3 7.6
vertex -14.18 5.3 7.6
vertex -16.95 5.3 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -14.18 -14.3 4
vertex -16.95 5.3 4
vertex -14.18 5.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -16.95 5.3 7.6
vertex -16.95 -14.3 7.6
vertex -14.18 -14.3 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -16.95 5.3 4
vertex -14.18 -14.3 4
vertex -16.95 -14.3 4
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -14.18 5.3 4
vertex -16.95 5.3 4
vertex -16.95 5.3 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -14.18 5.3 4
vertex -16.95 5.3 7.6
vertex -14.18 5.3 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -16.95 5.3 4
vertex -16.95 -14.3 4
vertex -16.95 -14.3 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -16.95 5.3 4
vertex -16.95 -14.3 7.6
vertex -16.95 5.3 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -16.95 -14.3 4
vertex -14.18 -14.3 4
vertex -14.18 -14.3 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex -16.95 -14.3 4
vertex -14.18 -14.3 7.6
vertex -16.95 -14.3 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -14.18 -14.3 4
vertex -14.18 5.3 4
vertex -14.18 5.3 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -14.18 -14.3 4
vertex -14.18 5.3 7.6
vertex -14.18 -14.3 7.6
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -19.66 -3.04 7.6
vertex -20.05 0.16 7.6
vertex -22.3 -3.04 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -19.66 -3.04 4
vertex -22.3 -3.04 4
vertex -20.05 0.16 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -20.05 0.16 7.6
vertex -22.48 -1.11 7.6
vertex -22.3 -3.04 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -20.05 0.16 4
vertex -22.3 -3.04 4
vertex -22.48 -1.11 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -20.05 0.16 7.6
vertex -21.12 2.04 7.6
vertex -22.48 -1.11 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -20.05 0.16 4
vertex -22.48 -1.11 4
vertex -21.12 2.04 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -21.12 2.04 7.6
vertex -22.99 0.29 7.6
vertex -22.48 -1.11 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -21.12 2.04 4
vertex -22.48 -1.11 4
vertex -22.99 0.29 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -21.12 2.04 7.6
vertex -22.75 3.43 7.6
vertex -22.99 0.29 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -21.12 2.04 4
vertex -22.99 0.29 4
vertex -22.75 3.43 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -22.75 3.43 7.6
vertex -23.78 1.16 7.6
vertex -22.99 0.29 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -22.75 3.43 4
vertex -22.99 0.29 4
vertex -23.78 1.16 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -22.75 3.43 7.6
vertex -24.79 3.92 7.6
vertex -23.78 1.16 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -22.75 3.43 4
vertex -23.78 1.16 4
vertex -24.79 3.92 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.79 3.92 7.6
vertex -24.79 1.45 7.6
vertex -23.78 1.16 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.79 3.92 4
vertex -23.78 1.16 4
vertex -24.79 1.45 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.79 3.92 7.6
vertex -25.83 1.16 7.6
vertex -24.79 1.45 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.79 3.92 4
vertex -24.79 1.45 4
vertex -25.83 1.16 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.79 3.92 7.6
vertex -26.87 3.43 7.6
vertex -25.83 1.16 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.79 3.92 4
vertex -25.83 1.16 4
vertex -26.87 3.43 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -26.87 3.43 7.6
vertex -26.63 0.29 7.6
vertex -25.83 1.16 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -26.87 3.43 4
vertex -25.83 1.16 4
vertex -26.63 0.29 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -26.87 3.43 7.6
vertex -28.52 2.04 7.6
vertex -26.63 0.29 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -26.87 3.43 4
vertex -26.63 0.29 4
vertex -28.52 2.04 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -28.52 2.04 7.6
vertex -27.15 -1.11 7.6
vertex -26.63 0.29 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -28.52 2.04 4
vertex -26.63 0.29 4
vertex -27.15 -1.11 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -28.52 2.04 7.6
vertex -29.59 0.16 7.6
vertex -27.15 -1.11 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -28.52 2.04 4
vertex -27.15 -1.11 4
vertex -29.59 0.16 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.59 0.16 7.6
vertex -27.33 -3.04 7.6
vertex -27.15 -1.11 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.59 0.16 4
vertex -27.15 -1.11 4
vertex -27.33 -3.04 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.59 0.16 7.6
vertex -29.97 -3.04 7.6
vertex -27.33 -3.04 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.59 0.16 4
vertex -27.33 -3.04 4
vertex -29.97 -3.04 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.97 -3.04 7.6
vertex -27.15 -4.97 7.6
vertex -27.33 -3.04 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.97 -3.04 4
vertex -27.33 -3.04 4
vertex -27.15 -4.97 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.97 -3.04 7.6
vertex -29.59 -5.94 7.6
vertex -27.15 -4.97 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.97 -3.04 4
vertex -27.15 -4.97 4
vertex -29.59 -5.94 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -29.59 -5.94 7.6
vertex -28.52 -8.14 7.6
vertex -27.15 -4.97 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -29.59 -5.94 4
vertex -27.15 -4.97 4
vertex -28.52 -8.14 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -28.52 -8.14 7.6
vertex -26.63 -6.38 7.6
vertex -27.15 -4.97 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -28.52 -8.14 4
vertex -27.15 -4.97 4
vertex -26.63 -6.38 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -28.52 -8.14 7.6
vertex -26.87 -9.53 7.6
vertex -26.63 -6.38 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -28.52 -8.14 4
vertex -26.63 -6.38 4
vertex -26.87 -9.53 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -26.87 -9.53 7.6
vertex -25.83 -7.24 7.6
vertex -26.63 -6.38 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -26.87 -9.53 4
vertex -26.63 -6.38 4
vertex -25.83 -7.24 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -26.87 -9.53 7.6
vertex -24.79 -10.02 7.6
vertex -25.83 -7.24 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -26.87 -9.53 4
vertex -25.83 -7.24 4
vertex -24.79 -10.02 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.79 -10.02 7.6
vertex -24.79 -7.53 7.6
vertex -25.83 -7.24 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.79 -10.02 4
vertex -25.83 -7.24 4
vertex -24.79 -7.53 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -24.79 -10.02 7.6
vertex -22.75 -9.53 7.6
vertex -24.79 -7.53 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -24.79 -10.02 4
vertex -24.79 -7.53 4
vertex -22.75 -9.53 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -22.75 -9.53 7.6
vertex -23.78 -7.24 7.6
vertex -24.79 -7.53 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -22.75 -9.53 4
vertex -24.79 -7.53 4
vertex -23.78 -7.24 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -22.75 -9.53 7.6
vertex -22.99 -6.38 7.6
vertex -23.78 -7.24 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -22.75 -9.53 4
vertex -23.78 -7.24 4
vertex -22.99 -6.38 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -22.75 -9.53 7.6
vertex -21.12 -8.14 7.6
vertex -22.99 -6.38 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -22.75 -9.53 4
vertex -22.99 -6.38 4
vertex -21.12 -8.14 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -21.12 -8.14 7.6
vertex -22.48 -4.97 7.6
vertex -22.99 -6.38 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -21.12 -8.14 4
vertex -22.99 -6.38 4
vertex -22.48 -4.97 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -21.12 -8.14 7.6
vertex -20.05 -5.94 7.6
vertex -22.48 -4.97 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -21.12 -8.14 4
vertex -22.48 -4.97 4
vertex -20.05 -5.94 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -20.05 -5.94 7.6
vertex -22.3 -3.04 7.6
vertex -22.48 -4.97 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -20.05 -5.94 4
vertex -22.48 -4.97 4
vertex -22.3 -3.04 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -20.05 -5.94 7.6
vertex -19.66 -3.04 7.6
vertex -22.3 -3.04 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -20.05 -5.94 4
vertex -22.3 -3.04 4
vertex -19.66 -3.04 4
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -24.79 3.92 4
vertex -26.87 3.43 4
vertex -26.87 3.43 7.6
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -24.79 3.92 4
vertex -26.87 3.43 7.6
vertex -24.79 3.92 7.6
endloop
endfacet
facet normal 0.65 0.76 0
outer loop
vertex -26.87 3.43 4
vertex -28.52 2.04 4
vertex -28.52 2.04 7.6
endloop
endfacet
facet normal 0.65 0.76 0
outer loop
vertex -26.87 3.43 4
vertex -28.52 2.04 7.6
vertex -26.87 3.43 7.6
endloop
endfacet
facet normal 0.9 0.44 0
outer loop
vertex -28.52 2.04 4
vertex -29.59 0.16 4
vertex -29.59 0.16 7.6
endloop
endfacet
facet normal 0.9 0.44 0
outer loop
vertex -28.52 2.04 4
vertex -29.59 0.16 7.6
vertex -28.52 2.04 7.6
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -29.59 0.16 4
vertex -29.97 -3.04 4
vertex -29.97 -3.04 7.6
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -29.59 0.16 4
vertex -29.97 -3.04 7.6
vertex -29.59 0.16 7.6
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -29.97 -3.04 4
vertex -29.59 -5.94 4
vertex -29.59 -5.94 7.6
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -29.97 -3.04 4
vertex -29.59 -5.94 7.6
vertex -29.97 -3.04 7.6
endloop
endfacet
facet normal 0.9 0.44 0
outer loop
vertex -29.59 -5.94 4
vertex -28.52 -8.14 4
vertex -28.52 -8.14 7.6
endloop
endfacet
facet normal 0.9 0.44 0
outer loop
vertex -29.59 -5.94 4
vertex -28.52 -8.14 7.6
vertex -29.59 -5.94 7.6
endloop
endfacet
facet normal 0.65 0.76 0
outer loop
vertex -28.52 -8.14 4
vertex -26.87 -9.53 4
vertex -26.87 -9.53 7.6
endloop
endfacet
facet normal 0.65 0.76 0
outer loop
vertex -28.52 -8.14 4
vertex -26.87 -9.53 7.6
vertex -28.52 -8.14 7.6
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -26.87 -9.53 4
vertex -24.79 -10.02 4
vertex -24.79 -10.02 7.6
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -26.87 -9.53 4
vertex -24.79 -10.02 7.6
vertex -26.87 -9.53 7.6
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -24.79 -10.02 4
vertex -22.75 -9.53 4
vertex -22.75 -9.53 7.6
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -24.79 -10.02 4
vertex -22.75 -9.53 7.6
vertex -24.79 -10.02 7.6
endloop
endfacet
facet normal 0.65 0.76 0
outer loop
vertex -22.75 -9.53 4
vertex -21.12 -8.14 4
vertex -21.12 -8.14 7.6
endloop
endfacet
facet normal 0.65 0.76 0
outer loop
vertex -22.75 -9.53 4
vertex -21.12 -8.14 7.6
vertex -22.75 -9.53 7.6
endloop
endfacet
facet normal 0.9 0.44 0
outer loop
vertex -21.12 -8.14 4
vertex -20.05 -5.94 4
vertex -20.05 -5.94 7.6
endloop
endfacet
facet normal 0.9 0.44 0
outer loop
vertex -21.12 -8.14 4
vertex -20.05 -5.94 7.6
vertex -21.12 -8.14 7.6
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -20.05 -5.94 4
vertex -19.66 -3.04 4
vertex -19.66 -3.04 7.6
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -20.05 -5.94 4
vertex -19.66 -3.04 7.6
vertex -20.05 -5.94 7.6
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -19.66 -3.04 4
vertex -20.05 0.16 4
vertex -20.05 0.16 7.6
endloop
endfacet
facet normal 0.99 0.13 0
outer loop
vertex -19.66 -3.04 4
vertex -20.05 0.16 7.6
vertex -19.66 -3.04 7.6
endloop
endfacet
facet normal 0.9 0.44 0
outer loop
vertex -20.05 0.16 4
vertex -21.12 2.04 4
vertex -21.12 2.04 7.6
endloop
endfacet
facet normal 0.9 0.44 0
outer loop
vertex -20.05 0.16 4
vertex -21.12 2.04 7.6
vertex -20.05 0.16 7.6
endloop
endfacet
facet normal 0.65 0.76 0
outer loop
vertex -21.12 2.04 4
vertex -22.75 3.43 4
vertex -22.75 3.43 7.6
endloop
endfacet
facet normal 0.65 0.76 0
outer loop
vertex -21.12 2.04 4
vertex -22.75 3.43 7.6
vertex -21.12 2.04 7.6
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -22.75 3.43 4
vertex -24.79 3.92 4
vertex -24.79 3.92 7.6
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -22.75 3.43 4
vertex -24.79 3.92 7.6
vertex -22.75 3.43 7.6
endloop
endfacet
facet normal 0.28 0.96 0
outer loop
vertex -24.79 1.45 4
vertex -23.78 1.16 4
vertex -23.78 1.16 7.6
endloop
endfacet
facet normal 0.28 0.96 0
outer loop
vertex -24.79 1.45 4
vertex -23.78 1.16 7.6
vertex -24.79 1.45 7.6
endloop
endfacet
facet normal 0.74 0.67 0
outer loop
vertex -23.78 1.16 4
vertex -22.99 0.29 4
vertex -22.99 0.29 7.6
endloop
endfacet
facet normal 0.74 0.67 0
outer loop
vertex -23.78 1.16 4
vertex -22.99 0.29 7.6
vertex -23.78 1.16 7.6
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex -22.99 0.29 4
vertex -22.48 -1.11 4
vertex -22.48 -1.11 7.6
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex -22.99 0.29 4
vertex -22.48 -1.11 7.6
vertex -22.99 0.29 7.6
endloop
endfacet
facet normal -1 0.09 0
outer loop
vertex -22.48 -1.11 4
vertex -22.3 -3.04 4
vertex -22.3 -3.04 7.6
endloop
endfacet
facet normal -1 0.09 0
outer loop
vertex -22.48 -1.11 4
vertex -22.3 -3.04 7.6
vertex -22.48 -1.11 7.6
endloop
endfacet
facet normal -1 0.09 0
outer loop
vertex -22.3 -3.04 4
vertex -22.48 -4.97 4
vertex -22.48 -4.97 7.6
endloop
endfacet
facet normal -1 0.09 0
outer loop
vertex -22.3 -3.04 4
vertex -22.48 -4.97 7.6
vertex -22.3 -3.04 7.6
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex -22.48 -4.97 4
vertex -22.99 -6.38 4
vertex -22.99 -6.38 7.6
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex -22.48 -4.97 4
vertex -22.99 -6.38 7.6
vertex -22.48 -4.97 7.6
endloop
endfacet
facet normal 0.74 0.68 0
outer loop
vertex -22.99 -6.38 4
vertex -23.78 -7.24 4
vertex -23.78 -7.24 7.6
endloop
endfacet
facet normal 0.74 0.68 0
outer loop
vertex -22.99 -6.38 4
vertex -23.78 -7.24 7.6
vertex -22.99 -6.38 7.6
endloop
endfacet
facet normal 0.28 0.96 0
outer loop
vertex -23.78 -7.24 4
vertex -24.79 -7.53 4
vertex -24.79 -7.53 7.6
endloop
endfacet
facet normal 0.28 0.96 0
outer loop
vertex -23.78 -7.24 4
vertex -24.79 -7.53 7.6
vertex -23.78 -7.24 7.6
endloop
endfacet
facet normal 0.27 0.96 0
outer loop
vertex -24.79 -7.53 4
vertex -25.83 -7.24 4
vertex -25.83 -7.24 7.6
endloop
endfacet
facet normal 0.27 0.96 0
outer loop
vertex -24.79 -7.53 4
vertex -25.83 -7.24 7.6
vertex -24.79 -7.53 7.6
endloop
endfacet
facet normal 0.73 0.68 0
outer loop
vertex -25.83 -7.24 4
vertex -26.63 -6.38 4
vertex -26.63 -6.38 7.6
endloop
endfacet
facet normal 0.73 0.68 0
outer loop
vertex -25.83 -7.24 4
vertex -26.63 -6.38 7.6
vertex -25.83 -7.24 7.6
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex -26.63 -6.38 4
vertex -27.15 -4.97 4
vertex -27.15 -4.97 7.6
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex -26.63 -6.38 4
vertex -27.15 -4.97 7.6
vertex -26.63 -6.38 7.6
endloop
endfacet
facet normal 1 0.09 0
outer loop
vertex -27.15 -4.97 4
vertex -27.33 -3.04 4
vertex -27.33 -3.04 7.6
endloop
endfacet
facet normal 1 0.09 0
outer loop
vertex -27.15 -4.97 4
vertex -27.33 -3.04 7.6
vertex -27.15 -4.97 7.6
endloop
endfacet
facet normal 1 0.09 0
outer loop
vertex -27.33 -3.04 4
vertex -27.15 -1.11 4
vertex -27.15 -1.11 7.6
endloop
endfacet
facet normal 1 0.09 0
outer loop
vertex -27.33 -3.04 4
vertex -27.15 -1.11 7.6
vertex -27.33 -3.04 7.6
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex -27.15 -1.11 4
vertex -26.63 0.29 4
vertex -26.63 0.29 7.6
endloop
endfacet
facet normal 0.94 0.34 0
outer loop
vertex -27.15 -1.11 4
vertex -26.63 0.29 7.6
vertex -27.15 -1.11 7.6
endloop
endfacet
facet normal 0.73 0.68 0
outer loop
vertex -26.63 0.29 4
vertex -25.83 1.16 4
vertex -25.83 1.16 7.6
endloop
endfacet
facet normal 0.73 0.68 0
outer loop
vertex -26.63 0.29 4
vertex -25.83 1.16 7.6
vertex -26.63 0.29 7.6
endloop
endfacet
facet normal 0.27 0.96 0
outer loop
vertex -25.83 1.16 4
vertex -24.79 1.45 4
vertex -24.79 1.45 7.6
endloop
endfacet
facet normal 0.27 0.96 0
outer loop
vertex -25.83 1.16 4
vertex -24.79 1.45 7.6
vertex -25.83 1.16 7.6
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -5.06 2.22 7.6
vertex -5.06 4.27 7.6
vertex -7.81 4.27 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.06 2.22 4
vertex -7.81 4.27 4
vertex -5.06 4.27 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -5.06 2.22 7.6
vertex -7.81 4.27 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -7.81 4.27 4
vertex -5.06 2.22 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -7.81 4.27 7.6
vertex -7.81 2.48 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -7.81 2.48 4
vertex -7.81 4.27 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -7.81 2.48 7.6
vertex -8.1 0.51 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -8.1 0.51 4
vertex -7.81 2.48 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -8.1 0.51 7.6
vertex -8.94 -1.3 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -8.94 -1.3 4
vertex -8.1 0.51 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -8.94 -1.3 7.6
vertex -10.39 -2.82 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -10.39 -2.82 4
vertex -8.94 -1.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -10.39 -2.82 7.6
vertex -12.5 -3.9 7.6
vertex -11.02 -6.05 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -10.39 -2.82 4
vertex -11.02 -6.05 4
vertex -12.5 -3.9 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -10.39 -2.82 7.6
vertex -11.02 -6.05 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -11.02 -6.05 4
vertex -10.39 -2.82 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -11.02 -6.05 7.6
vertex -9.47 -5.34 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -9.47 -5.34 4
vertex -11.02 -6.05 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -9.47 -5.34 7.6
vertex -8.2 -4.37 7.6
vertex -7.18 -3.17 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.47 -5.34 4
vertex -7.18 -3.17 4
vertex -8.2 -4.37 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -9.47 -5.34 7.6
vertex -7.18 -3.17 7.6
vertex -6.42 -1.77 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.47 -5.34 4
vertex -6.42 -1.77 4
vertex -7.18 -3.17 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -9.47 -5.34 7.6
vertex -6.42 -1.77 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -6.42 -1.77 4
vertex -9.47 -5.34 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -6.42 -1.77 7.6
vertex -5.67 -2.98 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -5.67 -2.98 4
vertex -6.42 -1.77 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -5.67 -2.98 7.6
vertex -4.7 -4.03 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -4.7 -4.03 4
vertex -5.67 -2.98 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -4.7 -4.03 7.6
vertex -3.49 -4.88 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -3.49 -4.88 4
vertex -4.7 -4.03 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -4.8 0.49 7.6
vertex -3.49 -4.88 7.6
vertex -2.06 -5.51 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -4.8 0.49 4
vertex -2.06 -5.51 4
vertex -3.49 -4.88 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.06 -5.51 7.6
vertex 0.6 -3.38 7.6
vertex -2.6 -2.43 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.06 -5.51 4
vertex -2.6 -2.43 4
vertex 0.6 -3.38 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.06 -5.51 7.6
vertex -2.6 -2.43 7.6
vertex -3.99 -1.1 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.06 -5.51 4
vertex -3.99 -1.1 4
vertex -2.6 -2.43 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -2.06 -5.51 7.6
vertex -3.99 -1.1 7.6
vertex -4.8 0.49 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -2.06 -5.51 4
vertex -4.8 0.49 4
vertex -3.99 -1.1 4
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.06 2.22 4
vertex -5.06 4.27 4
vertex -5.06 4.27 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex -5.06 2.22 4
vertex -5.06 4.27 7.6
vertex -5.06 2.22 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -5.06 4.27 4
vertex -7.81 4.27 4
vertex -7.81 4.27 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex -5.06 4.27 4
vertex -7.81 4.27 7.6
vertex -5.06 4.27 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -7.81 4.27 4
vertex -7.81 2.48 4
vertex -7.81 2.48 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex -7.81 4.27 4
vertex -7.81 2.48 7.6
vertex -7.81 4.27 7.6
endloop
endfacet
facet normal 0.99 0.14 0
outer loop
vertex -7.81 2.48 4
vertex -8.1 0.51 4
vertex -8.1 0.51 7.6
endloop
endfacet
facet normal 0.99 0.14 0
outer loop
vertex -7.81 2.48 4
vertex -8.1 0.51 7.6
vertex -7.81 2.48 7.6
endloop
endfacet
facet normal 0.91 0.42 0
outer loop
vertex -8.1 0.51 4
vertex -8.94 -1.3 4
vertex -8.94 -1.3 7.6
endloop
endfacet
facet normal 0.91 0.42 0
outer loop
vertex -8.1 0.51 4
vertex -8.94 -1.3 7.6
vertex -8.1 0.51 7.6
endloop
endfacet
facet normal 0.72 0.69 0
outer loop
vertex -8.94 -1.3 4
vertex -10.39 -2.82 4
vertex -10.39 -2.82 7.6
endloop
endfacet
facet normal 0.72 0.69 0
outer loop
vertex -8.94 -1.3 4
vertex -10.39 -2.82 7.6
vertex -8.94 -1.3 7.6
endloop
endfacet
facet normal 0.46 0.89 0
outer loop
vertex -10.39 -2.82 4
vertex -12.5 -3.9 4
vertex -12.5 -3.9 7.6
endloop
endfacet
facet normal 0.46 0.89 0
outer loop
vertex -10.39 -2.82 4
vertex -12.5 -3.9 7.6
vertex -10.39 -2.82 7.6
endloop
endfacet
facet normal 0.82 0.57 0
outer loop
vertex -12.5 -3.9 4
vertex -11.02 -6.05 4
vertex -11.02 -6.05 7.6
endloop
endfacet
facet normal 0.82 0.57 0
outer loop
vertex -12.5 -3.9 4
vertex -11.02 -6.05 7.6
vertex -12.5 -3.9 7.6
endloop
endfacet
facet normal 0.42 0.91 0
outer loop
vertex -11.02 -6.05 4
vertex -9.47 -5.34 4
vertex -9.47 -5.34 7.6
endloop
endfacet
facet normal 0.42 0.91 0
outer loop
vertex -11.02 -6.05 4
vertex -9.47 -5.34 7.6
vertex -11.02 -6.05 7.6
endloop
endfacet
facet normal 0.61 0.8 0
outer loop
vertex -9.47 -5.34 4
vertex -8.2 -4.37 4
vertex -8.2 -4.37 7.6
endloop
endfacet
facet normal 0.61 0.8 0
outer loop
vertex -9.47 -5.34 4
vertex -8.2 -4.37 7.6
vertex -9.47 -5.34 7.6
endloop
endfacet
facet normal 0.76 0.65 0
outer loop
vertex -8.2 -4.37 4
vertex -7.18 -3.17 4
vertex -7.18 -3.17 7.6
endloop
endfacet
facet normal 0.76 0.65 0
outer loop
vertex -8.2 -4.37 4
vertex -7.18 -3.17 7.6
vertex -8.2 -4.37 7.6
endloop
endfacet
facet normal 0.88 0.48 0
outer loop
vertex -7.18 -3.17 4
vertex -6.42 -1.77 4
vertex -6.42 -1.77 7.6
endloop
endfacet
facet normal 0.88 0.48 0
outer loop
vertex -7.18 -3.17 4
vertex -6.42 -1.77 7.6
vertex -7.18 -3.17 7.6
endloop
endfacet
facet normal 0.85 0.52 0
outer loop
vertex -6.42 -1.77 4
vertex -5.67 -2.98 4
vertex -5.67 -2.98 7.6
endloop
endfacet
facet normal 0.85 0.52 0
outer loop
vertex -6.42 -1.77 4
vertex -5.67 -2.98 7.6
vertex -6.42 -1.77 7.6
endloop
endfacet
facet normal 0.73 0.68 0
outer loop
vertex -5.67 -2.98 4
vertex -4.7 -4.03 4
vertex -4.7 -4.03 7.6
endloop
endfacet
facet normal 0.73 0.68 0
outer loop
vertex -5.67 -2.98 4
vertex -4.7 -4.03 7.6
vertex -5.67 -2.98 7.6
endloop
endfacet
facet normal 0.58 0.82 0
outer loop
vertex -4.7 -4.03 4
vertex -3.49 -4.88 4
vertex -3.49 -4.88 7.6
endloop
endfacet
facet normal 0.58 0.82 0
outer loop
vertex -4.7 -4.03 4
vertex -3.49 -4.88 7.6
vertex -4.7 -4.03 7.6
endloop
endfacet
facet normal 0.4 0.92 0
outer loop
vertex -3.49 -4.88 4
vertex -2.06 -5.51 4
vertex -2.06 -5.51 7.6
endloop
endfacet
facet normal 0.4 0.92 0
outer loop
vertex -3.49 -4.88 4
vertex -2.06 -5.51 7.6
vertex -3.49 -4.88 7.6
endloop
endfacet
facet normal 0.82 0.57 0
outer loop
vertex -2.06 -5.51 4
vertex 0.6 -3.38 4
vertex 0.6 -3.38 7.6
endloop
endfacet
facet normal 0.82 0.57 0
outer loop
vertex -2.06 -5.51 4
vertex 0.6 -3.38 7.6
vertex -2.06 -5.51 7.6
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex 0.6 -3.38 4
vertex -2.6 -2.43 4
vertex -2.6 -2.43 7.6
endloop
endfacet
facet normal 0.43 0.9 0
outer loop
vertex 0.6 -3.38 4
vertex -2.6 -2.43 7.6
vertex 0.6 -3.38 7.6
endloop
endfacet
facet normal 0.69 0.72 0
outer loop
vertex -2.6 -2.43 4
vertex -3.99 -1.1 4
vertex -3.99 -1.1 7.6
endloop
endfacet
facet normal 0.69 0.72 0
outer loop
vertex -2.6 -2.43 4
vertex -3.99 -1.1 7.6
vertex -2.6 -2.43 7.6
endloop
endfacet
facet normal 0.89 0.45 0
outer loop
vertex -3.99 -1.1 4
vertex -4.8 0.49 4
vertex -4.8 0.49 7.6
endloop
endfacet
facet normal 0.89 0.45 0
outer loop
vertex -3.99 -1.1 4
vertex -4.8 0.49 7.6
vertex -3.99 -1.1 7.6
endloop
endfacet
facet normal 0.99 0.15 0
outer loop
vertex -4.8 0.49 4
vertex -5.06 2.22 4
vertex -5.06 2.22 7.6
endloop
endfacet
facet normal 0.99 0.15 0
outer loop
vertex -4.8 0.49 4
vertex -5.06 2.22 7.6
vertex -4.8 0.49 7.6
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.31 0.72 7.6
vertex 3.31 5.3 7.6
vertex 0.56 5.3 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.31 0.72 4
vertex 0.56 5.3 4
vertex 3.31 5.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.31 0.72 7.6
vertex 0.56 5.3 7.6
vertex 0.56 -6.3 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.31 0.72 4
vertex 0.56 -6.3 4
vertex 0.56 5.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0.56 -6.3 7.6
vertex 3.31 -6.3 7.6
vertex 3.31 -1.56 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0.56 -6.3 4
vertex 3.31 -1.56 4
vertex 3.31 -6.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.31 0.72 7.6
vertex 0.56 -6.3 7.6
vertex 3.31 -1.56 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.31 0.72 4
vertex 3.31 -1.56 4
vertex 0.56 -6.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.31 0.72 7.6
vertex 3.31 -1.56 7.6
vertex 5.96 -1.56 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.31 0.72 4
vertex 5.96 -1.56 4
vertex 3.31 -1.56 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 5.96 -1.56 7.6
vertex 5.96 0.72 7.6
vertex 3.31 0.72 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 5.96 -1.56 4
vertex 3.31 0.72 4
vertex 5.96 0.72 4
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.31 5.3 4
vertex 0.56 5.3 4
vertex 0.56 5.3 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 3.31 5.3 4
vertex 0.56 5.3 7.6
vertex 3.31 5.3 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 0.56 5.3 4
vertex 0.56 -6.3 4
vertex 0.56 -6.3 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 0.56 5.3 4
vertex 0.56 -6.3 7.6
vertex 0.56 5.3 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 0.56 -6.3 4
vertex 3.31 -6.3 4
vertex 3.31 -6.3 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 0.56 -6.3 4
vertex 3.31 -6.3 7.6
vertex 0.56 -6.3 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.31 -6.3 4
vertex 3.31 -1.56 4
vertex 3.31 -1.56 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.31 -6.3 4
vertex 3.31 -1.56 7.6
vertex 3.31 -6.3 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.31 -1.56 4
vertex 5.96 -1.56 4
vertex 5.96 -1.56 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 3.31 -1.56 4
vertex 5.96 -1.56 7.6
vertex 3.31 -1.56 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.96 -1.56 4
vertex 5.96 0.72 4
vertex 5.96 0.72 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 5.96 -1.56 4
vertex 5.96 0.72 7.6
vertex 5.96 -1.56 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 5.96 0.72 4
vertex 3.31 0.72 4
vertex 3.31 0.72 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 5.96 0.72 4
vertex 3.31 0.72 7.6
vertex 5.96 0.72 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.31 0.72 4
vertex 3.31 5.3 4
vertex 3.31 5.3 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 3.31 0.72 4
vertex 3.31 5.3 7.6
vertex 3.31 0.72 7.6
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.51 -10.47 7.6
vertex 3.05 -8.88 7.6
vertex 0.8 -10.47 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.51 -10.47 4
vertex 0.8 -10.47 4
vertex 3.05 -8.88 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.05 -8.88 7.6
vertex 0.55 -9.76 7.6
vertex 0.8 -10.47 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.05 -8.88 4
vertex 0.8 -10.47 4
vertex 0.55 -9.76 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.05 -8.88 7.6
vertex 0.19 -9.25 7.6
vertex 0.55 -9.76 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.05 -8.88 4
vertex 0.55 -9.76 4
vertex 0.19 -9.25 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.05 -8.88 7.6
vertex 1.73 -7.69 7.6
vertex 0.19 -9.25 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.05 -8.88 4
vertex 0.19 -9.25 4
vertex 1.73 -7.69 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 1.73 -7.69 7.6
vertex -1.41 -8.94 7.6
vertex 0.19 -9.25 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.73 -7.69 4
vertex 0.19 -9.25 4
vertex -1.41 -8.94 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 1.73 -7.69 7.6
vertex 0.35 -6.95 7.6
vertex -1.41 -8.94 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.73 -7.69 4
vertex -1.41 -8.94 4
vertex 0.35 -6.95 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0.35 -6.95 7.6
vertex -3.09 -8.84 7.6
vertex -1.41 -8.94 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0.35 -6.95 4
vertex -1.41 -8.94 4
vertex -3.09 -8.84 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0.35 -6.95 7.6
vertex -3.09 -6.69 7.6
vertex -3.09 -8.84 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0.35 -6.95 4
vertex -3.09 -8.84 4
vertex -3.09 -6.69 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.09 -6.69 7.6
vertex -4.8 -8.94 7.6
vertex -3.09 -8.84 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.09 -6.69 4
vertex -3.09 -8.84 4
vertex -4.8 -8.94 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.09 -6.69 7.6
vertex -5.87 -6.95 7.6
vertex -4.8 -8.94 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.09 -6.69 4
vertex -4.8 -8.94 4
vertex -5.87 -6.95 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -5.87 -6.95 7.6
vertex -7.99 -7.69 7.6
vertex -4.8 -8.94 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.87 -6.95 4
vertex -4.8 -8.94 4
vertex -7.99 -7.69 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.99 -7.69 7.6
vertex -6.04 -9.25 7.6
vertex -4.8 -8.94 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.99 -7.69 4
vertex -4.8 -8.94 4
vertex -6.04 -9.25 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.99 -7.69 7.6
vertex -9.32 -8.88 7.6
vertex -6.04 -9.25 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.99 -7.69 4
vertex -6.04 -9.25 4
vertex -9.32 -8.88 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -9.32 -8.88 7.6
vertex -6.79 -9.76 7.6
vertex -6.04 -9.25 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.32 -8.88 4
vertex -6.04 -9.25 4
vertex -6.79 -9.76 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -9.32 -8.88 7.6
vertex -9.79 -10.47 7.6
vertex -6.79 -9.76 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.32 -8.88 4
vertex -6.79 -9.76 4
vertex -9.79 -10.47 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -9.79 -10.47 7.6
vertex -7.04 -10.47 7.6
vertex -6.79 -9.76 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.79 -10.47 4
vertex -6.79 -9.76 4
vertex -7.04 -10.47 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -9.79 -10.47 7.6
vertex -6.79 -11.2 7.6
vertex -7.04 -10.47 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.79 -10.47 4
vertex -7.04 -10.47 4
vertex -6.79 -11.2 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -9.79 -10.47 7.6
vertex -9.32 -12.08 7.6
vertex -6.79 -11.2 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.79 -10.47 4
vertex -6.79 -11.2 4
vertex -9.32 -12.08 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -9.32 -12.08 7.6
vertex -6.04 -11.71 7.6
vertex -6.79 -11.2 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.32 -12.08 4
vertex -6.79 -11.2 4
vertex -6.04 -11.71 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -9.32 -12.08 7.6
vertex -7.99 -13.27 7.6
vertex -6.04 -11.71 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -9.32 -12.08 4
vertex -6.04 -11.71 4
vertex -7.99 -13.27 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.99 -13.27 7.6
vertex -4.8 -12.01 7.6
vertex -6.04 -11.71 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.99 -13.27 4
vertex -6.04 -11.71 4
vertex -4.8 -12.01 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -7.99 -13.27 7.6
vertex -5.87 -14 7.6
vertex -4.8 -12.01 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -7.99 -13.27 4
vertex -4.8 -12.01 4
vertex -5.87 -14 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -5.87 -14 7.6
vertex -3.09 -12.11 7.6
vertex -4.8 -12.01 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.87 -14 4
vertex -4.8 -12.01 4
vertex -3.09 -12.11 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -5.87 -14 7.6
vertex -3.09 -14.25 7.6
vertex -3.09 -12.11 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -5.87 -14 4
vertex -3.09 -12.11 4
vertex -3.09 -14.25 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex -3.09 -14.25 7.6
vertex 0.35 -14 7.6
vertex -3.09 -12.11 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex -3.09 -14.25 4
vertex -3.09 -12.11 4
vertex 0.35 -14 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0.35 -14 7.6
vertex -1.41 -12.01 7.6
vertex -3.09 -12.11 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0.35 -14 4
vertex -3.09 -12.11 4
vertex -1.41 -12.01 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 0.35 -14 7.6
vertex 1.73 -13.27 7.6
vertex -1.41 -12.01 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 0.35 -14 4
vertex -1.41 -12.01 4
vertex 1.73 -13.27 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 1.73 -13.27 7.6
vertex 0.19 -11.71 7.6
vertex -1.41 -12.01 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.73 -13.27 4
vertex -1.41 -12.01 4
vertex 0.19 -11.71 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 1.73 -13.27 7.6
vertex 3.05 -12.08 7.6
vertex 0.19 -11.71 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 1.73 -13.27 4
vertex 0.19 -11.71 4
vertex 3.05 -12.08 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.05 -12.08 7.6
vertex 0.55 -11.2 7.6
vertex 0.19 -11.71 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.05 -12.08 4
vertex 0.19 -11.71 4
vertex 0.55 -11.2 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.05 -12.08 7.6
vertex 3.51 -10.47 7.6
vertex 0.55 -11.2 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.05 -12.08 4
vertex 0.55 -11.2 4
vertex 3.51 -10.47 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 3.51 -10.47 7.6
vertex 0.8 -10.47 7.6
vertex 0.55 -11.2 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 3.51 -10.47 4
vertex 0.55 -11.2 4
vertex 0.8 -10.47 4
endloop
endfacet
facet normal 0.09 1 0
outer loop
vertex -3.09 -6.69 4
vertex -5.87 -6.95 4
vertex -5.87 -6.95 7.6
endloop
endfacet
facet normal 0.09 1 0
outer loop
vertex -3.09 -6.69 4
vertex -5.87 -6.95 7.6
vertex -3.09 -6.69 7.6
endloop
endfacet
facet normal 0.33 0.94 0
outer loop
vertex -5.87 -6.95 4
vertex -7.99 -7.69 4
vertex -7.99 -7.69 7.6
endloop
endfacet
facet normal 0.33 0.94 0
outer loop
vertex -5.87 -6.95 4
vertex -7.99 -7.69 7.6
vertex -5.87 -6.95 7.6
endloop
endfacet
facet normal 0.66 0.75 0
outer loop
vertex -7.99 -7.69 4
vertex -9.32 -8.88 4
vertex -9.32 -8.88 7.6
endloop
endfacet
facet normal 0.66 0.75 0
outer loop
vertex -7.99 -7.69 4
vertex -9.32 -8.88 7.6
vertex -7.99 -7.69 7.6
endloop
endfacet
facet normal 0.96 0.28 0
outer loop
vertex -9.32 -8.88 4
vertex -9.79 -10.47 4
vertex -9.79 -10.47 7.6
endloop
endfacet
facet normal 0.96 0.28 0
outer loop
vertex -9.32 -8.88 4
vertex -9.79 -10.47 7.6
vertex -9.32 -8.88 7.6
endloop
endfacet
facet normal 0.96 0.28 0
outer loop
vertex -9.79 -10.47 4
vertex -9.32 -12.08 4
vertex -9.32 -12.08 7.6
endloop
endfacet
facet normal 0.96 0.28 0
outer loop
vertex -9.79 -10.47 4
vertex -9.32 -12.08 7.6
vertex -9.79 -10.47 7.6
endloop
endfacet
facet normal 0.66 0.75 0
outer loop
vertex -9.32 -12.08 4
vertex -7.99 -13.27 4
vertex -7.99 -13.27 7.6
endloop
endfacet
facet normal 0.66 0.75 0
outer loop
vertex -9.32 -12.08 4
vertex -7.99 -13.27 7.6
vertex -9.32 -12.08 7.6
endloop
endfacet
facet normal 0.33 0.94 0
outer loop
vertex -7.99 -13.27 4
vertex -5.87 -14 4
vertex -5.87 -14 7.6
endloop
endfacet
facet normal 0.33 0.94 0
outer loop
vertex -7.99 -13.27 4
vertex -5.87 -14 7.6
vertex -7.99 -13.27 7.6
endloop
endfacet
facet normal 0.09 -1 0
outer loop
vertex -5.87 -14 4
vertex -3.09 -14.25 4
vertex -3.09 -14.25 7.6
endloop
endfacet
facet normal 0.09 -1 0
outer loop
vertex -5.87 -14 4
vertex -3.09 -14.25 7.6
vertex -5.87 -14 7.6
endloop
endfacet
facet normal 0.09 -1 0
outer loop
vertex -3.09 -14.25 4
vertex 0.35 -14 4
vertex 0.35 -14 7.6
endloop
endfacet
facet normal 0.09 -1 0
outer loop
vertex -3.09 -14.25 4
vertex 0.35 -14 7.6
vertex -3.09 -14.25 7.6
endloop
endfacet
facet normal 0.33 0.94 0
outer loop
vertex 0.35 -14 4
vertex 1.73 -13.27 4
vertex 1.73 -13.27 7.6
endloop
endfacet
facet normal 0.33 0.94 0
outer loop
vertex 0.35 -14 4
vertex 1.73 -13.27 7.6
vertex 0.35 -14 7.6
endloop
endfacet
facet normal 0.67 0.74 0
outer loop
vertex 1.73 -13.27 4
vertex 3.05 -12.08 4
vertex 3.05 -12.08 7.6
endloop
endfacet
facet normal 0.67 0.74 0
outer loop
vertex 1.73 -13.27 4
vertex 3.05 -12.08 7.6
vertex 1.73 -13.27 7.6
endloop
endfacet
facet normal 0.96 0.28 0
outer loop
vertex 3.05 -12.08 4
vertex 3.51 -10.47 4
vertex 3.51 -10.47 7.6
endloop
endfacet
facet normal 0.96 0.28 0
outer loop
vertex 3.05 -12.08 4
vertex 3.51 -10.47 7.6
vertex 3.05 -12.08 7.6
endloop
endfacet
facet normal 0.96 0.28 0
outer loop
vertex 3.51 -10.47 4
vertex 3.05 -8.88 4
vertex 3.05 -8.88 7.6
endloop
endfacet
facet normal 0.96 0.28 0
outer loop
vertex 3.51 -10.47 4
vertex 3.05 -8.88 7.6
vertex 3.51 -10.47 7.6
endloop
endfacet
facet normal 0.67 0.74 0
outer loop
vertex 3.05 -8.88 4
vertex 1.73 -7.69 4
vertex 1.73 -7.69 7.6
endloop
endfacet
facet normal 0.67 0.74 0
outer loop
vertex 3.05 -8.88 4
vertex 1.73 -7.69 7.6
vertex 3.05 -8.88 7.6
endloop
endfacet
facet normal 0.34 0.94 0
outer loop
vertex 1.73 -7.69 4
vertex 0.35 -6.95 4
vertex 0.35 -6.95 7.6
endloop
endfacet
facet normal 0.34 0.94 0
outer loop
vertex 1.73 -7.69 4
vertex 0.35 -6.95 7.6
vertex 1.73 -7.69 7.6
endloop
endfacet
facet normal 0.09 1 0
outer loop
vertex 0.35 -6.95 4
vertex -3.09 -6.69 4
vertex -3.09 -6.69 7.6
endloop
endfacet
facet normal 0.09 1 0
outer loop
vertex 0.35 -6.95 4
vertex -3.09 -6.69 7.6
vertex 0.35 -6.95 7.6
endloop
endfacet
facet normal 0.06 -1 0
outer loop
vertex -3.09 -8.84 4
vertex -1.41 -8.94 4
vertex -1.41 -8.94 7.6
endloop
endfacet
facet normal 0.06 -1 0
outer loop
vertex -3.09 -8.84 4
vertex -1.41 -8.94 7.6
vertex -3.09 -8.84 7.6
endloop
endfacet
facet normal 0.25 0.97 0
outer loop
vertex -1.41 -8.94 4
vertex 0.19 -9.25 4
vertex 0.19 -9.25 7.6
endloop
endfacet
facet normal 0.25 0.97 0
outer loop
vertex -1.41 -8.94 4
vertex 0.19 -9.25 7.6
vertex -1.41 -8.94 7.6
endloop
endfacet
facet normal 0.57 0.82 0
outer loop
vertex 0.19 -9.25 4
vertex 0.55 -9.76 4
vertex 0.55 -9.76 7.6
endloop
endfacet
facet normal 0.57 0.82 0
outer loop
vertex 0.19 -9.25 4
vertex 0.55 -9.76 7.6
vertex 0.19 -9.25 7.6
endloop
endfacet
facet normal 0.94 0.33 0
outer loop
vertex 0.55 -9.76 4
vertex 0.8 -10.47 4
vertex 0.8 -10.47 7.6
endloop
endfacet
facet normal 0.94 0.33 0
outer loop
vertex 0.55 -9.76 4
vertex 0.8 -10.47 7.6
vertex 0.55 -9.76 7.6
endloop
endfacet
facet normal 0.95 0.33 0
outer loop
vertex 0.8 -10.47 4
vertex 0.55 -11.2 4
vertex 0.55 -11.2 7.6
endloop
endfacet
facet normal 0.95 0.33 0
outer loop
vertex 0.8 -10.47 4
vertex 0.55 -11.2 7.6
vertex 0.8 -10.47 7.6
endloop
endfacet
facet normal 0.57 0.82 0
outer loop
vertex 0.55 -11.2 4
vertex 0.19 -11.71 4
vertex 0.19 -11.71 7.6
endloop
endfacet
facet normal 0.57 0.82 0
outer loop
vertex 0.55 -11.2 4
vertex 0.19 -11.71 7.6
vertex 0.55 -11.2 7.6
endloop
endfacet
facet normal 0.24 0.97 0
outer loop
vertex 0.19 -11.71 4
vertex -1.41 -12.01 4
vertex -1.41 -12.01 7.6
endloop
endfacet
facet normal 0.24 0.97 0
outer loop
vertex 0.19 -11.71 4
vertex -1.41 -12.01 7.6
vertex 0.19 -11.71 7.6
endloop
endfacet
facet normal 0.06 1 0
outer loop
vertex -1.41 -12.01 4
vertex -3.09 -12.11 4
vertex -3.09 -12.11 7.6
endloop
endfacet
facet normal 0.06 1 0
outer loop
vertex -1.41 -12.01 4
vertex -3.09 -12.11 7.6
vertex -1.41 -12.01 7.6
endloop
endfacet
facet normal 0.06 1 0
outer loop
vertex -3.09 -12.11 4
vertex -4.8 -12.01 4
vertex -4.8 -12.01 7.6
endloop
endfacet
facet normal 0.06 1 0
outer loop
vertex -3.09 -12.11 4
vertex -4.8 -12.01 7.6
vertex -3.09 -12.11 7.6
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -4.8 -12.01 4
vertex -6.04 -11.71 4
vertex -6.04 -11.71 7.6
endloop
endfacet
facet normal 0.23 0.97 0
outer loop
vertex -4.8 -12.01 4
vertex -6.04 -11.71 7.6
vertex -4.8 -12.01 7.6
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex -6.04 -11.71 4
vertex -6.79 -11.2 4
vertex -6.79 -11.2 7.6
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex -6.04 -11.71 4
vertex -6.79 -11.2 7.6
vertex -6.04 -11.71 7.6
endloop
endfacet
facet normal 0.95 0.32 0
outer loop
vertex -6.79 -11.2 4
vertex -7.04 -10.47 4
vertex -7.04 -10.47 7.6
endloop
endfacet
facet normal 0.95 0.32 0
outer loop
vertex -6.79 -11.2 4
vertex -7.04 -10.47 7.6
vertex -6.79 -11.2 7.6
endloop
endfacet
facet normal 0.94 0.33 0
outer loop
vertex -7.04 -10.47 4
vertex -6.79 -9.76 4
vertex -6.79 -9.76 7.6
endloop
endfacet
facet normal 0.94 0.33 0
outer loop
vertex -7.04 -10.47 4
vertex -6.79 -9.76 7.6
vertex -7.04 -10.47 7.6
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex -6.79 -9.76 4
vertex -6.04 -9.25 4
vertex -6.04 -9.25 7.6
endloop
endfacet
facet normal 0.56 0.83 0
outer loop
vertex -6.79 -9.76 4
vertex -6.04 -9.25 7.6
vertex -6.79 -9.76 7.6
endloop
endfacet
facet normal 0.24 0.97 0
outer loop
vertex -6.04 -9.25 4
vertex -4.8 -8.94 4
vertex -4.8 -8.94 7.6
endloop
endfacet
facet normal 0.24 0.97 0
outer loop
vertex -6.04 -9.25 4
vertex -4.8 -8.94 7.6
vertex -6.04 -9.25 7.6
endloop
endfacet
facet normal 0.06 -1 0
outer loop
vertex -4.8 -8.94 4
vertex -3.09 -8.84 4
vertex -3.09 -8.84 7.6
endloop
endfacet
facet normal 0.06 -1 0
outer loop
vertex -4.8 -8.94 4
vertex -3.09 -8.84 7.6
vertex -4.8 -8.94 7.6
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 13.78 1.71 7.6
vertex 17.72 1.71 7.6
vertex 17.72 3.9 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 13.78 1.71 4
vertex 17.72 3.9 4
vertex 17.72 1.71 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 13.78 1.71 7.6
vertex 17.72 3.9 7.6
vertex 6.97 3.9 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 13.78 1.71 4
vertex 6.97 3.9 4
vertex 17.72 3.9 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 13.78 1.43 7.6
vertex 13.78 1.71 7.6
vertex 6.97 3.9 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 13.78 1.43 4
vertex 6.97 3.9 4
vertex 13.78 1.71 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 6.97 3.9 7.6
vertex 6.97 1.71 7.6
vertex 10.99 1.71 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 6.97 3.9 4
vertex 10.99 1.71 4
vertex 6.97 1.71 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 13.78 1.43 7.6
vertex 6.97 3.9 7.6
vertex 10.99 1.71 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 13.78 1.43 4
vertex 10.99 1.71 4
vertex 6.97 3.9 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 13.78 1.43 7.6
vertex 10.99 1.71 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 10.99 1.71 4
vertex 13.78 1.43 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 10.99 1.71 7.6
vertex 10.99 1.43 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 10.99 1.43 4
vertex 10.99 1.71 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 10.99 1.43 7.6
vertex 10.71 0.41 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 10.71 0.41 4
vertex 10.99 1.43 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 10.71 0.41 7.6
vertex 9.83 -2.13 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 9.83 -2.13 4
vertex 10.71 0.41 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 9.83 -2.13 7.6
vertex 8.35 -3.59 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 8.35 -3.59 4
vertex 9.83 -2.13 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 8.35 -3.59 7.6
vertex 6.24 -4.63 7.6
vertex 7.66 -6.78 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 8.35 -3.59 4
vertex 7.66 -6.78 4
vertex 6.24 -4.63 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 8.35 -3.59 7.6
vertex 7.66 -6.78 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 7.66 -6.78 4
vertex 8.35 -3.59 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 7.66 -6.78 7.6
vertex 9.25 -6.06 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 9.25 -6.06 4
vertex 7.66 -6.78 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 9.25 -6.06 7.6
vertex 10.57 -5.1 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 10.57 -5.1 4
vertex 9.25 -6.06 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 10.57 -5.1 7.6
vertex 11.63 -3.91 7.6
vertex 12.43 -2.54 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 10.57 -5.1 4
vertex 12.43 -2.54 4
vertex 11.63 -3.91 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 10.57 -5.1 7.6
vertex 12.43 -2.54 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 12.43 -2.54 4
vertex 10.57 -5.1 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 12.43 -2.54 7.6
vertex 13.22 -3.8 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 13.22 -3.8 4
vertex 12.43 -2.54 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 13.22 -3.8 7.6
vertex 14.25 -4.89 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 14.25 -4.89 4
vertex 13.22 -3.8 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 14.25 -4.89 7.6
vertex 15.53 -5.77 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 15.53 -5.77 4
vertex 14.25 -4.89 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 14.06 0.31 7.6
vertex 15.53 -5.77 7.6
vertex 17.05 -6.41 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 14.06 0.31 4
vertex 17.05 -6.41 4
vertex 15.53 -5.77 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 17.05 -6.41 7.6
vertex 18.45 -4.26 7.6
vertex 16.36 -3.3 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 17.05 -6.41 4
vertex 16.36 -3.3 4
vertex 18.45 -4.26 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 17.05 -6.41 7.6
vertex 16.36 -3.3 7.6
vertex 14.91 -1.93 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 17.05 -6.41 4
vertex 14.91 -1.93 4
vertex 16.36 -3.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 17.05 -6.41 7.6
vertex 14.91 -1.93 7.6
vertex 14.06 0.31 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 17.05 -6.41 4
vertex 14.06 0.31 4
vertex 14.91 -1.93 4
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 13.78 1.43 4
vertex 13.78 1.71 4
vertex 13.78 1.71 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 13.78 1.43 4
vertex 13.78 1.71 7.6
vertex 13.78 1.43 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 13.78 1.71 4
vertex 17.72 1.71 4
vertex 17.72 1.71 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 13.78 1.71 4
vertex 17.72 1.71 7.6
vertex 13.78 1.71 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 17.72 1.71 4
vertex 17.72 3.9 4
vertex 17.72 3.9 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 17.72 1.71 4
vertex 17.72 3.9 7.6
vertex 17.72 1.71 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 17.72 3.9 4
vertex 6.97 3.9 4
vertex 6.97 3.9 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 17.72 3.9 4
vertex 6.97 3.9 7.6
vertex 17.72 3.9 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 6.97 3.9 4
vertex 6.97 1.71 4
vertex 6.97 1.71 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 6.97 3.9 4
vertex 6.97 1.71 7.6
vertex 6.97 3.9 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 6.97 1.71 4
vertex 10.99 1.71 4
vertex 10.99 1.71 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 6.97 1.71 4
vertex 10.99 1.71 7.6
vertex 6.97 1.71 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 10.99 1.71 4
vertex 10.99 1.43 4
vertex 10.99 1.43 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 10.99 1.71 4
vertex 10.99 1.43 7.6
vertex 10.99 1.71 7.6
endloop
endfacet
facet normal 0.99 0.15 0
outer loop
vertex 10.99 1.43 4
vertex 10.71 0.41 4
vertex 10.71 0.41 7.6
endloop
endfacet
facet normal 0.99 0.15 0
outer loop
vertex 10.99 1.43 4
vertex 10.71 0.41 7.6
vertex 10.99 1.43 7.6
endloop
endfacet
facet normal 0.89 0.45 0
outer loop
vertex 10.71 0.41 4
vertex 9.83 -2.13 4
vertex 9.83 -2.13 7.6
endloop
endfacet
facet normal 0.89 0.45 0
outer loop
vertex 10.71 0.41 4
vertex 9.83 -2.13 7.6
vertex 10.71 0.41 7.6
endloop
endfacet
facet normal 0.7 0.71 0
outer loop
vertex 9.83 -2.13 4
vertex 8.35 -3.59 4
vertex 8.35 -3.59 7.6
endloop
endfacet
facet normal 0.7 0.71 0
outer loop
vertex 9.83 -2.13 4
vertex 8.35 -3.59 7.6
vertex 9.83 -2.13 7.6
endloop
endfacet
facet normal 0.44 0.9 0
outer loop
vertex 8.35 -3.59 4
vertex 6.24 -4.63 4
vertex 6.24 -4.63 7.6
endloop
endfacet
facet normal 0.44 0.9 0
outer loop
vertex 8.35 -3.59 4
vertex 6.24 -4.63 7.6
vertex 8.35 -3.59 7.6
endloop
endfacet
facet normal 0.83 0.55 0
outer loop
vertex 6.24 -4.63 4
vertex 7.66 -6.78 4
vertex 7.66 -6.78 7.6
endloop
endfacet
facet normal 0.83 0.55 0
outer loop
vertex 6.24 -4.63 4
vertex 7.66 -6.78 7.6
vertex 6.24 -4.63 7.6
endloop
endfacet
facet normal 0.41 0.91 0
outer loop
vertex 7.66 -6.78 4
vertex 9.25 -6.06 4
vertex 9.25 -6.06 7.6
endloop
endfacet
facet normal 0.41 0.91 0
outer loop
vertex 7.66 -6.78 4
vertex 9.25 -6.06 7.6
vertex 7.66 -6.78 7.6
endloop
endfacet
facet normal 0.59 0.81 0
outer loop
vertex 9.25 -6.06 4
vertex 10.57 -5.1 4
vertex 10.57 -5.1 7.6
endloop
endfacet
facet normal 0.59 0.81 0
outer loop
vertex 9.25 -6.06 4
vertex 10.57 -5.1 7.6
vertex 9.25 -6.06 7.6
endloop
endfacet
facet normal 0.75 0.67 0
outer loop
vertex 10.57 -5.1 4
vertex 11.63 -3.91 4
vertex 11.63 -3.91 7.6
endloop
endfacet
facet normal 0.75 0.67 0
outer loop
vertex 10.57 -5.1 4
vertex 11.63 -3.91 7.6
vertex 10.57 -5.1 7.6
endloop
endfacet
facet normal 0.86 0.51 0
outer loop
vertex 11.63 -3.91 4
vertex 12.43 -2.54 4
vertex 12.43 -2.54 7.6
endloop
endfacet
facet normal 0.86 0.51 0
outer loop
vertex 11.63 -3.91 4
vertex 12.43 -2.54 7.6
vertex 11.63 -3.91 7.6
endloop
endfacet
facet normal 0.85 0.53 0
outer loop
vertex 12.43 -2.54 4
vertex 13.22 -3.8 4
vertex 13.22 -3.8 7.6
endloop
endfacet
facet normal 0.85 0.53 0
outer loop
vertex 12.43 -2.54 4
vertex 13.22 -3.8 7.6
vertex 12.43 -2.54 7.6
endloop
endfacet
facet normal 0.72 0.69 0
outer loop
vertex 13.22 -3.8 4
vertex 14.25 -4.89 4
vertex 14.25 -4.89 7.6
endloop
endfacet
facet normal 0.72 0.69 0
outer loop
vertex 13.22 -3.8 4
vertex 14.25 -4.89 7.6
vertex 13.22 -3.8 7.6
endloop
endfacet
facet normal 0.57 0.82 0
outer loop
vertex 14.25 -4.89 4
vertex 15.53 -5.77 4
vertex 15.53 -5.77 7.6
endloop
endfacet
facet normal 0.57 0.82 0
outer loop
vertex 14.25 -4.89 4
vertex 15.53 -5.77 7.6
vertex 14.25 -4.89 7.6
endloop
endfacet
facet normal 0.39 0.92 0
outer loop
vertex 15.53 -5.77 4
vertex 17.05 -6.41 4
vertex 17.05 -6.41 7.6
endloop
endfacet
facet normal 0.39 0.92 0
outer loop
vertex 15.53 -5.77 4
vertex 17.05 -6.41 7.6
vertex 15.53 -5.77 7.6
endloop
endfacet
facet normal 0.84 0.54 0
outer loop
vertex 17.05 -6.41 4
vertex 18.45 -4.26 4
vertex 18.45 -4.26 7.6
endloop
endfacet
facet normal 0.84 0.54 0
outer loop
vertex 17.05 -6.41 4
vertex 18.45 -4.26 7.6
vertex 17.05 -6.41 7.6
endloop
endfacet
facet normal 0.42 0.91 0
outer loop
vertex 18.45 -4.26 4
vertex 16.36 -3.3 4
vertex 16.36 -3.3 7.6
endloop
endfacet
facet normal 0.42 0.91 0
outer loop
vertex 18.45 -4.26 4
vertex 16.36 -3.3 7.6
vertex 18.45 -4.26 7.6
endloop
endfacet
facet normal 0.68 0.73 0
outer loop
vertex 16.36 -3.3 4
vertex 14.91 -1.93 4
vertex 14.91 -1.93 7.6
endloop
endfacet
facet normal 0.68 0.73 0
outer loop
vertex 16.36 -3.3 4
vertex 14.91 -1.93 7.6
vertex 16.36 -3.3 7.6
endloop
endfacet
facet normal 0.89 0.46 0
outer loop
vertex 14.91 -1.93 4
vertex 14.06 0.31 4
vertex 14.06 0.31 7.6
endloop
endfacet
facet normal 0.89 0.46 0
outer loop
vertex 14.91 -1.93 4
vertex 14.06 0.31 7.6
vertex 14.91 -1.93 7.6
endloop
endfacet
facet normal 0.99 0.16 0
outer loop
vertex 14.06 0.31 4
vertex 13.78 1.43 4
vertex 13.78 1.43 7.6
endloop
endfacet
facet normal 0.99 0.16 0
outer loop
vertex 14.06 0.31 4
vertex 13.78 1.43 7.6
vertex 14.06 0.31 7.6
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 22.53 -8.86 7.6
vertex 22.53 5.28 7.6
vertex 19.78 5.28 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 22.53 -8.86 4
vertex 19.78 5.28 4
vertex 22.53 5.28 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 19.78 5.28 7.6
vertex 19.78 -8.86 7.6
vertex 22.53 -8.86 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 19.78 5.28 4
vertex 22.53 -8.86 4
vertex 19.78 -8.86 4
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 22.53 5.28 4
vertex 19.78 5.28 4
vertex 19.78 5.28 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 22.53 5.28 4
vertex 19.78 5.28 7.6
vertex 22.53 5.28 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 19.78 5.28 4
vertex 19.78 -8.86 4
vertex 19.78 -8.86 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 19.78 5.28 4
vertex 19.78 -8.86 7.6
vertex 19.78 5.28 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 19.78 -8.86 4
vertex 22.53 -8.86 4
vertex 22.53 -8.86 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 19.78 -8.86 4
vertex 22.53 -8.86 7.6
vertex 19.78 -8.86 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 22.53 -8.86 4
vertex 22.53 5.28 4
vertex 22.53 5.28 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 22.53 -8.86 4
vertex 22.53 5.28 7.6
vertex 22.53 -8.86 7.6
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 23.04 -13.91 7.6
vertex 23.04 -11.72 7.6
vertex 12.19 -11.72 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 23.04 -13.91 4
vertex 12.19 -11.72 4
vertex 23.04 -11.72 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.19 -11.72 7.6
vertex 12.19 -7.57 7.6
vertex 9.42 -7.57 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.19 -11.72 4
vertex 9.42 -7.57 4
vertex 12.19 -7.57 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.19 -11.72 7.6
vertex 9.42 -7.57 7.6
vertex 9.42 -13.91 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.19 -11.72 4
vertex 9.42 -13.91 4
vertex 9.42 -7.57 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 12.19 -11.72 7.6
vertex 9.42 -13.91 7.6
vertex 23.04 -13.91 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 12.19 -11.72 4
vertex 23.04 -13.91 4
vertex 9.42 -13.91 4
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 23.04 -11.72 4
vertex 12.19 -11.72 4
vertex 12.19 -11.72 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 23.04 -11.72 4
vertex 12.19 -11.72 7.6
vertex 23.04 -11.72 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 12.19 -11.72 4
vertex 12.19 -7.57 4
vertex 12.19 -7.57 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 12.19 -11.72 4
vertex 12.19 -7.57 7.6
vertex 12.19 -11.72 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 12.19 -7.57 4
vertex 9.42 -7.57 4
vertex 9.42 -7.57 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 12.19 -7.57 4
vertex 9.42 -7.57 7.6
vertex 12.19 -7.57 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 9.42 -7.57 4
vertex 9.42 -13.91 4
vertex 9.42 -13.91 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 9.42 -7.57 4
vertex 9.42 -13.91 7.6
vertex 9.42 -7.57 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 9.42 -13.91 4
vertex 23.04 -13.91 4
vertex 23.04 -13.91 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 9.42 -13.91 4
vertex 23.04 -13.91 7.6
vertex 9.42 -13.91 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 23.04 -13.91 4
vertex 23.04 -11.72 4
vertex 23.04 -11.72 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 23.04 -13.91 4
vertex 23.04 -11.72 7.6
vertex 23.04 -13.91 7.6
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 26.13 4.3 7.6
vertex 26.13 -13.3 7.6
vertex 29.33 -13.3 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 26.13 4.3 4
vertex 29.33 -13.3 4
vertex 26.13 -13.3 4
endloop
endfacet
facet normal 0 0 1
outer loop
vertex 29.33 -13.3 7.6
vertex 29.33 4.3 7.6
vertex 26.13 4.3 7.6
endloop
endfacet
facet normal 0 0 -1
outer loop
vertex 29.33 -13.3 4
vertex 26.13 4.3 4
vertex 29.33 4.3 4
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 26.13 -13.3 4
vertex 29.33 -13.3 4
vertex 29.33 -13.3 7.6
endloop
endfacet
facet normal 0 -1 0
outer loop
vertex 26.13 -13.3 4
vertex 29.33 -13.3 7.6
vertex 26.13 -13.3 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 29.33 -13.3 4
vertex 29.33 4.3 4
vertex 29.33 4.3 7.6
endloop
endfacet
facet normal 1 0 0
outer loop
vertex 29.33 -13.3 4
vertex 29.33 4.3 7.6
vertex 29.33 -13.3 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 29.33 4.3 4
vertex 26.13 4.3 4
vertex 26.13 4.3 7.6
endloop
endfacet
facet normal 0 1 0
outer loop
vertex 29.33 4.3 4
vertex 26.13 4.3 7.6
vertex 29.33 4.3 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 26.13 4.3 4
vertex 26.13 -13.3 4
vertex 26.13 -13.3 7.6
endloop
endfacet
facet normal -1 0 0
outer loop
vertex 26.13 4.3 4
vertex 26.13 -13.3 7.6
vertex 26.13 4.3 7.6
endloop
endfacet
endsolid nameplate
```

## contact.sh

[leesangjin128@gmail.com](mailto:leesangjin128@gmail.com)

