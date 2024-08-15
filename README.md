# I edited my README.me file for ce6-git-1
change on remote
change on local
```
| `git` commands                       | `gh` commands                        |
|--------------------------------------|--------------------------------------|
|Setup and Config                      | gh                                   |
|                                      |                                      |
|    git                               | alias                                |
|    config                            |  delete                              |
|    help                              |  import                              |
|    bugreport                         |  list                                |
|    Credential helpers                |  set                                 |
|                                      |                                      |
|Getting and Creating Projects         | api                                  |
|                                      |                                      |
|    init                              | attestation                          |
|    clone                             |  download                            |
|                                      |  trusted-root                        |
|Basic Snapshotting                    |  verify                              |
|                                      |                                      |
|    add                               | auth                                 |
|    status                            |  login                               |
|    diff                              |  logout                              |
|    commit                            |  refresh                             |
|    notes                             |  setup-git                           |
|    restore                           |  status                              |
|    reset                             |  switch                              |
|    rm                                |  token                               |
|    mv                                |                                      |
|                                      | browse                               |
|Branching and Merging                 |                                      |
|                                      | cache                                |
|    branch                            |  delete                              |
|    checkout                          |  list                                |
|    switch                            |                                      |
|    merge                             | codespace                            |
|    mergetool                         |  code                                |
|    log                               |  cp                                  |
|    stash                             |  create                              |
|    tag                               |  delete                              |
|    worktree                          |  edit                                |
|                                      |  jupyter                             |
|Sharing and Updating Projects         |  list                                |
|                                      |  logs                                |
|    fetch                             |  ports                               |
|    pull                              |  ports forward                       |
|    push                              |  ports visibility                    |
|    remote                            |  rebuild                             |
|    submodule                         |  ssh                                 |
|                                      |  stop                                |
|Inspection and Comparison             |  view                                |
|                                      |                                      |
|    show                              | completion                           |
|    log                               |                                      |
|    diff                              | config                               |
|    difftool                          |  clear-cache                         |
|    range-diff                        |  get                                 |
|    shortlog                          |  list                                |
|    describe                          |  set                                 |
|                                      |                                      |
|Patching                              | extension                            |
|                                      |  browse                              |
|    apply                             |  create                              |
|    cherry-pick                       |  exec                                |
|    diff                              |  install                             |
|    rebase                            |  list                                |
|    revert                            |  remove                              |
|                                      |  search                              |
|Debugging                             |  upgrade                             |
|                                      |                                      |
|    bisect                            | gist                                 |
|    blame                             |  clone                               |
|    grep                              |  create                              |
|--------------------------------------|--------------------------------------|


$ git clone -> for the first time cloning repo to local

need to change dir/folder to cloned repo

$ git pull -> only after cloning. everytime if there is some changes on remote repo, then git pull will works.

$ git status -> to check the status of the repo.

$ git add . -> to add ALL changes made to stage.

$ git add <path/filename> -> to add specific changes made to stage.

$ git commit -m "Change on README.md" -> to commit changes to local repository

$ git push -> to transfer all commits from local repository to remote repository

$ git branch -> list all branches in local repository

$ git branch <branch-name> -> to create new branch

$ git checkout <branch-name> -> to change branch

$ git checkout -b <branch-name> -> to create new branch and switch to that new branch

$ git fetch -> to downloads the updates from the remote repository including new branches.

```
