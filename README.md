# git-pr

Type `git pr` to open the GitHub page or website to open a PR for the current branch

## Usage
    git pr [remote-name] [branch-name]

### Examples
    $ git pr
    > open https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/compare/CURRENT_BRANCH?expand=1

    $ git pr upstream
    > open https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/CURRENT_BRANCH

    $ git pr upstream master
    > open https://github.com/REMOTE_UPSTREAM_USER/CURRENT_REPO/tree/master


## Installation


```sh
npm install --global git-pr
```


#### Supported:
* Github.com

## Thx
@jasonmccreary did [all the hard work](https://github.com/jasonmccreary/gh)
Paul Irish

## License

Copyright Joe Ennever. Licensed under MIT.

http://opensource.org/licenses/MIT
