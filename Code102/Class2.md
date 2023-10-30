# Text Editors, Terminal Commands, and Files
## Text Editors

- Text editors allow you to create the code necessary for a website or application.  
  - Baseline ones like Notepad are relatively bare bones and don't assist you with formatting.
  - There are other text editors that assist with syntax highlighting, code completion, installation of extensions, and etc. 
    - Examples: VS Code, Atom, Sublime

- An IDE (integrated development environment) is a software suite that includes a text editor, compiler, debugger right out of the box (i.e., without installing extensions)
  - Examples: Visual Studio, Eclipse

#### What are Important Features to Look For in a Text Editor?
 1. Code Completion; 
 2. Syntax Highlighting 
 3. Theme Variety
 4. Extension support / variety

[Source](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf) 

## Terminal Commands and Files

### Terminals

- A terminal is just a text based interface that allows you to interact with a system.
- You can use text commands in the terminal to navigate the file system and perform operations such as creating and deleting files.

#### What do these commands do?

1. pwd : **Print Working Directory**; this prints the current directory that you're located in

2. ls: **List**; this command lists out the contents of the current directory
    - You can add optional elements to modify the command for additional information

    >*Important Note*:
    >
    >Relative Path:
    A file or directory location relative to where we currently are in the file system.
    >
    >Absolute Path:
    A file or directory location in relation to the root of the file system.

3. cd: **Change Directory**; this changes the directory that you're currently in to whatever you put after cd
    - You may change to a file or folder relative to the current directory you're in, or you may list out an absolute path if you want to access a file outside of your relative position in the directory.
4. mkdir: **Make Directory**; this will create a directory within the directory that you're currently located (unless you specify an absolute file path)
5. touch: creates a file

### Files

- Linux treats everything as a file, which is the basis for its organzation.
- File extensions (e.g., .exe, .txt) are ignored by linux systems, which looks inside the file to determine its type.
  - This means that in a linux system, an image file could be named 'picture.txt' but it will still be treated as an image file.
    - the 'file' command will let you see what kind of file/directory it is.
      - File[path] is the correct usage since all things are a file, that means that all locations are a file.
- Linux is case sensitive, so there may be a File.txt and a file.txt.
- Spaces in file names are also accepted.
  - Since spaces are used in various terminal commands, files with spaces in them must utilize either escape commands or quotations to be accepted.
    - (e.g., `cd 'My File'` or `cd My\ File` )

Sources:

[Master File System](https://ryanstutorials.net/linuxtutorial/navigation.php)

[More About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

***
[Return to Table of Contents](https://hayden-cleaver.github.io/Reading-Notes/)