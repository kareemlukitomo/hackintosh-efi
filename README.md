# hackintosh-efi

## Hardware Specification
* CPU: Ryzen 9 5900x 12-core 24-thread
* Motherboard: [B550 Phantom Gaming 4 ATX](https://www.asrock.com/mb/AMD/B550%20Phantom%20Gaming%204/)
* GPU: [Gigabyte AORUS Radeon RX 5700 XT 8GB](https://www.gigabyte.com/id/Graphics-Card/GV-R57XTAORUS-8GD-rev-10#kf)
* RAM: Corsair Vengeance LPX 32 GB (2x16) DDR4-2666 CL16
* CPU cooler: ARCTIC Liquid Freezer II 280
* Storage:
  * (Hackintosh + EFI) Samsung 970 Evo Plus 1 TB NVME SSD
  * (Windows 10) Samsung 970 Evo Plus 1 TB NVME SSD
  * Seagate SkyHawk Surveillance 3 TB 3.5" 5900 RPM HDD

## Software Specification
* Opencore: Still using version [0.8.4 (Sep 5th)](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.8.4)
* SMBIOS: MacPro7,1
* macOS: 11.6.8 Big Sur

## What's Working
* Wi-Fi (plug-n-play thanks to Fenvi T919)
  - [x] Airdrop
  - [ ] Handoff (haven't test, should be ok)
  - [ ] Continuity (haven't test, should be ok)
* Bluetooth (plug-n-play thanks to Fenvi T919)
* Sound (using external USB DAC: Fiio E10k USB)
* Docker* (must use VirtualBox/minikube runtime, following [this guide](https://gist.github.com/slykar/e92732be9bf81a71e08068245656d70e?permalink_comment_id=4105556#gistcomment-4105556))

## What's Not Working
* Android Virtual Device/emulator from Android Studio
* Sidecar (the setting is clickable, but always fail to connect)

## To-Dos
- [ ] Update to [OpenCore 0.8.6 (Nov 7th)](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.8.6)
- [ ] Update to macOS 13.0 Ventura
- [ ] Find a workaround to run Android emulator on Ryzentosh (maybe using Genymotion etc)