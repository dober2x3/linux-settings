# Linux Settings

## Arch Linux Setup

### Install packages:
```bash
sudo pacman -S yazi ffmpeg 7zip jq poppler fd ripgrep fzf zoxide resvg imagemagick
sudo pacman -S zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/LazyVim/starter ~/.config/nvim
rm -rf ~/.config/nvim/.git
ya pkg add BennyOe/tokyo-night
```

### Configure Yazi theme:
Add to your Yazi config:
```ini
[flavor]
use = "tokyo-night"
# For Yazi 0.4 and above
dark = "tokyo-night"
```

## Ubuntu Setup

```bash
sudo apt update && sudo apt upgrade -y

sudo apt install ffmpeg 7zip jq poppler-utils fd-find ripgrep fzf zoxide imagemagick

sudo apt install zsh curl iputils-ping cifs-utils mc

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/LazyVim/starter ~/.config/nvim
rm -rf ~/.config/nvim/.git
```

## OpenClaw Setup

```bash
curl -fsSL https://openclaw.ai/install.sh | bash -s -- --no-onboard
```
