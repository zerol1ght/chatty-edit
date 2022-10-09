# Chatty Edit
![chatty-logo](assets/logo2.png)
Chatty is a customizable sleek-looking Discord theme, intended for the Powercord client-mod.

Originally made by [mrrobboss](https://github.com/mrrobboss), now maintained by me.
# Features
- [X] Custom Background Images, by default daily images from [Unsplash](https://unsplash.com/)
- [ ] BetterDiscord version
- [X] Support for Vencord
# How to set a custom background image
On powercord, go to "**settings --> themes --> quick css**" and paste this:
```css
:root {
  --chattyBackgroundImage: url(insert your image link here) !important;
}
```
Example
```css
:root {
  --chattyBackgroundImage: url(http://website.com/image.png) !important;
}
```
# Use with Vencord
For use with Vencord, either `@import url` the pre-compiled css file from its raw URL (coming soon), or compile it yourself.
## Acquiring [Sass](https://sass-lang.com)
In order to compile the Sass yourself, you'll need to have Sass available on your system, for which a few options exist.

Available on all operating systems:
1. [Standalone install](https://sass-lang.com/install) as per the instructions on the website
2. [Node.js Sass](https://www.npmjs.com/package/node-sass) `npm i -g sass`. This needs to be globally installed for it to be available on your system PATH.
3. [Ruby Sass](https://rubydoc.info/gems/sass-embedded) `gem install sass-embedded`. Assuming Ruby executables are available system-wide, this should just work as-is. Otherwise, try adding the `--no-user-install` flag.

For OS-specific installation methods, there are options like the Chocolatey package manager for Windows, Homebrew on Mac and your package manager or community repositories of choice for different Linux and Unix distributions.
## Compilation with Sass
This should be one easy command! Assuming you run it from the root of this repository:
```sh
$ sass theme.scss chatty-edit.css
```
When using this with Vencord, copy the contents to your quickcss file.
# Updates
I'll try to update the theme every time I see bugs or something that isn't working, if you notice a bug that is annoying you can contact me.
# Images
![image1](https://i.imgur.com/CVI0sUh.png)

# Customisation +
Change this variables only if you know what you're doing!
### **I DO NOT GARANTEE THAT IT WILL WORK IN EVERY PART OF THE THEME**
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
  - *You can dm me or just @tag me in [Powercord's server](https://discord.gg/SA7VN6rUVb)*
- **Mail:**  zerol1ght@protonmail.com
