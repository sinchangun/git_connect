# git_connect

# git 설치 --> 기본값으로 그대로 설치했음

# 시작버튼에서 git bash 열기

```
git config --global user.name "scn"
```

# github 가입시 입력한 이메일과 도일 해야한다.

```
git config --global user.name "sinchun6@gmail.com"
```
# 정보 확인하기
```
git config --list
```

위의 내용은 컴퓨터에 한번만 적용하면된다.
-------------------------
-------------------------

# Github에 코드 업로드하기

1. 초기화

   ```
   git init
   ```
# .git이라는 폴더가 생성된다.

2. 파일 올리기

  ```
  git add .
  ```

3. 히스토리 만들기

   ```
  git commit -m "내가적고싶은 메세지를 적기"

# -m 메세지의 준말

4. Github repository랑 내 로컬 프로젝트랑 연결 (깃헙에 프로젝트를 올릴 repository를 먼저 만들어야한다.)
# 아래 주소는 깃헙에서 만든 repository에서 복사해서 가져와야한다. (repository를 만들때 readme를 선택하지 말아야한다.)

```
git remote add origin https://github.com/sinchangun/webstandard.git
```
5. 잘연결되있는지 확인 (필수아님)

   git remote -v

6. github에 자료 올리기
   ```
   git push origin matser
   ```
#여기까지하면 github의 repository에 자료가 올라가 있다.



   
