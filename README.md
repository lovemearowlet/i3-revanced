# i3-Revanced
---
## About:
> Just a basic rice for i3. It has a custom rofi and polybar theme. It also has a slightly modified neofetch and uses screengrab for screenshots.  picom is there if you want to prevent screen tearing and if you want to you can add some fancy effects. To install just put the files in the .config folder but you do need to install the things for them.
---
## Software Needed:
> Picom, Polybar, Rofi, Kitty, Neofetch, Fastfetch, ScreenGrab
---
# .bashrc addons:
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
---
# Screenshots (might be outdated)

![image](https://github.com/user-attachments/assets/4fa756ce-529d-497c-890f-69746693f122)


![image](https://github.com/user-attachments/assets/060b1311-86ae-4916-8ae8-aac5b946f117)


![image](https://github.com/user-attachments/assets/39b536ac-ffb5-4493-8d3b-4f00332149ea)

![image](https://github.com/user-attachments/assets/af3a2396-dc5c-43e3-8293-fa9cb0e4f3d7)

![image](https://github.com/user-attachments/assets/313b28e4-11be-4245-b322-c63605a3ac56)

![image](https://github.com/user-attachments/assets/92762090-24f2-4e65-a1dc-e1826025e49f)

---

