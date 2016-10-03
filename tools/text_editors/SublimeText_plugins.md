My list of SublimeText Plugins:
==============================
1. **Installation Management**
	* Package Control
2. **Theme & Color Scheme**
	* ColorSublime: a plugin allowing to install many color schemes (including Acai)
	* Moka theme: apply Moka Light theme after installation by user preferences setting:
	```
	{
		"theme": "Moka Light.sublime-theme"
	}
	```
	* Material Theme
3. **Tools & Utilities**
	* Side​Bar​Enhancements
	* Shell Turtlestein:
		Plugin for running arbitrary shell commands in SublimeText (Ctrl + Shift + C to open command prompt)
	* Markdown Preview
	* Bracket Highlighter
	* Sublime​AStyle​Formatter:
		C/C++/C#/Java code formatter/beautifier with AStyle.
	* Local History:
		For maintaining a local history of files
	* FileDiffs:
		Show difference between files
	* SyncedSideBar:
		sync project sidebar (folder view) with currently active file.
4. **Preference Settings**
	* Auto-indent (reformat) code:
		Select text -> Edit -> Line -> Reindent. To add a key binding for the command, open Preferences -> Key Binding - User, add:
		```
		{ "keys": ["ctrl+shift+o"], "command": "reindent"}
		```
		to the binding list.

