# better-pkg

**better-pkg** is a universal CLI package managers wrapper for various Linux distributions and package managers. It allows you to install, remove, search, export, and manage packages and plugins and more from just one script, whether you use APT, DNF, Pacman, Zypper, Flatpak, Snap, Homebrew, and more.

## Features

- **Just one python script**
- **Universal install/remove/search** for packages (apt, dnf, pacman, zypper, yay, paru, flatpak, snap, brew, pacstall, appimage)
- **Universal update and cleanup** (apt, dnf, pacman, zypper, yay, paru, flatpak, snap, brew, pacstall, distrobox, firmwa
- **Export/import package lists** (for migration or backup)
- **[Plugin support](https://github.com/ExistingPerson08/Better-pkg-data/tree/main/plugins)** – easily extend with new features
- **Automation of common tasks** (update, upgrade, cleanup, repair, cache)
- **Security checks** (firewall, SELinux, auditd, fail2ban, sudoers, ...)
- **Colorful, user-friendly output**
- **Aliases and custom configuration support**
- **Install app that are not in distros repo**, from its github or official site

## Installation

1. **Requirements:**  
   - Python 3
   - dbus-x11, python-requests and python-distro
   - dnf-plugins-core for adding dnf repos
   - Recommended: `wget`, `curl`, `sudo`, and your package managers (apt, dnf, pacman, ...)

2. **Download python file from releases**

3. **(Optional) Add to your PATH:**
   ```bash
   sudo cp better-pkg /usr/local/bin/
   ```

## Contributing

- Pull requests and ideas are welcome!
- For most new features create plugins.
