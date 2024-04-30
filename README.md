# fix-electron-blurry-wayland

- To fix the blury text on fraction scale in wayland, add the following to .desktop file
- /usr/bin/XXXXXX --enable-features=UseOzonePlatform,WaylandWindowDecorations --ozone-platform-hint=auto
