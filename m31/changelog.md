# Samsung Galaxy M31 (m31)
## Version - **8.4 Ophelia**
### **Build date** - 23 April 2026
- Enable frame pacing
- Define screenRecorderAVCProfileLevel
- Decrease launch boost to 3sec
- Tune schedutil rate limits
- HWC Adapt from exynos9630 T BSP
- adapt struct decon_win_config_data to exynos9610
- fix missing dmabuf_trace_free call on buffer release path
- free exporter name on buffer release
- CONFIG_HZ to 300
- Enable HintManager for HWUI

## Version - **8.2 Serenity**
### **Build date** - 28 December 2025
- Initial Official release
- Core GApps build
- Optimise memory subsystem
- Enable THIN LTO
- Switch default i/o scheduler to mq-deadline
- Switch zram compression to Lz4
- Remove SurfaceFlinger durations
- Enable multi-stream ZRAM compression
- Drop debug.sf.disable_client_composition_cache
- Add props for handling blurs
- Disable wallpaper zooming
- Disable unnecessary logs
- Implement aggressive immediate page reclamation
- Enable kernel audit infrastructure
