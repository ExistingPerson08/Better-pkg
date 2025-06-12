# better-pkg

**better-pkg** is a universal CLI package managers wrapper for various Linux distributions and package managers. It allows you to install, remove, search, export, and manage packages and plugins and more from a single tool, whether you use APT, DNF, Pacman, Zypper, Flatpak, Snap, Homebrew, and more.

## Features

- **Just one python script**
- **Universal install/remove/search** for packages (apt, dnf, pacman, zypper, yay, paru, flatpak, snap, brew, pacstall, ...)
- **Export/import package lists** (for migration or backup)
- **Plugin support** – easily extend with new features
- **Automation of common tasks** (update, upgrade, cleanup, repair, cache)
- **Security checks** (firewall, SELinux, auditd, fail2ban, sudoers, ...)
- **Colorful, user-friendly output**
- **Aliases and custom configuration support**

## Installation

1. **Requirements:**  
   - Python 3
   - python-requests
   - Recommended: `wget`, `curl`, `sudo`, and your package managers (apt, dnf, pacman, ...)

2. **Download python file from releases**

3. **(Optional) Add to your PATH:**
   ```bash
   sudo cp better-pkg /usr/local/bin/
   ```

## Contributing

- Pull requests and ideas are welcome!
- For most new features, use the plugin system.
