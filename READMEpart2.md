![cmd](https://images.unsplash.com/photo-1629654291663-b91ad427698f?q=80&w=2874&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
# How to create a file using the Terminal
You can create,manage and edit files using the terminal in this tutorial i will show you how to do it.

## 1.Navigation
To move between directories in the terminal you need to use the _cd_ command to navigate.
use `cd ~` to navigate to the root directory then you can use `cd ./folder/file` to navigate to any folder, and `cd ..` to move up one level from your current directory.


## 2.Creating a new directory
Once you have navigated to where you want to start creating your files use the command _mkdir_ to create your new directory.

**Example:** 
```
mkdir projects
cd projects
```
once you navigate to your new directory you can create even more directories within it with the same command.

**Example:**

`mkdir css`


 
## 3.Creating a new file
Once you have created your new directory you can create files using the _touch_ command followed by the file name.

**Example:**
 `touch index.html`

if you want to create a file in a child directory  `touch css/style.css`



## 4.Putting it all together
Here is how you would structure a simple project
```
cd ~
mkdir project
cd project
mkdir js css
touch index.html css/style.css js/app.js
code .
```
### Steps
1. Navigate to root directory
2. Create the main project directory
3. Navigate to the project directory
4. Create seperate directories for js and css files
5. create the html css and js files in their respective directories
6. open the directory into vs code