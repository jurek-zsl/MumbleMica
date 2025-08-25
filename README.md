# 🥽 Acrylic / Mica Theme for Mumble

This is a custom **Windows 11 Acrylic/Mica inspired theme** for the [Mumble client](https://www.mumble.info/).  
It uses **Qt Stylesheets (QSS)** with semi-transparent backgrounds, which allows tools like [MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone) to apply **blurred Acrylic/Mica effects**.

---

## ℹ️ Features
- Windows 11 **Mica/Acrylic style** with semi-transparent UI.  
- Rounded corners, modern spacing, and Fluent Design colors.  
- Styled menus, buttons, input fields, channel list, scrollbars, etc.  
- Works with **dark mode** and lets the system background shine through.  

---

> [!NOTE]
> MumbleMica only works with MicaForEveryone, no other apps have been tested (without MicaForEveryone theme wouldn't work).

> [!WARNING]  
> This is a prototype, some features might not work or not look like they should to.

## 📩 Installation

### 1. Download
1. Clone this repo or download it as a ZIP:
```bash
git clone https://github.com/jurek-zsl/MumbleMica
```
2. Download MicaForEveryone from [Microsoft Store](https://apps.microsoft.com/detail/9p8v68p4z78p?hl=en-US&gl=PL)
### 2. Installing
Copy or move `MumbleMica` folder into `%APPDATA%\Mumble\Mumble\themes\`.
It should look something like this: 
```bash
Mumble/
 └── themes/
      └── MumbleMica/
           └── AcrylicTheme.qss
```
### 3. Configuring
1. Enabling Theme in Mumble
   - Open Mumble -> Settings -> User Interface -> In `Theme` choose `AcrylicTheme - Acrylic`
2. Enable MicaForEveryone
   - Open MicaForEveryone -> Add new rule -> Add proccess rule -> Search for `mumble` -> Change `Backdrop type` to `None` -> Enable both switches in Advanced
   - Open MicaForEveryone -> Select `Global` -> Inside change `Backdrop type` to `Acrylic`
### Done! Enjoy your new theme.

## 🌟 Star the Project

If you find MumbleMica Theme good looking, please consider giving it a star on GitHub to help others discover it!

## 🖼️ Preview
![Preview image of the theme](https://ohiofiles.live/c78cbe.png)
