<div align="center">

# YT Music App

A desktop wrapper for YouTube Music with plugin support.

</div>

> [!IMPORTANT]
> ⚠️ Disclaimer
>
> **No Affiliation**
>
> This project, and its contributors, are not affiliated with, authorized by, endorsed by, or in any way officially connected with Google LLC, YouTube, or any of their subsidiaries or affiliates. **This is an independent, non-profit, and unofficial extension developed by a team of volunteers with the goal of providing a desktop experience.**
>
> **Trademarks**
>
> The names "Google" and "YouTube Music", as well as related names, marks, emblems, and images, are registered trademarks of their respective owners. Any use of these trademarks is for identification and reference purposes only and does not imply any association with the trademark holder. We have no intention of infringing upon these trademarks or causing harm to the trademark holders.
>
> **Limitation of Liability**
>
> This application (extension) is provided "AS IS", and you use it at your own risk. In no event shall the developers or contributors be liable for any claim, damages, or other liability, including any legal consequences, arising from, out of, or in connection with the software or the use or other dealings in the software. The responsibility for any and all outcomes of using this software rests entirely with the user.

## Download & Installation

Pre-built binaries are available for **Linux** and **Windows** via the [Releases](https://github.com/rishit-symbi/ytmusic-desktop-app/releases) page.

### Linux

| Format | Distro | File |
|--------|--------|------|
| **AppImage** | Any Linux (universal) | `YT Music-*.AppImage` |
| **DEB** | Debian / Ubuntu / Linux Mint / Pop!_OS | `ytmusic_*.deb` |
| **RPM** | Fedora / RHEL / CentOS | `ytmusic_*.rpm` |
| **tar.gz** | Any Linux (portable) | `ytmusic-*.tar.gz` |

**AppImage:**
```bash
chmod +x YT\ Music-*.AppImage
./YT\ Music-*.AppImage
```

**Debian/Ubuntu:**
```bash
sudo dpkg -i ytmusic_*.deb
# or install dependencies if needed:
sudo apt install -f
```

**Fedora/RHEL:**
```bash
sudo rpm -i ytmusic_*.rpm
```

**Portable archive:**
```bash
tar -xzf ytmusic-*.tar.gz
./ytmusic
```

### Windows

| Format | File |
|--------|------|
| **Installer (NSIS)** | `YT Music Setup *.exe` |
| **Portable** | `YT Music *.exe` |

Run the installer `.exe` and follow the setup wizard. The portable version can be launched directly without installation.

> **Tip:** You can also build from source — see the build scripts in `package.json` (`pnpm dist:linux`, `pnpm dist:win`, etc.).

## FAQ

### Why apps menu isn't showing up?

If `Hide Menu` option is on - you can show the menu with the <kbd>alt</kbd> key (or <kbd>\`</kbd> [backtick] if using the in-app-menu plugin)
