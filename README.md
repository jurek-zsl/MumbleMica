# Acrylic / Mica Theme for Mumble

This is a custom **Windows 11 Acrylic/Mica inspired theme** for the [Mumble client](https://www.mumble.info/).  
It uses **Qt Stylesheets (QSS)** with semi-transparent backgrounds, which allows tools like [MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone) to apply **blurred Acrylic/Mica effects**.

---

## Features
- Windows 11 **Mica/Acrylic style** with semi-transparent UI.  
- Rounded corners, modern spacing, and Fluent Design colors.  
- Styled menus, buttons, input fields, channel list, scrollbars, etc.  
- Works with **dark mode** and lets the system background shine through.  

---

## Installation

> [!WARNING]  
> This is a prototype, some features might not work or not look like they should to.

### 1. Download
Clone this repo or download it as a ZIP:
```bash
git clone https://github.com/jurek-zsl/MumbleMica
```
Download MicaForEveryone from [Microsoft Store](https://apps.microsoft.com/detail/9p8v68p4z78p?hl=en-US&gl=PL)
### 2. Installing
Copy or move `MumbleMica` folder into `%APPDATA%\Mumble\Mumble\themes\`.
It should look something like this: 
```bash
Mumble/
 └── themes/
      └── MumbleTheme/
           └── AcrylicTheme.qss
```
### 3. Configuring
1. Enabling Theme in Mumble
   - Open Mumble -> Settings -> User Interface -> Choose `MumbleMica - AcrylicTheme`
2. Enable MicaForEveryone
   - Open MicaForEveryone -> Add new rule -> Add proccess rule -> Search for `mumble` -> Change `Backdrop type` to Acrylic or Mica -> Enable both switches in Advanced
### Done! Enjoy your new theme.

## Preview
![Preview image of the theme](https://ohiofiles.live/cd613c.png)
