![screencast](https://cloud.githubusercontent.com/assets/499192/10754100/c0e1cc4c-7c95-11e5-9d3b-842d3acc2fd5.gif)

# Screen Saver to Desktop Background on Startup
Only for Macintosh Computers, enjoy. <br>
If you can think of a better name please let me know.

Completely open source so feel free to contribute to or learn from project development.

Requirements: RVM, Ruby

## (macintosh) How do I package this repository in it's current form?
1) git clone https://github.com/shoes/shoes4.git
2) git clone https://github.com/MichaelDimmitt/aerial_desktop_with_shoes.git
3) cd shoes4
4) rvm install jruby-9.1.8.0
5) bundle install
6) bin/shoes package --mac ../aerial_desktop_with_shoes/Shoes.rb
7) open ../aerial_desktop_with_shoes/pkg/Shoes.app

note(as shown in instructions app will be in pkg folder inside aerial_desktop_with_shoes_
## How the program works after packaged.
1) open Shoes.app
2) click install button and follow directions to install.
3) click uninstall button to uninstall.

4) Shoes.app clones Aerial_Desktop to ~
5) to completely uninstall, click uninstall button after opening Shoes.app and ... (step 6)
6) in terminal, ```cd ~; rm -rf Aerial_Desktop```


## Usage:
Setting the program as your Desktop Background can be toggled after installation with "Start.app and "Stop.app" ... implementing "Stop.app" will leave "Aerial" as your default screensaver. This app can support other Screensavers as Backgrounds. If you would like that email me at michaelgdimmitt@gmail.com or open an issue.

## Adjusting Aerial Settings

1. Open System Preferences -> Desktop & Screen Saver -> Screen Saver
2. Choose Aerial and click on Screen Saver Options to select your settings.

![Screenshot](https://cloud.githubusercontent.com/assets/499192/10754102/c58cc076-7c95-11e5-9579-4275740ba339.png)


<hr>

## Aerial Installed by default with project.

If you only want Aerial as a screensaver without the desktop change, simply open **Uninstall.app**<br>
and you are done! The afterward uninstall steps are for removing the Aerial Screensaver.

To find more information on Aerial navigate to:
https://github.com/JohnCoates/Aerial<br><hr>

## Note:

The screensaver engine takes your default screensaver to project as a desktop background.<br>

## Community
- **Found a bug?** [Open an issue](https://github.com/MichaelDimmitt/ScreenSaver_to_DesktopBackground_mac/issues/new). Try to be as specific as possible.
- **Have a feature request?** [Open an issue](https://github.com/MichaelDimmitt/ScreenSaver_to_DesktopBackground_mac/issues/new). Tell me why this feature would be useful, and why you and others would want it.

## Contribute
I appreciate all pull requests.

## Useful Links

#### When I wanted the screensaver as a desktop background these were the windows to the solution.

<a href="http://www.techradar.com/how-to/computing/apple/easy-mac-hacks-set-screen-saver-as-desktop-background-1305622">techradar_article_By_MacLife_Set_Screen_Saver_as_Desktop_Background</a>

#### When I wanted the change to happen when the computer woke from sleep:
https://nathangrigg.com/2012/07/schedule-jobs-using-launchd
https://github.com/MichaelDimmitt/mac_plist_launch_agent

## License
[MIT License](https://raw.githubusercontent.com/MichaelDimmitt/ScreenSaver_to_DesktopBackground_mac/master/LICENSE)
