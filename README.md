# ShyFox 3.8 - Borderless


# Massive thank you to [Naezr](https://github.com/Naezr) for the original work!

<div>
 
![image](https://github.com/user-attachments/assets/4fdf77c2-b2b2-4f72-a0a6-cc0c5fb57fa9)

## Usage

### Install

#### Step 1 - Download files

 - [Download](https://github.com/BrancuAlexandru/ShyFoxBorderlessCompressed/raw/main/ShyFoxBorderless.zip) and unzip theme files

#### Step 2 - Configure extensions

 - Install [Userchrome toggle Extended](https://addons.mozilla.org/firefox/addon/userchrome-toggle-extended/)
   
   <details><summary>Configure Userchrome toggle Extended</summary> 
   
   <br/>

   You need to turn on "Allow multiple styles to be active together" and turn on the first four toggles. If you will be using a popup, enable "Close popup after clicking toggle" and rename the toggles for convenience. Play with the rest of the settings as you wish. Make sure you click "Apply changes" button after all
   
   ![settings](https://github.com/user-attachments/assets/44b8702d-3a92-458d-8a2e-23b8e9e5703d)

   It would also be nice to customize the shortcuts for toggles. I recommend these:
   
   ![how-to](https://github.com/user-attachments/assets/d49948f5-4544-4070-a691-dc090f37b2d3)
   ![shortcuts](https://github.com/user-attachments/assets/bef9f1be-878e-4103-b1a9-0d171e9850bd)
   
   <br/>
   
   </details>    


 - Install [Sidebery](https://addons.mozilla.org/firefox/addon/sidebery)

   <details><summary>Configure Sidebery</summary> 
   
   <br/>
   
   If you used Sidebery before, it would be better to reset its settings to default.
   
   Then import `sidebery-settings.json` from unzipped theme files

   ![import](https://github.com/Naezr/ShyFox/assets/95460152/9961a813-d035-41cc-a6b4-146e20db45bc)

   <br/>
   
   </details>    

#### Step 3 - Moving files to a profile folder

 - Find your [profile directory](https://support.mozilla.org/kb/profiles-where-firefox-stores-user-data)
 - Close Firefox
 - Move `chrome` folder and `user.js` file from unzipped theme files into your [profile directory](https://support.mozilla.org/kb/profiles-where-firefox-stores-user-data)
  
   <details><summary>Profile folder structure</summary> 
      
      <br/>

      ```js
      {random characters}.default-release // Profile folder itself
      |_ chrome // chrome folder you put in
      |  |_ userChrome.css
      |  |_ userContent.css
      |  |_ ShyFox
      |  |  |_ ... // css files
      |  |_ icons
      |  |  |_ ... // svg icons
      |  |_ wallpaper.png
      |  |_ wallpaper-light.png
      |_ user.js // user.js file you put in
      |_ ... // a lot of files that was there before
      ```

      <br/>
      
      </details>    

 - Open Firefox

#### Step 4 - Buttons layout

 - Go to the customizing page. <img src="https://github.com/Naezr/ShyFox/assets/95460152/49d963a3-ccb4-48f9-8892-f206894315d7"> > More tools > Customize toolbar
  
 - Move buttons to something like that:
   
   <details><summary>Customizing menu</summary>
   
   <br/>
   
   ![layout](https://github.com/user-attachments/assets/a0524f8b-a16d-4753-bbbe-8aeccae25b2b)
   
   > NOTE                                 
   > If you don't add `Flexible Space` to the right toolbar, all buttons except `Menu` and `Extensions` will be centered on the panel
   
   <br/>
   
   </summary>

> [!NOTE]
> `System theme - auto` can cause problems in some cases
> 
> ![image](https://github.com/user-attachments/assets/5da52c2e-6b04-414a-b492-478a87b55f9a)



### Upgrading

 - Migrate from old version
   <details><summary>Migrate from 2.0 </summary>
   
      <br/>
      
      If you migrating from 2.0 you need delete fx-autoconfig.                     
      To do it, at first clean up `chrome` folder, at second delete `config.js` and `/defaults/prefs/config-prefs.js` from Firefox installation folder.           
      
   </details>

   <details><summary>Migrate from 3.4 </summary>
   
      <br/>
      
      If you migrating from 3.4 you need to reset Sidebery settings to default and import new ones.
         
   </details>

 - In other cases redo the installation steps 1 and 3 is enough for updating to new ShyFox version

### Customization

If you don't like the way the standard dark and light themes look, you can colorize your ShyFox!

There are three ways you can do it, choose one:
- Install some theme from [Firefox Add-ons](https://addons.mozilla.org/firefox/themes/) (not all will be well compatible)
- Color your browser yourself with [Firefox Color](https://addons.mozilla.org/firefox/addon/firefox-color/). Presets from screenshots: [pink](https://color.firefox.com/?theme=XQAAAAJcAQAAAAAAAABBqYhm849SCia48_6EGccwS-xMDPsqvXkIar4KdrumPOaRpoqhRtylP5n4Zfpe_3lMuBvgYbla0qT1QOs34oqRKJ__vCF6FKTI9i1CVNq28mKrlpbA743Cig4kGHR6iZLsbfXGx2TWrRs-AEYfywqkYrtkIsD-hNDUEskonC-PtUjDQO60hJRYxAdc_ciaOdJZ3qLR8-ltnNQrBrjrkZPS0cKdYESG19Ce108sPUJ-sxtRJheP8uifehJAtfT_U_CMAA), [turquoise](https://color.firefox.com/?theme=XQAAAAJgAQAAAAAAAABBqYhm849SCia48_6EGccwS-xMDPrv2Sw35312EPwz49WPR2-KqLVciULUNG8hT47EAt7OFG0PM9EP_FOrqm0ZcrcuiqO7AJ4ZtOtYZJYmJW2UQbLGqUwsx5a1luSAeWzbTYBr_wq9rgHinuRP90rQNt7qFSEFpoA_QEVgntqma7ntnbh1n4ffmSGvCvZINPxUCniDpGX529KAsQ3OEifjH-k0NSutAReuloDG_oDBQO0f3f3mdUhny4nuWQSUjTHVzc480xP-PnQ6), [private](https://color.firefox.com/?theme=XQAAAAJgAQAAAAAAAABBqYhm849SCia48_6EGccwS-xMDPsQa-obYNsLXtQH-LkSl-xiFvguLlbVAytJ7iSRZYDjI5M0HGJIVok5YY7sQJYDNqALkbhYuNd7GLBtffJP_WihaR82B9eSNM5B_AwFPXi9jAhOGSVHrux-aPHsNExZwN_G33gbtzlHrsaZ6mQVS0iF5xGMJ7hAHNnY-o-q3_nklkOvFpHlzDrKB7504aWtuHtKFi5DvcCgNYsdPEE_Pom2287flglmiD3RyZ7nv59EheVP_9zDOgA)
- Install the [Adaptive Tab Bar Color](https://addons.mozilla.org/firefox/addon/adaptive-tab-bar-colour/) extension and then ShyFox will adapt to the colors of the currently open website.
 
   <details><summary> Recommended Adaptive Tab Bar Color settings</summary>  
   
   <br/>
   
   ![settings](https://github.com/Naezr/ShyFox/assets/95460152/36480217-8209-4f7d-9d54-1a07f6f2752c)
   
   > NOTE                        
   > If you make the `Tab bar` and `Toolbar` `Background` colors the same, the pull-down hidden panels will have a transparent background.
   
   <br/>
   
   </details>

> [!NOTE]
> Use only one thing. Adaptive Tab bar Color and Firefox Color are not compatible 

You can change new tab wallpaper to your own. There is two wallpaper files in `chrome` folder:
 - `wallpaper.png` - for dark theme                   
 - `wallpaper-light.png` - for light theme             
  
To use one image for all themes just delete `wallpaper-light.png`.

You can change theme accent color. To do it change value of `--shy-accent-color` variable in `chrome/ShyFox/shy-variables.css`. You can also equate it to the fill color of the buttons. See options below

### Options

Settings that can be toggled via [about:config](https://support.mozilla.org/kb/about-config-editor-firefox)

| Setting | true | false / not exist (default) |
| :--- | :--- | :--- |
| `shyfox.larger.context.menu` | Using large context menu | Using compact context menu |
| `shyfox.disable.floating.search` | Floating search disabled | Floating search enabled |
| `shyfox.disable.compact.unified.extensions` | Using default extensions menu | Using compact extensions menu |
| `shyfox.remove.window.controls` | `min` `max` `close` buttons removed at all | These buttons removed only in fullscreen |
| `shyfox.enable.ext.mono.toolbar.icons` | Supported* extensions get monochrome icons as toolbar buttons | Standard icons used |
| `shyfox.enable.ext.mono.context.icons` | Supported* extensions get monochrome icons as context menu items** | Standard icons used |
| `shyfox.enable.context.menu.icons` | Many context menu items get icons** | No icons in context menus |
| `shyfox.fill.accent.with.icons.fill.color` | Attempts to use icon fill color as accent | Using hardcoded accent |
| `shyfox.force.native.controls` (Linux only) | Attempts to use system theme for `min` `max` `close` buttons  | Adwaita icons used |

<details><summary>* - Supported extensions</summary>
   
   <br/>
   
   - Userchrome Toggle Extended - toolbar button (panels icon)
   - Bitwarden - both toolbar and context menu (+ submenu items)
   - uBlock Origin - both toolbar and context menu
   - Simple Translate - only context menu item
   - Dark Reader - toolbar button (moon icon)
   - Privacy Badger - toolbar button
   - Clear URLs - only context menu item (eraser icon)
   
   Feel free to suggest icons for other extensions
   
   <br/>
   
</details>

** - On macOS you need to disable native context menus to see icons. `widget.macos.native-context-menus` => `false`

## Overview

### Panels

The browser interface has been divided into three panels:
- On left - Sidebar - Just Sidebery. Functionality of this extension is incredible. It is in charge of managing tabs and bookmarks. Above the main sidebar is a small bookmarks bar.
- On top - Navbar - panel where you can find the address bar and everything related to it
- On right - Toolbar - a panel with customizable buttons

### Toggles

The core of the theme is the [Userchrome toggle Extended](https://addons.mozilla.org/firefox/addon/userchrome-toggle-extended/) extension. With the help of toggles added by it the main feature of this theme is realized.                           

| № | Name | Recommended shortcut |
| --- | --- | --- |
| 1 | Hide Sidebar | Ctrl + Alt + A |
| 2 | Hide Toolbar | Ctrl + Alt + D |
| 3 | Hide Navbar  | Ctrl + Alt + S |
| 4 | Clean Mode   | Ctrl + Alt + X |

Each of three panels has two states - visible and hidden. This state can be toggled independently for each panel.


## Thanks again, [Naezr](https://github.com/Naezr), for the original work!
