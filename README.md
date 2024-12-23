# Toucan Tweaks

This repository contains a very small CSS theme for Zen Browser. It is expected to be used on top of [Cohesion + Natsumi by TheBigWazz](https://github.com/TheBigWazz/ZenThemes/tree/main/Zen-current-theme), and as such Toucan Tweaks does very little. This theme does the followinmg three things:
1. Rather than having a million icons appear when hovering over the URL bar, a single one appears. Scrolling on it swaps it to the others.
2. Changes a few icons: notably the three dots menu button gets changed to the Zen logo, and the unified extensions icon looks a bit cooler. There's also a few changed icons for specific extensions.
3. When a tab is playing audio, the favicon will change to an animated audio visualizer-looking icon. When clicked, it toggles muting the tab.

None of this CSS was actually written by me! Theyre snippets taken from [Dark Harmony by itsmefen.](https://github.com/itsmefen/Dark-Harmony) I actually don't know how to write CSS, and as such I deny any credit or responsibility for this CSS theme. Full credit to itsmefen for putting this together, I just took the pa rts I liked the most and seperated them out for use with Cohesion + Natsumi.

## Showcase


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
