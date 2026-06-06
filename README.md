# LineageOS Build for Tecno LJ6 (POVA 7 4G)

Automated build workflow for LineageOS on Tecno LJ6 (MT6789).

## Usage

1. Push device tree, vendor, and kernel to your GitHub repos
2. Go to **Actions** → **Build LineageOS for LJ6**
3. Click **Run workflow**
4. Fill in:
   - `device_tree_url`: your device tree repo URL
   - `lineage_branch`: `lineage-22.2` (Android 15)
   - `vendor_tree_url` and `kernel_tree_url`: optional
5. Wait ~3-5 hours, download artifacts when done

## Build Output

Artifacts include:
- `lineage-*.zip` — flashable ROM
- `boot.img`, `dtbo.img` — boot images
- `vbmeta*.img` — verification metadata
