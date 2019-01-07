# VariousTools
There are various tools for Mac collected by myself, all of them are beneficial to efficiency.

## Chrome Extensions

###	[Tabbo](https://chrome.google.com/webstore/detail/tabbo/hedbkonckghacebehjebpfknhdbobiko)
This is an extension of Chrome browser. It is mainly used to manage tabs between different chrome windows. 
**Please note that here windows means the instances of chrome(i.e. the process of chrome)**

* Requirement: Because my requirement is that typically I need to use two chrome windows. One at Mac and the other one at the expand screen. Therefore sometimese I need search the Internet at Mac and them pop off the webpage to the expand screen chrome, so that I can code at Mac and also see the webpage in the same time. 
*Therefore, I need a shortcut to pop off the webpage to the expand screen quickly*.

* My settings:
	* pop off the tab: command + p
	* move current tab to another window: command + e


## Mac Tools

### [Karabiner:collision:](https://github.com/tekezo/Karabiner-Elements)
Karabiner is a Mac tool which is used to customize keyboard. Not only the simple key substituation, but also various complex mapping rules are implemented. 

* Requirement: It is weird that my Mac is not senstive for switching input sources with default shortcut key, in most cases I need to press command + space repeatedly many times, it is worse that the input sources can be switced all alone.  Therefore I want to use a single key to change input sources. My solution is mapping the right_shift to f17, and then change the switching input sources shortcut key to f17 at system preference. 
**Please note that Karabiner support that only press right_shift to change input source, if using combinated key like right_shift + slash, it is also the original right_shift command(i.e. right_shift can also be used as modifier key).**

* My Settings: It is a extremely powerful tool to remap keys as our aspiration. Here only list some rules, and you can explore endless possibilities in this tool. My settings profile can be download here:[Karabiner Profile](https://github.com/gzrjzcx/VariousTools/blob/master/AlexSettings.json)
	* Press right_shift alone produces F17 -> switch input sources.
	* Press left_shift + tab produces F18 -> switch screen sources.
	* Press right_command alone produces triggle full screen.
	* Press right_shift + a to open activity monitor.
	* Press 'right_shift + \' to open terminal

### [Keyboard Maestro:collision:](https://www.keyboardmaestro.com/main/)
This is also a very fantastic tool to help us manage Mac well, it allows us to use macros(work flow) to control Mac including launching application, click the mouse and so on. What it can do beyond your imagination!

* Requirement: Because I want to implement that using left_command to change input source to ABC, and right_command to change input source to the other language, therefore I need to use Maestro to define macros.

* My Settings: 
	* ![change_to_ABC](https://github.com/gzrjzcx/VariousTools/blob/master/res/maestro.png|width=48). 
	* Please note that there is a bash shell script to get the name of current input source, this is can be seen below. 

















