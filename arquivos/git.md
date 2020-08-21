# Git

- [Baixar arquivos via `git bash`](https://stackoverflow.com/questions/47838054/download-file-to-my-computer-using-git-bash).
- [Git log format string cheatsheet](https://devhints.io/git-log-format)
- [Git tag - Atlassian tutorials](https://www.atlassian.com/br/git/tutorials/inspecting-a-repository/git-tag)
- [Versionamento Semântico - X.Y.Z](https://semver.org/lang/pt-BR/)

## Comandos legais

Exige o log do git filtrando por autor, no formato para relatórios de trabalho

~~~git
git log --author='Jefferson Neves' --no-merges --abbrev-commit --date=short --pretty=format:'%Cred%h%Creset %C(bold blue)<%an>%Creset %Cgreen(%ci)%Creset %s'
~~~
