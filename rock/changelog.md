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
