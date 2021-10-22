# Linux Commands Chetsheet


## Opening Terminal

* Right click and select ```Open in Terminal```
* Use ```Ctrl``` + ```Alt``` + ```T```
* Search ```Terminal``` in ```Application``` and open



<br>

## Basic Linux Commands


### Navigating commands

* ```pwd```     -> Prints the path of present working directory
* ```ls```     -> Lists the components in directory
* ```ls -a```     -> Lists all the components in directory including hidden files
* ```ls -l```    -> Lists all the components in directory with permissions and other details
* ```cd```    -> Changed directory to root
* ```cd ..```    -> Changes directory to parent directory 
* ```cd /path/```   -> Changes the directory to ./path/ , where . is the parent directory to path

### Manipulating files and directory command

* ```mkdir <name>```    -> Makes empty directory
* ```mkdir -p <parent>/<child>```    -> Makes a <child> directory inside <parent> directory by creating <parent> directory if it does not exist
* ```rmdir <name>```    -> Removes empty directory 
* ```touch <filename>```    -> Creates a file
* ```rm <file>```   -> Removes a file
* ```rm -r <directory>```   -> Deletes non empty directory along with it's files and sub-directories
* ```cp <source> <destination>```   -> Copies source file to it's destination
* ```mv <source> <destination>```   -> Moves source file to it's destination
* ```xdg-open <file/directory>```   -> Opens the file/directory in it's default application
* ```grep <"keyword"> <filename>```   -> Gives the line in the file, that has the following keyword
  

### Additional commands

* ```echo <text>```     -> Prints text in shell
* ```cat <text file>```    -> Prints the content of text file in shell
* ```history```     -> Shows the history of commands used
* ```history -d <line>```    -> Deletes the command of line number <line> from history
* ```tree```      -> Displays the directory/sub-directory structure from parent in form of tree
* ```man <command>```     -> Displays manual of the command


<br>

# Authors
- [Aadarsha Dhakal](https://github.com/aadarshadhakalg/)
- [Ayush Paudel](https://github.com/AyushPaudel/)

<br>

# MIT License

Copyright (c) 2021 Green Club of Thoughts

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
