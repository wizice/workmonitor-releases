# WorkMonitor Releases

## Latest Version: v1.4.1

### Download Options

####  Windows Installer (Recommended)
- **Download**: [work-monitor-setup.msi](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor-setup.msi)
- **Size**: 7.34 MB
- **SHA256**: `95feb1905a8850db687a77f99a81121307e0fd8984e08a0f8c71a3e0dbc5d51e`

#### Portable Version (No Installation Required)
- **Download**: [work-monitor.exe](https://github.com/wizice/workmonitor-releases/raw/master/updates/work-monitor.exe)
- **Size**: 20.97 MB
- **SHA256**: `abd420cb3233d61c65ceb8496e0e7d7ebe5b3acf0407b3029db2990c94f0e2a9`

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
- [v1.4.1](./releases/v1.4.1/) - [v1.4.0](./releases/v1.4.0/) - [v1.3.1](./releases/v1.3.1/)

---
*Last updated: 10/03/2025 08:10:14*
