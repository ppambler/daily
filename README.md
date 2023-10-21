# daily

1. Gmeek 仓库更新了 -> `git pull`，`sh zero.sh`，`git push`
2. 当期仓库的 `config.json` 更新了 ->  `git pull`，`sh zero.sh`，`git push`
3. 在 Gmeek 仓库里边 -> 对于 `post` 和 `about` 这种特殊页面，在 `/templates/post.html` 里边的 `<a href="../">` 用的是 `./` 才对，而对于普通的文章页面，则是 `../`
4. 每次你在本地修改了这个仓库，你提交前，都得先 `git pull` 一下，之后再 `git push`