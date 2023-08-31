# alacritty
## Windows添加到右键菜单
```reg
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\Directory\Background\shell\alacritty]
@="Alacritty terminal here"
"Icon"="C:\\Tools\\Alacritty\\alacritty.ico"

[HKEY_CLASSES_ROOT\Directory\Background\shell\alacritty\command]
@="C:\\Tools\\Alacritty\\alacritty.exe"
```
