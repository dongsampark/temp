# GitHub와 Atom 연동하기
---
### 1. GitHub 계정 생성
- GitHub 홈페이지에 접속한다. (https://github.com/)

- 회원 가입을 위해 `Sign Up` 버튼을 클릭한다.  
![01](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/01.png)

- Login 시 사용할 `Username`과 `Email Address`, `Password`를 입력한 후, 하단 퀴즈를 진행한다. 모든 정보를 입력하고 `Create Account` 버튼을 클릭한다.  
![02](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/02.png)

- 계정 검증을 위해 다시한번 퀴즈를 풀고, `Join a free plan` 버튼을 클릭한다.  
![03](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/03.png)

- 메일이 도착하면 `Verify email address` 버튼을 클릭한다. 홈페이지에서는 관심사를 설정할 수 있다.
![04](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/04.png)  

### 2. Atom 설치
- Atom 홈페이지에 접속한다. (https://atom.io/)     
![05](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/05.png)    

- `Download` 버튼을 클릭하여 Atom 설치 파일을 다운로드 한다. (약 180MB)

- 다운로드가 완료되면, 설치 파일을 실행한다.
> 설치는 자동으로 진행된다.
>> 경로는 Windows의 경우 C:\Users\[USER]\AppData\Local\atom 이다.

- Atom이 시작되면, 우선 다음 단계를 진행한다.  
![05-1](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/05-1.png)  

### 3. Git 설치  
- Git 홈페이지에 접속한다. (https://git-scm.com/)  

- `Downloads` 메뉴나 좌측 모니터 모양의 메뉴에서 설치파일을 다운로드 한다. (약 45MB)  
![06](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/06.png)    

- 다운로드가완료되면, 설치를 진행한다.   
![08](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/08.png)    
![09](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/09.png)    
- 취향에 따라 체크박스를 선택하거나 제거할 수 있다.  
![10](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/10.png)  
![11](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/11.png)  
- Git에서 사용할 기본 Editor를 선택한다.
![12](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/12.png)  
![13](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/13.png)      
![14](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/14.png)  
![15](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/15.png)   
![16](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/16.png)    
![17](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/17.png)    
![18](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/18.png)    
![19](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/19.png)    

### 4. GitHub (Remote) Repository 생성
- 우측 상단 프로필 아이콘을 클릭한 후, `Your Repository`를 클릭한다. 초기 화면으로 이동되며, 좌측 `New`버튼을 클릭한다.  
![20](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/20.png)  
![21](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/21.png)  

- `Repository name`을 입려한 후, `Create repository`버튼을 클릭한다.  
![22](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/22.png)  
![23](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/23.png)  
> Repository를 Public혹은 Private하게 사용할 것인지를 선택할 수있다. 그 외에 Repository 초기화(initialization)를 하거나 등의 설정을 할 수 있으나, 나중에도 설정이 가능하기 때문에 지금은 건너뛴다.  

### 5. Atom 설정
- Atom에서  `Ctrl + ,` 키를 입력하여 `Setting` 페이지를 연다. 좌측 `Install` 메뉴를 선택한 후, `git-plus` 패키지를 검색하여 `Install` 버튼을 클릭한다.  
![24](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/24.png)  

- `Ctrl + Shift + A` 키를 이용하여 프로젝트 폴더를 생성하거나 지정한다.  
> Add Project Folder - `Ctrl + Shift + A`  

- 좌측 `Project` 탭에서 생성한 폴더를 클릭 한 후, `a`키를 입력하면 새로운 파일을 만들 수 있다.

- 파일명 : `README.md`
```bash
# README.md
Test File
```
- `Ctrl + S` 키를 입력하여 저장한 후, 상단 `Package` 메뉴에서 `Github-Toggle`-`Git Tab`을 선택하거나, `Ctrl + Shift + 9` 키를 이용하여 `Git Tab`을 연다.  

- `Git Tab`에 있는 `Create Repository` 버튼을 클릭한 후, 현재 프로젝트 폴더를 지정한다.  
![25](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/25.png)  
> 해당 프로젝트 폴더는 Local Repository 폴더가 된다.

- `Init` 버튼을 클릭하면, 프로젝트 폴더 아래 `.git` 폴더가 생성된다.
> 해당 과정은 `$git init` 이라는 명령어로 대체 할 수 있다.  

### Git Bash 설정
- Git Bash를 실행한 후, 프로젝트 폴더로 이동한다. (Local Repository)  
![26](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/26.png)
  > Linux의 다양한 명령어를 사용할 수 있다.
  >> Atom에서 해당 폴더를 git이 사용할 수있도록 초기화하였기 때문에, Master Branch를 나타내는 (master)가 프롬프트에 출력된다.

  ```Bash
  # GitHub 페이지에서 명령어를 참고할 수 있다.
  $git config user.name [USER_NAME]
  $git config user.email [E_MAIL]
  $git remote add origin https://github.com/[USERNAME]/[REPOSITORY_NAME].git
  ```
- 순서대로 명령어를 입력한다.  
![27](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/27.png)  
  ```Bash
  $git add README.md
  $git commit –m “First commit”
  $git push –u origin master
  ```
- 순서 대로 명령어를 입력한다.  
![28](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/28.png)

  ```Bash
  # git push Example
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 238 bytes | 119.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/dongsamtest/test.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
  ```

- `git push` 명령어 입력 시 최초 한번 로그인이 필요하다.  
![29](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/29.png)

### 연동 확인
- GitHub Repository에서 Push한 `README.md` 파일을 확인할 수 있다.  
![30](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/30.png)  

- Atom에서 `README.md` 파일의 내용을 변경한 후, 파일을 저장하면 `Unstaged Changes`에 파일이 위치하며, `Stage All` 을 클릭하여 모든 파일을 `Staged Changes`로 이동시키거나, 파일을 클릭하여 개별적으로 이동 시킬 수 있다.

- `Commit message`에 내용을 작성하면, 하단에 있는 `Commit to master` 버튼이 활성화 된다. `Commit to master` 버튼을 클릭하면 하단에 `Push` 버튼이 활성화 되고 GitHub Repository로 Push 할 수 있다.  
![31](https://github.com/dongsampark/temp/blob/master/incompletion/images/20200430/31.png)  
