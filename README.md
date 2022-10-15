# Chatty Edit
![chatty-logo](assets/logo2.png)
> Chatty is a customizable sleek-looking Discord theme with rounded borders, trasparency and a custom background.

# Features
- [X] Custom Background Images, by default daily images from [Unsplash](https://unsplash.com/)
- [X] Replugged Support
- [X] BetterDiscord Support
- [X] Vencord Support
- [X] OpenAsar Support

# Preview
![Preview](assets/chatty_preview.png)

# Installation
Follow those steps to install the theme on your client.
### **Replugged**
- Open the Replugged Theme Folder.
  - :one: Discord settings
  - :two: Themes
  - :three: Open Theme Folder
- Open a terminal instance in the folder. ([MacOS](https://www.maketecheasier.com/launch-terminal-current-folder-mac/) - [Windows](https://www.howtogeek.com/789662/how-to-open-a-cmd-window-in-a-folder-on-windows/))
- In the terminal paste this ``` git clone https://github.com/zerol1ght/chatty-edit.git ``` and click enter.

​
### **BetterDiscord**
- Open the BetterDiscord Theme Folder.
  - :one: Discord settings
  - :two: Themes
  - :three: Open Theme Folder
- Open a terminal instance in the folder. ([MacOS](https://www.maketecheasier.com/launch-terminal-current-folder-mac/) - [Windows](https://www.howtogeek.com/789662/how-to-open-a-cmd-window-in-a-folder-on-windows/))
- In the terminal paste this ``` git clone https://github.com/zerol1ght/chatty-edit.git ``` and click enter.
- Once you have the folder downloaded, open it and move out the ``` ChattyEdit.theme.css ``` file on the main ``` Themes Folder ```.
- Enable the theme from the themes settings on BetterDiscord.

​
### **Vencord**
- Open the Vencord settings.
  - :one: Discord Settings
  - :two: Vencord
- Open Quick CSS File.
- Paste this ``` @import url(https://cdn.jsdelivr.net/gh/zerol1ght/chatty-edit@master/ChattyEdit.theme.css); ``` and save file.
- Reload.
> For additional support contact [@RivenSkaye](https://github.com/RivenSkaye)

​
### **OpenAsar**
- Open Discord settings, and scroll at the bottom until you find you OpenAsar Version. ![OpenAsar-Version](https://i.imgur.com/ueKy1eI.png)
- Click on it.
- On the OpenAsar Settings go on the Theming tab.
- Paste this ``` @import url(https://cdn.jsdelivr.net/gh/zerol1ght/chatty-edit@master/ChattyEdit.theme.css); ``` and click **restart**.

​
# How to set a custom background image
Add this in the quick css.
```css
:root {
  --chattyBackgroundImage: url(http://website.com/image.png) !important;
}
```
Replace the url with the one of your image. (local files not supported).
You can use [imgur](https://www.imgur.com) or other image hosting sites.

# Updates
I'll try to update the theme every time I see bugs or something that isn't working, if you notice a bug please create an **[issue](https://github.com/zerol1ght/chatty-edit/issues)** or **[contact me](https://github.com/zerol1ght/chatty-edit#contacts)**.

# Customisation +
Change these variables only if you know what you're doing!
> **I DO NOT GARANTEE THAT IT WILL WORK IN EVERY PART OF THE THEME**

Paste this in the Quick CSS and edit it
```css
:root {
    --chattyBorderRadius: 15px !important;
    --chattyPadding: 10px !important;
    --chattyBlur: 5px !important;
    --interactive-muted: #D08770 !important;
    --background-primary: rgba(0, 0, 0, 0.2) !important;
    --background-secondary: rgba(0, 0, 0, 0.3) !important;
    --background-secondary-alt: rgba(0, 0, 0, 0.3) !important;
    --background-tertiary: rgb(39, 39, 39) !important;
}
```

# Contacts
You can contact me on:
- **Discord:** Light#0853
  - *You can dm me or just @tag me in [Replugged's server](https://discord.gg/s9aSD5Tfk3)*
- **Twitter:** [@honeystlyalbi](https://twitter.com/honeystlyalbi)
- **Mail:**  <zerol1ght@protonmail.com>
