# MCEE_Log_Test
 WSS Log for Minecraft Education Edition
This is the WSS stuff I created back in the End of 2021 to be able to log Minecraft Education Edition using a WSS connection.  

It also works on Bedrock provided you enable Minecraft to be able to do loopbacks.
This is done using the mysterious command in an elevated cmd prompt: 
CheckNetIsolation LoopbackExempt -a -n=microsoft.minecraftuwp_8wekyb3d8bbwe

 It isn't very polished, it is basically printing everything to the log file, headers and all so the log file gets all sorts of info that isn't really useful but I've never gone back to try to refine it.

To use the program in windows, you just need the .exe file.  You run it and it will open the wss console screen.  Copy the connection command and paste it into chat on Minecraft.  It should open a connection between Minecraft and the WSS.  Now you can type something in chat on Minecraft and it should show up on the console.
Also, in whatever folder you are running the program from, you should get some folders created in which you will find log files.  The folders should be following a year, month and day format so you can go back and find logs from a particular day if you were running the program that day.
