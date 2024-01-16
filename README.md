0x00. AirBnB clone - The console
0x00.Table of contents
0x01 Introduction
0x02 Environment
0x03 Installation
0x04 Testing
0x05 Usage
0x06 Authors
0x01 Introduction
Team project to build a clone of AirBnB.

The console is a command interpreter to manage objects abstraction between objects and how they are stored.

To see the fundamental background of the project visit the Wiki.

The console will perform the following tasks:

create a new object
retrive an object from a file
do operations on objects
destroy an object
Storage
All the classes are handled by the Storage engine in the FileStorage Class.

0x02 Environment
Suite CRM terminal python Suite CRM Suite CRM git distributed version control system Github

Execution
In interactive mode

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
in Non-interactive mode

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
0x04 Testing
All the test are defined in the tests folder.

Documentation
Modules:
python3 -c 'print(__import__("my_module").__doc__)'
Classes:
python3 -c 'print(__import__("my_module").MyClass.__doc__)'
Functions (inside and outside a class):
python3 -c 'print(__import__("my_module").my_function.__doc__)'
and

python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'

