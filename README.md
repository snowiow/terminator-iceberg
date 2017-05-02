# terminator-iceberg
![terminator iceberg](https://github.com/snowiow/terminator-iceberg/blob/master/screenshots/terminator-iceberg.png)
A color theme for [terminator](https://gnometerminator.blogspot.de/p/introduction.html) using  cocopons [iceberg color scheme](http://cocopon.me/app/vim-iceberg/).

## Installation
Install the terminator configuration file:

```bash
git clone https://github.com/snowiow/terminator-iceberg
cd terminator-iceberg
mkdir -p ~/.config/terminator/
touch ~/.config/terminator/config
# if you want to overwrite your current config:
cp config ~/.config/terminator
# if you want to append to your current config:
cat config >> ~/.config/terminator/config
```

To overwrite the default theme, copy all properties of the iceberg profile into the default profile. For example the following default profile:

```bash
[profiles]  
  [[default]]  
    background_color = "#000000"  
    cursor_blink = False  
    cursor_color = "#000000"  
    font = Source Code Pro Semi-Bold 10  
    foreground_color = "#000000"  
    scrollbar_position = hidden  
    show_titlebar = False  
    use_system_font = False  
```

Will result in this:
```bash
[profiles]
  [[default]]
    background_color = "#161821"
    cursor_blink = False
    cursor_color = "#c6c8d1"
    font = Source Code Pro Semi-Bold 10
    foreground_color = "#c6c8d1"
    palette = "#2a3158:#e27878:#89b8c2:#e4aa80:#84a0c6:#d1a8ad:#adc1cb:#c6c8d1:#444b71:#e2a478:#b4be82:#d8e599:#3e445e:#673e43:#686f9a:#d4d5db"
    scrollbar_position = hidden
    show_titlebar = False
    use_system_font = False
```
