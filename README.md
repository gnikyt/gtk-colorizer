# Colorizer

*Forked from: https://www.gnome-look.org/p/1242251/*

Colorize a GTK 2, GTK 3, and XFWM themes based on .Xresources colors.

+ XFWM theme will only be generated if you have xfconf-query installed
+ GTK2 theme will only be generated if you have GTK3 settings
+ GTK3 theme will only be generated if you have GTK3 settings

## Dependencies

+ `Inkscape` to render assets in GTK theme
+ `optipng` for asset automation
+ `sed` for modifying GTK 2 and GTK 3 settings
+ `xfconf-query` for modifying XFCE settings
+ `xrdb` for accessing Xresource colors

## Usage

`$ colorizer`

## Credits

+ Inspired by obtgen by [Fikri Omar](https://github.com/fikriomar16/obtgen/)
+ `fantome` GTK theme from [Adhi Pambudi](https://github.com/addy-dclxvi/gtk-theme-collections/)
