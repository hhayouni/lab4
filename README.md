## Lab 4
### Kernel
- A *Kernel* is the core of OS that controls and communicates with hardware resource.

### Shell
- A ***shell*** is a interface that allows users to communicate with kernel.  
Users run applications and give commands through shell.

### CLI(Command Line Interface) 
- Have to remember commands
- Relative fast
- Scripts enable automation and records

### GUI(Graphic User Interface)
- Easy to use and Intuitive
- Relatively slow
- Manual labors required for repetitive tasks

### Shell command: pwd,cd,ls

- pwd shows the current path in a hierarchical directory

- cd  changes directory

- ls lists files and directories

#### Arguments

```
/                       root
.                       current directory
..                      upper-level directory
~                       home of current user
/[directory name]       absolute path
./[directory name]      relative path
../[directory name]     relative path
```
---
### options
- l show detailed information(long format)
- lh same as above, but size in units
---
### Manipulation:

***cp*** copy files and directories

***mv*** move files and directories or rename them

***rm*** delete files and directories *permantely and irreversevely*

***mkdir*** makes a new directory

***Wildcards***
| Pattern | Matches |
| ----- | ----- |
| * | All filenames |
| g* | All filenames that begin with the character "g" |
| b*.txt | All filenames that begin with the character "b" and end with the characters ".txt" |
| Data??? | Any filename that begins with the characters "Data" followed by exactly 3 more characters |

---
#### WARNING!!
*Once you delete something with rm, it's gone. Before you use rm with wildcards, construct your command using ls instead.*

---
### Help command

***help*** shows information and instructions on how to use other commands

***man*** is used to close a terminal or end a script. It simply logs you out or stops the program.

 ***exit*** is used to close a terminal or end a script. It simply logs you out or stops the program.
