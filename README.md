# EZ-Rank
Android app where you can easily rank your favorite movies, music, or anything else!

Currently in beta form, so testing is ongoing and there are several known minor bugs,
which may depend on which model of phone you are using.

-------------------------------------------------------------------------------------------------

*WARNING*:
This app is in beta form, and downloading it requires allowing unknown app installs
on your phone. This setting is for your protection, so that you don't install an app that has
hidden malware. You will have to trust that my app is not malware. Additionally, EZ-Rank in theory
should not cause any harm to your phone or its data, as it is a simple app that only requires
a small amount of local storage space which is deleted when you uninstall the app.
However, I cannot guarantee that it will work perfectly for your device. But if you choose to
download it and try it out, I would greatly appreciate it! If you find any bugs or have a
question/suggestion, you can email me at karpenko.ryan@gmail.com. 

To download the app on your phone:
(This is based on my experience installing the app on a Pixel 3a)

From your phone web browser, click on the ez-rank-debug-x.x.apk file inside this repository, then download it.
Here is the link in case you can't find it: https://github.com/ryankarpenko/EZ-Rank/blob/master/ez-rank-debug-0.1.apk
When you open the file, you will be prompted to change your settings for installing unknown apps.
When you select "Settings" from this warning, you will be taken to an app permissions screen. For me it was permissions for Chrome.
Change the permissions setting to "Yes" (or activate the toggle).
Go to your files on your phone, and find the recently downloaded .apk file.
Open it, and you will be prompted to install the app.
You may have to pass one final warning, after which your phone will download the app.
Enjoy!


KNOWN BUGS:
(I will fix these soon!)
1) Clicking an item to edit its name can cause the keyboard to appear over the text box (Pixel 3a)
2) Clicking an item to edit its name does not set the cursor to the beginning of the text box (Pixel 3a)
3) When editing an item's name, clicking outside of the text box when the cursor is not active does not complete the edit as intended (Pixel 3a)
  (It appears 1 and 3 might be related to 2.)
4) After clicking on an item "n" that is on the lower part of the screen which subsequently gets covered by the keyboard (1),
  swiping up to see the item n causes the n-1 item to turn into a edit text box, instead of the nth item.
