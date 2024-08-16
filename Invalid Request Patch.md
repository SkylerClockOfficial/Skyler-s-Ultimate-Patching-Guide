# Invalid Request Patch

1. Open your client on x32dbg
2. Go to the "Symbols" Tab and double click "robloxplayerbeta.exe" or "robloxapp.exe"
3. Right click ----> Search for ----> Current Module ----> String Refrences
4. Search "invalid request"
5. In every single one there is a jne or je above it, change it to jmp
6. Save the file
