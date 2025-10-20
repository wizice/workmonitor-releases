# WorkMonitor Releases

## Latest Version: v1.4.1

### Download Options

####  Windows Installer (Recommended)
- **Download**: [work-monitor-setup.msi](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor-setup.msi)
- **Size**: 7.38 MB
- **SHA256**: `4cc2def7636adbc939a510f59792464e098f0ccc293c1453e644eb36eaa28047`

#### Portable Version (No Installation Required)
- **Download**: [work-monitor.exe](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor.exe)
- **Size**: 22.59 MB
- **SHA256**: `0125201b362a10f3c7069f8c710dfed3457430756e89db07e90239ef686be908`

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
*Last updated: 10/21/2025 08:29:59*
