## dotfiles

Clone dotfiles repo

```
git clone https://github.com/drmatthews/dotfiles.git $HOME/.dotfiles
```

Symlink files using stow

```
cd $HOME/.dotfiles && stow -v asdf direnv git ipython iterm neovim tmux zsh
```

Install vim-plug

```
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```


Install plugins for vim

```
nvim +PlugInstall +qa
````

Source shell (make sure zsh is installed and is default shell)
```
omz reload
```
