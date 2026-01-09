# StartupTunerPro
A Magisk Module for Automatic Phone Optimization at Boot

## 📖 Module Description
StartupTunerPro is a comprehensive Magisk module that automatically optimizes your Android device upon first screen unlock after boot. It runs silently in the background, enhancing system security, cleaning up residual system files, and automatically launching essential services.

## 📝 Development History
This Magisk module is adapted from a post by Coolapk user @Yz堕仙:  
https://www.coolapk.com/feed/65005997?s=YjdmY2UzYzAyM2ExNDg4ZzY5NjBmZDRjega1591

## ✨ Features

### Original Functions
- **SDK Interface Fix**: Automatically fixes SDK interface anomalies upon first unlock after boot
- **Security Hardening**: Automatically disables USB debugging and Developer options
- **System Cleanup**: Deletes TWRP folder to clear Recovery residual files
- **SELinux Hardening**: Enables SELinux enforcing mode to enhance security
- **Service Management**: Automatically starts BlackDomain (app) for background app control
- **Serial Number Management**: Only supports manual execution of action.sh to generate new serial numbers; no new serials are generated after reboot

### New Features
- **Dynamic Serial Number Generation**: Automatically generates new random serial numbers upon first unlock after boot (manual generation still supported)
- **Audio Service Startup**: Automatically starts HxAudio (app) audio enhancement service

## ⚙️ Optional Configurations
During module installation, you can use volume keys to select whether to enable:
- Random serial number generation
- BlackDomain auto-startup
- HxAudio auto-startup

## 🛠️ System Requirements
- Magisk 24.0+ or KernelSU or APatch installed (theoretically supports Magisk 24.0+ only)
- Android 8.0+ (API level 26+)
- Root access obtained

## ⚠️ Important Notes
- **Language Support**: The module installation interface currently supports Chinese only; multi-language support will be added in future versions
- **First Unlock Trigger**: All optimization features are triggered only upon first screen unlock after boot
- **Compatibility Notice**: May not be compatible with all custom ROMs or heavily modified systems

## 🤝 Contributing
Feedback and suggestions are welcome! When reporting issues, please provide device model, Android version, and framework version information.

## 🙏 Acknowledgments
- Original concept and implementation: @Yz堕仙 (Coolapk)
- Community feedback and beta testers
- Magisk and KernelSU development teams
