# INFO 343 In-Class Code

We will use this repo for all code we write in class. To begin, **Fork this repo** into your own account using the "Fork" button above, and then clone it to your development machine.

## Add an Upstream Remote

Now that you've forked this repo, you are working on your own copy, but I may need to update this repo with new starter files as we go along. To be able to pull these updates into your forked copy, you need to add a new **remote** to your local repo. 

If you using your own laptop, you only need to do this once, but if you are using a lab machine, you will need to do this whenever I ask you to pull updates from the upstream master.

`cd` into your local repo directory and execute this command:

```bash
$ git remote add upstream https://github.com/info343-a16/info343-in-class
```

## Pulling Updates

Whenever I ask you to pull updates from the upstream master, `cd` into your local repo directory, execute `git status` to ensure that all your local changes are committed, and then execute this command:

```bash
$ git pull upstream master
```

This will put you into a command-line text editor to approve the merge commit message. If you configured your editor to be `nano`, hit `Ctrl+X` to exit (see menu along the bottom). If you are in `vim` instead, hit `Esc` and then type `:wq` to exit. After exiting, the new directories and files should be in your local repo. You can push them to your copy on GitHub using a normal `git push`.

