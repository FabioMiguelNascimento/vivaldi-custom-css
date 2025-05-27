# Vivaldi Mods

Custom CSS tweaks for a more modern and sleek Vivaldi experience — including a hover-expandable tab sidebar and a redesigned quick search.

## ⚠️ Disclaimer

These modifications involve editing Vivaldi's internal files. Proceed at your own risk. Future browser updates may override your changes or break compatibility.

---

## 🔧 Requirements

Before installing the mods, make sure:

- You are using **vertical tabs**.
- The **tab bar width** is set to the smallest size.
- **Custom CSS modification** is enabled in Vivaldi settings.
- The **Workspace button** is *not* located inside the vertical tab bar.

---

## 📁 Installation

1. Navigate to Vivaldi's installation directory:
   ```
   C:\Users\YOUR_USER\AppData\Local\Vivaldi\Application\x.x.xxxx.xx\resources\vivaldi
   ```

2. Create a folder named:
   ```
   custom
   ```

3. Place your `.css` mod files inside the `custom` folder.

4. Open the `window.html` file in the `resources\vivaldi` directory.

5. Link your CSS files by adding the following line(s) before the closing `</head>` tag:
   ```html
<head>
  <meta charset="UTF-8" />
  <title>Vivaldi</title>
  <link rel="stylesheet" href="custom/tabbar.css" />
  <link rel="stylesheet" href="custom/quick.css" />
  <link rel="stylesheet" href="style/common.css" />
  <link rel="stylesheet" href="chrome://vivaldi-data/css-mods/css" />
</head>
   ```

6. Save the file and restart Vivaldi.

---

Enjoy your enhanced interface with a sidebar that expands on hover and a much sleeker quick search!
