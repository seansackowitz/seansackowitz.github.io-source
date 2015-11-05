Allows you to take snapshots of files to test new code and easily roll back changes to previous snapshots.

<img src="https://raw.githubusercontent.com/seansackowitz/Code-Snapshot/master/readme%20content/Screenshot.png" alt="Drawing" style="width:100%"/>

# Features
* Add files and project folders to the tree view to keep track of your snapshots.
* Take an unlimited number of snapshots of any number of files.
* When importing a folder, you can use file and folder excludes.

# Settings
<img src="https://raw.githubusercontent.com/seansackowitz/Code-Snapshot/master/readme%20content/Settings.png" alt="Drawing" style="width:100%"/>

# About
I first thought of making an undo-redo tree like what is in vim for Visual Studio based on an issue marked in the limetext project https://github.com/limetext/lime/issues/533. I quickly realized that hooking into visual studio's system was limiting me to only one editor for this feature, and I quite like Sublime Text for anything not C#. So, I decided to make a standalone program which would allow you to take "Snapshots" of your code so you could test an edit safely.