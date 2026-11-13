<p align="center">
  <img src="https://tsudev.com/brand/logo-tsudev-256.png" alt="tsudev" width="128">
</p>

<h1 align="center">tsudev</h1>

<p align="center">
  Small, honest open-source tools for Windows, Linux, macOS and Android - Vietnamese-first, installable with one command.<br>
  <sub>Phần mềm nhỏ, gọn, mã nguồn mở - tiếng Việt trước tiên, cài bằng một lệnh.</sub>
</p>

<p align="center">
  <a href="https://tsudev.com/apps">App directory</a> ·
  <a href="https://tsudev.com/docs">Docs</a> ·
  <a href="https://tsudev.com/ung-ho">Support the project</a>
</p>

## Install with one command

```bash
# Linux (apt/dnf) and macOS (Homebrew)
curl -fsSL https://tsudev.com/install.sh | sh -s -- <package>
```

```powershell
# Windows (winget, then Scoop)
& ([scriptblock]::Create((irm https://tsudev.com/install.ps1))) <package>
```

Use `--list` (Windows: `-List`) to see what is available. The scripts only call your package manager; signing keys are
pinned by SHA-256 and each script publishes its own checksum ([install.sh.sha256](https://tsudev.com/install.sh.sha256),
[install.ps1.sha256](https://tsudev.com/install.ps1.sha256)) - read them before running.

## Projects

| Project | What it does | Platforms | Install |
| --- | --- | --- | --- |
| [Lotus Share](https://github.com/tsudev-org/lotus-share) | Share files and messages on the same Wi-Fi, end-to-end encrypted (fork of LocalSend) | Windows · macOS · Linux · Android | Scoop · Homebrew · APT/DNF |
| [tsudev-files](https://github.com/tsudev-org/tsudev-files) | Offline file converter for 260+ formats (fork of Filee) | Windows · macOS · Linux | Scoop · Homebrew · APT/DNF |
| [tsudev-trafficmonitor](https://github.com/tsudev-org/tsudev-trafficmonitor) | Network/CPU/RAM monitor on the Windows taskbar (fork of TrafficMonitor) | Windows | Scoop |
| [cwico](https://github.com/tsudev-org/tsudev-cwico) | Deep Windows cleanup with a restore point before every run | Windows | winget |
| [tsudev SWICO](https://github.com/tsudev-org/tsudev-swico) | Windows/Office licensing check and hardware inventory, offline | Windows | winget · Scoop |
| [tsudev-contact](https://github.com/tsudev-org/tsudev-contact) | CSV contacts to vCard (.vcf) with preview | Windows | Scoop |

Package infrastructure: [scoop-bucket](https://github.com/tsudev-org/scoop-bucket) ·
[homebrew-tap](https://github.com/tsudev-org/homebrew-tap) ·
[linux-packages](https://github.com/tsudev-org/linux-packages) (signed APT/RPM at `pkg.tsudev.com`).
Engineering rules shared by every repo: [tsudev-standards](https://github.com/tsudev-org/tsudev-standards).

## Contributing

Issues, translations and pull requests are welcome in every repository - see
[CONTRIBUTING](https://github.com/tsudev-org/.github/blob/main/CONTRIBUTING.md). Security reports go through
**private vulnerability reporting** on each repository's Security tab, never public issues.
