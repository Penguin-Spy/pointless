> Because Powercord's development has ceased, this theme will no longer be developed, nor support given. You are free to fork & update it for use with Powercord forks, following the terms of the [LICENSE](LICENSE), although I highly recommand against it, the code sucks ass lmao  
Also, I will be rewriting this theme for [GooseMod](https://goosemod.com "A light, secure, and easy to use Discord mod"), and will update this message when I have a GitHub repo created. If it's not too difficult, I will consider support for other client mods (it's css, hOw HaRd CoUlD iT bE?/??)  
The original README.md is as follows:

⚠ THIS THEME IS IN BETA! it should work and i won't commit any completly broken code, but some stuff may look funky/unstyled. you have been warned.

# Pointless
![clones](https://img.shields.io/endpoint?url=https://githubstats.penguinspy.repl.co/shields/pointless) [![Powercord](https://img.shields.io/badge/client-Powercord-7289D9?logo=discord&logoColor=fff)](https://powercord.dev/)  
A rectangular -but not pointy- customizable Powercord theme, with multiple skins (supporting dark and light mode), an option for backround images, and message bubbles + your messages are right-aligned.  

## Configuration
To choose a palette for the theme, copy+paste the following snippet into your QuickCSS:
```css
:root {
  --pointless-palette-NAME: 1;
}
```
Replacing "NAME" with one of: `forest`, `discord`, `background` (all lowercase). To choose the default `blue` theme, remove this line.  
If you want to use a background image, use this configuration:
```css
:root {
  --pointless-palette-background: .05;
‎  --pointless-background-image: url("IMAGE URL GOES HERE");
}
```
You may want to adjust the opacity by increasing/decreasing the `.05`.

To configure the radiuses of various elements, add this to your QuickCSS (you can combine it with the above snippet):
```css
:root {
  --pointless-radius-avatar: 5px;     /* Squircle: 5px, Round: 50% */
  --pointless-radius-server: 8px;     /* Squircle: 8px, Round: 50% */
  --pointless-radius-interface: 6px;  /* Squircle: 6px, Round: 20px */
}
```
To enable/disable other features, open the `settings.scss` file and follow the instructions enclosed. If you edit the settings at all, you should also open the `.gitignore` file and edit as instructed. A notice will appear to let you know if there are new settings and you need to manually update your settings file.

# Installation - Powercord
Open command prompt and run:
```cd powercord/src/Powercord/themes && git clone https://github.com/Penguin-Spy/pointless```

Other client mods are not supported at this time, this may or may not change. Do not make a Github issue requesting support for a different client mod :)

# Previews
//TODO
