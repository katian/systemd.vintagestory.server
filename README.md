Vintage Story server using systemd

$ sudo loginctl enable-linger <user> (service autostart on boot)
$ systemctl --user enable vintagestoryserver.service
$ systemctl --user start vintagestoryserver.service
