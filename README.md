# Toucan Tweaks

This repository contains a very small CSS theme for Zen Browser. It is expected to be used on top of other themes, such as [Natsumi Browser by Greeen-Dev](https://github.com/itsmefen/Dark-Harmony) and [Pineapple Fried by TheBigWazz](https://github.com/TheBigWazz/Pineapple-Fried). As such Toucan Tweaks by itself does very little. This theme does the following two things:
1. Rather than having a million icons appear when hovering over the URL bar, a single one appears. Scrolling on it swaps it to the others. Thank you to itsmefen, maker of [Dark Harmony](https://github.com/itsmefen/Dark-Harmony), for the code for this. I did not write it myself.
2. Changes icons. The menu button is changed to the Zen logo, and the unified extensions button is changed to a version with a subtle Z shape in it. In addition, the logos of [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search), [Dark Reader](https://addons.mozilla.org/en-US/firefox/addon/darkreader/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search), [Zotero Connector](https://www.zotero.org/download/connectors), [Cast Kodi](https://addons.mozilla.org/en-US/firefox/addon/castkodi/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search), [KeepassXC-Browser](https://addons.mozilla.org/en-US/firefox/addon/keepassxc-browser/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search), [Bitwarden](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search), and [ProtonPass](https://addons.mozilla.org/en-US/firefox/addon/proton-pass/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) are changed to appear like they are a native part of the browser. Further extensions will be added on request.

## Showcase

URL Scrolling Showcase (from [Dark Harmony](https://github.com/itsmefen/Dark-Harmony)):

https://github.com/user-attachments/assets/9bb8f374-3e23-4587-b1ed-2b081dd121e5

From left to right: uBlock Origin, Dark Reader, Workspace Swapper, Zotero Connector, Cast Kodi.
![image](https://github.com/user-attachments/assets/2e399674-7905-4f37-a983-2d994572921a)

Menu button and unified extension button:

![image](https://github.com/user-attachments/assets/ac6962b7-89f0-4bdd-8053-8c5d564d4d4d)

Natsumi + Pineapple Fried + ToucanTweaks: 
![Screenshot_20250110_223529](https://github.com/user-attachments/assets/53f24525-e1f8-451d-9f6a-67f2ce2fb2d4)



## Installation via the UCL
What is uCL?
- [uCL (userChrome-Loader)](https://github.com/greeeen-dev/userchrome-loader) is an alternative method of structuring custom CSS to make it easier for users to swap in and out specific Modules of code from the community. This method is more similar to how Zen Browser already structrues its Mods. In addition to being a simpler setup process, it's a much easier structure to debug and maintain.
- Using uCL Structure allows an end user to simply drop a Mod folder into their /chrome folder to install a mod, theme, or custom CSS.
- Instead of copying entire CSS files into a userChrome.css, the user only needs to add a single import line in their userChrome.css.
- Mod creators can take advantage of this by making their custom css projects modular. Only want one feature of a project? Only use the import statement for that particular module.

Instructions:
- If you have not already, follow the [Zen Live Editing guide](https://docs.zen-browser.app/guides/live-editing) to first make your own userChrome.css file.
- Download [Natsumi](https://github.com/itsmefen/Dark-Harmony) following their instructions. Skip this if you only want ToucanTweaks.
- Download [Pineapple Fried](https://github.com/TheBigWazz/ZenThemes/tree/main/Zen-current-theme) following their instructions. Skip this if you only want ToucanTweaks.
- Download the ToucanTweaks folder from above and drop them into your "chrome" folder.
- Add this import statement to your userChrome.css: @import "ToucanTweaks/ToucanTweaks.css";
