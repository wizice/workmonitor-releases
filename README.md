# WorkMonitor Releases

## Latest Version: v1.5.0

### Download Options

####  Windows Installer (Recommended)
- **Download**: [work-monitor-setup.msi](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor-setup.msi)
- **Size**: 8.59 MB
- **SHA256**: `d7f3a8214f8fc60fc4c31fbb76d2adc8fe78e546980dd364ccea1977ce997e30`

#### Portable Version (No Installation Required)
- **Download**: [work-monitor.exe](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor.exe)
- **Size**: 25.09 MB
- **SHA256**: `90da0e3485e185a4df3ec6bb1ca38a6791f447731e41a0b852d20197cbefff29`

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
- [v1.5.0](./releases/v1.5.0/) - [v1.4.2](./releases/v1.4.2/) - [v1.4.1](./releases/v1.4.1/) - [v1.4.0](./releases/v1.4.0/) - [v1.3.1](./releases/v1.3.1/)

---
*Last updated: 03/01/2026 13:28:23*
