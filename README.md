# flatpak-zsh-completion
Flatpak completion for ZSH
<div align="center">
<img src="flatpak-zsh.gif" alt="Flatpak zsh gif" />
</div>

# Depdencies
-  `zsh`
-  `oh-my-zsh`


# Installation
### Using Antigen
Bundle `flatpak-zsh-completion` in your `.zshrc`
```bash
  antigen bundle bil-elmoussaoui/flatpak-zsh-completion
```
### Using zplug : 
Load `flatpak-zsh-completion` as a plugin in your `.zshrc`
```bash
  zplug "bil-elmoussaoui/flatpak-zsh-completion", nice:10
```
### Oh-my-ZSH:
Clone this repository under the custom plugins directory
```bash
  git clone https://github.com/bil-elmoussaoui/flatpak-zsh-completion
  cd ./flatpak-zsh-completion
  cp -r ./flatpak  ~/.oh-my-zsh/custom/plugins/
```
Load the plugin on `.zshrc`
```bash
  plugins+=(flatpak)
```

Restart your terminal emulator or source the `.zshrc` file
```bash
source ~/.zshrc
```
