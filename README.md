#Numix Siva
Get the modularity and simplicity from [Numix](https://numixproject.org) and combine it with a mate design by [Siva Flat Dark](http://www.deviantart.com/art/Siva-Flat-1-3-0-353499016) and you get this

So far only aviable for the Xfce desktop enviroment (Xfwm)

### Manual installation

Extract the zip file to the themes directory i.e. `/usr/share/themes/`

To set the theme in Xfce, run the following commands in Terminal,

```
xfconf-query -c xsettings -p /Net/ThemeName -s "Numix-Siva"
xfconf-query -c xfwm4 -p /general/theme -s "Numix-Siva"
```

License: GPL-3.0+
