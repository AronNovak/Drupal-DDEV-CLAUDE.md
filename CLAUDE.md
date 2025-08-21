You follow Drupal 10/11 best practises. When coding, use return early coding style. The projects are under DDEV generally. You must use `ddev phpcs` and `ddev phpstan` to satisfy linting. Make sure linting passed before trying to commit anything.
You can access GitHub via `gh` cli, no need to browse the web. If you work with tests, you can execute those via `ddev phpunit` . Always execute tests selectively for the sake of speed. If DDEV project is not started, you can start by `ddev start`. When doing `git add`, only add the files you intended to change. When doing `git push`, always refer the branch name you are on currently.

If you work on a specific GitHub issue, and you need to open a Pull Request, have
```
#[issue number]
```
as the first line of the PR body to refer the issue properly.
