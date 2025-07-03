### <ins> FF Ultima Version 3.0 Release
- **[Click Me ⬇️ Release Download](https://github.com/soulhotel/FF-ULTIMA/releases/download/3.0/ffultima3.0.zip)**
- **[Click Me ⬇️ Source Download](https://github.com/soulhotel/FF-ULTIMA/archive/refs/heads/main.zip)**
- 🗨️ [Submit an issue](https://github.com/soulhotel/FF-ULTIMA/issues/new/choose) or ask questions not answered in [the Wiki](https://github.com/soulhotel/FF-ULTIMA/wiki).
- ⚙️ [Change settings](https://github.com/soulhotel/FF-ULTIMA/wiki/Settings), tab size, autohiding, spacing, and more.
- ⚙️ [How to Update](https://github.com/soulhotel/FF-ULTIMA/wiki/How-to-Update-the-Theme) the Theme to a new version.
  
### <ins> Version Notes
- This is a big *quality of life* update focused on stability. With a full restructure of source files, and a less = more approach. Using less code but keeping the same look & functionality. Organizing code categorically to improve readability. Also some major improvements for Color Scheme handling.
- Firefox 138+ required.
- User.js required.
<!--
- User.js required. 
- User.js not required.
- User.js (recommended) not required. 
-->

<details><summary><ins>Before You Update (CLICK ME)</summary>

>
- Returning Users: **User.js is Required** for this update. To help avoid confusion if a setting is deleted or changed. The about:config page now notifies you when an old/deleted/renamed setting is detected.

https://github.com/user-attachments/assets/e0dfb849-cf89-4818-b196-118757e85c4a

<img src="https://github.com/user-attachments/assets/5dfaa05b-d838-4f5b-9883-148708ba714a" width="50%" />

</details>

### <ins> Change Log:
- #308 #310 #311 #315 #317
- `fyi • ℹ️ •` "The Hard Way" installation method fully [automates](https://github.com/soulhotel/FF-ULTIMA?tab=readme-ov-file#installation) install & updates for all Operating Systems
- `fix • 🔴 •` As of Firefox 141-142 window controls (in Windows) are no longer toolbarbutton-icons, they are now appended via ::before elements that inherit the default style. However, the original toolbar-icons are still in the browser source, they just default to display:none now. I reverted this change and applied display:none to the new ::before elements when using custom controls window controls. So custom window controls for Windows are restored. 7baa6e5
- `fix • 🔴 •` Fixed in 3.0 quick patch, Websites that appear altered, have been fixed via the browsers default content handling
- `fix • 🔴 •` About:config will now notify you about setting `user.theme.transparent`
- `fix • 🔴 •` Find bar visibility adjustment 92cba3d
- `fix • 🔴 •` Setting `ultima.navbar.bookmarks.centered` adjust when Window width is smaller 5283649
- `fix • 🔴 •` Setting `ultima.tabs.tabgroups.background.4` no longer increases width of vertical tabs, no more shift 23f0311
- `new • 🟢 •` Setting `ultima.tabs.tabgroups.label.3` is now the new default tab groups style 23f0311
- `qol • 🟡 •` Tab groups background colors adjustments
- `qol • 🟡 •` Window controls spacing (in Windows) & consistent colors when window is active/inactive/colorscheme 0422b64
<!--
`fyi • ℹ️ •` 
`fix • 🔴 •` 
`new • 🟢 •` 
`qol • 🟡 •` 
`wip • ℹ️ •` 
-->

> FF Ultima *Kanagawa Wave* Edition by @pitchaya-s

![image](https://github.com/user-attachments/assets/748ab6bb-b2c9-421e-abf7-4a05415eb198)

> Setting `user.theme.transparent`. See the [wiki](https://github.com/soulhotel/FF-ULTIMA/wiki/Transparent-Theming).

![transparentt](https://github.com/user-attachments/assets/f78d6606-e194-4b48-a395-145874789575)
![Screenshot_20250624_050538](https://github.com/user-attachments/assets/3be6c64b-338a-4c65-a183-3a0ac16896b5)

> FF Ultima is reaching it's maturity, additional updates to the theme will most likely only focus on bugs, patches, and fine-tuning. If you'd like to see more features added to the list, feel free to fork or push via pull request. Contributors, like always - are always welcome. Otherwise, enjoy.
