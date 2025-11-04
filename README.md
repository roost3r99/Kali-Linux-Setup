# 🧩 Config Files

Custom configuration setup for **Zsh**, **Oh My Zsh**, **Alacritty**, and **Tmux** — optimized for a clean, modern Linux workflow with support for custom themes and 24-bit colors.

---

## 🛠️ Dependencies

- Alacritty  
- Tmux  
- TPM (Tmux Plugin Manager)  
- Oh My Zsh  
- Zsh-autosuggestions (Oh My Zsh plugin)  
- True Color (24-bit terminal support)  
- Nerd Font (recommended: Hack Nerd Font)

---

## 🔗 Links and Resources

- [Alacritty](https://github.com/alacritty/alacritty/blob/master/INSTALL.md)  
  _Make sure to install the required dependencies and follow directions for Zsh completions post build._

- [Tmux Plugin Manager (TPM)](https://github.com/tmux-plugins/tpm)

- [Oh My Zsh](https://ohmyz.sh)

- [Zsh Autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)

- [True Color (24-bit test)](https://gist.github.com/andersevenrud/015e61af2fd264371032763d4ed965b6)

- [Hack Nerd Font](https://www.nerdfonts.com/font-downloads)

**Once installed, simply copy all the configuration files to your home directory.**

---

## 🧰 Configuration Files Overview

| File | Path | Description |
|------|------|--------------|
| `.zshrc` | `~/.zshrc` | Main Zsh configuration file |
| `roost3r.zsh-theme` | `~/.oh-my-zsh/themes/` | Custom Oh My Zsh theme |
| `zsh-roost3r.plugin.zsh` | `~/.oh-my-zsh/plugins/zsh-roost3r/` | Custom plugin and aliases |
| `alacritty.toml` | `~/.config/alacritty/` | Alacritty terminal configuration |
| `tmux.conf` | `~/.tmux.conf` | Tmux configuration file |
| `vpn.sh` | `/opt/vpn.sh` | Script to check and display VPN IP (used in Polybar/i3) |

---

## 🧠 Notes

### 🌀 Zsh / Oh My Zsh

- Theme: `roost3r`
- Plugins: `git`, `fzf`, `zsh-autosuggestions`, `zsh-roost3r`
- Font: `Hack Nerd Font`
- True Color: Enabled

### 🧱 Tmux

- Use `Prefix + E` to send a command to all panes in the current session.  
- Use `Shift + arrow keys` to navigate **windows**.  
- Use `Ctrl + Shift + arrow keys` to navigate **panes**.  
- Managed by **TPM (Tmux Plugin Manager)**.

### 🖥️ Alacritty

- Transparent background and padding for minimal look.  
- Font set to **Hack Nerd Font**.  
- Colors follow a dark pastel palette optimized for Zsh & i3-gaps.

### 🔒 VPN Script

- File: `/opt/vpn.sh`  
- Displays VPN IP when active (for Polybar or terminal output).  
- Make it executable:  
  ```bash
  sudo chmod +x /opt/vpn.sh
