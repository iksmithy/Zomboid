idk anything about programming but I've gotten ChatGPT to make this program lol - it takes the output from this Zomboid mod: 
https://steamcommunity.com/sharedfiles/filedetails/?id=3204323366 (I'm in no way affiliated, just found this mod today and had the thought to make this utility)
and turns it into a mostly usable list for Zomboid servers and 
solo (if you modify your saved_modlists.txt) by taking the list and compiling the Workshop IDs into a list, eliminating duplicates, 
searching the Steam Workshop for each mod and pulling the Mod ID and (if applicable) the Map Folder, 
exporting them to a list in the proper format for Zomboid servers, and that's it.  I also uploaded the executable.
This should allow you to copy/paste the results from the above mod, or browse and select a .txt with the list in it.  

How this works in the real world (ideally):
Subscribe to all your mods on Workshop (including the one linked above)
Launch Zomboid
Go to Mods
Enable all the mods you want
Edit Mod Load Order
Configure your Mod Load Order
Export
Go to ~\\C:\<user>\Zomboid\Lua\ModManagerList\
Either copy/paste the info in that file to the Mod List Processor or convert the ini to a txt
Once the file is uploaded to the Mod List Processor or the list is pasted in the top text box, click Process
Wait
Enjoy your Workshop IDs, Mod IDs, and Map Folders being organized and ready to paste into your configs
