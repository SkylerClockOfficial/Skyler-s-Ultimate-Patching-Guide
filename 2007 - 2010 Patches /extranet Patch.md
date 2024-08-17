# extranet Patch (2006-2007)

1. Install x32dbg (Do not use x64dbg or it won't work)
2. Extract x32dbg Anywhere
3. Open up x32dbg
4. Download any client from any archiving source Like The Roblonium Archive
5. Extract your client
6. Drag RobloxPlayerBeta.exe or RobloxApp.exe onto x32dbg
7. Go to the "Symbols" tab and double click robloxplayerbeta.exe or robloxapp.exe
8. Right click ----> Search for ----> Current Module ----> String Refrences
9. Wait until it finishes
10. String search "extranet" and Double click the string
11. Check for a jne/je and change it into jmp
12. Save the file
