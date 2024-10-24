# XiaomiParts - WIP

Supported for SM8250 devices
- Mi 10 (UMI)
- Mi 10 Pro (CMI)

## Clone the repo
Clone this repo to your enviroment
   ```bash
   # if . build/envsetup has run
   croot
   git clone https://github.com/TechPanelGM/packages_apps_XiaomiParts.git packages/apps/XiaomiParts
   ```

Add in your device config (lineage_codename.mk)

   ```bash
   #XiaomiParts
   $(call inherit-product, packages/apps/XiaomiParts/config.mk)
   ```
