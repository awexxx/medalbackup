# Before diving in..
This script is specifically meant for the [Medal.tv](https://medal.tv) service. In short, they're a gaming moment clipping service.<br/>
You'll need to know what the Windows File Explorer address bar is. It's that little bar at the top of your screen that shows where you're at. You can click on that and type in it, keep this in mind!

# This is not finished!
Due to my heaps of boredom, I'm gonna maintain this. Some of this might be come as it might become automated. This is a very early stage of this script!

# What does this script do?
This script is designed to copy your "clips.json" file to the folder this script is located in. Your clips.json stores clip data and is specifically useful in having a backup of in the case of a purge install/PC wipe.

# How do I run this script?
I'm working on improving this, but for now, this is how to do it:
Copy the source code from whatever bat you want to use (ex. the Google Drive one or the local one), create a text doc, and paste it in there.<br/>
![Creating the bat file](http://plaguecraft.xyz/assets/img/medal/clip-backup.png)

You'll need to have your user profile name. Easiest way to type "C:\Users\%userprofile%" (without quotations) in Windows File Explorer's address bar. Whatever shows after C:\Users is your user profile.
Amend the "xcopy" string so the "//user-profile//" field equals your user profile name found in the last step. In my case, my user profile name is "w", so the xcopy string would look like this:

xcopy C:\Users\w\AppData\Roaming\Medal\store\clips.json

Click Save As, and save it as a .bat file.
Then, open cmd, cd to the folder containing the .bat file you just created (right click the address bar in file explorer and copy the address, then type "cd " (without quotations) and then paste the address in), type the .bat name, and you're done!

# Questions?
Open an issue on this repo if you have any issues with this! I'll be more then happy to help!

# To do list!
Finish the Google Drive script<br/>
Make everything automated; eliminate the editing of the file<br/>
Possibly make this with another language (.bat is not my best lmao)<br/>
