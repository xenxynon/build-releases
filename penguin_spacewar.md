***The rom includes dex2oat configuration and will definitely lag post OTA for some mins, so don't behave like ramdi ploxx***


========   Tue, 03 Dec 2024  ========

 - Update system to LA.QSSI.14.0.r1-18600-qssi.0
 - Enable -O3 optimization in surfaceflinger and renderengine and globally
 - Use O3 LTO GC Opt Level when without profile
 - Update dalvik heap for 8gb
 - Move app lock to app list instead of security settings
 - Add statusbar battery styles
 - Disable all bugreport settings
 - Improvements in keyguard affordance shortcuts
 - Improvements in system wide padding
 - Remove folder selection restrictions
 - Make the spinners faster
 - Add animations for some settings page
 - Remove some redundant overlays
 - Fonts: add samsung one, add AlbertSans, add OnePlus Slate, update inter to 4.1
 - Add support for NTFS
 - Disable phantom process monitoring
 - Other miscellaneous changes
 - And yes includes pabji 120 fps spoof

========   Thu, 21 Nov 2024  ========

 - Merged latest CLO tag into source (LA.QSSI.14.0.r1-18200-qssi.0 into system LA.VENDOR.13.2.0.r1-25200-KAILUA.QSSI15.0 in vendor)
 - Updated to November patch
 - Re-enable some launcher flags
 - Explicitly enable ThinLTO and whole
 - Don't include tasks from tests, platform_testing & additional debug information by default
 - Fix keymaster log cat spam due to missing vendor spl property
 - Fix broken download ETA/progress in updater
 - Add /mnt/scratch detection during OTA
 - Fix changelog url in updater
 - Merge latest ACK android11-5.4 branch & msm-5.4 tag into kernel 
 - Merge tag LA.UM.9.14.r1-25000.02-LAHAINA.QSSI14.0 in kernel drivers (teckpack/fw-api/qcald/wifi)
 - Strip various debug infos and verbosity
 - Add dex2oat optimizations
 - Minor translation updates
