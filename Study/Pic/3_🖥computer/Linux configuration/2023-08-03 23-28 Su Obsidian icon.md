#obsidian 

# Obsidian icon
Created:2023-08-03 23-28

Extract Appimage with
```bash
./Obsidian.appimage --appimage-extract
```


Actually after extraction in Dock directory you probably face a $.desktopfile$ If you don't you can create in Dock directory. And select your icon. I left all of extracted files in Dock.

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

And after creating you should change $Exec=/home/surena/Dock/squashfs-root/obsidian$ and $Icon=/home/surena/Dock/squashfs-root/obsidian$

ree
## References:

## Related:



