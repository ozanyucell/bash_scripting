### EXPLAIN DIFFERENT SHELLS

# How to create a script?
 * Firstly, you need to know how to create a script. A script file is nothing more than a text file before it is converted.
 * So, we need to create a text file. You can do that simply by typing,
 ```
 $ touch scriptName 
 ```
 * If you create it with a .sh extension, someone can tell it's a bash script. I recommend you to create it as,
 ```
 $ touch scriptName.sh
 ```
 * By this, anyone can tell this is a script file. But be carefull, bash is not the only shell exists.

# Bash Script Structure
 * Bash scripts have 3 core components.
   * Shebang (Sha-bang) Line
   * Bash Commands
   * Exit Statement

# Shebang (Sha-bang) Line
 * This is the line where we define our file as a bash script. If we type "#!/bin/bash" at the beginning of our script, our terminal will understand that this is a bash script.
 * If we typed "#!/usr/bin/python3" instead of "#!/bin/bash" our terminal would think it was a Python3 script. 