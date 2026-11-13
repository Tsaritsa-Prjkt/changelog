# Changelog 13/11/2026
- rootdir: Remove duplicate fingerprint node declarations
- overlay: Use stock signal strength thresholds
- Build LiveDisplay AIDL HAL
- Fix seccomp policy for imsrtp
- parts: Implement VPP Picture Engine
- Patch vpp.configstore.xml to enable VPP
- Sync to latest kernel qcom-sm8250

# Changelog 07/11/2026
- fstab: Drop AVB keys
- Drop BOARD_MOVE_GSI_AVB_KEYS_TO_VENDOR_BOOT
- Match hotword grants to bundled enrollment apps
- media: Advertise Dolby Vision on AVC/HEVC decoders
- Switch audio HAL to V7
- dolby: Switch to compact navbar design
- dolby: Fix floating navbar width
- Sync Latest kernel to qcom-sm8250
- Declare format profiles for bluetooth 7.0 policy

# Changelog 20/10/2026
- overlay: Set IWLAN data service package name
- sepolicy: Allow init to mount the public FastRPC shell copy
- media: Advertise Dolby Vision on AVC/HEVC decoders
- audio: Update Dolby Spatial Audio
- parts: add icon for hi-fi toggle inside dirac
- parts: Adapt Material U design in some configs
- parts: add bypass charging toggle
- dolby: Remove Head Tracking
- dolby: Link source build AIDL dependencies with vendor.dolby.media.c2@1.0-service
- dolby: Link source build AIDL dependencies with dolby vision
- dolby: sepolicy: Add platform_app_36 rules where is possible
- dolby: sepolicy: Add AIDL rules
- dolby: Link Dolby vision stack with AIDL prebuilts
- dolby: Import AIDL prebuilts and Link with c2 Dolby
- dolby: Link libswdap and libdlbvol with libspatializerparamstorage
- dolby: Move Spatial props to system_ext
- dolby: Enable volume leveler for Dynamic profile
- dolby: Update Dolby volume listener stack
- dolby: Add Standalone Dolby Spatial Audio support
- LunarisDolby: Redesign UI with expressive typography
- overlay: Enable min & peak refresh rate toggle in Settings
- Update munch camera properties

# Changelog 22/09/2026
- increase audio offload buffer size from 32KB to 64KB

# Changelog 10/09/2026
- Update blobs from munch OS1.0.12.0.ULMMIXM
- Revert "sm8250-common: remove OMX"
- props: Drop c2 input surface
- Use HyperOS poweroff charging animation
- parts: harden MiSound and audio effect lifecycle
- audio: Fix dynamic USB channel mask declarations
- Enable speaker protection
- sepolicy: Add rule for qtidataservices_app
- dolby: Redesign UI with Material 3 Expressive colors
- dolby: Add per-band fine tuner to equalizer
- dolby: Add AutoEQ headphone correction profiles contributor entry
- dolby: Add persian translations
- dolby: Redesign main card banner with Dolby logo
- dolby: fix headphone surround slider stuck at 35
- dolby: Simplify translation contributor definitions
- dolby: Add stacked animated avatars with multi-contributor support
- dolby: Fetch contributor profile pictures from GitHub
- dolby: Use 2-column grid for translation contributors
- dolby: Add callout to contribute translations in Credits dialog
- dolby: Add translation contributors to Credits dialog

# Changelog 02/09/2026
- init: Set media XML codecs variant to _kona
- overlay: Drop deprecated config_dynamic_bind_ims
- wlan: Disable RX wakelock feature
- overlay: Don't let any carrier default WFC mode to IMS Preferred
- Use foreground cpuset/uclamp for gralloc
- Use foreground uclamp for hwcomposer
- Move runtime cpuset configuration after post_boot completed
- Set dex2oat thread count and cpuset
- Do not allow foreground tasks to run on CPU7
- overlay: Use the new auto network selection UI
- overlay: Set max network scan search time to 254
- overlay: Overlay the config_network_selection_list_aggregation_enabled
- switch to Kawase2 render engine blur algorithm

# Changelog 20/08/2026
- Fix mic issues in apps like WhatsApp
- Fix low max volume in speakers
- rootdir: Add HTSR property handlers
- rootdir: Set correct permission for ntsync
- Set default_network to 33 for 5G

# Changelog 14/08/2026
- Apply Dolby profiles only to compatible audio routes.
- Sync kernel from latest https://github.com/LineageOS/android_kernel_qcom_sm8250

# Changelog 10/08/2026
- Fix Keyguard issue
- sepolicy: Grant tee access to vendor gatekeeper data
- Enable speaker protection

# Changelog 24/07/2026
- Update Xiaomi Parts icon
- Define proper dimensions for the keyguard indication
- Import 32bit adsp/cdsp default listener libs
- DSPVolumeSynchronizer: Fix boot receiver and service lifecycle
- dolby: Implement AutoEQ headphone correction profiles
- dolby: Use CLICK haptic instead of DOUBLE_CLICK
- dolby: Implement swipe navigation between main screens
- hardware/xiaomi: Mark setTouchMode as void
- vintf: Add HIDL NFC to FCM

# Android 17 Changes
- Drop no longer used TARGET_KERNEL_NO_GCC
- Update WFD system blobs from marvel_g A171WEH.20
- Drop UFFD flag
- fastbootd is now enabled by default
- Use Clang r563880c for kernel build
- overlay: Add webview pinning
- Use legacy libion implementation
- power-libperfmgr: Update included soong namespaces
- Build libperfmgr for Lineage Power Service
- Remove disable_configstore from PRODUCT_PACKAGES

----------------------------------------------------------------

# Changelog 04/07/2026
- Rebase tree
- dolby: Patch libdolbyvision.so to allocate GraphicBuffer with new size
- dolby: Switch to Newer Standalone Dolby Vision Stack taken from A16
- dolby: Add Dolby vision Service support
- dolby: sepolicy: Initial rules for DVS
- dolby: Check and dismiss notification listener card if perm granted
- video: enable linear color format for encoder
- dolby: sepolicy: Rewrite dolby rules
- merge kernel from lineage qcom_sm8250
