# Poco F4 (Munch)

## Version - **8.3 Lastblood**
### **Build date** - 05 March 2025
- Rebase Whole trees
- Use Oxygen+ Kernel
- Use Lunaris DOLBY
- BPF kernel
- Set BOARD_USES_ADRENO to true  * libc2dconvert wont be included unless this is set
- sepolicy: Allow toolbox to manage resourcecache_data_file
- vintf: Uprev vendor.qti.hardware.bluetooth_audio to 2.1
- Import 64 bit vendor.qti.hardware.bluetooth_audio@2.1-impl.so
- overlay: Add overlay to improve signal reception
- Enable new network selection UI
- overlay: Disable global mode and CDMA choices
- overlay: Enable VoNR on Jio 5G
- overlay: Only allow 5G SA on Jio
- overlay: Enable ViLTE & hide IMS APN
- overlay: Don't let any carrier default WFC mode to `IMS Preferred`
- overlay: Make WiFi Calling preference editable globally
- Overlay: Enable vonr for Airtel and Jio
- overlay: Enable IMS feature flags for supported carriers available      
- overlay: Set LTE+ threshold bandwidth to 0 * so LTE+ icon will show whenever it's available        
- parts: Improve hbm & dcdimming UI state synchronization
- parts: Add option to disable hbm when screen off
- parts: Disable Auto BrightnessMode when HBM on

## Version - **8.2 Serenity**
### **Build date** - 12 December 2025
- Drop SSR blobs and set SSR restart_level in init.xiaomi.rc
- Drop BCR
- Enable QTI Memory Optimization
- Enable AOSP surfaceflinger
- Import display config from HyperOS
- Opt out of speaker_layout_channel_mask field
- parts: SettingsFragment: Defer applying divider
- parts: Adapt to Material 3 Expressive design
- parts: fix dirac and touch profile cant turned on
- prop: Add a property to enable prefetching video
- prop: use_smooth_motion
- Update sepolicy
- Use hardware/xiaomi FCM
- Update WFD system blobs from dada OS2.0.217.0.WOCMIXM
---

## Version - **8.1 Happiness**
### **Build date** - 20 November 2025
- Initial Build
- Firmware Included
- KernelSU + SUSFS 1.5.5
- Leica Camera
- Dolby Atmos