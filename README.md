# manjaro-i3-files
For HiDPI Monitors:
in ~/.Xresources
Xft.dpi: 192
URxvt.font: xft:FiraMono-Regular:size=10
Xft.autohint: 0
Xft.lcdfilter:  lcddefault
Xft.hintstyle:  hintfull
Xft.hinting: 1
Xft.antialias: 1
Xft.rgba: rgb


Create / Edit ~/.profile with the following:
export GDK_SCALE=2
export GDK_DPI_SCALE=0.5
export QT_AUTO_SCREEN_SCALE_FACTOR=1


