# Neovim Setup 

My default neovim setup.

## Steps :
1. Install neovim using [homebrew](https://formulae.brew.sh/formula/neovim)
```bash
brew install neovim
```
2. Make a folder in your home directory called ".nvim" to store all the plugins.
```bash
cd ~
mkdir .nvim
```
3. Go to your .config folder then to the nvim folder (this is the directory where your nvim is installed by homebrew). After that create a file called "init.vim" then paste the code in this repo.
```bash
cd ~/.config/nvim
vim init.vim
```
4. After you paste the code, save it and install the plugins
```bash
source %
:PlugInstall
```
5. Ta-da you just finished installing the plugins. To activate your new beautiful Neovim you just need to "source" it again then you'll have it.
```bash
sorce %
:PlugInstall
```

## Notes
* All the plugins that have been installed is located in ".nvim" directory
* Meanwhile your init.vim is located in ~/.config/nvim

__It's a different directory!__
