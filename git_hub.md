# Review of terminal commands
- pwd - show the current working directory
- touch - create a new file 
- code . - pull up the vs code
- mkdir - makes a folder or directory
- ls - lists files and folders in your current directory
- cp - copy command, copies a file, uses two arguments 1(what are you copying) 2(where is it going).
- rm - removes/deletes files and folders
- mv - moves and renames files and folders
- cd ,,/../../ (takes you back 3 directories)
- cd - (jumps you back to a previous directory)
- control + L - will clean off previous commands
- open . (opens gui, graphical user interface)


# About GitHub

## Git -

**It is about Sharing Code and Collaboration**

***What exactly is Git?***

	- It's a distributed version control system
	- stores data in a file system made up of snapshots
	- It lets multiple developers to work on the same code
	- A history of changes to your files
	- The ability to view, apply, and remove those changes
	- Keep all of your project files in one repository
	- Each time you save a changed version of your project - called commit - Git creates a snapshot
	- Key attributes of Git: Snapshots, Local Operations, Tracking Changes, Loss of Data, States (committed, modified, staged)

***Without Version Control System*** 

	- One folder with multiple files in the same folder with slight name changes, being tracked
	- Git manages this version

**Local Version Control vs Centralized Version Control vs Distributed Version Control**

	- LVC - A Local VCS entails one database on your hard disk that stores changes to files.
	- CVC - This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process (by eliminating the need to involve all local databases)
	- DVCS - addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.
		- DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.
		- Because the DVCS allows for multiple mirrored repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows.


***It uses a commit***

	- Commits represent each successive version of a file or files
	- Each successive version creates a new snapshot on the timeline of the project
	- Vc allows us only one file but we can still go back and review previous versions. Manages the changes along the way
	- Each commit snaphot has a label that points to it
	- HEAD = the label meaning 'you are here' (the most recent version)
	- You can also assign messages to commits
	- Messages are like writing a caption for your snapshot

***Summary of GiT***

	- You use git to take snapshots of your code at points in time
	- Git keeps a history of what those snapshots look like
	- Git has a special label, called HEAD, tat means "You Are Here"
	- Usually you give a snapshot a label called a message
	
***History of GiT***
	- Began with the. open source software project Linux kernel
	- Developers of this project began using a DVCS called BitKeeper in 2002.
	- In 2005 - tension between Linux kernel community and the company behind BitKeeper, the DVCS' gratis status was revoked. Linus Torvalds, the chief architect of the Linux kernel, began creating Git. Git was similar in design to BitKeeper. It allowed for non-linear development via multiple branches, could support large projects, strong menchanisms preventing corruption, and a simple design. Has become one of the most utilized VCS in the world.
	

***What About GitHub?***

GitHub is the application that uses Git. GitHub adds some additional features on top of Git. Ex. Amazon has GitFarm. GitHub is by far the most popular/a user interface for Git. 

	- Is. A way to share code with others
	- An online place to store your code
	- It uses Git to help you manage your teams work
		○ Version tracking
		○ Reviewing changes
Keep changes separate until you want to add them in

***Some Elements of using Git***

- Seting up a Repository
	- To change: `$ cd test` (cd = change directory)
	- To use the git initcommand: `$ git init` (Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.)
	- Start tracking repository files: `$ git add *.c $ git add LICENSE $ git commit -m “any message here”` (Now, your files are tracked and there’s an initial commit.)
- Cloning
	- Creating a copy of an existing Git repo from a server: `$ git clone https://github.com/test`
	- To clone a repo into a directory with another name of your choosing: `$ git clone https://github.com/test mydirectory`
- Local Repository Structure
	1. Working Directory: The actual files reside here.
	2. Index: The area used for staging
	3. Head: Points to the most recent commit
- Life Cycle of File Statue
	1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
	2. You stage the modified file.
	3. Then, you commit staged changes.
- Check File Statue
	- `$ git status`
- Track a single file
	- `git add filename`
- Track All Files
	- `$ git add *`
- To see information regarding chages to be committed
	- `$ git status`
	
**Someother items/actions you can do:**

[Click Here to see the Git Tutorial A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

Commit a File, Commit All Changes, Push Changes, Stash Changes, Seeing your remotes, adding remotes, fetching, pushing, renaming/removing remotes, undoing actions, unstaging a file, undoing a committed snapshot, unmodifying a file, creating a new branch, switching branches, create a branch and check-out, list > branches, merging, fast-forward merging, no fast-forward, three-way merge, fetch and merge, deleting branches, preview changes, listing branches, etc.
	

[<== Back to Readme](README.md)
