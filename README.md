# Creality_Mainsail_Themes

Multiple colored Creality themes for Mainsail

**Installation Instructions:**

**IMPORTANT**: Your printer must be rooted and have Mainsail installed

SSH into your printer via software of choice

[Klipper Extruder Settings](#klipper-extruder-settings)

copy the following below and paste into the terminal command line based on the color scheme you wish to use:

# Blue Theme
![image](https://github.com/tlace17/Creality_Mainsail_Themes/assets/55593962/56b49f94-cacf-46bb-a1bc-a2f33640c504)
```
cd /usr/data/printer_data/config/
mkdir .theme
cd /root
git clone https://github.com/tlace17/Creality_Mainsail_Themes.git temp
mv temp/Blue/custom.css /usr/data/printer_data/config/.theme
mv temp/Blue/favicon-16x16.png /usr/data/printer_data/config/.theme
mv temp/Blue/favicon-32x32.png /usr/data/printer_data/config/.theme
mv temp/Blue/sidebar-background.png /usr/data/printer_data/config/.theme
mv temp/Blue/sidebar-logo.svg /usr/data/printer_data/config/.theme
cd /root
rm -rf temp

```

# Red Theme
![image](https://github.com/tlace17/Creality_Mainsail_Themes/assets/55593962/198a9c3a-1f43-4306-bcd2-cfc477621f34)
```
cd /usr/data/printer_data/config/
mkdir .theme
cd /root
git clone https://github.com/tlace17/Creality_Mainsail_Themes.git temp
mv temp/Red/custom.css /usr/data/printer_data/config/.theme
mv temp/Red/favicon-16x16.png /usr/data/printer_data/config/.theme
mv temp/Red/favicon-32x32.png /usr/data/printer_data/config/.theme
mv temp/Red/sidebar-background.png /usr/data/printer_data/config/.theme
mv temp/Red/sidebar-logo.svg /usr/data/printer_data/config/.theme
cd /root
rm -rf temp

```

# Orange Theme
![image](https://github.com/tlace17/Creality_Mainsail_Themes/assets/55593962/c073591c-de91-4828-b402-b3d2b7a95e2d)
```
cd /usr/data/printer_data/config/
mkdir .theme
cd /root
git clone https://github.com/tlace17/Creality_Mainsail_Themes.git temp
mv temp/Orange/custom.css /usr/data/printer_data/config/.theme
mv temp/Orange/favicon-16x16.png /usr/data/printer_data/config/.theme
mv temp/Orange/favicon-32x32.png /usr/data/printer_data/config/.theme
mv temp/Orange/sidebar-background.png /usr/data/printer_data/config/.theme
mv temp/Orange/sidebar-logo.svg /usr/data/printer_data/config/.theme
cd /root
rm -rf temp

```

# Green Theme
![image](https://github.com/tlace17/Creality_Mainsail_Themes/assets/55593962/fd5b8771-e83d-4ddd-86c3-1b70786f7440)
```
cd /usr/data/printer_data/config/
mkdir .theme
cd /root
git clone https://github.com/tlace17/Creality_Mainsail_Themes.git temp
mv temp/Green/custom.css /usr/data/printer_data/config/.theme
mv temp/Green/favicon-16x16.png /usr/data/printer_data/config/.theme
mv temp/Green/favicon-32x32.png /usr/data/printer_data/config/.theme
mv temp/Green/sidebar-background.png /usr/data/printer_data/config/.theme
mv temp/Green/sidebar-logo.svg /usr/data/printer_data/config/.theme
cd /root
rm -rf temp

```
All Done!

## Klipper Extruder Settings

Navigate to your Fluidd Themes section and pick your theme of choice!
