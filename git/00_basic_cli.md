# 00.basic CLI

- `ls` : 목록조회(list)

  ```
  a.txt  aa.txt  b/  b.txt
  ```

- `pwd` : 현재 디렉토리

  ```
  /c/Users/이소연
  ```

- echo $HOME : 홈 디렉토리

  ```
  /c/Users/이소연
  ```

- `ls -al` :  상세 목록조회(list)

  ```
  total 29
  drwxr-xr-x 1 AzureAD+이소연 4096  0 Jul  5 11:15 ./
  drwxr-xr-x 1 AzureAD+이소연 4096  0 Jul  5 11:42 ../
  drwxr-xr-x 1 AzureAD+이소연 4096  0 Jul  5 11:21 .git/
  -rw-r--r-- 1 AzureAD+이소연 4096 11 Jul  5 11:38 a.txt
  drwxr-xr-x 1 AzureAD+이소연 4096  0 Jul  5 10:29 b/
  -rw-r--r-- 1 AzureAD+이소연 4096  0 Jul  5 10:28 c.txt
  drwxr-xr-x 1 AzureAD+이소연 4096  0 Jul  5 11:18 my/
  ```

- `cd ..` : 상위 디렉토리 이동

  ```
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~
  $ cd ..
  
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 /c/Users
  ```

- `cd` : 홈 디렉토리로 이동

  ```
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 /c/Users
  $ cd
  
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~
  ```

- `mkdir` : 폴더 생성

  ```
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ mkdir b
  ls
  
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ ls
  a.txt  b/
  
  ```

- `touch` : 빈폴더 생성

  ```
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ touch a.txt
  
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ ls
  a.txt
  ```

- `cp` : 파일 복사

  ```
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ cp a.txt b.txt
  
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ ls
  a.txt  b/  b.txt
  ```

- `mv` : 파일 이동 및 변경

  ```
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ mv b.txt b/b.txt
  
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ ls
  a.txt  aa.txt  b/
  
  
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ mv aa.txt c.txt
  l
  AzureAD+이소연@DESKTOP-Q2CN2H7 MINGW64 ~/my-first-repo
  $ ls
  a.txt  b/  c.txt
  ```

  

