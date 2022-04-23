I decided to fork and maintain this userChrome.css because it was no longer being developed (I don't like dead projects). I'm weak in CSS so I won't be able to improve everything. I am updating the README too. Peace ✌️.

## The Goal
This is silentfox, it is a fork of the now dead project called quietfox. I decided to update it and maintain it.

## But what is this??
This is a userChrome.css theme to make your firefox look a lot more cleaner then it was.
![]()

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
1. [Download](https://github.com/themoonmeetsthesun/silentfox/releases/download/v1.0.0/silentfox.zip) and unzip
2. Go to `about:support` in Firefox and open your Profile Folder
3. Drop your unzipped "chrome" folder and user.js (I have included the about:config tweak so you don't need to change it) into the folder that appears
4. Restart Firefox


Tested with Firefox 98
---

### Older version
If you need Quietfox for an older version of Firefox, you can find the older userChrome.css files in the "old" folder

### Note about transparent themes
Although deliberate effort has been put into making this work with most themes, some transparent themes make menu text hard to read. Transparent themes also make the bottom corners of rounded tabs look wonky, so the file includes instructions to remove tabs' bottom corner rounding if you encounter this issue.

## P. S.
If you have any issues you can post the issue in the issues section.
A big thanks to coekuss for making this wonderful thing.
