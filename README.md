# Zen Browser CSS Enhancements

<p align="center">
  <a href="https://zen-browser.app"><img height="40" src="https://github.com/heyitszenithyt/zen-browser-badges/blob/fb14dcd72694b7176d141c774629df76af87514e/light/zen-badge-light.png"></a>
</p>

Enhance the visual experience of Zen Browser with a refined and optimized design, bringing consistency and modernity to the interface. This project was specially created for Windows 11 users, ensuring seamless integration with the operating system.

![image](https://github.com/user-attachments/assets/a3bb977b-6f02-4d94-b722-54d718623ab0)


## 🎨 Key Improvements

- Consistent Visuals: Unified styling across the entire browser for a harmonious visual experience.
- Pixel-Perfect Design: Precise alignment and attention to detail for a professional and pleasant look.
- New Icons: Redesigned icons throughout the interface, optimized for high resolution and a modern aesthetic.


## 🛠️ Installation

1. Clone or download this repository:

```
git clone https://github.com/jobsrobson/zen-browser-css.git
```

2. Navigate to your Zen profile folder.
3. Copy the repository contents into the "chrome" folder.
4. Restart Zen to apply the changes.


> [!WARNING]
> Zen Twilight has been updated to version 1.8t, bringing major changes to the behavior of Sidebar elements. If you're using this version, copy the files from the ```Zen Browser 1.8+``` folder to your ```chrome``` folder.



## 💻 Compatibility

- OS: Windows 11 (Linux coming soon).
- Browser: [Zen Browser](https://zen-browser.app/) (latest beta version recommended).


## 📄 License

This project is licensed under the GNU GPL3 License.


## ✅ Changelog

**1.8.1 - 2025-02-21** - Only for **Zen Twilight 1.8t**

  - Fixed: Position of the extended URL Bar on the screen.
  - Fixed: Position of the extended URL Bar when Compact Mode is enabled.
  - Fixed: Layout of the URL Bar buttons.
  - Fixed: Removed the "Reset Pinned Tab" button from pinned tabs.
  - General bug fixes.


**1.8 - 2025-02-15**
- For **Zen Twilight 1.8t**

  - Updated: Zen Twilight has been updated to version 1.8t, bringing major changes to the behavior of Sidebar elements. If you're using this version, copy the files from the ```Zen Browser 1.8+``` folder to your ```chrome``` folder.
  - Removed: Pinned tabs and the New Tab button now scroll along with the open tabs list due to the new Sidebar behavior (sorry!).
  - Fixed: Pinned tabs now retain the grid layout, just like Essentials.
  - Recommendation: Temporarily disable the ```zen.widget.windows.acrylic``` option in ```about:config```.
  - Code Cleanup: Reorganized the code into multiple CSS files to improve maintainability.
  
- For **Zen Beta 1.7.6b**

  - Code Cleanup: Since it's an experimental feature, the CSS for Tab Groups is now in a separate file to improve maintainability.

**1.7.6 (Zen Browser 1.7.6b) - 2025-02-12**
- WARNING: Zen Twillight 1.7.7t is broken. Do not update.
- Essentials design updates
- Bug fixes

**1.7.5 (Zen Browser 1.7.5t) - 2025-02-04**
- Fixed: new tab opening animation is now only activated when ```zen.workspaces.open-new-tab-if-last-unpinned-tab-is-closed``` is disabled (Requires Zen 1.7.5t)
- Fixed: width of Sidebar elements in compact mode

**1.7.4 (Zen Browser 1.7.4t) - 2025-02-01**
- New: Add to Tab Group icon in the context menu
- New: Remove from Tab Group icon in the context menu
- Fixed: Tab Group name not appearing after Zen 1.7.4t update
- Fixed: rearrange split tabs icon now correctly represents the function
- Improved: design of visited site cards on the New Tab page
- Improved: animation when opening a new tab

**1.7.21 (Zen Browser 1.7.2t) - 2025-01-28**
- Rolled back the border-radius of tabs in the Sidebar to the default 10px
- Removed the line above open tabs within a Group

**1.7.2 (Zen Browser 1.7.2t) - 2025-01-27**
- Layout tweaks to the top buttons in the Screenshot function
- Layout tweaks to the post-Screenshot dialog
- Fixed element colors for the Screenshot function in light and dark modes
- New entry animations for the expanded URL Bar (via [TheBigWazz/Pineapple-Fried](https://github.com/TheBigWazz/Pineapple-Fried/tree/main))
- Fixed the position of dialogOverlays
- Fixed scrolling behavior of Sidebar elements after the Zen 1.7.2t update: pinned tabs and the New Tab button are now fixed and no longer scroll up with open tabs
- Fixed the minimum width of Pinned Tabs after the Zen 1.7.2t update, prioritizing the layout with three columns
- Minor visual adjustments to Tab Groups
- Minor visual adjustments to global buttons
- SiteDataRemoveSelectedDialog layout tweaks