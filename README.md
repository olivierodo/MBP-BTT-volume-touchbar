# BetterTouchTool - Volume - Touch Bar

## Description

If you have a MacBook Pro with the touchbar this project will help you to customize your touchbar by :
 - Displaying the current volume of your sound

Example Full bar (last widget) :

![config widget](./img/full-touchbar.png)

Example widget :

![screenshot](./img/screenshot-touchbar.png)


## Prerequisite

 - MacBook pro with the Touch Bar
 - You can read this article: [Hands-on: Creating a custom Touch Bar button using BetterTouchTool](https://9to5mac.com/2016/12/02/hands-on-custom-touch-bar-button-bettertouchtool-video/)
 - [BetterTouchTool](https://www.boastr.net/downloads/)

## Config

First, you need to add a new widget on the global section. Find the configuration below.

![config widget](./img/screenshot-config.png)

#### Icon

For this widget we just use the build in icons.
You just need to click on the icon box and scroll down to find the volume icon.

![icon](./img/screenshot-icon.png)

#### Script

For the widget display paste the following script as shared on the previous screenshot:

[touchbar.applescript](./touchbar.applescript)

And Voila !

![config widget](./img/full-touchbar.png)

#### Action

If you want you can add an extra action when you click on the widget to open the Activity monitor app.

### Other widget available on github

- [Spotify](https://github.com/olivierodo/MBP-BTT-spotify-touchbar)
- [Clipboard](https://github.com/olivierodo/MBP-BTT-clipboard-touchbar)
- [Wifi](https://github.com/olivierodo/MBP-BTT-wifi-touchbar)
- [Activity Monitor](https://github.com/olivierodo/MBP-BTT-activity-monitor-touchbar)
