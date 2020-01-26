<div align="center">

<img src="assets/firefox.svg" alt="Firefox Logo" width="120px"/>

<h1>Firefox Overlay Scrollbars</h1>

🦊 <em>A working prototype of custom styleable overlay scrollbars on Firefox 72+.</em>

![](https://img.shields.io/badge/Firefox-72+-ff7139?logo=Mozilla%20Firefox&style=flat-square)
[![](https://img.shields.io/badge/license-MIT-6c5eee?style=flat-square)](./LICENSE)
</div>

<h5> 🎲 Derived from the all-in-one feature-complete Firefox user script repo <a href="https://github.com/Aris-t2/CustomJSforFx">Aris-t2/CustomJSforFx</a>.<h5>

## Demo

![](assets/demo.gif)

## Installation

First, close all instances of Firefox, and **delete Firefox's old script/startup cache** at `about:profiles » Local Directory » Open Folder`

![](https://i.loli.net/2020/01/26/wxiPjBKWothuGVf.png)

Next, **download the entire repo** with either Git or `Download ZIP`. Uncompress the downloaded zip file.

Then, find the folder `firefox` inside the downloaded repo directory, **copy the `defaults` folder and the file `config.js` to Firefox's installation directory**, i.e., where `firefox.exe` lives.

![](https://i.loli.net/2020/01/26/bhz1VpZav4MCKlx.png)

Finally:

- Find Firefox's profile folder at `about:support » Profile Folder » Open Folder`, **create a folder called `chrome` inside**

![](https://i.loli.net/2020/01/26/QwMtSFAVLbryepY.png)

- Then, find the folder `profile` inside the downloaded repo directory, **copy the `userChrome` folder and the file `userChrome.js` to the folder `chrome` that we just created**

![](https://i.loli.net/2020/01/26/HESxRq9XmWFhBfC.png)

Restart Firefox and you should be able to see the custom scrollbar take effect.

## Customization

We can tweak the file inside our newly created `chrome/userChrome` folder called `custom_scrollbars.uc.js`. The following features can be customized:

- hide scrollbars
- hide scrollbar buttons
- **floating scrollbars (on top of web content)**
- custom scrollbar size
- custom scrollbar opacity
- custom scrollbar background color / background image for color gradient
- custom scrollbar corner background color / background image for color gradient
- **custom scrollbar thumb color / background image**
- custom scrollbar hovered-thumb color / background image for color gradient
- custom scrollbar thumb roundness / border-radius
- custom scrollbar thumb border width
- custom scrollbar thumb border color
- custom scrollbar button color / background image for color gradient
- custom scrollbar hovered-button color / background image for color gradient
- custom scrollbar button roundness / border-radius / arrow

See the file's comments for more information.

**You'll need to delete Firefox's old script/startup cache at `about:profiles » Local Directory » Open Folder` every time you change the script under `chrome/userChrome` folder.**

---

🦊 **Firefox Overlay Scrollbars** ©Spencer Woo. Released under the [MIT License](LICENSE).

Authored and maintained by Spencer Woo.

[@Portfolio](https://spencerwoo.com/) · [@Blog](https://blog.spencerwoo.com/) · [@GitHub](https://github.com/spencerwooo)
