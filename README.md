# macOS

My macOS config files

* tmux
* vim
* zsh (oh my zsh)

## Configure vim

### Install Pathogen

```bash
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```

Configure .vimrc

```
execute pathogen#infect()
syntax on
filetype plugin indent on
```

### Install Terraform package

```bash
:q
git clone https://github.com/hashivim/vim-terraform.git ~/.vim/bundle/vim-terraform
```

### Install Sensitive package

```bash
cd ~/.vim/bundle && \
git clone https://github.com/tpope/vim-sensible.git
```

### Install Fugitive package

```bash
cd ~/.vim/bundle && \
git clone git@github.com:tpope/vim-fugitive.git
```
