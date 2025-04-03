<h1 align="center">Vyang</h1>

###

<div align="center">
  <img height="350" src="https://i.redd.it/w7im1n35akqe1.png"  />
</div>

###

<h2 align="left">❤️ What is Vyang?</h2>

###


# 🦋 Vyang Browser Theme  

**A modern, minimalist browser theme inspired by nature.**  

## 🙏 Acknowledgments  
Special thanks to **Mr. Green**, creator of the **Natsumi Browser**, for inspiring this project.  

## ⚠️ Beta Notice  
**This is an experimental version!**  
- Not recommended for casual users unfamiliar with CSS.  
- May contain bugs or incomplete features.  
- Use only if you're comfortable troubleshooting themes.  

🔧 **Contributions** and feedback welcome!  

<p align="left">Vyang is a custom theme for Zen browser which overhauls the UI of Zen making it look like how I imagined it to be, giving it a clean look.<br><br>This is my personal userChrome which I made to personalize Zen to my own liking. ❤️<br>If some of you don't like the design choices I made, you can edit the userChrome yourself if you know how to code, and if you don't, you can use ChatGPT to customize it as per your preference.</p>

###

## 🛠️ Setup Instructions  

### 1. Use a Clean Profile  
- To avoid interference from other CSS, **test this theme on a new, clean browser profile**.  
- Do not use it on existing profiles with custom styles or extensions that modify the browser's appearance.  

### 2. Move Window Controls to the Left  
- type `about:config` in your url bar and go to advanced preferences.  
- Toggle `zen.view.experimental-force-window-controls-left` to `true`.
- this will require a restart of browser to take effect 

### 3. Set Density to Touch  
- Right-click on the empty space of tabs section and select **Customize Toolbar**.  
- Set **Density** to **Touch**.  

### 4. Enable Single Toolbar Mode  
- This theme is **only compatible with single toolbar mode enable that in zen settings under 'look and feel' section **.  

### 5. Clean Up Extra Icons  
- type `about:config` in your url bar and go to advanced preferences.
- Search for `zen.theme.content-element-separation` and set it to `10`.
- Remove unnecessary icons from the toolbar.  
- Move them to the **hovering toolbar on the right side** to avoid cluttering the tabs section.
 

### 6. Enable Tab Groups  
- type `about:config` in your url bar and go to advanced preferences. 
- Search for `browser.tabs.groups.enabled` and set it to `true`.  

### 7. URL Bar Lag During Animations  
- The URL bar may lag if animations or video content is displayed on the screen.  
- To fix this, either:  
  - **Cope with the lag**, or  
  - **Remove the URL bar CSS** from the theme.  


<h2 align="left">💿 Installation:</h2>

###

<h4 align="left">1. Install the CSS:</h4>

###

<p align="left">• If you have not already, follow the Zen Live Editing guide to first create your chrome folder: https://docs.zen-browser.app/guides/live-editing<br><br>• Download the chrome ZIP file from latest Release version and paste the vyang folder, vyang-config.css, userChrome.css, userContent.css inside the chrome folder <br><br>• Restart the browser to see if the UI has changed.<br><br>• Go to about:config in Zen and search for "browser.tabs.allow_transparent_browser". If the option is visible, set it to "true". If not, click the "+" icon and set it to "boolean".</p>

###

<h4 align="left">2. Install Mica for everyone (For windows 11 only)</h4>

###

<p align="left">• To get real backdrop filter transparency (note: that this method provides a better blur effect than the transparent zen extension by sameerasw), go to "https://github.com/MicaForEveryone/MicaForEveryone" and install the app.<br><br>• Click the "+ Add new Rule" at the bottom left and "Add process rule" for "zen".</p>

###

<p align="left">• Change the Backdrop type to Acrylic and enable blur behind in advanced options.<br><br>• Restart Zen and see how it looks.</p>

###

<h4 align="left">3. Install Tacky borders. config of tacky borders is in release (Optional)</h4>

###

<p align="left">• Go through the installation process from their github for a nice border around zen browser's window<br>https://github.com/lukeyou05/tacky-borders<br><br>• Restart Zen</p>

###

<h4 align="left">4. Add the extension Zen Internet by Sameerasw (Optional)</h4>

###


<p align="left">• this extension makes web pages transparent<br>https://addons.mozilla.org/en-US/firefox/addon/zen-internet/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search</p>

###

### 🚨 **WARNING:** This is a BETA version with many bugs – use at your own risk! 🚨 

<h2 align="left">Credits:</h2>

###

<p align="left">• https://github.com/Anoms12/Advanced-Tab-Groups</p>

<p align="left">• https://github.com/greeeen-dev/natsumi-browser</p>

###
