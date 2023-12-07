# Configuracion de entorno en Arch linux con bspwm y sxhkd

Suele haber un ejemplo de configuracion en ``/usr/share/doc/bspwm/examples``

Copiamos ``bspwmrc`` y ``sxhkdrc `` en ``./config/bspwm`` y ``./config/sxhkd``
Si la carpeta ``./config`` no existe, entonces la creamos



Es importante que el archivo de configuracion de bspwm tenga permisos.
```
chmod +x ~/.config/bspwm/bspwmrc
```

## VirtualBox

Existe una libreria para virtual box

`sudo pacman -Sy virtualbox-guest-utils`

`sudo systemctl enable vboxservice.service`



### ZSH

`sudo pacman -S zsh zsh-completions zsh-autosuggestions`

https://github.com/zsh-users/zsh-autosuggestions/tree/master


### Fuentes 
Descargar las fuentes de  https://www.nerdfonts.com/
Extraer en `~/.local/share/fonts/nerd-fonts`
