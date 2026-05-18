# Xiaomi Redmi 12 4G KSU Kernel
Custom kernel for Xiaomi Redmi 12 4G (fire) featuring integrated KernelSU and path_umount backport fix for pre-GKI module hiding.

# Instructions
You can either download the pre-compiled boot.img or flash the Kernel via TWRP/OrangeFox recovery.

# Method 1: Installation via Fastboot
Reboot your device into Fastboot Mode using your phone's hardware button combinations.

Connect your phone to your PC and execute the following commands in your terminal:

fastboot flash boot ksuboot.img
fastboot reboot

# Method 2: Installation via TWRP / OrangeFox
Reboot your device into Recovery Mode.

Go to Install, select the downloaded Kernel zip file, and swipe to flash.

Reboot your system.

# Post-Installation (Crucial Step)
After flashing the kernel using either method, you must download and install the specific KernelSU Manager App (v0.9.5), which is the latest supported version for the Redmi 12 4G:

Download KernelSU Manager v0.9.5 from GitHub releases: https://github.com/tiann/KernelSU/releases/tag/v0.9.5

Once installed, open the manager and your good to go!

# Credits & Acknowledgements
A huge thanks to the developers and the open-source community who made this project possible:

xxblebleblexx - For the amazing android_kernel_xiaomi_fire base kernel source tree. (https://github.com/xxblebleblexx/android_kernel_xiaomi_fire)

osm0sis - For the legendary AnyKernel3 deployment template. (https://github.com/osm0sis/AnyKernel3)

tiann - For the Kernel based root solution. (https://github.com/tiann/KernelSU)

Xiaomi Developers - For providing the original kernel source codes.

HUGE THANKS TO YOU ALL!
