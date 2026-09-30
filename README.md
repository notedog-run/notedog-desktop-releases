# Notedog Desktop

Downloads of the [Notedog](https://notedog.run) desktop app for Linux and
Windows. It shows your phone's Notedog journal in its own window, so you need
the Notedog app on your Android phone.

**Preview.** Expect rough edges. There's no auto-update yet: to update,
install the new version over the old one. Your login is kept.

## Install

Get the files from [Releases](../../releases).

- **Fedora:** `sudo dnf install ./notedog-desktop-<version>.x86_64.rpm`
- **Debian / Ubuntu:** `sudo apt install ./notedog-desktop_<version>_amd64.deb`
- **Arch / Omarchy:** `sudo pacman -U ./notedog-desktop-<version>-1-x86_64.pkg.tar.xz`
- **Other Linux:** `notedog-desktop-<version>-x86_64.AppImage`. Make it
  executable (`chmod +x`) and run it. It adds no launcher entry, and some
  distros need FUSE 2 (`libfuse2`) to run AppImages.
- **Windows:** run `notedog-desktop-<version>-setup.exe`. The installer isn't
  signed yet, so Windows SmartScreen warns: click **More info → Run anyway**.

Each release has a `SHA256SUMS` file to check the downloads.

## First start

Notedog opens its Settings window. Paste the `https://…` address Notedog shows
under "On this network", your tunnel URL, or both, then approve the pairing
on your phone. More on [notedog.run/desktop](https://notedog.run/desktop).

## Feedback

Found a problem? Please [open an issue](../../issues). Say which system you use and which version (bottom of Settings, top of the
tray menu, or `notedog-desktop --version`).

## License

Free to use; not open source. See [LICENSE](LICENSE).
