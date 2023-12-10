# 0x00. AirBnB clone - The console

## Project Description:
This is the first part of the AirBnB clone project where we worked on the backend of the project whiles interfacing it with a console application with the help of the cmd module in python by use (python).

Data (python objects) generated are stored in a json file and can be accessed using json module in python

## Description of the command interpreter:
This command line interpreter  serves as the frontend of the web app where users can interact with the backend which was developed with python OOP programming.

As part of the implementation of the command line interpreter, the folowing actions can be performed:
-   Creating new objects (ex: a new User or a new Place)
-   Retrieving an object from a file, a database etc…
-   Doing operations on objects (count, compute stats, etc…)
-   Updating attributes of an object
-   Destroying an object

## How to start it:
1. Clone the repository of the project from Github. This will contain the simple shell program and all of its dependencies.

```

(https://github.com/Marwanfouz/AirBnB_clone.git)

```
2. After cloning the repository, there is a folder called AirBnB_clone with several files necessary for program to work.

> ./console.py : The main executable of the project, the command interpreter.
>
> models/engine/file_storage.py: Class that serializes instances to a JSON file and deserializes JSON file to instances
> 
> models/__ init __.py:  A unique `FileStorage` instance for the application
> 
> models/base_model.py: Class that defines all common attributes/methods for other classes.
> 
> models/user.py: User class that inherits from BaseModel
> 



## How to use it:
It can work in two different modes:


**Interactive** and **Non-interactive**.

In **Interactive mode**, the console will display a prompt (hbnb) indicating that the user can interact with the prompt.

```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```

In **Non-interactive mode** ((like the Shell project in C)), the shell will need to be run with a command input piped into its execution so that the command is run as soon as the Shell starts. In this mode no prompt will appear, and no further input will be expected from the user.
