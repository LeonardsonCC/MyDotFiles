# My ugly dot files!

Yes, I know, there's a lot of different configurations for different apps that do the same thing... But what can I say, is nice try everything!

----

## Versioning
Certainly this was not just copied from internet [👨‍💻](https://www.atlassian.com/git/tutorials/dotfiles)
```bash
git init --bare $HOME/.cfg
alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
config config --local status.showUntrackedFiles no
echo "alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'" >> $HOME/.bashrc
echo "alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'" >> $HOME/.zshrc
config remote add origin git@github.com:LeonardsonCC/MyDotFiles.git
```

## Current Workspace
- WM: [dwm](https://github.com/LeonardsonCC/dwm);
- Terminal: [st](https://github.com/LeonardsonCC/st);
- Shell: [zsh](https://ohmyz.sh/);
- Font: [UbuntuMono Nerd Font Mono](https://github.com/LeonardsonCC/MyDotFiles/blob/main/.local/share/fonts/Ubuntu%20Mono%20Nerd%20Font%20Complete%20Mono.ttf);
- Emoji Font: [Symbola](https://github.com/LeonardsonCC/MyDotFiles/blob/main/.local/share/fonts/Symbola.ttf) (My suckless apps does not like color emojis 😕);
- Application Menu: [dmenu](https://github.com/LeonardsonCC/dmenu);
- Neovim v0.5.0: [LunarVim](https://github.com/ChristianChiarulli/LunarVim);

## To-do
- [ ] Clear unsed [fonts](https://github.com/LeonardsonCC/MyDotFiles/tree/main/.local/share/fonts);
- [ ] Clear old configs;
- [ ] Script to just install everything;
- [ ] Improve versioning with [stow](https://www.gnu.org/software/stow/manual/stow.html);