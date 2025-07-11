#  Windows Rice Setup

## 📦 Setup Steps

### 🛠 1. Install Scoop

```powershell

Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
irm get.scoop.sh | iex

```

### 🧱 2. Install Core Tools

```powershell

scoop install wezterm starship neovim git neofetch

```
⚠️ For Zebra and GlazeWM, manual installation is recommended. See below.

### 🪟 3. Install GlazeWM (Tiling Window Manager for Windows)
Download the latest release here:
➡️ [Download GlazeWM](https://github.com/glzr-io/glazewm)

Extract and run glazewm.exe.

🔧 GlazeWM Config
Place your config file at:

```arduino

$HOME\.glz\glazewm\config.yaml

```
My config: [glazewm config](https://github.com/keshavarun20/dotfiles/blob/master/.config/glazevm/config.yaml)

🔧 Zebra Config
Place config file at:

```arduino

$HOME\.glz\zebar

```
My config: [Zebar config](https://github.com/keshavarun20/dotfiles/tree/master/.config/zebar)

### 💻 4. WezTerm Terminal
Download WezTerm here:
➡️ [Download WezTerm](https://wezterm.org/index.html)

🔧 WezTerm Config
Place your config file at:

```arduino

$HOME\

```
My config: [wezterm config](https://github.com/keshavarun20/dotfiles/blob/master/.config/wezterm/.wezterm.lua)

### 🚀 5. Starship Prompt

🔧 Config Location
```arduino

$HOME/.config/starship.toml

```
My config: [starship config](https://github.com/keshavarun20/dotfiles/blob/master/.config/starship.toml)

### 📟 6. Neofetch System Info

🔧 Config Location
```arduino

$HOME/.config/neofetch/config.conf

```
My config: [neofetch config](https://github.com/keshavarun20/dotfiles/blob/master/.config/neofetch/config.conf)

### 📝 8. Neovim with NvChad
Download from: [NvChad](https://nvchad.com/}
