# Munch PE Plus ROM Releases

## About -
I am building this PE Plus rom for POCO F4 / Redmi K40s, this will also have some extra features as compared to standard PE Plus. OTA updates are not working for now but you can always update by dirty flashing new build without wiping anything. 

## Instructions to flash -
1. Have unlocked bootloader and be on latest MIUI
2. adb reboot fastboot
4. fastboot flash boot boot.img
5. fastboot flash vendor_boot vendor_boot.img
6. reboot to recovery now
7. wipe data because you are changing rom
8. select adb sideload
9. adb sideload PixelExperience_Plus_munch_xxxxxxx.zip

## Instructions to update for existing PE users -
1. reboot to recovery
2. wipe data because you are changing rom
3. select adb sideload
4. adb sideload PixelExperience_Plus_munch_xxxxxxx.zip

## Downloads -
https://github.com/Umang96/munch_custom_pe_rom_releases/releases
