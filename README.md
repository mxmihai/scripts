# Windows Scripts Usage

To run the speedtest script directly from this repository on a Windows machine, use one of the following PowerShell commands:

```powershell
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/mxmihai/scripts/refs/heads/main/windows/speedtest10.ps1" -UseBasicParsing | Invoke-Expression
```

or the shorter alias version:

```powershell
iwr "https://raw.githubusercontent.com/mxmihai/scripts/refs/heads/main/windows/speedtest10.ps1" -UseBasicParsing | iex
```

Have fun!
