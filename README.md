# Android device tree for oplus vitamin (ossi)

# Clone
    git clone https://github.com/MFO-STAGING/android_device_oppo_vitamin.git -b staging device/oplus/vitamin

# Build
    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_vitamin-eng; mka vendorbootimage
