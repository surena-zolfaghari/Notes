#Obsidian 

# Obsidian icon
Created:2023-08-03 23-28

Extract Appimage with
```bash
./Obsidian.appimage --appimage-extract
```


Actually after extraction in Dock directory you probably face a $.desktopfile$ If you don't you can create in Dock directory. And select your icon.

```markdown
[Desktop Entry]
Name=Obsidian
Exec=AppRun --no-sandbox %U
Terminal=false
Type=Application
Icon=obsidian
StartupWMClass=Obsidian
X-AppImage-Version=1.3.4
Comment=Obsidian
MimeType=x-scheme-handler/obsidian;
Categories=Office;
```



## References:

## Related:



