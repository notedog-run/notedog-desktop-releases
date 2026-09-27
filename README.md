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
- **Windows:** run `notedog-desktop-<version>-setup.exe`. The installer isn't
  signed yet, so Windows SmartScreen warns: click **More info → Run anyway**.

Each release has a `SHA256SUMS` file to check the downloads.

## First start

Notedog opens its Settings window. Enter your phone's address on the local
network, your tunnel URL, or both, then approve the pairing on your phone.

## License

Free to use; not open source. See [LICENSE](LICENSE).
