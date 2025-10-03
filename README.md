# WorkMonitor Releases

## Latest Version: v1.4.2

### Download Options

####  Windows Installer (Recommended)
- **Download**: [work-monitor-setup.msi](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor-setup.msi)
- **Size**: 7.36 MB
- **SHA256**: `5d69384ac49e279005f38c4c6eb1f2c00b778b808c23ea3f88a2be6338d26987`

#### Portable Version (No Installation Required)
- **Download**: [work-monitor.exe](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor.exe)
- **Size**: 21.07 MB
- **SHA256**: `4619df615c12ba79e026b0e0239a5eefcd937bee6dd80cf055df9e6c0c13c17f`

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
*Last updated: 10/03/2025 09:00:07*
