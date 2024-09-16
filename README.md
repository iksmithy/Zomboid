idk anything about programming but I've gotten ChatGPT to make this program lol - it takes the output from this Zomboid mod: <br />
https://steamcommunity.com/sharedfiles/filedetails/?id=3204323366 (I'm in no way affiliated, just found this mod today and had the thought to make this utility) <br />
and turns it into a mostly usable list for Zomboid servers and <br />
solo (if you modify your saved_modlists.txt) by taking the list and compiling the Workshop IDs into a list, eliminating duplicates, <br />
searching the Steam Workshop for each mod and pulling the Mod ID and (if applicable) the Map Folder, <br />
exporting them to a list in the proper format for Zomboid servers, and that's it.  I also uploaded the executable.<br />
This should allow you to copy/paste the results from the above mod, or browse and select a .txt with the list in it.  <br />

How this works in the real world (ideally): <br />
Subscribe to all your mods on Workshop (including the one linked above) <br />
Launch Zomboid <br />
Go to Mods <br />
Enable all the mods you want <br />
Edit Mod Load Order <br />
Configure your Mod Load Order <br />
Export <br />
Go to ~\\C:\<user>\Zomboid\Lua\ModManagerList\ <br />
Either copy/paste the info in that file to the Mod List Processor or convert the ini to a txt <br />
Once the file is uploaded to the Mod List Processor or the list is pasted in the top text box, click Process <br />
Wait <br />
Enjoy your Workshop IDs, Mod IDs, and Map Folders being organized and ready to paste into your configs <br />
