---
layout: post
title:  "Application Cycling"
date:   2020-05-14
categories: blog
typora-root-url: ../../
typora-copy-images-to: ../../images
---

# The application cycle

I started off this day focusing on the blogging content for the past few entries.  As I was looking up URLs for the applications I wrote about earlier, I found a few replacement candidates.

## Window management
(Moom ---> ~~Spectacle~~ ---> ShiftIt ---> Tiles ---> ~~ShiftIt~~ ---> Rectangle & Catalina)

Quite a long trail of utilities for a simple purpose.  When I first used a Mac I was doing mobile development for iOS, but my main computer was my windows desktop for gaming.  I didn't understand the green window button and why it didn't behave like the Windows maximize button.  I found out that using the Alt/Option key would make it maximize but I couldn't get used to that and felt that the Mac application window sizes were very inconsistent in their default states.

The first utility I used was [Moom](https://manytricks.com/moom/) and that helped a lot so I could use the green button and have the window be the right size (full/half screen).  At some point in time I think Moom was or became paid software and because this wasn't my go-to machine I wasn't going to pay for it and found Spectacle.

The next set of switching was trying to find a minimal application that supported the Command-Option-Control combinations, and included a Maximize and Zoom/FullScreen option:

* [Spectacle](https://www.spectacleapp.com/) --- Worked great... *Not maintained*
* [ShiftIt](https://github.com/fikovnik/ShiftIt) --- Worked great... *Was looking up [AppCleaner](https://freemacsoft.net/appcleaner/) and saw that they also had Tiles*
* [Tiles](https://freemacsoft.net/tiles/) --- *Complained that Cmd-Option-Ctrl-Left/Up was already taken*
* [ShiftIt](https://github.com/fikovnik/ShiftIt) --- *Turns out [this is not maintained](https://github.com/fikovnik/ShiftIt/issues/296)*
* [Rectangle](https://rectangleapp.com/) --- Does *almost* everything...

Which brings me to the final selection, [Rectangle](https://rectangleapp.com/).  Rectangle does Maximize the way I expect, and I was able to set all of the hotkeys I was looking for.  The only thing missing is a shortcut for Full Screen.  Here is how I added it in Catalina.

## Full screen shortcut in Catalina
macOS already has the ability to define custom shortcut keys.  These are set up in the [System Preferences](x-apple.systempreferences:) Keyboard ---> Shortcut tab.

![Keyboard Settings: Shortcuts](/images/shortcuts1.png)

To set up a global shortcut for the Full Screen functionality, I looked up the menu option for Full Screen under the View menu.

![View Menu](/images/shortcuts2.png)

All that was left was to enter this information and select the shortcut key.  My window configuration modifier combination is Ctrl-Option-Cmd and for Full Screen I decided on F.

![New Shortcut](/images/shortcuts3.png)

## Disk space usage
(DiskInventory X --> Disk Cartographer --> DiskInventory X)

For the longest time I used [DiskInventory X](http://www.derlien.com/).  I picked this application because it was very similar to WinDirStat that I used on Windows.  For some reason I decided that I was going to switch to [Disk Cartography](https://apps.apple.com/us/app/disk-cartography-clever-disk-space-analyzer/id905264208).  Come to think of it, I believe it was because I was trying to replace all my applications with applications from the Mac App Store.

Disk Cartographer did not have the graphical map that I was looking for.  This quickly and easily shows me the largest files and I like that it groups and colors them by file type.

![DiskInventory X](/images/diskspace1.png)

