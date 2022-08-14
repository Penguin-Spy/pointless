# Pointless
![clones](https://img.shields.io/endpoint?url=https://githubstats.penguinspy.repl.co/shields/pointless) [![Powercord](https://img.shields.io/badge/client-Powercord-7289da?logo=discord&logoColor=fff)](https://powercord.dev/) [![Topaz](https://img.shields.io/badge/client-Topaz-fdda0d?logo=discord&logoColor=fff)](https://topaz.goosemod.com/)  [![Replugged](https://img.shields.io/badge/client-Replugged-7289da?logo=discord&logoColor=fff)](https://replugged.dev/)  
A rectangular -but not pointy- customizable Powercord theme, with multiple skins (supporting dark and light mode), an option for backround images,  message bubbles, right-aligning your messages.  


# Installation
## Replugged/Powercord
> If you are migrating from Powercord and already have the theme installed, you don't need to reinstall.  

Open this link to install the theme: https://replugged.dev/install?url=Penguin-Spy/pointless

## Topaz
Open the Topaz theme settings and copy+paste `Penguin-Spy/pointless` into the "Add Theme" box, and then press enter.

## Other client mods
Other client mods are not supported at this time, this may or may not change. Do not make a Github issue requesting support for a different client mod :)


# Configuration
> Note: this system will likely change soon, it sucks to use and maintain
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
  --pointless-background-image: url("IMAGE URL GOES HERE");
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

# Previews
//TODO
