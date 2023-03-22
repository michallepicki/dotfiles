# dotfiles

```bash
git clone --separate-git-dir=$HOME/.dotfiles git@github.com:michallepicki/dotfiles.git $HOME/dotfiles-tmp
rm -rf $HOME/dotfiles-tmp
alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
dotfiles config status.showUntrackedFiles no
dotfiles status
```
