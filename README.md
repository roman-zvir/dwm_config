# DWM + slstatus Configuration

This repository contains my customized configuration files for [dwm](https://dwm.suckless.org/) (Dynamic Window Manager) and [slstatus](https://tools.suckless.org/slstatus/) (status monitor for dwm). These configurations are tailored for a minimalist, efficient workflow with a clean aesthetic.

## Features

- **Customized dwm:**
  - Keybindings for enhanced productivity.
  - Patched with useful features like:
  - Gaps between windows.
  - Systray support.
  - Additional layout options.
  - Theme with a focus on simplicity and readability.

- **slstatus Integration:**
  - CPU usage.
  - Memory usage.
  - Free disk space
  - Volume level.
  - Battery status.
  - Minimal and non-intrusive.

## Screenshots

Screenshots to showcase setup:

![image](https://github.com/user-attachments/assets/6406b303-e3e9-44cd-b85c-edbb126fc6a8)

![image](https://github.com/user-attachments/assets/288b4adc-bba6-46f6-b34b-0e70dd9c6eee)


## Installation

### Prerequisites

- A working C compiler (e.g., `gcc`).
- `make` tool.
- X11 server.

### Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/roman-zvir/dwm-config.git
   cd dwm-config
   ```
2. **Replace the `config.h` Files:**
   - Copy the provided `config.h` files into the respective directories of your dwm and slstatus installations:
     
     ```bash
     cp dwm-config.h /path/to/dwm/config.h
     cp slstatus-config.h /path/to/slstatus/config.h
     ```

3. **Rebuild dwm and slstatus:**
   - For dwm:
     ```bash
     cd /path/to/dwm
     sudo make clean install
     ```
   - For slstatus:
     ```bash
     cd /path/to/slstatus
     sudo make clean install
     ```

4. **Restart dwm:**
   
   Log out and log back in to start using the customized dwm with slstatus.


## License

This configuration is available under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [suckless.org](https://suckless.org/) for creating such minimal and efficient software.
- The open-source community for patches and inspirations.
