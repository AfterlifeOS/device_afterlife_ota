# Redmi Note 12 Pro 4G (Sweet_k6a)
---
## Version - **8.4 Ophelia**
### **Build date** - 23 April 2026
- Vulkan has been activated
- Switched StriXotic-MeMeDo kernel
- Many changes were dropped for video stabilization
- Fixed some issues,optimized rom
- Performance has been improved
- Initial Afterlife A16 QPR2 build
## Version - **8.3-lastblood**
### **Build date** - 4 March 2026
- properties: Set persist.sys.purgeable_assets=1
- prop: Add a property to enable prefetching video
- Enable frame pacing for smoother visual performance
- properties: ro.sf.blurs_are_expensive 1
- overlay: Set app animation speed to 0.8
- display: Fix HDR functionality by enabling Vulkan
- properties: Add props to improve battery backup
- Expose aux cameras to com.snapchat.android
- Enable ScrollOptimizer
- overlay: Import activity open/close animations
- overlay: anim: Replace fixed dp with a percentage of screen
- overlay: anim: Replace standard_accelerate with linear interpolator
- overlay: anim: Increase alpha duration from 83ms to 160ms
- overlay: Adapt it for sweet2
- Force disable iorapd
- wifi: Smarter decisions on whether to use a 2 or 5Ghz AP
- Increase CPU Boost duration from 120ms to 200ms
- Move background cpuset to CPU0-1 
- rootdir: Enable suspend to RAM
- Tweak input boost
- Setup zram with post-boot script"
- rootdir: Set 55% of zRAM size
- rootdir: Update zram configuration 
+ zram: Enable zram writeback job scheduler
- zram: Adjust zram write back policy
- Add SonyDolby and remove MiDolby
- Append Dolby manifests
- Improve recovery compatibility and network configs 
- Allow games to use 120fps
- overlay-lineage: Disable blurs by default
- overlay: Remove decoupled power mode configs
- overlay: Drop COLOR_MODE_AUTOMATIC
- Address QCOM WFD denials
---

## Version - **8.2 Serenity**
### **Build date** - 20 December 2025
- Define OEM fast charge sysfs node
- Fix screen recorder lag
- Properly setup fast charging configuration
- Add burn-in protection for statusbar and navbar
- overlay: Tune ambient display burn-in protection
- Add power button location for correct unlock animation
- props: Enable config_avoidGfxAccel
- props: Enable support for kernel idle timer
- Disable logging sensors-hal events
- For smoother scrolling and better responsiveness
- disable_gl_backpressure
- Use hwui and add some hwui props for improve perf
- Apply dex2oat optimizations
- Force disable iorapd
- Enable LTO Optimizations
- Enable debug.performance.tuning
- prop: Add a property to enable prefetching video
- Enable frame pacing for smoother visual performance
- properties: Add props to improve battery backup
- Expose aux cameras to com.snapchat.android
- Stop using vulkan
---

## Version - **8.2 Serenity**
### **Build date** - 12 December 2025
- Initial Afterlife Release 
