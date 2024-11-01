# GIT 과 GITHUB

<h3>2024.11.01</h3>

- GIT : 분산 관리 시스템

- GITHUB : 저장소 

    1. git init -> 저장소 생성
    2. git 설정
        ``` bash
        - git config user.name "donggil Han"
        - git config user.email "khdg1202@naver.com"
        # 공용 git 설정 -g
        ex> git config -g user.name 이름
    3. git add -> staging 등록
        ``` bash
        - git add .
    4. git commit -> 실제 저장소 저장
        ``` bash
        - git commit -m "이름"
    5. git status (상태 확인)
    6. git log

### Local Git to GitHub

    - 깃헙에서 저장소 생성
    - 저장소 주소
        - https://github.com/kkameoo/GITTEST.git

    - 원격지 등록
        - git remote add 이름 주소
        - git remote add origin https://github.com/kkameoo/GITTEST.git
    
    - push
        - git push 원격지 브랜치명
        - git push -u origin master

### From Github to Local Git

    - 복제할 원격 저장소 주소 확보
        - git clone 원격지 주소

    - 저장소 설정
        - git config name 이름
        - git config email 이메일

    - 변경 사항 확인
        - git fetch

    - 변경 사항 받아오기
        - git pull
        :wq로 저장하고 나가기

### 지켜줘야될 사항

    작업 시작 전 - git pull 
    작업 종류 후 - git commit and push