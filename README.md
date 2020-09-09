# cautrofender.github.io

$ mkdir /path/to/source-code
$ cd /path/to/source-code
$ git clone https://github.com/username/username.github.io.git
$ cd username.github.io

$ ls
README.md
$ ls -a
. .. .git README.md

$ echo “Hello, world” > index.html

$ git add index.html
$ git commit index.html -m “My hello world commit”
[master 48d71e6] My hello world commit
1 files changed, 1 insertions(+), 0 deletions(-)
create mode 100644 index.html
$ git push origin master
Counting objects: 4, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 364 bytes, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/username/username.github.io
￼49c4721..48d71e6 master -> master
