# Vivaldi Arc

My attempt at customizing [Vivaldi](https://vivaldi.com) to look &amp; feel like [Arc Browser](https://arc.net)

# Screenshots

![1](https://github.com/monkedevlife/vivaldi-arc/blob/main/screenshots/1.png)
![2](https://github.com/monkedevlife/vivaldi-arc/blob/main/screenshots/2.png)
![3](https://github.com/monkedevlife/vivaldi-arc/blob/main/screenshots/3.png)

1. It is essentially changing the appearance using the Vivaldi browser’s "Custom UI Moditifcations" feature
2. This configuration also works on Windows. When setting the shortcut keys, simply replace `Command` with `Ctrl`
3. If you want to return to the default theme, you remove the file path in the "Custom UI Moditifcations" input

---

## 🛠️ Setup Steps：

### 1. Install Vivaldi Browser

- Install [Vivaldi](https://vivaldi.com) browser

### 2. Open Vivaldi Settings

> During the setup process, you can search for keywords in the upper left corner of the "Settings" page to quickly find them

**Must-haves**

- **Tabs** > Tab bar position > `Left`
- **Address Bar** > `Uncheck 'Show Address Bar'`
- **Keyboard** (Set the necessary keyboard shortcuts)
  - Address Bar > `Command + B` (Remove Booksmarks shortcuts first in Windows)
- **Additional Scrollbar Configuration for Windows Users**: As the default Windows scrollbar is quite prominent and somewhat unattractive, we require an extra tweak to optimize its appearance. Here's how to do it:
  - Enter this in the address bar: `chrome://flags``
  - Search keyword `fluent` and enable something like `Fluent scrollbars`，than you'll have a more subtle scrollbar.

**Nice-to-haves**

- **Appearance** > Status Bar > `Status Info Overlay`
- **Panel** > Panel Options > `Check 'Floating Panel'`
- **Quick Commands** > `Check 'Open Links In New Tab'`
- **Keyboard** (Set the necessary keyboard shortcuts)
  - New Tab > Remove it
  - Quick Command > `Command + T`
  - Save Page As > Remove it
  - Tab Bar > `Command + S`
  - Create Bookmark > Remove it
  - Pin / Unpin Tab > `Command + D`
  - Print > Remove it
  - Panel > `Comand + P`

### 3. Custom UI Modifications

- [Download the repo as .zip](https://github.com/monkedevlife/vivaldi-arc), extract it to anywhere safe on your PC
- You can use this theme as a base [Arc Dark Pure OLED][https://themes.vivaldi.net/themes/okQlZoWWvDX] or use the themes in `themes`
- Open `vivaldi://experiments` and enable `"Allow for using CSS modifications"`
- Open Settings > Appearance > Custom UI Modifications
- Select the folder where you've extracted the .zip above
- Restart Vivaldi

# Thanks and Inspried by:

- https://github.com/tovifun/VivalArc (Overall Arc theming)
- https://github.com/wokhan/Misc (AutoHiding)
