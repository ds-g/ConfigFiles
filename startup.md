;monitor
xrandr --output DVI-D-0 --mode 1920x1080 --rate 144
;nvidia
nvidia-settings --load-config-only
;redshift
redshift-gtk
;xresources
xrdb -merge ~/.Xresources