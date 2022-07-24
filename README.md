# Script-Dumper [COPY CLIENT SCRIPTS & FIND CLIENTSIDED ANTICHEATS]
Hello! Welcome to this Script Dumper!
This script uses decompile and Drawing Library.
### A really quick time to save all of the scripts
This script takes like 15 seconds to save for KRNL, and for Synapse X takes like 30/20 seconds to save all of the scripts (My friend tested it)
### How to use?
Its as simple as that, you just run the script.
The path for the folder is **workspace**. (YourExploitFolder => **workspace**)
There will be paths like: **Players**, **ReplicatedStorage**, **LocalPlayer**, **ReplicatedFirst**, **Workspace**.
### How does it look like?
It just is a text that uses "Saving...", "Readying up folder..." and then saves.
Here is a video:


https://user-images.githubusercontent.com/57674319/180648479-a0535fa3-6ee4-4daf-8445-0b85d49cdf70.mp4

This is how an decompiled script should look like:

![image](https://user-images.githubusercontent.com/57674319/180648586-ac93b9f6-ae9c-459b-8cbe-51d2449fd36d.png)

This is how the folder should look like when ran:

![image](https://user-images.githubusercontent.com/57674319/180648644-f753cad9-a9eb-44ee-9a12-abe957e0a59a.png)

### Result after decompiling

KRNL:
```lua
local v1 = game
local v2 = v1.Players
local v3 = v2.LocalPlayer
local v4 = "This is a test!"
v3:Kick(v4)
```
Synapse X (I don't own Synapse X, so it might not look realistic):
```lua
local I__LocalPlayer__I = game.Players.LocalPlayer
local v1 = "This is a test!"
I__LocalPlayer__I:Kick(v1)
```
