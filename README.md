# challenge-git

I have followed given below steps to complete the challenge.

  - Created master branch & done Initial commit on the branch
  - Then I have created a branch named add-echo and added echo.html file to that branch and pushed that branch.
  - Next, I created a branch named add-reverse and added reverse.html

To complete the challenge, I've fired given below commands to merge code branch without creating merge commit.

```sh
$ git rebase add-reverse master
$ git rebase add-echo master
$ git log
```

Above commads generated log given below.

```sh
commit 1ada981c5537f5ba8a0a55d56bebc26e17ae26d5 (HEAD -> master, origin/master, origin/HEAD)
Author: Anant Jain <anant@creolestudios.com>
Date:   Wed Nov 27 18:42:59 2019 +0530

    Reverse route commit

commit 18f76905fba76deb02f8c9dfce39aa44d3bf5ddb (origin/add-echo, add-echo)
Author: Anant Jain <anant@creolestudios.com>
Date:   Wed Nov 27 18:40:40 2019 +0530

    Echo route commit

commit 9dbf1429b76845c01dabb5a59d42dcf27729b371
Author: anantjain88 <32643636+anantjain88@users.noreply.github.com>
Date:   Wed Nov 27 18:29:31 2019 +0530

    Initial commit
```
