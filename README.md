I decided to fork and maintain this userChrome.css because it was no longer being developed (I don't like dead projects). Give me some time I'll study the code and then will get back to you guys (I'm weak in CSS so I won't be able to change everything). I need to update the README too so please give me some time.

## The Goal
This userChrome mod was created to make the Firefox UI cleaner and more modern without sacrificing any of its original features. You can still use themes, and you can still use Compact Mode and Touch Mode. You can pretty much forget that you have a mod installed, it works *quietly* in the background. Here are some of the notable features:


## Customizable values 
Simply open userChrome.css in a text editor and change the values at the top of the file. Restart Firefox to see changes.

### Toolbar Customizations

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 7px;
    /* --menu-corner-rounding: 10px; */
    /* --menu-item-height: 30px;     */
    --button-corner-rounding: 20px;
    --animation-speed: 0.4s;
```

<br>

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    --tab-corner-rounding: 0px;
    /* --menu-corner-rounding: 10px; */
    /* --menu-item-height: 30px;     */
    --button-corner-rounding: 0px;
    --animation-speed: 0.0s;
```

### Menu Customizations
```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    /* --tab-corner-rounding: 7px;     */
    --menu-corner-rounding: 10px;
    --menu-item-height: 30px;
    /* --button-corner-rounding: 20px; */
    /* --animation-speed: 0.4s;        */
```

<p align="center">
</p>

<br>

```CSS
/* -------------------- 🎨 Customization 🎨 -------------------- */
    /* --tab-corner-rounding: 7px;     */
    --menu-corner-rounding: 0px;
    --menu-item-height: 25px;
    /* --button-corner-rounding: 20px; */
    /* --animation-speed: 0.4s;        */
```
<p align="center">
</p>


## Theme-adapted menus

## Address bar buttons appear when needed



## How to install
1. [Download](https://github.com/themoonmeetsthesun/silentfox/releases/latest/download/quietfox.zip) and unzip
2. Go to `about:support` in Firefox and open your Profile Folder
3. Drop your unzipped "chrome" folder into the folder that appears
4. Go to `about:config` in your Firefox and set the value of `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` (this enables the loading of userChrome mods)
5. Restart Firefox


I need to test it 😅.
---

### Older version
If you need Quietfox for an older version of Firefox, [see the releases page.](https://github.com/coekuss/quietfox/releases)

### Note about transparent themes
Although deliberate effort has been put into making this mod work with most themes, some transparent themes make menu text hard to read. Transparent themes also make the bottom corners of rounded tabs look wonky, so the file includes instructions to remove tabs' bottom corner rounding if you encounter this issue.

## P. S.
If you have any issues you can post the issue in the issues section.
