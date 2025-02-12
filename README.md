# Pixel-Prime Theme

<p align="center">
  <img src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/logo.png">
</p>

<div align = center>
  
  ![BUILT WITH](https://img.shields.io/badge/BUILT%20WITH-%E2%9D%A4-cd6133?labelColor=ff793f&style=for-the-badge&logoColor=f0f0f0)
  [![][made-with]][gimp]
  [![Github All Releases](https://img.shields.io/github/downloads/PixeliGer/OPL-Theme-Pixel-Prime/total?style=for-the-badge)]()
  
  [gimp]: https://www.gimp.org/
  [made-with]: https://img.shields.io/badge/gimp-5C5543?style=for-the-badge&logo=gimp&logoColor=white&logoSize=auto&label=Made%20With
  
  
  [![][download-pixel-prime]][pixel-prime]
  
  [pixel-prime]: https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/releases/latest
  [download-pixel-prime]: https://img.shields.io/badge/Download%20🡇-35BF5C?style=for-the-badge
  
</div>

**Pixel Prime** theme for Open PS2 Loader is inspired by the sleek and modern design of Amazon Prime Video, this theme integrates its latest redesigns , offering a clean, minimalist, and visually appealing interface.


<div align = middle>
  <br>
  
  &ensp;[<kbd> <br> Installation <br> </kbd>](#-installation)&ensp;
  &ensp;[<kbd> <br> Features <br> </kbd>](#-features)&ensp;
  &ensp;[<kbd> <br> Screenshots <br> </kbd>](#-screenshots)&ensp;
  &ensp;[<kbd> <br> Recomendations <br> </kbd>](#-recommendations)&ensp;
  &ensp;[<kbd> <br> More Themes <br> </kbd>](https://pixeliger.github.io/opl-themes/)&ensp;
    
  <br>  
</div>


## 🌱 Inspiration

<p align="middle">
  <img width="48%" src="https://tvline.com/wp-content/uploads/2022/07/new-prime-video-ui-1.jpg">
  <img width="48%" src="https://m.media-amazon.com/images/I/B1HVIxbegjL.png">
</p>

## ✨ Features

* Minimalist navigation bars
* Two different styles, icons in the sidebar and top bar.
* Interface with transparencies to show the background of the game.
* Working with HD/Full-HD on 16:9 and 4:3
* Compatible with the latest versions of [Open Ps2 Loader 1.2](https://github.com/ps2homebrew/Open-PS2-Loader/releases)

## 📸 Screenshots

#### Sidebar Icons style

<p align="middle">  
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot1.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot2.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot3.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot4.png">  
</p>

#### Topbar style

<p align="middle">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot5.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot6.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot7.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot8.png">
</p>

#### NEW 🌟 - Topbar (No Logo)
<p align="middle">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot9.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot10.png">
</p>

#### NEW 🌟 - **Accent** Variants
<p align="middle">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot11.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot12.png">
  
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot13.png">
  <img width="48%" src="https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/blob/main/assets/screenshots/screenshot14.png">
</p>


## 💾 Installation

**1. Initially, ensure your OPL folder is structured like this on your Device or in your Shared folder**
```
APPS/
ART/
CD/
CFG/
CHT/
DVD/
POPS/
THM/
VMC/
```

**2. Download one of the zip files that contains one of the Theme variants from the [Releases](https://github.com/PixeliGer/OPL-Theme-Pixel-Prime/releases/latest) page or using the green `DOWNLOAD` button at the top, (make sure it's one with the `thm_` prefix in its name)**
```
thm_Pixel-Prime
thm_Pixel-Prime-Top
thm_Pixel-Prime-Accent
```

**3. Extract the ZIP file and move the theme folder to your `THM` directory.**
```
THM/
├─ thm_Pixel-Prime/
├─ thm_Pixel-Prime-Top/
├─ thm_Pixel-Prime-Accent/
```

> [!NOTE]  
> Themes must be placed inside a folder named `THM` (in uppercase) for any of the devices: SMB share, HDD, USB, SD (MX4SIO), once the device starts, OPL will list the themes found in these locations

* **SMB** (Network Share)

In the root directory or drive you set as your PS2SMB share, in a THM folder

```
PS2SMB/THM/thm_Pixel-Prime/
```

* **USB**, **SD** device

In the root of the drive or partition set for OPL, in a THM folder

```
mass:/THM/thm_Pixel-Prime/
```

* **HDD** (Internal hard drive)

Place the THM folder in the `OPL Partition` of the HDD `+OPL`, you can create the partition if it doesn't exist, by using `uLaunchELF`: [FileBrowser > MISC > HddManager]

```
hdd0:/+OPL/THM/thm_Pixel-Prime/
```

> [!IMPORTANT]  
> Themes on any of these devices won’t display unless the device is enabled, so make sure to enable the device where your themes are stored through the OPL settings.

> [!WARNING]
> Avoid installing themes on the Memory Card, as their storage size can impact the proper functioning of the themes and cause issues with OPL.


**4. Launch OPL, if it was already open, restart it.**

**5. Go to OPL Settings and then `Display Settings`. In the 'Theme' option, find and select your theme, then click `OK` to apply it.**


## 💡 Recommendations

To enhance your experience with the theme, consider these recommendations:

* Make sure you are using an updated or recent version of [Open Ps2 Loader 1.2](https://github.com/ps2homebrew/Open-PS2-Loader/releases/tag/latest)
* Download the assets for the `ART` folder (Background Image, Cover, Logo, etc.) using the latest version of [OPL Manager](https://oplmanager.com/site/)
* Use **OPL Manager** to edit the `CFG` files for each game, to correctly display the game information (Description, Developer, Release Date, etc.).
* Use `MM-DD-YYYY` format for the release date in the Information section for optimal display.
* Enable Widescreen mode in OPL Settings for better text visibility.


