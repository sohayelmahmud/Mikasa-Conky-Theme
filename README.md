# 🌟 Mikasa Conky Theme

Welcome to **Mikasa**, a minimalist and futuristic Conky theme designed to enhance your desktop with essential information and a clean aesthetic.

### ✨ **Features**

* **Large Digital Clock:** Displays the day of the week, month, date, and year in a unique, stylish font.
* **System Monitoring:** Cleanly shows your vital system statistics (RAM and HD usage).
* **Aesthetic Design:** Merges elements from different styles to create a cohesive, dark-themed look perfect for nightscapes or minimal wallpapers.

### 📦 **Package Contents**

This package includes everything you need to run the theme:

* `Mikasa` (The main Conky configuration file)
* `fonts/` (Essential and extra fonts required for the theme to display correctly)
* `wallpaper/` (Extra wallpapers provided for an optimized look)
* `LICENSE` (MIT License for open use and modification)
* `source.txt` (Credits and inspiration for the design)
* `README.md` (This guide)

### 🛠️ **Prerequisites**

To use the Mikasa theme, you must have the following installed on your Linux system:

1.  **Conky:** The `conky-all` package is usually required for full functionality.
2.  **Required Fonts:** Please **install all the fonts** found in the `fonts/` folder before running Conky. This is crucial for the theme to appear as shown in the screenshot.

### 🚀 **Installation Guide**

Follow these simple steps to get Mikasa running on your desktop:

1.  **Copy the Theme Folder:** Copy the entire **`Mikasa`** folder into your primary Conky configuration directory.
    * *Common location:* `~/.config/conky/`

2.  **Run Conky:** Open your Terminal and execute the following command to run the theme:
    ```bash
    conky -c ~/.config/conky/Mikasa/Mikasa
    ```

3.  **Setup Autostart:** For the theme to load automatically every time you log in, add the command from **Step 2** to your desktop environment's **Startup Applications** list.

### ⚙️ **Customization**

If the theme's position does not perfectly align with your desktop, you can easily adjust it:

* Open the `Mikasa` file with a text editor.
* Look for the `Window Settings` section.
* Adjust the horizontal position using `gap_x` (negative values move it left, positive moves it right).
* Adjust the vertical position using `gap_y` (negative values move it up, positive moves it down).

---

### **Thank You!**

Thank you for downloading the Mikasa theme! We hope you enjoy this blend of information and design on your desktop.
