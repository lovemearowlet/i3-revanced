# i3-Revanced
---
## About:
> Just a basic rice for i3. It has a custom rofi and polybar theme. It also has a slightly modified neofetch and uses screengrab for screenshots. The custom Kitty theme is coming out soon. picom is there if you want to prevent screen tearing and if you want to you can add some fancy effects. To install just put the files in the .config folder but you do need to install the things for them.
---
## Software Needed:
> Picom, Polybar, Rofi, Kitty, Neofetch, Fastfetch ScreenGrab
---
.bashrc addons:
```
if [ "$TERM" = "xterm-kitty" ]
then
  fastfetch --kitty-direct /home/SP649/.config/gentoo.png --logo-width 26 --logo-height 14
else
  fastfetch
fi

alias ff="fastfetch --kitty-direct /home/SP649/.config/gentoo.png --logo-width 26 --logo-height 14"
alias nff="fastfetch"




PS1='\[\e[38;5;25;1m\]┌─\[\e[0;38;5;25m\][\[\e[38;5;111;1m\]\u\[\e[22m\]@\[\e[1m\]\h\[\e[0;38;5;25m\]]\[\e[38;5;25m\]-\[\e[38;5;25m\][\[\e[38;5;111m\]\T\[\e[38;5;25m\]]-[\[\e[0m\] \[\e[38;5;117;3m\]\w\[\e[0m\] \[\e[38;5;25m\]]\n\[\e[1m\]└\[\e[22m\]\$\[\e[0m\] '
```
