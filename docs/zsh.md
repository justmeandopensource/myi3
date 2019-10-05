## oh-my-zsh with zsh-autosuggestions

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
cp $HOME/myi3/files/configs/robbyrussell.zsh-theme $HOME/.oh-my-zsh/themes/robbyrussell.zsh-theme
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```
Update $HOME/.zshrc
```
plugins=(zsh-autosuggestions)
```
