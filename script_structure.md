### EXPLAIN DIFFERENT SHELLS | NANOYA REFERANS VEREBİLİRSİN

# Working with scripts
### How to create a script file?
 * Firstly, you need to know how to create a script. A script file is nothing more than a text file before it is converted.
 * So, we need to create a text file. You can do that simply by typing,
 ```
 $ touch scriptName 
 ```
 * If you create it with a .sh extension, someone can tell it's a bash script. I recommend you to create it as,
 ```
 $ touch scriptName.sh
 ```
 * Now anyone can say this is a script file. However, keep in mind that bash is not the only shell.
 ### How to edit a script file?
 * You can edit your script file with your favorite text editor. I will be using nano. If you don't have one as your favorite, I recommend you to use nano as well.
 ```
 $ nano scriptName.sh
 ```
 * Now you are good to go!


# Bash Script Structure
 * Bash scripts have 3 core components.
   * Shebang (Sha-bang) Line
   * Bash Commands
   * Exit Statement

### Shebang (Sha-bang) Line
 * This is the line where we define our file as a bash script. If we type "#!/bin/bash" at the beginning of our script, our terminal will understand that this is a bash script.
 * If we typed "#!/usr/bin/python3" instead of "#!/bin/bash" our terminal would think it was a Python3 script.

### Bash Commands
 * 

### Exit Statement
 * 

# Comment Lines
 * We can add secret notes to our script file, which is ignored by our shell. These comment lines are only visible on source code. This is very useful for other developers or for the future you.
 * To create a comment line, all we need to do is putting a **#** at the beginning of our line. 