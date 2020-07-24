# EZ-Rank
Android app where you can easily rank your favorite movies, music, or anything else!

Currently in beta form, so testing is ongoing and there are almost certainly bugs,
which may depend on which model of phone you are using.

<p>
<img src="https://github.com/ryankarpenko/EZ-Rank/blob/master/screenshots/main_screen.png?raw=true" alt="Ranking Screen" width="300"/>
<img src="https://github.com/ryankarpenko/EZ-Rank/blob/master/screenshots/ranking_screen.png?raw=true" alt="Ranking Screen" width="300"/>
<img src="https://github.com/ryankarpenko/EZ-Rank/blob/master/screenshots/change_icon_screen.png?raw=true" alt="Change Icon Screen" width="300"/>
</p>

-------------------------------------------------------------------------------------------------

WARNING:

This app is in beta form, and downloading it requires allowing installs of unknown apps on your phone. This is blocked by default for your protection, so that you don't install an app from outside the Play Store that has hidden malware. So you will have to trust that my app is not malware.

Additionally, EZ-Rank in theory should not cause any harm to your phone or its data, as it is a simple app that only requires a small amount of local storage space which is deleted when you uninstall the app. However, I cannot guarantee that it will work perfectly for your device. But if you choose to download it and try it out, I would greatly appreciate it!

If you find any bugs or have a question/suggestion, you can email me at karpenko.ryan@gmail.com. 

INSTRUCTIONS TO DOWNLOAD:

(This is based on my experience installing the app on a Pixel 3a)

1) From your phone's web browser, click on the ez-rank-debug-x.x.apk file inside this repository, then download it.

2) When you open the file, you will be prompted to change your settings for installing unknown apps.

3) When you select "Settings" from this warning, you will be taken to an app permissions screen. For me it was permissions for Chrome.

4) Change the permissions setting to "Yes" (or activate the toggle).

5) Go to your files on your phone, and find the recently downloaded .apk file.

6) Open it, and you will be prompted to install the app.

7) You may have to pass one final warning, after which your phone will download the app.

8) Enjoy!


KNOWN BUGS:

These bugs have all been fixed in the "debug" branch. The fixes will come to the master branch in the next update.

1) Clicking an item to edit its name can cause the keyboard to appear over the text box (Pixel 3a)

2) Clicking an item to edit its name does not set the cursor to the beginning of the text box (Pixel 3a)

3) When editing an item's name, clicking outside of the text box when the cursor is not active does not complete the edit as intended (Pixel 3a)
  
4) After clicking on an item "n" that is on the lower part of the screen which subsequently gets covered by the keyboard (1), swiping up to see the item n causes the n-1 item to turn into a edit text box, instead of the nth item.
  
5) While editing the name of a list, if the user presses the dots button and tries to edit icon or delete list, the app will crash.

6) Main screen does not show updated "Number of items" info etc after returning from Ranking screen when using phone's back button (as opposed to the back button in the app).
