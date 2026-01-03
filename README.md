# AfterLifeOS OTA Services

<!-- NAVIGATION TABS -->
<p align="center">
  <a href="README.md">
    <img src="https://img.shields.io/badge/📖_README-Current-blue?style=for-the-badge" alt="README">
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/🚀_CONTRIBUTING-Click_Here-gray?style=for-the-badge" alt="CONTRIBUTING">
  </a>
</p>
<!-- END NAVIGATION TABS -->

Welcome to the official Over-The-Air (OTA) configuration repository for AfterLifeOS. This repository serves as the central hub for managing device support, update delivery, and changelogs for all officially supported devices.

## 📚 Documentation

We have separated the detailed technical documentation for maintainers into a dedicated guide.

| [**📖 README (Home)**](README.md) | [**🚀 Contributing Guide**](CONTRIBUTING.md) |
| :---: | :---: |
| *Project Overview & General Info* | *Step-by-step guide for releasing builds* |

> **New Device?** Check the [Contributing Guide](CONTRIBUTING.md) for instructions on adding your device to `devices.json` and setting up the directory structure.

## 🚀 Project Overview

This system allows AfterLifeOS to deliver updates directly to user devices. It relies on a structured file system where each device has its own configuration for:
- **Update JSON:** Defining the latest build details (version, download link, hash).
- **Changelogs:** Providing users with a history of changes and improvements.

## 🛠️ Quick Links

- [**Template: updates.json**](templates/updates.json)
- [**Template: changelog.md**](templates/changelog.md)

## 🤝 How to Contribute

If you are a maintainer looking to update your device:

1.  **Read the Guide:** Click the **MAINTAINER GUIDE** badge above or [click here](CONTRIBUTING.md).
2.  **Update Config:** Modify `updates.json` in your device's directory.
3.  **Update Changelog:** Append the latest changes to `changelog.md` following the standard format.
4.  **Submit PR:** Open a Pull Request with your changes.

---
*AfterLifeOS - Experience the Afterlife.*
