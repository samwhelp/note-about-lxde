
# demo-overwrite-lxde-xsession

## Overwrite File

| File | Target |
| --- | --- |
| [/usr/local/bin/startlxde](asset/overlay/usr/local/bin/startlxde ) | /usr/bin/startlxde |
| [/usr/local/bin/openbox-lxde](asset/overlay/usr/local/bin/openbox-lxde) | /usr/bin/openbox-lxde |
| [/usr/share/xsessions/LXDE.desktop](asset/overlay/usr/share/xsessions/LXDE.desktop) | /usr/share/xsessions/LXDE.desktop |

``` sh
echo $PATH
```

## Openbox At Lxde / Config File

| File |
| --- |
| [~/.config/openbox-at-lxde](asset/overlay/skel/.config/openbox-at-lxde) |
| [~/.config/openbox-at-lxde/rc.xml](asset/overlay/skel/.config/openbox-at-lxde/rc.xml) |
| [~/.config/openbox-at-lxde/rc.xml](asset/overlay/skel/.config/openbox-at-lxde/menu.xml) |


## Openbox / Help

* Menus / [Debian-menu](http://openbox.org/wiki/Help:Menus/Debian-menu)
