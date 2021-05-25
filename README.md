# Setting_dconf_linux_OS20.04_21.04_V47.0_By_Griggorii_Wayland_adaptation
dconf , gnome , wayland , X11 , PipeWire and Pulse Audio fix , setting global , qt-dbus

Ubuntu 16.04....21.04 all support ubuntu stable-> gnome-shell-3.36-3.38 | beta-> gnome-shell-40 nemo support proview https://youtu.be/fqCYEX4uOhg

Ubuntu debian

Download theame + icons https://github.com/Griggorii/ubuntu-21.04-hirsute-desktop-amd64-griggorii-zsync.iso/archive/refs/heads/main.zip inpack sudo dpkg -i *.deb

$ sudo rm -rf /usr/share/gnome-shell/extensions/user-theme@gnome-shell-extensions.gcampax.github.com $HOME/.local/share/gnome-shell/extensions/user-theme@gnome-shell-extensions.gcampax.github.com

$ sudo apt update && sudo apt --reinstall install gnome-shell-extensions -y && sudo chmod -R 755 /usr/share/themes/Orchis && sudo glib-compile-schemas /usr/share/glib-2.0/schemas

Variant Nemo , Nautilus two options readme instructions fix sh script chmod + x re run

Idea fast gui off animations autorun flag wine playonlinux , steam and all run applications emulators program send $ gsettings set org.gnome.desktop.interface enable-animations false

close program wine $ $ gsettings set org.gnome.desktop.interface enable-animations true

Full flags experiment copy to full EOF enter

EOF
gsettings set org.mate.interface gtk-enable-animations false
EOF
gsettings set org.gnome.desktop.interface gtk-menu-popdown-delay false
EOF
gsettings set org.gnome.desktop.interface gtk-menu-bar-popup-delay false
EOF
gsettings set org.gnome.desktop.interface gtk-timeout-expand false
EOF
gsettings set org.gnome.desktop.interface enable-animations false
EOF
gsettings set org.gnome.desktop.interface menu-popdown-delay false
EOF
gsettings set org.gnome.desktop.interface menu-bar-popup-delay false
EOF
gsettings set org.gnome.desktop.interface timeout-expand false
EOF

All gnome-shell + 40 variant https://github.com/Griggorii/Setting_dconf_linux_OS20.04_V46.0_By_Griggorii_Wayland_adaptation/releases/tag/gnome-shell-3.38-40.0

horizontal_adaptation not recommended for 3.36-3.38 lag , horizontal for gnome-shell-40

Ubuntu stable: https://github.com/Griggorii/ubuntu-21.04-hirsute-desktop-amd64-griggorii-zsync.iso
