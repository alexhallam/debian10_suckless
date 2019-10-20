# dotfiles for a minimal suckless build on Debian 10

The main suckless tools used are `st` and `dwm`. 

### Instructions

```
git clone

cd dotfiles

stow bashrc nvim tmux mpd ncmpcpp xsession bashrc 

sudo apt-get install nvim tmux mpd ncmpcpp 

clone my st and dwm builds
```

If a mistake was made use `stow -D <dir>`.

```
dotfiles/
├── bashrc
│   └── .bashrc
├── nvim
│   └── .config
│       └── nvim
│           └── init.vim
├── README.md
└── tmux
    └── .tmux.conf

```

# Other things to do when setting up a new OS

- [ ] `sudo apt-get install neovim` https://github.com/neovim/neovim/wiki/Installing-Neovim

- [ ] vim-plug https://github.com/junegunn/vim-plug
