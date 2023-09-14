# Notes

## cleaning and building it again

``` bash
rm -f notifications-alert-on-user-menu@hackedbellini.gmail.com.zip && rm -fr ~/.local/share/gnome-shell/extensions/notifications-alert-on-user-menu@hackedbellini.gmail.com && make install
```

In a terminal, start `journalctl -f` to see potential logs / issues.

Restart GNome with ALT+F2.

Check in the app Tweaks / Extension if the extension has been loaded without issues.