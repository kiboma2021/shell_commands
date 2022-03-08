# shell_commands

---ALIAS COMMAND---

To see all aliases that are effect to the current user, type 'alious' in cmd

syntax: alias [-p] [name="value"]

	alias p='pwd'
	alias ls='ls -al'
	alias l='ls -al/etc'  //to display contents of etc folder

To disable an alias, we use '\' e.g

	 \ls

Multiple commands can be included in the same alias:

	alias pl='pwd; ls' // pwd is launched then ls

One can also create two separate aliases simultaneously on a single 
command line:
	alias p='pwd'; l='ls -al'

	alias dir='ls -al | grep ^d' // generates a list of names and information 
		about all the subdirectories in the current directory that
		 begin with d

To remove an alias we use 'unalias'

	unalias rm
