# WorkMonitor Releases

## Latest Version: v1.4.1

### Download Options

####  Windows Installer (Recommended)
- **Download**: [work-monitor-setup.msi](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor-setup.msi)
- **Size**: 7.38 MB
- **SHA256**: `ed5aa6af9ad62833bc2ed158cbdd75835b498a9db64edd2324f865564c0486f4`

#### Portable Version (No Installation Required)
- **Download**: [work-monitor.exe](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor.exe)
- **Size**: 21.28 MB
- **SHA256**: `8a88caef529c69bde542e567b41752427dd92f351d0e05a4b42815c05f480031`

### Installation

```powershell
# Option 1: Install using MSI (Recommended)
Invoke-WebRequest -Uri "https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor-setup.msi" -OutFile "work-monitor-setup.msi"
Start-Process msiexec.exe -ArgumentList "/i work-monitor-setup.msi" -Wait

# Option 2: Download portable EXE
Invoke-WebRequest -Uri "https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor.exe" -OutFile "work-monitor.exe"
```

### Auto-Update
The application automatically checks for updates using:
```
https://github.com/wizice/workmonitor-releases/raw/master/updates/version.json
```

### Version History
- [v1.4.2](./releases/v1.4.2/) - [v1.4.1](./releases/v1.4.1/) - [v1.4.0](./releases/v1.4.0/) - [v1.3.1](./releases/v1.3.1/)

---
*Last updated: 10/16/2025 05:46:56*
