# This is my notes on the coders computer

## Topic 1 - Choosing A Text-Editor

1. **What is a text editor?**

A text editor is a piece of software that allows you to write and manage text. Some text editors you can download and install on your computer, others you can access online through your web browser.

1. **What are some key features & their associated benefits to consider when choosing a text editor?**

* *Code completion* - saves you time by providing a choice, rather than allowing you to finish typing and possibly encounter typos.
* *Emmet* - it's a kind of short hand that allows you to write your HTML and CSS more efficiently. Some editors have it built in, others as an extension.
* *Syntax highlighting* - is a feature that makes the text you write more noticeable by colorizing the text and changing the color based on if it's an attribute or element. It also makes it easier to find errors as the text is easier to read. 
* *Themes* - allow you to change the color of the background, text, and can sometimes affect other aspects of your text editing software.
   * A popular theme choice: dark background and bright colored text. It can be easier on the eyes/reduce eye strain and fatigue.
* *Extensions* - i.e.,'Work Smarter not Harder' you want a text editor that will allow you to accomplish more with less effort. Choosing a text editor that will grow as you grow.

### Types of Text Editors

* Standard by Computer 
* No bells or whistles, no code completion.
   * Text Edit(MAC)
   * Notepad (Windows)
   * Will vary by name (ex.Gedit) (Linux)
* Third Party Options
* Most are free, most include some or all of the features mentioned previously. They can all be downloaded and installed to your computer from their website.
   * Notepad++ - Free, Windows only
   * Text Wrangler (retired, 2007)
   * BB Edit - Incorporated TextWrangler into it. Free Version and Paid Version ($49.99).
   * Visual Studio Code -Free, made by Microsoft. It's available for MAC/Windows/Linux. Emmet is built in for HTML/CSS. It has ***ALL*** the features mentioned previously.
   * Atom - Free, made by GitHub. It's available for MAC/Windows/Linux. It has all the features.
   * Brackets - Free, made by Adobe. It's available for MAC/Windows/Linux. It has all the features but only supports HTML/CSS/JS
   * Sublim Text - Premium software ($70). It does have a free version. Has all the bells and whistles.

### Text Editors vs IDEs

* Text Editor - a text editor manages text and files, and allows you to edit text.
* IDE (Integrated Development Environment) - is a software bundle; text editor, file manager, compiler, and debugger.

1. **Why is it important as a software developer to be thoughtful when choosing the text editor to use to write code?**

Per 'The Older Coder'

> Choosing a text editor ends up being a very personal choice, as personal as the sports teams you support.

* Choosing the right text editor is about giving yourself the features to help you be more efficient in your work and allow you to grow. Ideally the right text editor will grow with you and continue to push you further. For the most part the different text editors seem pretty similar. It seems simple but the best text editor might be the one that 'feels' the best to use or that you enjoy using most.

## Topic 2 - How Commands are used & which look similar to how you are used to using the GUI File Explorer/Finder.

Command Line (aka a Terminal) - you can have multiple terminals open.
What are they? It is a text based interface to the system. You can type commands and receive feedback.

* Commands - typcially the first thing you type; (ls), (echo) to display messages, 
  * pwd - Print Working Directory (abbreviation) - it tells you your current/present working directory
  * ls - list. Without arguments it will just do a plain listing of the current location. It can be run with (-l) indicates a long list or (-l /etc) which tells not to list our current directory but to list that directories contents. (ls -a) - lists the contents of a directory, including hidden files.
  * CD - Change Directory. If ran without an argument it will take you back to the home directory. It is usually run with a single command line argument, ex. (cd ~/Documents), (cd ../../)
  * file - obtain information about what type of file a file or directory is.
  
* Argument - (-l /home/ryan)
  * Option - the first argument in a command line, used to modify the behaviour of the command. Usually listed before other arguments and typically start with a dash (-)  
  
* Output - most commands produce an output. Others perform a task and don't display information unless there is an error.

* Shell - part of the operating system that defines how the terminal will behave and look after running commands. 
  * Many kinds, one that's most common: *'bash'* 
  
* Shortcuts - ex. commands entered are store in a history. You can scroll back up to run the command again or you can edit the previous commands.
  * Tab Completion - Mechanism to auto complete filling out the path being written.

* Path - whenever a reference is made to a file or directory on the command line it is infact a path, i.e, a path is a means to get to a particular file or directory on the system.

  * Absolute - specifies a location, file or directory, in relation to the root directory - denoted by (/). ex. (ls /home/name/Documents)
  * Relative - specify a location, file or directory, in relation to where we currently are in the system - will not begin with a slash. ex. (ls Documents)
  
  * ~(tilde) - shortcut for your home directory. Ex. (/home/name/Documents) or ~/Documents
  * .(dot) - a reference to your current directory. 
  * ..(dotdot) - a reference to the parent directory.
  
  * /etc - Stores config files for the system.
  * /var/log - Stores log files for various system programs. (You may not have permission to look at everything in this directory. Don't let that stop you exploring though. A few error messages never hurt anyone.)
  * /bin - The location of several commonly used programs (some of which we will learn about in the rest of this tutorial.
  * /usr/bin - Another location for programs on the system.
  
* Important to remember
  * Everything is a file under Linux - Even directories.
  * Linux is an extensionless system - Files can have any extension they like or none at all.
  * Linux is case sensitive - Beware of silly typos.

### How it's similar
1. 
1.
1.
1.


