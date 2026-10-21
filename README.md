# Just-wifi-CLI-tool

A lightweight Zsh CLI wrapper for NetworkManager

Written by me just to make Wi-Fi configuration simple and headache-free on Linux. Feel free to use it!

## Dependencies
Make sure you have the following installed:
- `zsh`
- `NetworkManager` (`nmcli`)

## Instalation
1. Download the script and place it in your local binary path:
   ```bash
   mkdir -p ~/.local/bin
   git clone https://github.com/mXd-mXn/just-wifi-CLI-tool.git -o ~/.local/bin/wifi
   chmod +x ~/.local/bin/wifi

2. Make sure ~/.local/bin is in your $PATH (e.g. in your ~/.zshrc):
  ```bash
   export PATH="$HOME/.local/bin:$PATH"
  ```

## Usage

```bash
wifi scan                 # List available networks
wifi connect SSID [pass]  # Connect to network
wifi status               # Show connection info
wifi on / off             # Enable / disable networking
wifi saved                # List saved networks
wifi forget SSID          # Delete saved network
wifi help                 # Show info
```
