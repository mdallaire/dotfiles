

## Termux installation

Upgrade and accept all maintainer configurations (Y at each prompts)
```bash
pkg upgrade
pkg install openssh proot

```

pkg install proot openssh
termux-chroot
curl -sSfL https://github.com/mdallaire/dotfiles/raw/main/install.sh | bash
/home/.local/bin/chezmoi init mdallaire --apply
