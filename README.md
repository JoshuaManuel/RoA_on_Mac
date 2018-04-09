# Playing Rivals of Aether on Mac

## Getting Started:

Although I originally went through this process to be able to play RoA on my Mac, this guide will likely be useful for those wanting to install the Windows version of Steam on their Mac. This should allow you to play other games that are Windows-only.

Given how close Mac and Linux are internally, this guide might be useful for those wanting to get RoA on Linux. I don't know, maybe.

Finally, this guide is for people who have already bought RoA on Steam and want to play it on Mac. I won't show you how to get the game for free (I don't even know how to do it).

Bottom line: if you want the game, support the developers!
## 1. Downloads:
+ [Wineskin Winery](https://sourceforge.net/projects/wineskin/files/Wineskin%20Winery.app%20Version%201.7.zip/download)
    + Wine is a compatibility layer that allows Windows programs to run on Unix-like (aka Mac and Linux) operating systems.
+ [SteamSetup.exe](http://store.steampowered.com/about/) (the Windows Steam installer from the official website)

## 2. Creating a Wineskin Wrapper
Once you download and install Wineskin, open it and you should see a window like this:

![Wineskin image](pics/pic1.png?raw=true "Wineskin image")

Click the "plus" icon under the list of installed engines to be taken to this window:

![Add engine window](pics/pic2.png?raw=true "Add engine window")

From there, click the dropdown and the most recent version of "WS9Wine". As of now, the most recent version is "WS9Wine2.22".

Click "Download and Install", then "Ok".

After you install the most recent WS9Wine engine, you should be taken back to the original Wineskin Winery window. Now, select the engine you just installed and hit "Create a Blank New Wrapper" at the bottom.

In the next popup window, name it something like "Steam.app" and hit "Ok".

A window like this should appear:

![File downloader](pics/pic4.png?raw=true "File downloader")

![Wrapper creation finished](pics/pic6.png?raw=true "Wrapper creation finished")

Select "View Wrapper in Finder" to be taken to where the wrapper was made.

## 3. Installing Steam
Double-click your wrapper. If you see an error that says it can't be opened, just try again. I'm not sure why you can't open it the first time, but it seems to be consistent on my Mac.

![Wineskin](pics/pic7.png?raw=true "Wineskin")

Click "Choose a Setup Executable" and navigate to where you downloaded SteamSetup.exe. For me it's on my desktop.

A window should briefly appear that says something like "Wineskin is currently busy" but then the Steam setup window should pop up.

![Steam setup](pics/pic8.png?raw=true "Steam setup")

Go through the Steam install wizard until you reach a window like this:

[COMPLETING STEAM SETUP]
![Completing steam setup](pics/pic9.png?raw=true "Completing steam setup")

Make sure "Run Steam" is checked, and hit finish.

## 4. Installing Rivals of Aether

Steam should start installing an update:

![Steam install update](pics/pic10.png?raw=true "Steam install update")

You may get an error about steamwebhelper.exe not being able to run, but feel free to close out of that window. It hasn't affected my ability to play RoA.

![Steam sign-in window](pics/pic11.png?raw=true "Steam sign-in window")

Once you log in, you may have to complete a Steam Guard authentication because this installation of Steam will be recognized as a new computer. All you have to do is follow the instructions in the windows that pop up.

After you're logged in, a small window will appear:

![Tiny steam](pics/pic13.png?raw=true "Tiny Riiiiick!")

Click on the tiny steam icon and then select Rivals of Aether from your library. Install that baby!

[STEAM ROA INSTALL]
![Steam RoA install](pics/pic14.png?raw=true "Steam RoA install")

You can re-select RoA from the tiny steam icon to monitor the game's progress.

We got 'em!

![RoA shots](pics/pic15.png?raw=true "RoA shots")
![RoA shots](pics/pic16.png?raw=true "RoA shots")

## 5. Cleanup
In order to access RoA again, look for this window:

![Choose executable](pics/pic17.png?raw=true "Choose executable")

It should have popped up after completing the Steam install wizard. From the dropdown menu, change it from SteamSetup.exe to "/ProgramFiles/Steam/Steam.exe" and hit "OK".

If you want to make a desktop shortcut, I recommend making an alias to the Steam Wine wrapper. This is done by right clicking (or command-clicking) the wrapper and then clicking "Make Alias".

![Make alias](pics/pic18.png?raw=true "Make alias")

Rename the alias whatever you want and then drag it to the desktop!

The next time you start up Steam on this computer, Steam should pop up correctly:

![Steam RoA](pics/pic1.png?raw=true "Steam RoA")

## 6. Notes:
+ Gamecube controller support works out-of-the-box with Mayflash adapters. In my experience it only works if the adapter is already plugged in and set to PC mode before you start up the game. The black USB port is for data and the grey one is for rumble, so if you can only plug in one, do the black one.
+ Sometimes the game doesn't scale correctly when going fullscreen. The most reliable fix I've found is maximizing/resizing only once you're at the title screen.
