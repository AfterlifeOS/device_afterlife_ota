# Poco F3 (Alioth)
## Version - **8.4-Ophelia**
### **Build date** - 15 April 2026
- props: Do not use phase offsets as duration
- Enable small battery configuration
- Disable QCOM system daemon
- sepolicy: Enable ntsync sepolicy rules
- Sync kernel to xiaomi_sm8250_kernel_e404 latest
- Overlays: Also Build AOSP-default color modes
- Overlays: Switch to vendor-defined color modes
- Disable logging sensors-hal events
- props: Enable ro.audio.monitorRotation
- sepolicy: Allow zygote to access unix_stream_socket
- sepolicy: Allow untrusted_app to getopt zygote
- Back to GPU Driver from HyperOS munch V816.0.9.0.ULMMIXM
- Update blobs from pipa OS2.0.14.0.UMZMIXM
- Sync kernel to xiaomi_sm8250_kernel_e404 latest
- Dropped Spoof BuildFingerprint as Pixel Beta and back to HyperOS BuildFingerprint

## Version - **8.3-lastblood**
### **Build date** - 28 February 2026
- Allow mi_thermald read/write access to HBM sysfs
- Properly disable phantom process killing
- init: Give proper permissions for /dev/diag
- props: enable_camera_smooth
- Fix touch thermal profile cant turned on
- Uprev vendor.qti.hardware.bluetooth_audio to 2.1
- Allow toolbox to manage resourcecache_data_file
- Import 64 bit vendor.qti.hardware.bluetooth_audio@2.1-impl.so
- Enable QCRIL radio power saving
- Add Gryphline games to unity boosting
- Disable GPU protected composition
- Limit dex2oat cpu utilization
- Disable WiFi Multi-STA
- Update some Prebuilts from HyperOS 1.0.5.0 Mi
- Disable MTE on system_server and apps
- Override kernel BPF version
- wifi: Add parameters for Hotspot 2.0
- Allow devicesettings_app to access LiveDisplay tuneables
- Label expressive design and skia renderthread properties
- Allow vendor_init to tune kernel scheduler interfaces
- Label libgpudataproducer.so to address denial
---

## Version - **8.2 Serenity (HOTFIX)**
### **Build date** - 24 December 2025
- Increase SurfaceFlinger idle and touch timers
- Address sepolicy denial for NFC
- powerhint: boost GPU freq during interaction
- Provide thermal profile permissions
- Restore default swappiness parameters
- Add New HBM, DC Dimming. Gmaebar. Refrest Rate UI
- Configure high touch sampling rate nodes
- FIXED NFC and Microphone Issue
---

## Version - **8.2 Serenity**
### **Build date** - 12 December 2025
- Update blobs from alioth 1.0.10.0 TKHCNXM
- Implement New DC Dimming, HBM & Auto HBM
- Remove redundant mlock() limit setting
- Implement startup service to restore Saturation Setting
- Add missing Dirac prefernce strings
- Gamebar: Revamp per-app config UI with search and new layout
- Address some binder call denials to system_app
- Allow audio hal to get boot_status prop
- Set wide color display prop to false
- Add MLBB and MCGG to sched_lib_name
- Configure high touch sampling rate nodes
- Uprev vendor.qti.hardware.bluetooth_audio to 2.1
- Switch to vendor-defined color modes
- Enable QS media player turbulence effect
- Fixed 48mp camera in leica camera
- Fix microphone issue
---

## Version - **8.1 Happiness**
### **Build date** - 20 November 2025
- Fix Developer Option crash
- Enable Lineage Health service
- Enabe Battery Health
- Enhance LE Audio and voice codec configurations
- Opt out of speaker_layout_channel_mask field
- Revert "sm8250-common: Move to Xiaomi IR AIDL"
- Add a property to enable prefetching video