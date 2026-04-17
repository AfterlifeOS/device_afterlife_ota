# Redmi 11 Prime / POCO M5 (rock)

## Version - **8.4 Ophelia**
## **Build date** - 17 April 2026
- Welcome Afterlify

Perf / Memory
- increase thrashing limits and PSI thresholds
- set zram size to 95% of RAM
- set heap size to 6GB
- add performance tuning (ADPF + powerhal)
- cleanup and move vendor properties
- drop unused properties
- drop redundant runtime properties
- drop persistent native USAP

HWUI
- tune scheduler phase durations
- set max screen recorder framerate to 60FPS
- configure peak refresh rate
- enable fading marquee
- fix stay_on_while_plugged_in behavior

Connectivity
- enable SIM hot swap support
- use 4G icon for LTE by default
- use lib_driver_cmd_mt66xx
- build MTK WiFi lib and enable OUI support
- set all supported HAL interface combinations
- switch HAL interface to AP_BRIDGED

Codec / Media(C2)
- switch to AIDL Codec2
- use source-built Codec2 service
- bring back legacy audio policy for Hi-Res support
- enable MediaTek thumbnail optimization
- Use DOLBY aospa by default

Misc
- re-enable vendor_dlkm support
- drop duplicate wakeup label
- extend camera rules
- allow hal_fingerprint read sysfs_wakeup
- import game manager configuration