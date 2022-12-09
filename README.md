# 📕프로젝트 소개
전북대학교 학생들을 위한 챗봇 서비스 개발입니다.

📌 Tools & Language 📌<br>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=Node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat&logo=Visual Studio Code&logoColor=white"/>
<br>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/>
<img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat&logo=ESLint&logoColor=white"/> 
<img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=flat&logo=GitHub Actions&logoColor=white"/>


<br>


## 팀원 소개

| **이혜인** | **이진형** | **서세인** |
|:-----:|:-----:|:-----: |
 **Github**: [hyein0229](https://github.com/hyein0229) | **Github**: [suhsein](https://github.com/suhsein) | **Github**: [Jinnyzinny](https://github.com/Jinnyzinny) |
| **구현 기능** | **구현 기능** | **구현 기능** | 
|  단위 테스트 <br> 학사일정 <br> 식단 안내 |  학과사무실 안내 <br> |  랜덤 인사 <br> 학사일정 <br> 식단 평가  |
<br>



## 기능 소개
- ✋Hi라고 인사를 하면 랜덤 인사를 한다.<br>
- '학사일정' 을 입력하고 원하는 날짜를 입력하면 해당 날짜의 전북대 학사일정을 안내한다. <br>
- '오늘 밥 뭐야' 를 입력하면 진수당의 🍴오늘의 점심 메뉴🥄를 알려주고 평가 결과를 안내한다.<br>
- '이번주 뭐 나와' 를 입력하면 주간 메뉴🥄의 평가 결과를 보여준다.<br>
- '학과 사무실' 을 입력하고 원하는 학과 이름을 영문으로 입력하면 📣학과사무실의 위치📣를 알려준다.<br>
<br>
<br>

# 기능 구현

# 🛠프로젝트 세팅 방법
repository를 clone 해오거나 zip을 다운받아 압축을 해제하여 작업공간에 코드를 가져옵니다.<br>
- clone 방법:

      git clone https://github.com/suhsein/2022_OSS_Teamproject.git
    
npm install 하여 package.json 에 있는 패키지들을 설치하여 환경을 세팅합니다.
- 모든 패키지 설치:

      npm install 

- devDependencies 제외하고 설치:

      npm install -production    
      
# 👬협업 컨벤션 세팅
ESLint를 사용한 코드 컨벤션을 검사.<br>
기본적으로 Airbnb 규칙을 기반으로 ESLint를 수행하고 추가된 규칙은 eslintrc.js 에 설정.
- ESLint 세팅:

        sudo npm install -g eslint eslint-config-airbnb-base eslint-plugin-import
        eslint --init
        npx install-peerdeps --dev eslint-config-airbnb
        eslintrc.js 에 'extends': ['airbnb-base'] 추가 
        
커밋 템플릿 사용
<details>
    <summary>커밋 템플릿 양식 보기</summary>
      
      ################
      # <타입> : <제목> 의 형식으로 제목을 아래 공백줄에 작성
      # 제목은 50자 이내 / 변경사항이 "무엇"인지 명확히 작성
      # 예) feat : 로그인 기능 추가

      # 바로 아래 공백은 지우지 마세요 (제목과 본문의 분리를 위함)

      ################
      # 본문(구체적인 내용)을 아랫줄에 작성
      # 여러 줄의 메시지를 작성할 땐 "-"로 구분 (한 줄은 72자 이내)

      ################
      # 꼬릿말(footer)을 아랫줄에 작성 (현재 커밋과 관련된 이슈 번호 추가 등)
      # 예) Close #7

      ################
      # feat : 새로운 기능 추가
      # fix : 버그 수정
      # docs : 문서 수정
      # test : 테스트 코드 추가
      # refact : 코드 리팩토링
      # style : 코드 의미에 영향을 주지 않는 변경사항
      # chore : 빌드 부분 혹은 패키지 매니저 수정사항
      ################

</details>
- 커밋 템플릿 설정 방법:
      
      vim .gitmessage.txt (커밋 템플릿 양식 넣기)
      git config --global commit.template .gitmessage.txt



     

