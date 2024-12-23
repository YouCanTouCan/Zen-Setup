# Toucan Tweaks

This repository contains a very small CSS theme for Zen Browser. It is expected to be used on top of [Cohesion + Natsumi by TheBigWazz](https://github.com/TheBigWazz/ZenThemes/tree/main/Zen-current-theme), and as such Toucan Tweaks by itself does very little. This theme does the following three things:
1. Rather than having a million icons appear when hovering over the URL bar, a single one appears. Scrolling on it swaps it to the others.
2. Changes a few icons: notably the three dots menu button gets changed to the Zen logo, and the unified extensions icon looks a bit cooler. There's also a few changed icons for specific extensions.
3. When a tab is playing audio, the favicon will change to an animated audio visualizer-looking icon. When clicked, it toggles muting the tab.

None of this CSS was actually written by me! Theyre snippets taken from [Dark Harmony by itsmefen.](https://github.com/itsmefen/Dark-Harmony) I actually don't know how to write CSS, and as such I deny any credit or responsibility for this CSS theme. Full credit to itsmefen for putting this together, I just took the parts I liked the most and seperated them out for use with Cohesion + Natsumi.

## Showcase

General Cohesion/Natsumi Showcase: 

https://github.com/user-attachments/assets/5a29b5a1-d8e4-4eb2-9b7b-57ef2c3ade99

Icons and URL Scrolling Showcase (from Dark Harmony):

https://github.com/user-attachments/assets/9bb8f374-3e23-4587-b1ed-2b081dd121e5

Audio Indicator Showcase (from Dark Harmony):

https://github.com/user-attachments/assets/020a44c2-373a-49fd-ace4-9c9fe7684301

Cohesion + Natsumi with ToucanTweaks: ![Screenshot_20241223_144728](https://github.com/user-attachments/assets/f8f5c4b9-1055-4614-a34c-cb5d6517555f)
![Screenshot_20241223_144740](https://github.com/user-attachments/assets/f78fd537-5312-404a-bf66-771362382e3a)


## Installation via the UCL
What is uCL?
- [uCL (userChrome-Loader)](https://github.com/greeeen-dev/userchrome-loader) is an alternative method of structuring custom CSS to make it easier for users to swap in and out specific Modules of code from the community. This method is more similar to how Zen Browser already structrues its Mods. In addition to being a simpler setup process, it's a much easier structure to debug and maintain.
- Using uCL Structure allows an end user to simply drop a Mod folder into their /chrome folder to install a mod, theme, or custom CSS.
- Instead of copying entire CSS files into a userChrome.css, the user only needs to add a single import line in their userChrome.css.
- Mod creators can take advantage of this by making their custom css projects modular. Only want one feature of a project? Only use the import statement for that particular module.

Instructions:
- If you have not already, follow the [Zen Live Editing guide](https://docs.zen-browser.app/guides/live-editing) to first make your own userChrome.css file.
- Download [Cohesion + Natsumi](https://github.com/TheBigWazz/ZenThemes/tree/main/Zen-current-theme) following their instructions if you so desire (it's an awesome mod!)
- Download the ToucanTweaks folder from above and drop them into your "chrome" folder.
- Add this import statement to your userChrome.css: @import "ToucanTweaks/ToucanTweaks.css";
