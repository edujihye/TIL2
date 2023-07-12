- `git init` : 이 폴더 공간을 앞으로 git으로 관리할거야!
- `git status` : 지금 이 폴더에 변화가 어떻게되니?
- `git add`: 
    - `.` : 모든 파일 다 깃으로 관리 시작해!!
    - `[파일 이름.확장자]`: 특정 파일 깃으로 관리 시작해!!
    - ` ` : 공백으로 파일명 구분
    - `git status` 를 통해서 **staging area 에 잘 올라갔는지 확인**


- `git commit`:
    - `-m "[내가 적고 싶은 커밋 메시지]"` : 메시지를 적겠어!
        -`git commit -m "my first commit"`
        - 명령어로 시작해라. edit, ammend, done


* `git config` : 내 계정 연결
    * `--global user.email "[나의 깃헙 이메일 주소]"` 
    * `--global user.name "[나의 깃헙 유저이름]"`
    * 내 계정 연결 등록이 잘 됐는지 확인할려면 따옴표로 묶은 내용 없이 명령어 입력
        * `git config --global user.email | user.name`

* `git remote`: branch 첫 연결
    * `add [branch 별명] [repo 주소]`
    * `git remote add origin https://github.com/edujihye/TIL2.git`
    * `git remote -v` : remote 연결 확인


