# Bypass "Initialization error 4" on VM Protected Clients.

First, make sure you have x32dbg installed
Then, launch it without an exe specified.
Go to Options > Preferences
And remove any checks except for System Breakpoint

Then, restart x32dbg and launch it with a player .exe specified
Now, click on blue arrow 2 times, go to symbols and select your .exe
Now click Az and enjoy VM Protected strings showing up!

You have to then select .vmpx in Memory Map and do this guide:

Go to the Dump and find an empty space and put your urls in like this:

------------
.example.com
example.com
------------

(Ignore the "-")

Then select your URLs that you just put in .vmpx, right click and then press "Copy address"

Search for roblox URLs

Double click the string roblox.com 

You find yourself at a push instruction for example 0x2029420 or something like that.

Press space and with your copied address replace the 0x2029420 or something like that.

You have to do the same with bgiaas as well.

Then, click File > Patch File and save it.

---------------------------------------------------------------------------------------------

Credits:
	VisualPlugin: telling me a theory
	VMsLover: Checking that theory and writing that guide.
