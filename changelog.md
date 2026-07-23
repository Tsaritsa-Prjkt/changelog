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
- Patch libwfdservice to load android.media.audio.common.types-V5-cpp
- Patch libwfdmmsrc_system with libgui_shim
- Add libaudiobase dependency to libwfdmmsrc_system
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
