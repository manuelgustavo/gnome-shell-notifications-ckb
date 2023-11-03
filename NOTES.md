# Notes

## cleaning and building it again

``` bash
rm -f manuel.gustavo@gnome-shell-notifications-ckb.manuelgustavo.github.com.zip && rm -fr ~/.local/share/gnome-shell/extensions/manuel.gustavo@gnome-shell-notifications-ckb.manuelgustavo.github.com && make install
```

In a terminal, start `journalctl -f` to see potential logs / issues.

Restart GNome with `ALT+F2` and `r`.

Check in the app Tweaks / Extension if the extension has been loaded without issues.