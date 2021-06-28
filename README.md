# The Command Line Notes

- Linux has a graphical user interface and it works pretty much like the GUI's on other systems that you are familiar with such as Windows and OSX.

- A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

- The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands.

- Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you.

- There are various shells available but the most common one is called bash which stands for Bourne again shell.

## Basic Navigation Notes

- pwd stands for Print Working Directory

- A lot of commands on the terminal will rely on you being in the right location.

- Line 1 - We ran ls in it's most basic form. It listed the contents of our current directory.

- Line 4 - We ran ls with a single command line option ( -l ) which indicates we are going to do a long listing. A long listing has the following:
First character indicates whether it is a normal file ( - ) or directory ( d )
Next 9 characters are permissions for the file or directory.
The next field is the number of blocks.
The next field is the owner of the file or directory.
The next field is the group the file or directory belongs to (users in this case).
Following this is the file size.
Next up is the file modification time.
Finally we have the actual name of the file or directory.

- Line 10 - We ran ls with a command line argument ( /etc ). When we do this it tells ls not to list our current directory but instead to list that directories contents.

### More About Files Notes

- file.exe - an executable file, or program.
file.txt - a plain text file.
file.png, file.gif, file.jpg - an image.

- Linux actually has a very simple and elegant mechanism for specifying that a file or directory is hidden. If the file or directory's name begins with a . (full stop) then it is considered to be hidden.
