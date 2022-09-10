My Vim configuration
====================

Want to use this config? Go ahead!

On Linux/macOS
```sh
git clone https://github.com/renzmann/.vim ~/.vim
```

On Windows (Powershell)
```powershell
git clone https://github.com/renzmann/.vim $Env:USERPROFILE\vimfiles
```

On Windows (CMD)
```
git clone https://github.com/renzmann/.vim %USERPROFILE%\vimfiles
```

## It's portable!
It's also possible to try out this configuration without explicitly setting it
as your default

```sh
git clone https://github.com/renzmann/.vim renzmann-dotvim
vim -u renzmann-dotvim/vimrc
```

## Goals

This is a minimal configuration compared to my
[neovim](https://github.com/renzmann/config-nvim) setup.  The goal here is to
work on much older systems, and have consistent performance nearly everywhere,
with no additional setup required other than copying this repository to
`~/.vim`.
