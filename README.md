# WorkMonitor Releases

## Latest Version: v1.4.0

### Download Options

#### Windows Installer (Recommended)
- **Download**: [work-monitor-setup.msi](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor-setup.msi)
- **Size**: 7.46 MB
- **SHA256**: `7b2b7d19132ca0d7362ce5a7e99f5eb766283680111ad0ccb99c04de70f48907`

####  Portable Version (No Installation Required)
- **Download**: [work-monitor.exe](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor.exe)
- **Size**: 21.15 MB
- **SHA256**: `ee612e14d8091917a646212160ae20254e8c6e628b20b62d00bfe621a5d862d2`

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
- [v1.4.0](./releases/v1.4.0/) - [v1.3.1](./releases/v1.3.1/)

---
*Last updated: 07/16/2025 04:08:28*
