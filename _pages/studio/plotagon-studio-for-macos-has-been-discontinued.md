---
layout: page
title: Plotagon for MacOS discontinued
---

# Plotagon Studio for MacOS has been discontinued

Plotagon is discontinuing the Plotagon Studio application for Mac due to incompatibility with the new MacOS 10.15 (“Catalina”) Operating System. New users will no longer be able to sign up for trial accounts or download the Mac version of the application.

If you are a Mac user with an existing paid Plotagon Studio subscription, you have three options:

## Option 1: Before you upgrade your Mac to Catalina
As long as your computer is running MacOS 10.14 (Mojave) or earlier, Plotagon Studio 1.9.3 will continue to function on your machine for the foreseeable future. However, because this is an end-of-life application, we will be unable to fully warrant the performance or provide full support.

If you choose this option, then we suggest you immediately export any videos that you wish to keep, and use the Export Plot function in case you wish to continue working on them on a Windows computer later (see below).

## Option 2: Continue working on Plotagon Studio for Windows

You can copy your characters and video scripts over to a Windows computer and continue your work.  If you have not yet upgraded your Mac to Catalina, then do the following:

  1. Use the **Export Plot** function, which will create a .plot file containing the characters, script, and voice recordings for each video.
  2. Put the .plot files on a USB stick or network drive, and then connect it to your Windows computer.
  3. [Download](https://plotagon.com/#getstudio/) and install the Plotagon Studio application on your Windows computer. You can log in with the same Plotagon username and password.
  4. Use the **Import Plot** function, browse to find the .plot files on the USB stick or network drive, and then import the plots into the application. Your characters and scripts will then appear in Plotagon Studio on the new Windows computer.

If you already have upgraded your Mac to Catalina and are unable to start the application, you can still transfer your files over to a Windows computer. Here’s how:

  1. On your Mac computer, locate the **Documents > Plotagon Studio** folder. Copy this folder onto a USB stick or network drive. __This is the source folder.__
  2. [Download](https://plotagon.com/#getstudio/) and install the Plotagon Studio application on your Windows computer.
  3. Find the Characters and Bundles folders.If you are the only user using Plotagon Studio on the machine, it should be easy to find the character files:
      1. Go to Programdata folder (usually C:\\programdata). This folder may be hidden.
      2. To get there if it is hidden, just paste %programdata% into the **Start** menu search field and hit **Enter**.
      3. Inside the Programdata dir, you should find at least one directory starting with the name: `PLOTAGON\PROGRAMDATA` then followed by some long string of characters.
      4. In there you will find plots in the **/Plots** folder, and characters in the **/Bundles** folder.If there are multiple users using Plotagon Studio on the machine, do the following to identify where the Plotagon data is found.
      5. Enter into search bar: %appdata
      %..\\roaming\\Plotagon Studio\_DATAPATH
      6. There will be a .json file, open this with notepad, and the path for your specific user will be in the file.

  1. Connect the USB stick or network drive to your Windows computer.
  2. Copy the contents of the source folders in the USB stick or network drive over to the Windows computer:
    * Plotagon characters are in the **Bundles** subfolder. Copy the contents of the Bundles folder in the source folder and place them in the /**Bundles** destination subfolder.
    * Plotagon scripts (“plots”) are in the **Plots** subfolder. Copy the contents of the Plots source folder and place them in the **/Plots** destination subfolder.
  3. Restart the Plotagon Studio application and log in. (You can use the same Plotagon username and password. All your old characters and scripts will be present. Open the scripts and hit the play button to be sure everything has worked properly! When you are positive that you have successfully transferred over your characters and scripts, then you can delete the **Documents > Plotagon Studio** folder from your Mac.

## Option 3: Contact us
Email Plotagon and describe your situation. Be sure to include the email address that is associated with your Plotagon Studio account. We will be happy to assist you.

If you have any questions about this process or concerns about your account, please let us know, and we will assist you promptly. On behalf of the entire Plotagon team, thank you for your patience.

Best regards,
_Team Plotagon_