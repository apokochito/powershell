# powerShell

- **Getting Started**
  
  - PowerShell
    
    It is an object-oriented automation engine and scripting language with an interactive command-line shell.
  
	PowerShell offers both a command-line option and an integrated scripting environment (ISE).

  - Command line
	
	powershell.exe
	
  - Scripting
	
	powershell_ise.exe
	
	Scripts are stored in .ps1 files, to run them you need to do right-click the file and select "Run with PowerShell".
  
  - Restrictions
  
	Enter > Get-ExecutionPolicy and you'll know if you're restricted to run scripts.
	
	Restricted — No scripts are allowed. This is the default setting, so you will see it the first time you run the command.
	
	AllSigned — You can run scripts signed by a trusted developer. With this setting in place, before executing, a script will ask you to confirm that you want to run it.
	
	RemoteSigned — You can run your own scripts or scripts signed by a trusted developer.
	
	Unrestricted — You can run any script you want.
	
	To chage your restrictions you can run this command > Set-ExecutionPolicy RemoteSigned

- **My first script**
  
  - Create a new file called task.ps1 (using notepad command) and write some commands.
  
  - Lastly, execute your new script by prefixing its name with **>& .\task.ps1**