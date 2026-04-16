# Redmi Note 14 4G (Tanzanite)
## Version - **8.4-Ophelia**
### **Build date** - 15 April 2026
- Sync RCU settings
- sepolicy: address vendor_init sysfs denials
- init: disable multiple kswapd threads
- init: match cpuset with Pixel layout
- Allow games to use 120fps
- rootdir: Drop ext4 fstab entries of dynamic partitions
- Force to use EROFS
- rootdir: Set auto for mmcblk0p1
- sepolicy: Allow recovery to read and write exfat partitions
- sepolicy: Allow recovery to read sysfs to get mmc type
- rootdir: Add entry for mounting sdcard in recovery
- Bump vulkan to 1.3
- Bump opengl, vulkan deqp level to 2024-03-01
- Upgrade mali blobs to latest blobs gpu 1.3
- overlay: Update multiple vibration strength levels overlay for 13
- overlay: Enable vibration intensity control
- Disable memcg
- Disable kmem cgroup accounting
- Set PELT HALFLIFE to 8ms before early init boot stage
- Explicitly set log_buf_len
- Set product marketname properly

## Version - **8.3-lastblood**
### **Build date** - 28 February 2026
- Initial Release Android 16 QPR2
- tanzanite: Set ro.config.vc_call_vol_steps to 11
- Import activity open/close animations
- audio: improve mute duration
- Add Opt out of speaker_layout_channel_mask field
- Add some popular game packages to sched_lib_name
- Enable ScrollOptimizer
- Build DSPVolumeSynchronizer
- Import volumes audio policy from raven
- fixup! tanzanite: wifi: Use lib_driver_cmd_mt66xx
- Patch some blobs to depend on libtinyxml2-v34.so
- Add com.android.bluetooth context to seapp_contexts
- Update blobs and firmware from OS2.0.212.0.VOGEUXM
- Move to Lunaris Dolby

## Version - **8.2 Serenity**
### **Build date** - 28 December 2025
- Switch to Mahiru Kernel Vanila (no ksu)
- tanzanite: disable sf blur support
- Revert "tanzanite: Switch to common MediaTek ConsumerIR service"
- tanzanite: move to common mediatek ims
- tanzanite: Address system_server sepolicy
- tanzanite: uprev blobs to OS2.0.209.0.VOGEUXM
- (hotfix) deepsleep already working fine
---

## Version - **8.1 Happiness**
### **Build date** - 11 November 2025
- Initial afterlife Android 16 Release
- KSUN + SUSFS Already included
