<<<<<<< HEAD
# Module 02 Mini-Project: CSS Snippet Cheat Sheet

In this activity, you will work with a group to build a webpage that will hold a collection of CSS snippets. What better way to learn CSS than to build a knowledge base of CSS?

## Instructions

The completed application should meet the following criteria:

* As a user, I can view a collection of labeled CSS snippets in a responsive grid.

* As a user, I can easily identify these CSS snippets by their headings.

* As a user, I can highlight a code snippet by clicking on it.

* As a user, I can view my application on a mobile device as well as a desktop.

### Specifications

* Must use semantic HTML elements and proper indentation.

* Use CSS variables to maintain clean and reusable values for a color scheme.

* Use flexbox and media queries to create a responsive grid layout.

* Each CSS snippet should have a card-like layout with the CSS syntax wrapped in an [HTML pre element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/pre).

* Each CSS snippet can easily be highlighted for copying on click using the [CSS user-select property](https://developer.mozilla.org/en-US/docs/Web/CSS/user-select).

* Must incorporate a background color using a [CSS linear-gradient function](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient).

* Must incorporate a bit of animation using the [CSS transition property](https://developer.mozilla.org/en-US/docs/Web/CSS/transition).

* You and your group can decide which CSS styles and colors you will use to design the application, but the app needs to be a responsive. Use the following images to gain an understanding of how the app should look at different screen sizes, from a layout perspective:

  * At size 992px and above, the app should resemble the following image:

    ![On a desktop, the application displays three CSS code snippets per row.](./Images/01-app-desktop.png)

  * At size 768px and above, the app should resemble the following image:

    ![On a tablet, the application displays two CSS code snippets per row.](./Images/02-app-tablet.png)

  * On mobile devices, anything under 768px, the app should resemble the following image:

    ![On a mobile device, the application displays one CSS code snippet per row.](./Images/03-app-mobile.png)

## 💡 Hints

* The HTML `<pre>` element is very literal about spaces and indentation. To gain a better understanding of how to work with it, check out this article on [considerations for styling the pre tag](https://css-tricks.com/considerations-styling-pre-tag/).

## 🏆 Bonus

* Set this project up in your own GitHub repositories so that you can deploy and use it for future reference!

---
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
=======
# mini-project-css
>>>>>>> origin/main

*****************************************************************************************************************************************
Issue faced

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp
$ cd mini-project-css/

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git clone https://github.com/Bilenie/mini-project-css.git
Cloning into 'mini-project-css'...
remote: Enumerating objects: 25, done.
remote: Counting objects: 100% (25/25), done.
remote: Compressing objects: 100% (19/19), done.
remote: Total 25 (delta 3), reused 10 (delta 2), pack-reused 0
Receiving objects: 100% (25/25), 10.63 KiB | 1.06 MiB/s, done.
Resolving deltas: 100% (3/3), done.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ ls
asset/  index.html  mini-project-css/  README.md

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ cd mini-project-css/

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push
remote: Repository not found.
fatal: repository 'https://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote add origin Bilenie/mini-project-css
error: remote origin already exists.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote add origin 
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote add origin https://github.com/Bilenie
error: remote origin already exists.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push
remote: Repository not found.
fatal: repository 'https://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git pull main origin
fatal: 'main' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push
remote: Repository not found.
fatal: repository 'https://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git add -A

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git commit -m "adding repo."
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push
remote: Repository not found.
fatal: repository 'https://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote push add
error: unknown subcommand: `push'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --[no-]verbose    be verbose; must be placed before a subcommand


bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git init
Reinitialized existing Git repository in C:/Users/bilum/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css/.git/

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push -u origin main
remote: Repository not found.
fatal: repository 'https://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push -u origin main
remote: Repository not found.
fatal: repository 'https://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote add origin main
error: remote origin already exists.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote -v
origin  https://github.com/Bilenie/mini-project-css.git (fetch)
origin  https://github.com/Bilenie/mini-project-css.git (push)

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote set-url origin https://github.com/Bilenie/mini-project-css.git

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push -u origin main
remote: Repository not found.
fatal: repository 'https://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push -u origin main
To https://github.com/Bilenie/mini-project-css.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Bilenie/mini-project-css.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote set-url origin https://github.com/Bilenie/mini-project-css.githttps://github.com/Bilenie/mini-project-css.git

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote add https://github.com/Bilenie/mini-project-css.git
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push
remote: Not Found
fatal: repository 'https://github.com/Bilenie/mini-project-css.githttps://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote add origin https://github.com/Bilenie/mini-project-css.git
error: remote origin already exists.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git pull
remote: Not Found
fatal: repository 'https://github.com/Bilenie/mini-project-css.githttps://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git add -A

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git commite -m "b"
git: 'commite' is not a git command. See 'git --help'.

The most similar command is
        commit

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push
remote: Not Found
fatal: repository 'https://github.com/Bilenie/mini-project-css.githttps://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ ls
asset/  index.html  README.md

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push
remote: Not Found
fatal: repository 'https://github.com/Bilenie/mini-project-css.githttps://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push https://github.com/Bilenie/mini-project-css.git
To https://github.com/Bilenie/mini-project-css.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Bilenie/mini-project-css.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git add -A

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git commite -m "added file "
git: 'commite' is not a git command. See 'git --help'.

The most similar command is
        commit

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git commit -m "updated file"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push
remote: Not Found
fatal: repository 'https://github.com/Bilenie/mini-project-css.githttps://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ gh repo clone Bilenie/mini-project-css
bash: gh: command not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote add origin gh repo clone Bilenie/mini-project-css
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git remote add origin https://github.com/Bilenie/mini-project-css.git
error: remote origin already exists.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git pull
remote: Not Found
fatal: repository 'https://github.com/Bilenie/mini-project-css.githttps://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git push
remote: Not Found
fatal: repository 'https://github.com/Bilenie/mini-project-css.githttps://github.com/Bilenie/mini-project-css.git/' not found

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ git fix
git: 'fix' is not a git command. See 'git --help'.

The most similar command is
        diff

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css/mini-project-css (main)
$ cd ..

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ cd ..

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp
$ git clone https://github.com/Bilenie/mini-project-css.git
fatal: destination path 'mini-project-css' already exists and is not an empty directory.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp
$ cd mini-project-
bash: cd: mini-project-: No such file or directory

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp
$ cd mini-project-css

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ rm -r 
rm: missing operand
Try 'rm --help' for more information.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ ls
asset/  index.html  mini-project-css/  README.md

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ rm -r mini-project-css/
rm: remove write-protected regular file 'mini-project-css/.git/objects/pack/pack-51218656a2827c302cf2cbe17eb544c4dfac247b.idx'? yes
rm: remove write-protected regular file 'mini-project-css/.git/objects/pack/pack-51218656a2827c302cf2cbe17eb544c4dfac247b.pack'?
rm: remove write-protected regular file 'mini-project-css/.git/objects/pack/pack-51218656a2827c302cf2cbe17eb544c4dfac247b.rev'?
rm: cannot remove 'mini-project-css/.git/objects/pack': Directory not empty

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ ls
asset/  index.html  mini-project-css/  README.md

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ rm -rf mini-project-css/

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ ls
asset/  index.html  README.md

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ cd ..

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp
$ git status
fatal: not a git repository (or any of the parent directories): .git

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp
$ git init
Initialized empty Git repository in C:/Users/bilum/OneDrive/Desktop/SMU/Boothcamp/.git/

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp (main)
$ ls
 bilenie-repo/   bootcamp/   conflict-resolution/   Experment/   git-init-sample/   mini-project-css/   mini-project-html/  'model 2 Advance CSS'/   resource/

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp (main)
$ cd mini-project-
bash: cd: mini-project-: No such file or directory

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp (main)
$ cd mini-project-css

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git statu
git: 'statu' is not a git command. See 'git --help'.

The most similar commands are
        status
        stage
        stash

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git push
To https://github.com/Bilenie/mini-project-css.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Bilenie/mini-project-css.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git fetch
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (5/5), 2.48 KiB | 110.00 KiB/s, done.
From https://github.com/Bilenie/mini-project-css
 + 1fdc94d...e7d52da main       -> origin/main  (forced update)

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git merge origin/main
fatal: refusing to merge unrelated histories

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git merge origin/main --allow-unrelated-histories
Auto-merging README.md
CONFLICT (add/add): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main|MERGING)
$ git commit -m "Merge remote changes into local main branch"
U       README.md
error: Committing is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main|MERGING)
$ git push
To https://github.com/Bilenie/mini-project-css.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Bilenie/mini-project-css.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main|MERGING)
$ git fetch origin

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main|MERGING)
$ git add README.md  # Replace with the name of your conflicted file(s)

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main|MERGING)
$ git commit -m "Resolve merge conflicts in README.md"
[main 262fd19] Resolve merge conflicts in README.md

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git push
Enumerating objects: 30, done.
Counting objects: 100% (30/30), done.
Delta compression using up to 8 threads
Compressing objects: 100% (23/23), done.
Writing objects: 100% (28/28), 11.00 KiB | 3.67 MiB/s, done.
Total 28 (delta 4), reused 20 (delta 1), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/Bilenie/mini-project-css.git
   e7d52da..262fd19  main -> main

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git pull origin main
From https://github.com/Bilenie/mini-project-css
 * branch            main       -> FETCH_HEAD
Already up to date.

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ code .

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$ git push
Everything up-to-date

bilum@Bilenie-PC MINGW64 ~/OneDrive/Desktop/SMU/Boothcamp/mini-project-css (main)
$
