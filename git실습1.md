```bash

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop
$ cd test

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test
$ git init
Initialized empty Git repository in C:/Users/cooka/Desktop/test/.git/

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ touch a.txt

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ git add a.txt

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ git commit -m 'first commit'
[master (root-commit) 035335e] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 a.txt

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ touch b.png

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ git add b.png

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ git commit -m 'second commit'
[master c8c0a8c] second commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 b.png

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ git add a.txt

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ git commit -m 'first commit2'
[master e4643d9] first commit2
 1 file changed, 1 insertion(+)

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ /status
bash: /status: No such file or directory

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ ls
a.txt  b.png

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ log
bash: log: command not found

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ log -1
bash: log: command not found

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$ git log
commit e4643d9a59e491b23926025c10c20e87fdb5bfcd (HEAD -> master)
Author: KyungsooPark <cookadsl@naver.com>
Date:   Mon Aug 9 14:25:46 2021 +0900

    first commit2

commit c8c0a8c7931f8f85f4a92f3bc7bc46c7f16af468
Author: KyungsooPark <cookadsl@naver.com>
Date:   Mon Aug 9 14:24:39 2021 +0900

    second commit

commit 035335ed830c3e5dd1025073fec2c27208f21db7
Author: KyungsooPark <cookadsl@naver.com>
Date:   Mon Aug 9 14:24:04 2021 +0900

    first commit

cooka@DESKTOP-P53P1IV MINGW64 ~/Desktop/test (master)
$
```

