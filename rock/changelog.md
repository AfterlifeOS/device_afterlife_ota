# Redmi 11 Prime / POCO M5 (rock)

## Version - **8.3 LastBlood**
## **Build date** - 08 March 2026
- Welcome Afterlify

Audio
- Add MTK Bessound Aurisys scenarios
- Map MiSound to MTK Bessound
- import dolby lunaris oss thx @yuki_millennium MillenniumOSS stuff

Memory
- Tune kill parameters
- Disable LMK minfree levels
- Set filecache min threshold to 300MB
- Mark device as non low-ram
- Silence stats logging
- Move LMKD props to product properties
- Remove home app OOM adj override

HWUI
- Enable battery percentage by default
- Reduce QS top padding (80dp → 45dp)
- Add display color mode overlay
- Enable color transform accelerated flag
- Update quick charge indicator path
- Mark composer as not supporting color transform (GPU fallback)
- Configure MTK PQ props from HyperOS stack
- Move purgeable assets prop to display category
- Drop DFPS level prop

Features Flags
- Import freeform window flags
- Import software device ID attestation flags
- Import software verified boot flags

SEPolicy
- Allow vendor_init set Netflix props
- Allow vendor_init set MTK manager props
- Allow vendor_init read powerctl props
- Allow vendor_init set camera props
- Allow power HAL find thermal service

Misc
- Bypass NVT edge reject gesture via Power HAL
- Fix init service race condition
- Import Dolby permission (PACKAGE_USAGE_STATS)
- Set Zygote critical crash window to 10m

## Version - **8.4 Ophelia**
## **Build date** - 17 April 2026

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

