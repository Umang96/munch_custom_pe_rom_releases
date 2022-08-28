# Munch PE Plus ROM Releases

## About -
I am building this PE Plus rom for POCO F4 / Redmi K40s, this will also have some extra features as compared to standard PE Plus as listed below. OTA updates are not working for now but you can always update by dirty flashing new build without wiping anything. I will try to keep this rom updated.

## Extra Features -
- Schedule reboot, performance slider, cpu governor change dropdown
- Better privacy indicators, charging indicator, cpu info overlay tile
- Both rom and kernel + dt side performance improvements

## Instructions to flash -
1. Have unlocked bootloader
2. adb reboot fastboot
4. fastboot flash boot boot.img
5. fastboot flash vendor_boot vendor_boot.img
6. reboot to recovery now
7. wipe data because you are changing rom
8. select adb sideload
9. adb sideload PixelExperience_Plus_munch_xxxxxxx.zip

## Instructions to update for existing PE users -
1. reboot to recovery
2. select adb sideload
3. adb sideload PixelExperience_Plus_munch_xxxxxxx.zip

## Downloads -
https://github.com/Umang96/munch_custom_pe_rom_releases/releases
