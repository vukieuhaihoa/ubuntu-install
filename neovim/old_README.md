# Install neovim with tar file

1. Download nvim-linux64.tar.gz
2. Extract: tar xzvf nvim-linux64.tar.gz
3. Run ./nvim-linux64/bin/nvim
4. mv nvim-linux64 nvim
5. sudo mv nvim /usr/bin
6. vim .zshrc, after that add alias nvim="/usr/bin/nvim/bin/nvim"
7. nvim :)))

Install vim plug: [follow this link](https://github.com/junegunn/vim-plug)

Install fzf: sudo apt-get install fzf

cd .configs -> clone dotfiles from [github](https://github.com/vukieuhaihoa/dotfiles) -> mv dotfiles nvim -> nvim init.vim -> :source(reload config) -> :PlugInstall
