S2V (Slide2View) v0.42 (3-9-2008) by A_C
=========================================
S2V is a stylus-free picture viewing application. It can also be used to set up the wallpapers for S2U2 (v0.97 or later); assign a pic to a contact; set it as Today's wallpaper; or send it via MMS/email.

Prerequisition:
===============
- WM5 Phone or WM6/6.1 Professional devices
- free RAM: at least 6M for QVGA

Changes of v0.42
================
- fixed the occasional bug that S2V quit unexpectedly when viewing a particular folder.
- added the options to change the sorting menu symbol. It's only usefull for those devices that cannot display the triangles on the sorting menu. How? Create a registry value "AscendingSymbol" (String) at \HKEY_CURRENT_USER\Software\A_C\S2V\, set the content to whatever you want, e.g. "^", or even a word "(ascending)". Create another one called "DescendingSymbol" for the descending order.
- fixed some minor bugs.

Changes of v0.40
================
- added sort option by time or name.
- added thumbnail pic cache (the cache folder can be custom by the registry value "CacheFolder" at \HKEY_CURRENT_USER\Software\A_C\S2V\).
- added send function to send a pic via MMS/email.
- added sliding effect when zooming a pic.
- added support to RealVGA.
- reduced the chances of blank screen when a device has enough memory.
- separate CAB files for QVGA(low-res) & VGA(high-res) devices.
- changed some menu labels; for non-English translation, pls refer to the lang.ini file.
- fixed some minor bugs.

Changes of v0.38
================
- added a delete function.
- added option to open a pic through the command switch (for advanced users, you can now associate pic files to be opened by S2V).
- added some shortcuts: ANSWER key to quit; END/OK key to minimize; tap the top right corner to minimize.
- reduced the RAM usage a little.
- reduced the contact pic size so as to reduce the chance of Outlook sync error (but for VGA or above devices, there is still chances that the pic will over the size that Outlook can handle).
- all system icons are live when S2U2 (v1.00 or later) is already running in the background.
- fixed the issue that some devices cannot run in Landscape mode.
- fixed some minor bugs.

Changes of v0.35
================
- added option to set a pic as Today's wallpaper.
- removed the dependancy of S2U2 version; you can install whichever version of S2U2. But if you want an instant wallpaper change, only S2U2 v0.97 or later can do that.
- removed the start-up animation which caused some problems on some devices.
- removed the forced lowercase view when browsing folders.
- enlarged the subfolder buttons (pls press this button when you want to view the subfolders, instead of posting a complaint)
- fixed some minor bugs.

Changes of v0.32
================
- fixed it could not execute on some devices.
- fixed some photos could not be cropped.
- fixed some possible memory leak.
- in sync with S2U2 v0.99c.

Changes of v0.30
================
- better memory management, thus fixed the issue that it suddenly quits but also increased the minimum free RAM requirement.
- added rotation animation.
- added DPAD navigation (left & right) when viewing or zooming.
- when zooming, double-tap the screen or push the DPAD-ACTION to return to the normal view.
- added option to set a folder as the S2U2 folder.
- added option to assign a pic to a contact.
- when setting a pic to be a S2U2 wallpaper/contact pic, the zoomed pic will be cropped as the wallpaper/contact pic.
 (except GIF file cannot be assigned to a contact)
- when browsing folder which has sub-folder, either press the folder to view that folder; or press the arrow to drill down.
- added multi-language support (edit the lang.ini & save it as an UNICODE file).
- changed some layout.
- some bugs fixed.

Changes of v0.20
================
- added ZOOM IN/OUT & PANE function - use the Up/Down DPAD to zoom in/out; tap & move the screen to pane.
- added ROTATE function - slide the left-side screen from top to bottom to rotate 90 degrees anti-clockwise; slide from bottom to top to rotate 90 degrees clockwise; when sliding the right-side screen, the rotation will be opposite.
- added auto-save the last browsed folder.
- added auto-save the last rotated orientation.
- added switch command to open a destinated folder, e.g. "s2v.exe" \storage card\my pictures
- added visual feedback when selecting a thumbnail or folder.
- fixed the blank screen problem on some devices. (if you still have this issue, read the FAQ below)
- some bugs fixed.

v0.01
=====
- initial release.

Installation:
=============
- Under your PC/MAC/device, extract the content of the downloaded file & copy the CAB file to your device.
- If you have S2U2 installed, pls upgrade it to v1.00 or later. And Make sure S2U2 is stopped when installing S2V, otherwise S2V cannot be started.
- Under your device, run any File Explorer application; go to the folder where the CAB file is copied; run the CAB file.

Operations:
===========
- Slide the screen to view the previous or next picture (or press the DPAD left/right);
- Slide on the left-side screen from top to bottom to rotate 90 degrees anti-clockwise; slide from bottom to top to rotate 90 degrees clockwise; when sliding on the right-side screen, the rotation will be opposite.
- Press DPAD Up to Zoom-in or Down to Zoom-out; double-tap the screen or push the DPAD-ACTION to return to the normal view.
- Slightly press the screen to call up the lower menu.
- Press the Back button at the Thumbnail screen to browse folders.
- When browsing folders, if there is an Arrow button next to a folder, it means that folder has subfolders. Press this Arrow button to view the subfolders.
- Shortcuts: ANSWER key to quit; END/OK key to minimize; tap the top right corner to minimize.

Known limitations & FAQs:
=========================
Q. Do I have to install the old version before using this version?
A. No.

Q. How to use the .CAB file?
A. http://www.google.com/search?q=install+cab

Q. Do I have to install S2U2 before installing S2V?
A. No.

Q. Can a GIF file be assigned to a contact?
A. No.

Q. When viewing GIF file, there is no animation?!
A. Yes.

Q. After assigning a photo to a contact, the Activesync on the PC shows an error!
A. It's because the size of the assigned photo is too large for outlook to handle. You may manually press the sync button once more to dismiss the error, but it will not be saved in outlook.
A. Upgrade to v0.38 or later.

Q. After running S2V a while, the ZOOM function/folder browsing does not work!
A. It's because your device is running out of free memory.

Q. When browsing folders, I cannot view the subfolders?! S2V always say "no picture here"?!
A. It's because the pics are sit at the subfolders. If a folder has subfolders, an "ARROW" button will be displayed next to it. Press that "ARROW" button will show the subfolders.

Q. After assigned a pic as Today's wallpaper, then change to Landscape mode, the wallpaper does not work?!
A. You have to assign another pic as the Landscape wallpaper as well.

Q. After assigned a pic as Today's wallpaper, it does not work?!
A. Try other today theme; some themes have problem when wallpaper is altered.

Others
======
Q. Is S2V free?
A. Yes, but any donation is welcome (https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=ac_dl%40hotmail%2ecom&item_name=S2V%20Donations&no_shipping=0&no_note=1&tax=0), thanks.

Special Thanks
==============
- Forum fellows at xda-developers (http://forum.xda-developers.com). Thank you for your testings, comments, supports & patience.

Enjoy!
A_C