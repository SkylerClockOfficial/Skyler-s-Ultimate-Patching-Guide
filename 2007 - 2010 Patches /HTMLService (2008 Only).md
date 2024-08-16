# 2008 HTMLService Patch

1.  Open x32dbg
2.  Open your client
3.  Go to the "Symbols" tab and double-click your client (e.g RobloxApp.exe)
4.  Then click the "Az" button at the top
5.  Wait for it to load then search "HtmlService"
6.  There should be about 1 result
7.  Double click the first one
8.  Scroll up a few lines until you find "jne (module name).(hexadecimal)" (example: "jne Roblox.63FADC")
9.  Click on the line containing "jne"
10. Press the spacebar
11. Replace the "jne" with "jmp" (DO NOT ALTER ANY OTHER LINES)
12. Press the enter key
13. Press the CTRL+P keys
14. Double-click your client name (ie: Roblox.exe)
15. Press Patch File
16. Save your file
