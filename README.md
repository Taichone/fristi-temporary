# fristi-temporary

```
mkdir -p ~/.local/share/applications

cat <<EOF > ~/.local/share/applications/cursor.desktop
[Desktop Entry]
Name=Cursor
Exec=$HOME/Downloads/cursor.AppImage --no-sandbox
Icon=cursor
Type=Application
Categories=Development;
EOF
```
