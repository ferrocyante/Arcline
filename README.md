<p align="center">
    <h1 align="center">Arc-H 🌌</h2>
</p>

<p align="center">How I customizes my zen browser 🌸</p>

![](https://github.com/ferrocyante/Arc-H/blob/main/extras/Screenshot%20(172).png?raw=true)

![](https://github.com/ferrocyante/Arc-H/blob/main/extras/Screenshot%20(176).png?raw=true)


###

# 🍋‍🟩 Arc-h Browser Theme  

**A modern, minimalist browser theme inspired by organic architecture**  


## Stable Release Features

- **URL-bar** with custom scaling animations



https://github.com/user-attachments/assets/27ae1ab4-4ec8-4645-884f-98f808d4f06f



- **ARC like tidy tabs** with improved animations

https://github.com/user-attachments/assets/a1b63b7a-e32d-4d84-9132-584bff56f6bd


- **Performance-optimized** CSS animations
- **platform consistency** across Windows11
- **Enhanced compatibility** with Zen Browser v3.2+

<p align="left">Arc-h is a personal-grade theme for Zen browser that reimagines the browser interface with focus-preserving design principles.<br><br>This userChrome customization offers:<br>- Adaptive transparency effects<br>- Ergonomic spacing system<br>- Unified visual language<br>- Configurable accent colors</p>

###

## 🛠️ Setup Instructions  

### 1. Profile Preparation  
- Works best on **new profiles** or profiles without conflicting CSS modifications
- Compatible with most content-blocking extensions

### 2. Window Control Alignment  
- In `about:config`, set:  
  `zen.view.experimental-force-window-controls-left = true`  
  *(requires browser restart)*

### 3. Interface Optimization  
1. Right-click tabs area → **Customize Toolbar** → Set **Density** to **Touch**
![Screenshot 2025-04-16 172014](https://github.com/user-attachments/assets/f2197a98-3332-4db0-823b-ea666968634e)
2. Enable **Single Toolbar Mode** in Zen Settings → Look & Feel
3. Set `zen.theme.content-element-separation = 10` in `about:config`

### 4. Tab Groups Activation  
- In `about:config`, set:  
  `browser.tabs.groups.enabled = true`

### 5. Performance Considerations  
- Hardware acceleration recommended for best animation performance
- URL bar animations automatically disable during media playback

### 6. Preferences
- In `about:config` , make these prefernces according to your wish
- `arch.traffic.lights` to get mac os like title bar button on windows
- `arch.borders` for adding a white border around the browser
- `arch.urlbar.scale` for adding scaling effect url bar search results
- `arch.usable.blur.sidebar` to add a psuedo background behind tabs section(navigator tool box) in compact mode to ensure blur , you will need to adjust width according to you system
- `arch.four.essen` for making essential always stay in 4x grid style
- `arch.workspace.transition` very initial stage and can cause lagging very resource intensive
- `arch.workspace.buttons` for making  inactive workspace button into circles arc style has some limitions can only work for 3 workspaces and width of tabs section should be fixed accordingly                   
### Tutorial of setting preferences


https://github.com/user-attachments/assets/29eaf351-5d33-4d09-8717-64eac22b3fd2



<h2 align="left">💿 Installation</h2>

###

<h4 align="left">1. Theme Installation</h4>

###

<p align="left">1. Follow Zen's <a href="https://docs.zen-browser.app/guides/live-editing">Live Editing Guide</a> to create chrome folder<br>
2. Download latest release from <a href="https://github.com/[yourusername]/arc-h/releases">Releases page</a><br>
3. Extract these into your chrome folder:<br>
   - arc-h folder<br>
   - arc-h-config.css<br>
   - userChrome.css<br>
   - userContent.css<br>
4. Restart browser and enable:<br>
   `browser.tabs.allow_transparent_browser = true` in about:config</p>

###

<h4 align="left">2. Visual Enhancements (Windows 11)</h4>

###

<p align="left">1. Install <a href="https://github.com/MicaForEveryone/MicaForEveryone">MicaForEveryone</a><br>
2. Add process rule for Zen with:<br>
   - Backdrop Type: Acrylic<br>
   - Enable "Blur Behind" in advanced settings</p>

###

<h4 align="left">3. Optional Components</h4>

###

<p align="left">• <a href="https://github.com/lukeyou05/tacky-borders">Tacky Borders</a> - Preconfigured rules included<br>
• <a href="https://addons.mozilla.org/en-US/firefox/addon/zen-internet/">Zen Internet Extension</a> - For page transparency</p>

## 🙏 Acknowledgments  
Special thanks to **Mr. Green**, creator of the **Natsumi Browser**, for inspiring this project.  


###

<h2 align="left">Credits & Resources</h2>

###

<p align="left">• Tab Group implementation: <a href="https://github.com/Anoms12/Advanced-Tab-Groups">Advanced Tab Groups</a><br>
• Design inspiration: <a href="https://github.com/greeeen-dev/natsumi-browser">Natsumi Browser</a><br>
• Community contributions welcome via Issues and PRs</p>

###

<div align="center">
  <img src="https://img.shields.io/github/release/[yourusername]/arc-h?style=for-the-badge&label=STABLE%20RELEASE">
</div>
