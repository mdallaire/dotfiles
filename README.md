

## Termux installation

Upgrade and accept all maintainer configurations (Y at each prompts)

```bash
pkg upgrade
pkg install openssh proot chezmoi
termux-chroot
/home/.local/bin/chezmoi init mdallaire --apply
```


