IMPORTANT UPDATE!!!!!

Rockstar Games just released an Update of "Rockstar Games SDK" in the RGL launcher.
and I think they patched the loophole to use FSL to get into GTA Online.

So if you try to join GTA Online with FSL and YimMenu loaded, 
it will directly kick you back to story node.

I'd suggest to not use YimMenu again,
and with FSL you will not be able to join GTA Online,
so just re-enable BattleEye and delete the "version.dll" file from the dir of GTA V


![Screenshot (1022)](https://github.com/user-attachments/assets/db704485-62b1-47ac-9256-e3591459836a)

So to roll back the changes that were made to use FSL and to use YImMenu, 
You'd have to undo everything.

1. Re-enable BattleEye :
   
   - Open Rockstar Games Launcher
   - Go to settings tab
   - Check the BattleEyE option to enable it.
   - if you made a "commandline.txt" fiel and put the "-nobattleeye" launch argument,
     just delete that argument or delete the file itself.
  
3. Delete "version.dll" file from BattleEye, otherwise it will flag "blocked from loading"
   on BattleEye again and again. This is necessary because with FSL you won't be able to
   load into GTA Online.

And after rolling back changes, you will be able to play GTA Online normally without any issues!


and Don't worry about accoutn suspension, when you unload FSL from GTA V,
it will use the Server based data of your multiplayer data, so you're safe!


I'll look forward to find another trick to use YImMenu, or maybe never
Who knows
