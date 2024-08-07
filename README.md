# 依赖安装

## 字体依赖

安装 nerd-font 字体

```shell
sudo pacman -S ttf-jetbrains-mono-nerd
```

安装 Consolas-nerd-font 字体

```shell
mkdir ~/.fonts && cd ~/.fonts
wget https://github.com/wclr/my-nerd-fonts/blob/master/Consolas%20NF/Consolas%20Nerd%20Font%20Complete%20Mono%20Windows%20Compatible.ttf
cd ~
```

## 软件依赖安装

```shell
yay -S fortune-mod fortune-mod-zh exa lolcat bspwm fcitx5-im fcitx5-rime polybar picom-ftlabs-git rofi wezterm dunst keymapper sxhkd zsh lxappearance feh xclip ripgrep fzf xorg-xsetroot apple_cursor xtitle

```

其他我忘了，缺啥装啥吧

## 正式套用配置

```shell
cp bspwm ~/.config/ -r
cp dunst ~/.config/ -r
cp picom ~/.config/ -r
cp rofi ~/.config/ -r
cp wezterm ~/.config/ -r
cp sxhkd ~/.config/ -r
cp polybar ~/.config/ -r
cp keymapper.conf ~/.config/ -r
cp .zshenv ~/
cp .p10k.zsh ~/
cp zsh ~/.config/
reboot
```
```
xinghe@debian:~$ mv ./* ~/.fonts/^C
xinghe@debian:~$ ln -s ~/dotfile/bspwm ~/.config/bspwm
xinghe@debian:~$ ln -s ~/dotfile/dunst ~/.config/dunst
xinghe@debian:~$ ln -s ~/dotfile/picom ~/.config/picom
xinghe@debian:~$ ln -s ~/dotfile/rofi ~/.config/rofi
xinghe@debian:~$ ln -s ~/dotfile/sxhkd ~/.config/sxhkd
xinghe@debian:~$ ln -s ~/dotfile/polybar ~/.config/polybar
xinghe@debian:~$ ln -s ~/dotfile/keymapper.conf ~/.config/keymapper.conf
xinghe@debian:~$ ln -s ~/dotfile/.zshenv ~/.zshenv
xinghe@debian:~$ ln -s ~/dotfile/zsh ~/.config/zsh
```

# 结果

![](./pic.jpg)
