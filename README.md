# LineageOS Build for Tecno LJ6 (POVA 7 4G)

Automated build workflow for LineageOS on Tecno LJ6 (MT6789).

## Usage

1. Go to **Actions** → **Build LineageOS for LJ6**
2. Click **Run workflow**
3. Pilih branch dan build type
4. Wait ~3-5 hours, download artifacts when done

Repos sudah di-hardcode:
- Device tree: https://github.com/bradarwhatisdis/android_device_tecno_LJ6
- Vendor tree: https://github.com/bradarwhatisdis/android_vendor_tecno_LJ6
- Vendor common: https://github.com/bradarwhatisdis/android_vendor_tecno_mt6789-common

## Build Output

Artifacts include:
- `lineage-*.zip` — flashable ROM
- `boot.img`, `dtbo.img` — boot images
- `vbmeta*.img` — verification metadata
