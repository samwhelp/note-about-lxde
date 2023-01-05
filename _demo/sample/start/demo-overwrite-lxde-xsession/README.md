
# demo-overwrite-lxde-xsession


## Xsession / Overwrite File

| File | Target |
| --- | --- |
| [/usr/local/bin/startlxde](asset/overlay/usr/local/bin/startlxde#L50) | /usr/bin/startlxde |
| [/usr/local/bin/openbox-lxde](asset/overlay/usr/local/bin/openbox-lxde#L4) | /usr/bin/openbox-lxde |
| [/usr/share/xsessions/LXDE.desktop](asset/overlay/usr/share/xsessions/LXDE.desktop#L27) | /usr/share/xsessions/LXDE.desktop |

``` sh
echo $PATH
```

## /usr/share/xsessions/LXDE.desktop

* /usr/share/xsessions/LXDE.desktop](asset/overlay/usr/share/xsessions/LXDE.desktop#L27)

| Old | New |
| --- | --- |
| `Exec=/usr/bin/startlxde` | `Exec=startlxde` |

## Openbox At Lxde / Config File

| File |
| --- |
| [~/.config/openbox-at-lxde](asset/overlay/skel/.config/openbox-at-lxde) |
| [~/.config/openbox-at-lxde/rc.xml](asset/overlay/skel/.config/openbox-at-lxde/rc.xml#L2741) |
| [~/.config/openbox-at-lxde/menu.xml](asset/overlay/skel/.config/openbox-at-lxde/menu.xml) |


## Openbox / Help

* Menus / [Debian-menu](http://openbox.org/wiki/Help:Menus/Debian-menu)
