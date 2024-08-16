# Name And ID

1.  Open x32dbg
2.  Open your client
3.  Once you have x32dbg open, spam the run button, symbolized as a blue arrow pointing to the right. Once you have done it eunogh, the roblox application should open up in the background. If it is frozen, go back to x32dbg and keep spamming the run button.
4.  Once the application stabilizes, create a new game. The application will freeze, so keep spamming the run button until it frees up.
At this point, make sure the command bar is shown in the roblox application. If not, go to View<Toolbars Then Click Command.
5.  Run this line of code in the command bar "game.Players:CreateLocalPlayer(0):LoadCharacter()" (Without Quotes).
6.  Go back to x32dbg and go to the symbols tab. Look for the roblox application and click it. Then search for "_CxxThrowException" (Without Quotes). Right click the result and click toggle breakpoint.
7.  Try renaming the player, or changing their id in Players<Player. The application should seize up, this is good. DO NOT SPAM RUN.
8.  Go back to x32dbg, go to the CPU tab, There should be a window just above "Time Wasted Debugging" in this tab. Go to the very top value that is currently shown on that window (Dont scroll up), and right click it. Click follow DWORD in dissassembler. or Follow in dissassembler.
9.  Scroll up just alittle to find a dotted arrow pointing to the selected value. The arrow should be coming from a bit that starts with jne. Double click this bit and change the "jne" part to "jmp".
10. There should be a Patches icon in x32dbg, indicated by a Band-Aid. Click this, then click "Patch File". Now you must name the file.
