# Custom-Firefox-Icon-Tutorial.
**PLEASE NOTE THAT THIS GUIDE ONLY CHANGES THE NEW TAB ICON AND VERY VERY FEW OTHERS! It also can change your program icon if you choose.**
# DISCLAIMER!
**If you are using a different browser than firefox or librewolf, then get the paths yourself. The omni.ja should still be in the browser folder of your firefox install/fork.**
This is a tutorial on how to change the icon of Firefox. Firefox is a web browser. If you want to change the icon outside of the web browser. I Would recommend doing this with Librewolf due to this being mainly tested on it, as i originally came up with this idea while playing with librewolf.

# omni.ja's location.
This section is simply to tell you where omni.ja is stored. Its usually in the "browser" folder in your firefox installation folder, usually in C:\Program Files\Mozilla Firefox\browser\omni.ja. For librewolf, its usually stored in C:\Program Files\Librewolf\browser\omni.ja.

# Step 1: Extract omni.ja.
To extract omni.ja (The file containing the logos), we need a regular tool to open it. Use 7-Zip, as it is most-likely to work. Rename omni.ja to omni.zip or open it with 7-zip, Create a folder called "omnimod" in the browser folder. (You can call it whatever you want.) Then select all the files in the root of the omni.ja in 7-Zip, and drag and drop it to the omnimod folder. If windows asks you for administrative permissions to move the files, then confirm it.

# Step 2: Find the logos.
To find the logos, go to the folder that you copied omni.ja's data to, Go to chrome, go to browser, go to content, then go to branding. All the logos are in there.

# Step 3: Adjust the logos to your liking.
Get the image you want to change the logo to. Modify your image and rescale it to 16x16. Save it as icon16.png, then modify the image but this time scale it to icon32.png at a 32x32 resolution, and do the same thing but name it icon48.png and scale it at 48x48, Do the same thing but save it as icon64.png at 64x64 scale, and then finally do it but save it as icon128.png at 128x128 scale.

# Step 3.5: Modifying the other firefox logos (Optional)
Optional, but you can also rescale your image to 192x192 resolution and save it as about-logo.png, this will change the icon in the about. If you do this, i recommend you also save it again in SVG Format as about-logo.svg. You can also modify about.png to your liking. I Would recommend just making your own version of this image, and scale it at 300x236 resolution. You can also modify about-logo-private.png (192x192) and about-logo-private@2x.png (384x384) to your liking, but that isn't at all needed. We're just focusing on the main logo here.
![image](https://github.com/user-attachments/assets/dab4ccbb-73bc-4b28-8356-a4ecda15404f)

# Step 4: Re-archive omni.ja.
Like how we were able to just open omni.ja, its really just an uncompressed zip file. Use 7-Zip or another program to recreate the archive containing everything in omnimod. Make sure you save it as omni.zip withOUT Compression enabled. In 7-Zip, set the compression level to "0 (Store)". Rename omni.ja to omni.jaOLD (You can rename it back to omni.ja to revert our changes, this is just for backup reasons.), then rename our newly-created omni.zip to omni.ja. Re-open firefox, and if nothing wrong happened, the icon should now be our custom images!

# Step 5: Change the actual program icon.
If you are using Librewolf, simply just convert your image to a .ico file. (Probably store it as a resolution that is a square. For example, 32x32 is fine. 64x64 is too. But i have not tested.) And save it as librewolf.ico. Probably rename the old librewolf.ico to something like librewolfOLD.ico. The modifying ico file doesn't do anything to my knowledge. So probably use step 5.5 instead.

# Step 5.5: ACTUALLY Change the actual program icon.
To actually modify the icon (The one that shows up on your taskbar usually, or in file explorer), Use a tool like Resource Hacker to modify firefox.exe. (Or librewolf.exe) Replace the icon by right clicking the Icon folder, and clicking Replace icon. Select a .ico Version of your custom icon, specifically one that is rescaled to a square resolution like 32x32. Click save as, then save it in a folder like Downloads as firefox.exe. (Or librewolf.exe, whichever you are using), Rename the firefox.exe in your firefox installation to something like firefoxOLD.exe (same with librewolf, name as something like librewolfOLD.exe), then move the firefox.exe (Or librewolf.exe) into your firefox install folder. You should be done now. Once re-opening firefox, almost all icons should be changed.
If you would like to change individual icons, Open the folder in resource hacker called "Icon groups" and change each logo to your version by right clicking the one you wanna change. You can click them to view. This has been done in the pre-mod.

# Completed
Thats pretty much it! Hopefully this was helpful. You can try to request to have me make any changes to this guide if needed, or ask for help. I Rarely check on github (Usually every like 3 to 8 months), so don't expect much help. The program versions i used are down below, along with a link.

[7-Zip version 21.07](https://github.com/Breelandthecat/Custom-Firefox-Icon-Tutorial/blob/main/7z2107-x64.msi)
[Resource Hacker 5.2.6/Build 425](https://github.com/Breelandthecat/Custom-Firefox-Icon-Tutorial/blob/main/reshacker_setup.exe)

# Using Premade Assets (Unrecommended, because by the time you read this, librewolf or firefox will probably be updated by now.)
If you don't want to make assets or need to just test, you can use the pre-made assets in premadeassets.zip. You can get the pre-made assets [here.](https://github.com/Breelandthecat/Custom-Firefox-Icon-Tutorial/blob/main/premadeassets.zip) Probably either just import the assets yourself or something. To apply the in-program icons, then replace the omni.ja with the pre-made asset mods. This can break some things though, or revert updates that added or changed stuff in there. Probably do it yourself. This is just here if you need.

Basically, replace librewolf.exe with librewolfPreModded.exe, and rename the PreModded EXE to just librewolf. With firefox, rename firefoxPreModded.exe to just firefox.exe. And replace omni.ja in Librewolf with the pre-modded librewolf omni.ja. For firefox, use the pre-modded firefox omni.ja.
