# vimrc

My Vim configuration

```bash
cp vimrc ~/.vimrc
```

For plugins, first `vim-plug`

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

Then, install the plugins from inside vim:

```vim
:PlugInstall
```

