

This ReVanced/Morphe builder creates only apks for rootless devices [Offical ReVanced](https://github.com/ReVanced), [Dropped ReVanced Patches](https://github.com/indrastorms/Dropped-Patches) [ReVanced Extended by anddea](https://github.com/anddea/revanced-patches), and [Morphe](https://github.com/MorpheApp) versions of YouTube and YouTube Music.

#### **Get the latest CI release [here](https://github.com/peternmuller/revanced-morphe-builder/releases/latest)!**

## Installation
### Non-root users
- Install the [ReVanced GmsCore app](https://github.com/ReVanced/GmsCore/releases/latest) or the [Morphe MicroG-RE app](https://github.com/MorpheApp/MicroG-RE).
- Download the APK files you want to install from the [releases page](https://github.com/peternmuller/revanced-morphe-builder/releases/latest), or follow the installation steps [here](https://github.com/peternmuller/revanced-morphe-builder?tab=readme-ov-file#easily-install-or-update-revancedmorphe-apps-with-obtainium).
- (Optional) Import [one of my custom settings files](https://github.com/peternmuller/revanced-morphe-builder/tree/main/custom-settings) into your application. [*How to do this?*](https://github.com/peternmuller/revanced-morphe-builder?tab=readme-ov-file#import-custom-settings-in-revancedmorphe-applications)
- Enjoy!


## Easily install or update ReVanced/Morphe apps with Obtainium
You can easily install or keep your ReVanced/Morphe apps up to date by using [Obtainium](https://github.com/ImranR98/Obtainium), which lets you install and update apps directly from the source and receive notifications when new releases are available.

#### Here is a quick tutorial on how to add them to Obtainium:

<img width="2160" alt="obtainium_quick_tutorial" src="https://github.com/user-attachments/assets/345e0536-529e-4f64-8b0b-ab44ca9e285d">

> [!NOTE]
> In step 3, you need to enter the regular expression that corresponds to the application you want to install:
> - YouTube ReVanced: `youtube-revanced-v`
> - YouTube Music ReVanced: `yt-music-revanced-v`
> - YouTube ReVanced anddea: `youtube-revanced-anddea`
> - YouTube Music ReVanced anddea: `yt-music-revanced-anddea`
> - YouTube Morphe: `youtube-morphe`
> - YouTube Music Morphe: `yt-music-morphe`
> - FX: `fx-revanced`


## Building Locally
### On Termux
```bash
bash <(curl -sSf https://raw.githubusercontent.com/peternmuller/revanced-morphe-builder/main/build-termux.sh)
```
### On Desktop
```bash
git clone https://github.com/peternmuller/revanced-morphe-builder
cd revanced-morphe-builder
./build.sh
```

## Credits
- [j-hc](https://github.com/j-hc) for creating this amazing builder.
- [Kevinr99089](https://github.com/kevinr99089) for providing assistance with the builder.
- And of course, the [ReVanced](https://github.com/ReVanced) team, [anddea](https://github.com/anddea), and the [Morphe](https://github.com/MorpheApp) team for their work on the ReVanced/Morphe apps!
- [peternmuller](https://github.com/peternmuller) for providing this repo to build on.

## License
    Copyright (C) 2024-2026 

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <https://www.gnu.org/licenses/>.
