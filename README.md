# 251230

  ## Clone
  git clone https://github.com/TeamChoiKim/T2.git
  
  
  
  ## 업로드
  ```
  git add .
  git commit -m "설명내용"
  git push
  ```
  
  
  ## 최신화
  ```
  git pull
  ```
  
  
  ## branch 관련
  ```
  git branch // 현재 branch 확인
  
  git fetch origin
  git checkout 최윤우 // branch변경

  git checkout -b [신규 branch 이름] // 로컬에서만 생성
  
  ```
  
  ## branch 이름 변경
  ```
  git branch -m (oldname) (newname)
  git push origin :(oldname)
  git push --set-upstream origin (newname)
  ```
  
  ## 로컬에만 있는 브랜치 삭제하기
  ```
  git branch -d [삭제할브랜치이름]
  git branch -D [삭제할브랜치이름] (병합되지 않은 변경 사항이 있는 브랜치를 강제로 삭제하려면 대문자 -D 옵션을 사용합니다)
  ```


  ## git-hub / organizations 익숙해지기
  ```
  0. repository 생성
  1. main branch에 app 파일 업로드
  2. 각 팀원들 issue 부여
    - npm i react-router
    - page 1,2 만들기
    - Page1.jsx, Pag2.jsx 분리
    - ./src/router 폴더 만들고 index.jsx 만들어 분리