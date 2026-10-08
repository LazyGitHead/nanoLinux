# Basic Linux Commands


##pwd(Print Working Directory)
- What it does: shows the folder I am right now.
- Example: pwd
- Output I saw: /home/piyush

##ls(LIST DIRECTORIES)
-What it does: use ls to inspect directory content and control how entries are displayed.
-Example: ls
-Output I saw: newFile,linspace
-Types: you can use the command "ls --help" or "ls man" to get the side commands related to ls, like- ls -l,ls -la,ls -a etc.
 ls -a = displayed the files hidden with or start with "." ex ".gitex".

##cd(Change Directory)
-What it does: To move around the Linux filesystem, you use paths to specify your destination.
 The primary tool for this is the cd command, short for change directory. It changes the shell's current working directory.
-Example: cd /home/piyush/linspace/nanoLinux/notes
-Output I saw: ~/linspace/nanoLinux/notes$ 
-SOME ESSENTIAL SHORTCUT:
- (.) (current directory): Represents the directory you are currently in.
-(..) (parent directory): Moves you one level up to the directory containing your current one.
-(~) (home directory): A shortcut to your personal home directory, like /home/pete.
-(-) (previous directory): Takes you back to the last directory you were in.
-SYNTAX: $ cd .
         $ cd ..
         $ cd ~
         $ cd -
 
##mkdir(Make Directories)
-WHat it does: creates directories for organizing files and other directories.
-Example: mkdir linspace
-Output i saw: new directory named linspace.
 
