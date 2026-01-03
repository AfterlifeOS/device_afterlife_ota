# Contributing & Release Guide

This document outlines the steps required for maintainers to release a clean build for a **new device** and contribute to the AfterLifeOS OTA repository.

## 1. Add Device to `devices.json`

First, you must register your device in the root `devices.json` file. Add a new object to the `devices` array.

**Required Fields:**
*   `name`: Full marketing name of the device.
*   `codename`: The unique device codename (e.g., `a51`, `sweet`).
*   `brand`: Device manufacturer (e.g., `Samsung`, `Xiaomi`).
*   `maintainer`: Your name/handle.
*   `github_username`: Your GitHub username (optional but recommended).
*   `image_url`: A direct link to a transparent PNG of the device.
*   `pling_id`: The Pling ID for your project (if applicable).
*   `status`: Set to "Active".

**Example:**
```json
{
    "name": "Samsung Galaxy A51",
    "codename": "a51",
    "brand": "Samsung",
    "maintainer": "YourName",
    "github_username": "yourgithub",
    "image_url": "https://link.to/image.png",
    "pling_id": "1234567",
    "status": "Active"
}
```

## 2. Create Device Directory

Create a new directory in the root of this repository matching your device's **codename**.

```bash
mkdir <codename>
# Example: mkdir a51
```

## 3. Create `updates.json`

Inside your new directory (`<codename>/`), create a file named `updates.json`. This file serves OTA updates to users.

**Important:** The `download` URL must follow the format: `https://afterlifeos.com/download/?search=<codename>`

**Template:**
```json
{
    "response": [
        {
            "maintainer": "YourName",
            "oem": "Manufacturer",
            "device": "Device Name",
            "device_code": "codename",
            "buildtype": "OFFICIAL",
            "download": "https://afterlifeos.com/download/?search=codename",
            "forum": "https://t.me/YourSupportGroup",
            "telegram": "https://t.me/YourSupportGroup",
            "variants": {
                "gapps": {
                    "codename": "version_codename",
                    "version": "8.x",
                    "filename": "AfterlifeOS_codename-8.x-vercode-official_YYYYMMDD-gapps.zip",
                    "timestamp": 1767064419,
                    "md5": "your_build_md5_hash",
                    "sha256": "your_build_sha256_hash",
                    "size": 1234567890
                }
            }
        }
    ]
}
```

*   Replace `gapps` with `vanilla` or `coregapps` depending on your build variant key.
*   `timestamp` is the Unix Epoch time.

## 4. Create `changelog.md`

Inside your new directory (`<codename>/`), create a file named `changelog.md`. This file is displayed to users when they check for updates. The format supports multiple versions separated by a horizontal rule (`---`).

**Format:**
```markdown
# Brand Device Name (codename)
## Version - **8.x VersionName**
### **Build date** - DD Month YYYY
- Synced with latest source
- Fixed specific bug
- Added feature X
- Kernel upstreamed to x.x.xxx
---

## Version - **Old Version Name**
### **Build date** - DD Month YYYY
- Previous changes...
---
```

**Example:**
```markdown
# Poco X3 NFC (surya)
## Version - **8.2 Serenity**
### **Build date** - 11 December 2025
- Synced with latest source
- Update kernel with latest Gilver kernel
---

## Version - **8.1 Happiness (HOTFIX)**
### **Build date** - 22 November 2025
- Fixed google login issue
- Fixed can't open media (in some apps like WhatsApp, Telegram, etc)
- Fixed some weather icon not showing
- Optimize perf
---
```

## Summary of Files

When you are done, your new folder structure should look like this:

```text
/
├── devices.json (Modified)
└── <codename>/ (New Directory)
    ├── changelog.md (New File)
    └── updates.json (New File)
```
