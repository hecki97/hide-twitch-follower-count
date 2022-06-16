# Hide twitch follower count

Hides follower count from profile header and about section on twitch profiles.

Before:

![Image showing twitch user profile with visible follower counts](https://user-images.githubusercontent.com/1690071/174077875-8df997d4-ce15-4ac3-8050-451c205db7f1.png)

After:

![Image showing twitch user profile with hidden follower counts](https://user-images.githubusercontent.com/1690071/174077981-c0883d64-ff28-4cc1-80c8-68ae1c1d0f6b.png)


# Important Note
By default this userstyle is enabled globally!
This is due to the SPA (single page application) nature of twitch.
Whenenver you click on another channel, twitch updates the url immediately but the actual page transition is delayed.
This means the CSS selector no longer matches rendering this userscript naught.

![Gif showing follower counts becoming visible again after clicking on another twitch channel](https://user-images.githubusercontent.com/1690071/174083554-347e00d2-a34d-4f8d-8ed1-c0aa7778debe.gif)

If you're okay with that behaviour, you can replace `domain("twitch.tv")` with `url-prefix("<INSERT_YOUR_TWITCH_PROFILE_URL>")`

![Image showing what change needs to be made to restrict the plugin to a single profile page](https://user-images.githubusercontent.com/1690071/174084098-3f21ea27-58ee-4a4d-b53a-5722941fea7f.png)


# Installation

## 1. Install a UserStyle manager extension

[UserCSS recommends](https://github.com/openstyles/stylus/wiki/Usercss#how-do-i-install-usercss) Stylus. Alternatively there's also xStyle

> Note: Please don't use Stylish for the reasons listed in [this article](https://robertheaton.com/2018/08/16/stylish-is-back-and-you-still-shouldnt-use-it/)

- Stylus is available for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), and [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/)
- xStyle is available for [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/xstyle/) and [Chrome](https://chrome.google.com/webstore/detail/xstyle/hncgkmhphmncjohllpoleelnibpmccpj)

## 2. Install UserScript

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/hecki97/hide-twitch-follower-count/main/hide-twitch-follower-count.user.css)

If you're using Stylus, all you have to do is to click the button above!

![Image showing the Stylus editor with an option to install the style on the lefthand side](https://user-images.githubusercontent.com/1690071/174081200-5e495d97-c928-4439-a96f-563f57d17ec5.png)

A new tab should open with a button labeled "Install style" on the lefthand side

Click this button and you're done 🎉
