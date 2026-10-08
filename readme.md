#Git course
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git --version
git version 2.56.0.windows.2
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git config --global user.name 'demo'
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git config --global user.email 'imcharumathi@gmail.com'
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git config user.name
demo
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git config user.email
imcharumathi@gmail.com
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git config --global init.defaultBranch main
PS C:\Users\Charu\OneDrive\Desktop\GO\git> 
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git init
Initialized empty Git repository in C:/Users/Charu/OneDrive/Desktop/GO/git/.git/
PS C:\Users\Charu\OneDrive\Desktop\GO\git> 


U ----> Untracked File

PS C:\Users\Charu\OneDrive\Desktop\GO\git> git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        index.js
        readme.md

nothing added to commit but untracked files present (use "git add"to track)

PS C:\Users\Charu\OneDrive\Desktop\GO\git> git add readme.md
# readme file will change as A 

# commit store a snapshot
# commit id : 6e672362cb769cb52744708d7b326123a2567915

PS C:\Users\Charu\OneDrive\Desktop\GO\git> git commit -m 'readme'
[main (root-commit) 6e67236] readme
 1 file changed, 31 insertions(+)
 create mode 100644 readme.md

# view the changes you done
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git log
commit 6e672362cb769cb52744708d7b326123a2567915 (HEAD -> main)
Author: demo <imcharumathi@gmail.com>
Date:   Thu Oct 8 20:15:05 2026 +0530

    readme
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git status            
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        index.js

no changes added to commit (use "git add" and/or "git commit -a")

# make changes all the files
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git add .
PS C:\Users\Charu\OneDrive\Desktop\GO\git> git commit -m 'initial commit'
[main edf7044] initial commit
 3 files changed, 33 insertions(+)
 create mode 100644 index.html
 create mode 100644 index.js

PS C:\Users\Charu\OneDrive\Desktop\GO\git> git log
commit edf7044f7aa0eced90e5ea60ddb4749258f5b0b4 (HEAD -> main)
Author: demo <imcharumathi@gmail.com>
Date:   Thu Oct 8 20:21:14 2026 +0530

    initial commit

commit 6e672362cb769cb52744708d7b326123a2567915
Author: demo <imcharumathi@gmail.com>
Date:   Thu Oct 8 20:15:05 2026 +0530

    readme
PS C:\Users\Charu\OneDrive\Desktop\GO\git> 


# need to see previous version

