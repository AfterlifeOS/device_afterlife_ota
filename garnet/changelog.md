# Redmi Note 13 Pro 5G / Poco X6 5G (Garnet)
## Version - **8.4 Ophelia**
### **Build date** - 19 April 2026
- Kang Adreno driver from aurora OS3.0.7.0.WNACNXM (V@762.36 OGL & VK 1.3.128)
- Use hwui and add some hwui props for improve perf
- Set vulkan as default renderer
- Relax thermal limits and optimize charging behavior (cr @Flyingsquirrel02)
- GameBar update (cr @ph12nex)
- KernelSU-Next 3.2.0 & SUSFS 2.1.0 included
- Kernel rebase & upstream 5.10.253 (cr @ramabondanp)
- kernel: Imported Adaptive Deadline I/O Scheduler (ADIOS) v3.2.0
- kernel: Import Reflex CPUFreq Governor v0.3.0r2
- kernel: Enabled IP set support
- power: Improved deep sleep and switched to suspend-to-idle
- f2fs: Optimized GC, fsync, and cache pressure
- zRAM: Fixed race conditions and optimized entry flags
- GPU: Forced idle timeout to 58ms for better balance
- system: Reduced OOM and scheduler logspam
- Various upstream fixes and improvements for block & I/O scheduler
---

## Version - **8.3 Lastblood** (HOTFIX)
### **Build date** - 10 March 2026
- Kernel rebase
- Pre-rooted support SukiSU & ReSukiSU
- Fix external audio issue
- Fix voice calls always play through the loudspeaker instead of the earpiece.
- LunarisDolby UI
---

# Redmi Note 13 Pro 5G / Poco X6 5G (Garnet)
## Version - **8.3 Lastblood**
### **Build date** - 08 March 2026
- GApps Build 
- Pre-rooted with multi manager support.
- Include Sony Dolby Atmos & MI Cam
- Switch back to stock GPU driver (V@0615.93 & vk 1.1.128)
- Sync with grewal changes
- Kernel Upstream (5.10.252)
- Some camera fixes from kleidione commit
- Added Xiaomi Parts
- props: Enable support for kernel idle timer
- Disable logging sensors-hal events
- Improve scrolling and responsiveness
- disable_gl_backpressure
- Enable frame pacing for smoother visual performance
- props: Add missing layer buffer slots cache clear property
- Enable debug.performance.tuning
- Enable AOSP surfaceflinger
- Enable Qualcomm TrueWireless™ Stereo
- Default HWUI renderer to SkiaGL
- Use HintManager for HWUI
---

## Version - **8.2 Serenity**
### **Build date** - 23 December 2025
- GApps Build 
- SukiSU v4.1.0 & SUSFS v2.0.0 Included
- Upgraded GPU driver to Adreno 819.0.2 & Vulkan 1.3.295
- Dolby & Mi Cam Included
---

## Version - **8.1 Happiness**
### **Build date** - 16 November 2025
- Improve performance 
- Improve battery backup
- Update from OS2.0.204.0.VNRMIXM
- Upstream kernel
- KSUN v1.1.1 & SUSFS v1.5.12 Included
- Misc Changes and Improvement
