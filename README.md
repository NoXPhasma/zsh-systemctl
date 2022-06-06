# zsh-systemctl
A systemctl plugin for zsh.

This plugin adds aliases for systemctl commands with sudo if needed.

## Usage

Some examples:

```bash
# Before
systemctl status nginx
# After:
sc-status nginx

# Before
sudo systemctl restart nginx
# After
sc-restart nginx

# It also supports --user services
# Before
systemctl --user status pipewire
# After
scu-status pipewire
```