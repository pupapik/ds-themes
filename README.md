# 🎨 ds-themes — Custom Discord Themes Hub

<p align="center">
  <img src="https://i.imgur.com/GxgAYLn.gif" width="100%" alt="Reze Theme Preview">
</p>

![License](https://img.shields.io/github/license/pupapik/ds-themes?style=flat-edge)
![Maintained](https://img.shields.io/badge/maintained-yes-green?style=flat-edge)

Welcome to my personal repository of custom, performance-optimized themes for Discord (optimized for **Vencord** and **BetterDiscord**). Here you can find unique builds, anime-inspired themes, and minimal aesthetics.

All themes in this repository include a built-in **Smart Performance Saver** (Auto-Pause) that freezes heavy background GIFs whenever Discord is out of focus to save your gaming FPS.

---

## 📚 Available Themes / Доступные темы

| Theme Name | Description | Accent Colors | Direct Raw Link |
| :--- | :--- | :--- | :--- |
| **Reze Edition** | Chainsaw Man aesthetic, deep wine/purple colors with a GIF background. | `#4B2C6B`, `#8E4D6E` | [reze.css Link](https://raw.githubusercontent.com/pupapik/ds-themes/main/reze.css) |
| *More coming soon...* | *New themes will be added here.* | *TBD* | *TBD* |

---

## 🚀 Installation & Usage

You can use these themes either by linking them directly or by downloading a lightweight local loader file.

### Method 1: Local Loader File (For Custom Overrides ⚙️)
*Use this method if you want to keep the core theme up-to-date but override specific colors or backgrounds locally.*

1. Create a file named `YourThemeName.theme.css` inside your client's themes folder.
2. Paste the following loader template inside it (example using the Reze theme):
```css
   /**
    * @name Custom Theme Build
    * @author pupapik
    * @version 1.0.0
    * @description Remote engine loader.
    */

   /* Import the remote theme engine from this repo */
   @import url("[https://raw.githubusercontent.com/pupapik/ds-themes/main/reze.css](https://raw.githubusercontent.com/pupapik/ds-themes/main/reze.css)");

   :root {
     /* You can override any specific variables here if you want */
     /* --main-color: #your_color; */
   }



