
User@DESKTOP-QA5HAO2 MINGW64 ~
$ cd ~/Desktop/

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop
$ cd mig

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig
$ git init
Initialized empty Git repository in C:/Users/User/Desktop/mig/.git/

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git commit -m "ver1"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'User@DESKTOP-QA5HAO2.(none)')

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git config user.email "mmigaa434@gmail.com"

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git config user.name "mig"

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git commit -m "ver2"
[master (root-commit) 9fad360] ver2
 1 file changed, 2 insertions(+)
 create mode 100644 hello

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git commit -m "ver3"
[master 37eed9b] ver3
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git log --all --graph
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934 (HEAD -> master)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git commit -m "feature commit 1"
[master 0a61c88] feature commit 1
 1 file changed, 1 insertion(+)
 create mode 100644 feature

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git log --all --graph
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439 (HEAD -> master)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git commit -m "feature commit 2"
[master ce896b5] feature commit 2
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git log --all --graph
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6 (HEAD -> master)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git checkout  master
Already on 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git log --all --graph
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6 (HEAD -> master)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git commit -m "bugfix"
[master d1a7ea7] bugfix
 1 file changed, 1 insertion(+)
 create mode 100644 bugfix

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git log --all --graph
* commit d1a7ea7d220dae9d41e535f99aee9a036ff490e3 (HEAD -> master)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:07:30 2026 +0800
|
|     bugfix
|
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git checkout  master
Already on 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git log --all --graph
* commit d1a7ea7d220dae9d41e535f99aee9a036ff490e3 (HEAD -> master)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:07:30 2026 +0800
|
|     bugfix
|
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git commit -m "feature commit 1"
On branch master
nothing to commit, working tree clean

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git commit -m "feature commit 2"
On branch master
nothing to commit, working tree clean

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git merge feature1 -m "merge feature1"
merge: feature1 - not something we can merge

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git merge feature -m "merge feature1"
merge: feature - not something we can merge

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git checkout -b feature1 37eed9bd50d8f51a2ed924f8adb90da507b3b934
Switched to a new branch 'feature1'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature1)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git merge feature1 -m "merge feature1"
Already up to date.

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git checkout -b feature1
fatal: a branch named 'feature1' already exists

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git branch conflict

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git log --all --graph
* commit d1a7ea7d220dae9d41e535f99aee9a036ff490e3 (HEAD -> master, conflict)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:07:30 2026 +0800
|
|     bugfix
|
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934 (feature1)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git checkout conflict
Switched to branch 'conflict'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (conflict)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (conflict)
$ git commit -m "complict1"
[conflict 5e0c80d] complict1
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (conflict)
$ git log --all --graph
* commit 5e0c80d4e07881973fca3437935b5d3e6d8fa6de (HEAD -> conflict)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:21:14 2026 +0800
|
|     complict1
|
* commit d1a7ea7d220dae9d41e535f99aee9a036ff490e3 (master)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:07:30 2026 +0800
|
|     bugfix
|
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
* commit 5e0c80d4e07881973fca3437935b5d3e6d8fa6de (HEAD -> conflict)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:21:14 2026 +0800
|
|     complict1
|
* commit d1a7ea7d220dae9d41e535f99aee9a036ff490e3 (master)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:07:30 2026 +0800
|
|     bugfix
|
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934 (feature1)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (conflict)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git commit -m "complict2"
[master e0ab2cf] complict2
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git merge conflict -m "merge conflict"
Auto-merging feature
CONFLICT (content): Merge conflict in feature
Automatic merge failed; fix conflicts and then commit the result.

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master|MERGING)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master|MERGING)
$ git commit -m "merge complict resolved"
[master 5b21f37] merge complict resolved

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git branch new-feature

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git log --all --graph
*   commit 5b21f37df36662feeb4d6cc66d624b731c2e90bb (HEAD -> master, new-feature)
|\  Merge: e0ab2cf 5e0c80d
| | Author: mig <mmigaa434@gmail.com>
| | Date:   Tue Mar 31 17:27:46 2026 +0800
| |
| |     merge complict resolved
| |
| * commit 5e0c80d4e07881973fca3437935b5d3e6d8fa6de (conflict)
| | Author: mig <mmigaa434@gmail.com>
| | Date:   Tue Mar 31 17:21:14 2026 +0800
| |
| |     complict1
| |
* | commit e0ab2cf45f0b59e145ee2711b50fff9eb9f01985
|/  Author: mig <mmigaa434@gmail.com>
|   Date:   Tue Mar 31 17:23:31 2026 +0800
|
|       complict2
|
* commit d1a7ea7d220dae9d41e535f99aee9a036ff490e3
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:07:30 2026 +0800
|
|     bugfix
|
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934 (feature1)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git checkout new-feature
Switched to branch 'new-feature'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (new-feature)
$ git log --all --graph
*   commit 5b21f37df36662feeb4d6cc66d624b731c2e90bb (HEAD -> new-feature, master)
|\  Merge: e0ab2cf 5e0c80d
| | Author: mig <mmigaa434@gmail.com>
| | Date:   Tue Mar 31 17:27:46 2026 +0800
| |
| |     merge complict resolved
| |
| * commit 5e0c80d4e07881973fca3437935b5d3e6d8fa6de (conflict)
| | Author: mig <mmigaa434@gmail.com>
| | Date:   Tue Mar 31 17:21:14 2026 +0800
| |
| |     complict1
| |
* | commit e0ab2cf45f0b59e145ee2711b50fff9eb9f01985
|/  Author: mig <mmigaa434@gmail.com>
|   Date:   Tue Mar 31 17:23:31 2026 +0800
|
|       complict2
|
* commit d1a7ea7d220dae9d41e535f99aee9a036ff490e3
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:07:30 2026 +0800
|
|     bugfix
|
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934 (feature1)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (new-feature)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (new-feature)
$ git commit -m "new feature"
[new-feature 5b6b687] new feature
 1 file changed, 1 insertion(+)
 create mode 100644 new_feature

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (new-feature)
$ git remote add origin https://github.com/tumpen11/mig1.git

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (new-feature)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git push origin master
info: please complete authentication in your browser...
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 20 threads
Compressing objects: 100% (14/14), done.
Writing objects: 100% (24/24), 1.90 KiB | 1.90 MiB/s, done.
Total 24 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/tumpen11/mig1.git
 * [new branch]      master -> master

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git checkout new-feature
Switched to branch 'new-feature'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (new-feature)
$ git push origin new-feature
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 20 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 275 bytes | 275.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'new-feature' on GitHub by visiting:
remote:      https://github.com/tumpen11/mig1/pull/new/new-feature
remote:
To https://github.com/tumpen11/mig1.git
 * [new branch]      new-feature -> new-feature

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (new-feature)
$ git fetch
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 890 bytes | 890.00 KiB/s, done.
From https://github.com/tumpen11/mig1
   5b21f37..491e0e6  master     -> origin/master

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (new-feature)
$ git log --all --graph
*   commit 491e0e6eb95cac7aeeb674e4442c3d10d6ece702 (origin/master, origin/HEAD)
|\  Merge: 5b21f37 5b6b687
| | Author: miigaascar <mmigaa434@gmail.com>
| | Date:   Tue Mar 31 17:41:55 2026 +0800
| |
| |     Merge pull request #1 from tumpen11/new-feature
| |
| |     new feature
| |
| * commit 5b6b68726ffcc0f64b532443c23ea96250865075 (HEAD -> new-feature, origin/new-feature)
|/  Author: mig <mmigaa434@gmail.com>
|   Date:   Tue Mar 31 17:33:24 2026 +0800
|
|       new feature
|
*   commit 5b21f37df36662feeb4d6cc66d624b731c2e90bb (master)
|\  Merge: e0ab2cf 5e0c80d
| | Author: mig <mmigaa434@gmail.com>
| | Date:   Tue Mar 31 17:27:46 2026 +0800
| |
| |     merge complict resolved
| |
| * commit 5e0c80d4e07881973fca3437935b5d3e6d8fa6de (conflict)
| | Author: mig <mmigaa434@gmail.com>
| | Date:   Tue Mar 31 17:21:14 2026 +0800
| |
| |     complict1
| |
* | commit e0ab2cf45f0b59e145ee2711b50fff9eb9f01985
|/  Author: mig <mmigaa434@gmail.com>
|   Date:   Tue Mar 31 17:23:31 2026 +0800
|
|       complict2
|
* commit d1a7ea7d220dae9d41e535f99aee9a036ff490e3
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:07:30 2026 +0800
|
|     bugfix
|
* commit ce896b530c85d3fa95a6bc2ec32fd5e4a82258a6
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:04:20 2026 +0800
|
|     feature commit 2
|
* commit 0a61c881872e100d3c844f4feb01dbc3796a8439
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 17:01:45 2026 +0800
|
|     feature commit 1
|
* commit 37eed9bd50d8f51a2ed924f8adb90da507b3b934 (feature1)
| Author: mig <mmigaa434@gmail.com>
| Date:   Tue Mar 31 16:55:48 2026 +0800
|
|     ver3
|
* commit 9fad360f4f79b7ae63ed6fa8be2c8dd73c81f71e
  Author: mig <mmigaa434@gmail.com>
  Date:   Tue Mar 31 16:55:21 2026 +0800

      ver2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (new-feature)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> master


User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git pull origin master
From https://github.com/tumpen11/mig1
 * branch            master     -> FETCH_HEAD
Updating 5b21f37..491e0e6
Fast-forward
 new_feature | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 new_feature

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git branch feature1
fatal: a branch named 'feature1' already exists

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git branch -D feature1
Deleted branch feature1 (was 37eed9b).

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git branch feature1

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git checkout feature1
M       feature
Switched to branch 'feature1'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature1)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature1)
$ git commit -m "feature1"
[feature1 9fe8f06] feature1
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature1)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git branch feature2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git checkout feature2
Switched to branch 'feature2'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature2)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature2)
$ git commit -m "feature2"
[feature2 c41e7cb] feature2
 1 file changed, 1 insertion(+), 2 deletions(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature2)
$ git push origin feature2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 20 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 330 bytes | 330.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'feature2' on GitHub by visiting:
remote:      https://github.com/tumpen11/mig1/pull/new/feature2
remote:
To https://github.com/tumpen11/mig1.git
 * [new branch]      feature2 -> feature2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature2)
$ git checkout feature1
Switched to branch 'feature1'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature1)
$ git push origin feature1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 20 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'feature1' on GitHub by visiting:
remote:      https://github.com/tumpen11/mig1/pull/new/feature1
remote:
To https://github.com/tumpen11/mig1.git
 * [new branch]      feature1 -> feature1

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (feature1)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$ git pull origin master
remote: Enumerating objects: 11, done.
remote: Counting objects: 100% (11/11), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (5/5), 2.71 KiB | 396.00 KiB/s, done.
From https://github.com/tumpen11/mig1
 * branch            master     -> FETCH_HEAD
   491e0e6..d919710  master     -> origin/master
Updating 491e0e6..d919710
Fast-forward
 feature | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/mig (master)
$
