# Fshare for Windows

Private file sharing between nearby devices on the same local network.
Fshare uses encrypted peer connections, receiver consent, numeric pairing,
continuous file uploads, resume checkpoints and whole-file checksum verification.

## Download

Download **Fshare-Setup-0.1.2-windows-x64.exe** from the
[v0.1.2 release](https://github.com/imhmb23/Fshare/releases/tag/v0.1.2).
The installer includes all required application files and installs for the
current user on Windows 10/11 systems capable of running x64 applications.

The setup and application are currently unsigned. Close older Fshare instances
before installing. Both devices need compatible Fshare apps on the same private
network. Allow Fshare on Private networks when Windows Firewall prompts.

## WinGet

The planned package ID is **Bilal.Fshare**. After its community-repository
submission is merged and indexed, install it with:

```powershell
winget install --id Bilal.Fshare --exact --source winget
```

The command becomes available after Microsoft accepts the manifest; publishing
a GitHub release alone does not add an application to WinGet.

## License and source

Fshare is proprietary software. Official binaries may be used without charge
under [LICENSE.txt](LICENSE.txt). This repository contains installer releases
and download information only. Application source code is maintained privately.
Third-party license notices are included in the installed application.
