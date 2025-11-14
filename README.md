"# git-command-practice-1" 



Microsoft Windows [Version 10.0.26200.7019]
(c) Microsoft Corporation. All rights reserved.

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>echo "# git-command-practice-1" >> README.md

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>git init
Initialized empty Git repository in D:/Air-Asia-POC-7-11-2025/git-command-practice-demo-1/.git/

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>git add README.md

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>git commit -m "first commit"
[master (root-commit) a71bbf4] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>git branch -M main

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>git remote add origin https://github.com/RamaGopal-ZapCom/git-command-practice-1.git

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 247 bytes | 247.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/RamaGopal-ZapCom/git-command-practice-1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>git add .
warning: in the working copy of 'demo-git-command/.gitattributes', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'demo-git-command/.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'demo-git-command/.mvn/wrapper/maven-wrapper.properties', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'demo-git-command/mvnw.cmd', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'demo-git-command/pom.xml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'demo-git-command/src/main/java/com/example/demo_git_command/DemoGitCommandApplication.java', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'demo-git-command/src/main/resources/application.properties', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'demo-git-command/src/test/java/com/example/demo_git_command/DemoGitCommandApplicationTests.java', LF will be replaced by CRLF the next time Git touches it

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>git commit -m "added files"
[main 238a56b] added files
 9 files changed, 628 insertions(+)
 create mode 100644 demo-git-command/.gitattributes
 create mode 100644 demo-git-command/.gitignore
 create mode 100644 demo-git-command/.mvn/wrapper/maven-wrapper.properties
 create mode 100644 demo-git-command/mvnw
 create mode 100644 demo-git-command/mvnw.cmd
 create mode 100644 demo-git-command/pom.xml
 create mode 100644 demo-git-command/src/main/java/com/example/demo_git_command/DemoGitCommandApplication.java
 create mode 100644 demo-git-command/src/main/resources/application.properties
 create mode 100644 demo-git-command/src/test/java/com/example/demo_git_command/DemoGitCommandApplicationTests.java

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>git push -u origin main
Enumerating objects: 27, done.
Counting objects: 100% (27/27), done.
Delta compression using up to 8 threads
Compressing objects: 100% (16/16), done.
Writing objects: 100% (26/26), 9.52 KiB | 1.06 MiB/s, done.
Total 26 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/RamaGopal-ZapCom/git-command-practice-1.git
   a71bbf4..238a56b  main -> main
branch 'main' set up to track 'origin/main'.

D:\Air-Asia-POC-7-11-2025\git-command-practice-demo-1>
