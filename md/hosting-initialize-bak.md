```bash
root@OmO MINGW64 /i/code/hosting
$ git init --initial-branch=image
Initialized empty Git repository in I:/code/hosting/.git/

root@OmO MINGW64 /i/code/hosting (image)
$ git remote add origin git@github.com:omomeme/hosting.git

root@OmO MINGW64 /i/code/hosting (image)
$ git add .

root@OmO MINGW64 /i/code/hosting (image)
$ git commit -m "initialize."
[image (root-commit) 286d281] initialize.
 2 files changed, 3 insertions(+)
 create mode 100644 DVOfcRLoAP2KC75.png
 create mode 100644 README.md

root@OmO MINGW64 /i/code/hosting (image)
$ git push -u orgin image
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 106.54 KiB | 369.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:omomeme/hosting.git
 * [new branch]      image -> image
branch 'image' set up to track 'origin/image'.

root@OmO MINGW64 /i/code/hosting (image)
$ git checkout --orphan=md
Switched to a new branch 'md'

root@OmO MINGW64 /i/code/hosting (md)
$ git rm -rf .
rm 'DVOfcRLoAP2KC75.png'
rm 'README.md'

root@OmO MINGW64 /i/code/hosting (md)
$ git add .

root@OmO MINGW64 /i/code/hosting (md)
$ git commit -m "push branch via git."
[md (root-commit) 696b312] push branch via git.
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 hosting-initialize.md

root@OmO MINGW64 /i/code/hosting (md)
$ git push origin md
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 228 bytes | 228.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'md' on GitHub by visiting:
remote:      https://github.com/omomeme/hosting/pull/new/md
remote:
To github.com:omomeme/hosting.git
 * [new branch]      md -> md
```