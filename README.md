This is all old and chunky code that I did when I was a beeginer. If you only need the functionality you can download in the releases tab since it does work.

You are better off doing your own script if you want to look at the code LUL.

# DogSon-Parser
If you need help/assistance make sure to join this Discord server: https://discordapp.com/invite/wUqukba



# HOW TO USE:
This tool is a very simple tool to use. 

Before starting: Every time after you drag and drop something you will have to press enter.

When you open this tool it will ask you for the file extension. Here you have to type “vmf” or “map” depending on the file extension of what you want to parse.

If you type map:
	You will be asked if you want to also parse the mapents. You will have to write “Yes” or “No” depending on what you want to do. 	If you 	type “Yes” you will be able to drag and drop the mapents file. If you type “No” you will automatically skip this part.
	After this you will be asked to drag and drop the .map file. Just drag and drop it and the parser will start parsing.

If you type vmf:
	You will be asked to drag and drop the vmf file. Just drag and drop it and the parser will start parsing.

# WHAT WILL THE OUTPUT BE?
After parsing any file (does not matter if its a .vmf or a .map) the output will be a “.json” file which will always come with this structure:

	[
	  {
	    "Name": "example_name",
	    "PosX": "0.0000",
	    "PosY": "0.0000",
	    "PosZ": "0.0000",
	    "RotX": "0.0000",
	    "RotY": "0.0000",
	    "RotZ": "0.0000",
	    "Scale": "1.0000"
	  }
	]

This type of structure can also be found in [c2m's](https://github.com/sheilan102/C2M)
 json files.

Also, if you parse a .map there will be a list of models exported, it would be called “filename_xmodelslist.txt”

# EXTRA INFO:
mapEnts can be found after exporting from [c2m.](https://github.com/sheilan102/C2M)

The only difference between [c2m's](https://github.com/sheilan102/C2M) json and DogSon’s json is the arrangement of rotations. DogSon exports as “xyz” while [c2m](https://github.com/sheilan102/C2M) exports as “yzx.”

# For those who download the source code:
You will need [colorama](https://pypi.org/project/colorama/) in order to run this script.

**If you are downloading a [release](https://github.com/AgenteDog/DogSon-Parser/releases) you can ignore this.**
