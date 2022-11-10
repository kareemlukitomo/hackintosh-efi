# hackintosh-efi

## Specification
* CPU: Ryzen 9 5900x
* Motherboard: Ryzen 9 5900x
* GPU: Gigabyte AORUS Radeon RX 5700 XT 8GB
* RAM: Corsair Vengeance LPX 32 GB (2x16) DDR4-2666 CL16
* CPU cooler: ARCTIC Liquid Freezer II 280
* Storage:
  * (Hackintosh + EFI) Samsung 970 Evo Plus 1 TB NVME SSD
  * (Windows 10) Samsung 970 Evo Plus 1 TB NVME SSD
  * Seagate SkyHawk Surveillance 3 TB 3.5" 5900 RPM HDD

## What's Working
* Wi-Fi (plug-n-play thanks to Fenvi T919)
* Bluetooth (plug-n-play thanks to Fenvi T919)
* Sound (using Fiio E10k USB DAC)
* Docker* (must use VirtualBox/minikube runtime, following [this guide](https://gist.github.com/slykar/e92732be9bf81a71e08068245656d70e?permalink_comment_id=4105556#gistcomment-4105556))

## What's Not Working
* Android Virtual Device/emulator from Android Studio
* Sidecar (the setting is clickable, but always fail to connect)