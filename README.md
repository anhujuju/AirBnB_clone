![ScreenShot](https://github.com/joer9514/AirBnB_clone/blob/master/.img/AirBnB_.png)

# Background Context

## Welcome to the AirBnB clone project! (The Holberton B&B)

Before starting, please read the [AirBnB concept page](https://intranet.hbtn.io/concepts/74) and watch [this video](https://www.youtube.com/watch?v=jeJwRB33YNg&feature=youtu.be) from I[saac Wong, Cohort #5](https://twitter.com/KYIsaacWong), showing what the Console should look like when you are complete with this project.

**First step: Write a command interpreter to manage your AirBnB objects.**
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

* put in place a parent class (called `BaseModel`) to take care of the initialization, serialization and deserialization of your future instances

* create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file

* create all classes used for AirBnB (`User`, `State`, `City`, `Place`…) that inherit from `BaseModel`

* create the first abstracted storage engine of the project: File storage.

* create all unittests to validate all our classes and storage engine

## What’s a command interpreter

Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

* Create a new object (ex: a new User or a new Place)

* Retrieve an object from a file, a database etc…

* Do operations on objects (count, compute stats, etc…)

* Update attributes of an object

* Destroy an object

## Resources

**Read or watch:**

* [cmd module](https://docs.python.org/3.4/library/cmd.html)

* [packages](https://intranet.hbtn.io/concepts/66)

* [uuid module](https://docs.python.org/3.4/library/uuid.html)

* [datetime](https://docs.python.org/3.4/library/datetime.html)

* [unittest module](https://docs.python.org/3.4/library/unittest.html#module-unittest)

* [args/kwargs](https://yasoob.me/2013/08/04/args-and-kwargs-in-python-explained/)

* [Python test cheatsheet](https://www.pythonsheets.com/notes/python-tests.html)

## Learning Objectives

### General

* How to create a Python package

* How to create a command interpreter in Python using the cmd module

* What is Unit testing and how to implement it in a large project

* How to serialize and deserialize a Class

* How to write and read a JSON file

* How to manage `datetime`

* What is an `UUID`

* What is `*args` and how to use it

* What is `**kwargs` and how to use it

* How to handle named arguments in a function

## Requirements

### Python Scripts

* Allowed editors: `vi`, `vim`, `emacs`
* All your files will be interpreted/compiled on Ubuntu 14.04 LTS using `python3` (version 3.4.3)
* All your files should end with a new line
* The first line of all your files should be exactly `#!/usr/bin/python3`
* A `README.md` file, at the root of the folder of the project, is mandatory
* Your code should use the `PEP 8` style (version 1.7 or more)
* All your files must be executable
* The length of your files will be tested using `wc`
* All your modules should have a documentation `(python3 -c 'print(__import__("my_module").__doc__)')`
* All your classes should have a documentation `(python3 -c 'print(__import__("my_module").MyClass.__doc__)')`
* All your functions (inside and outside a class) should have a documentation `(python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')`

### Python Unit Tests

* Allowed editors: `vi`, `vim`, `emacs`
* All your files should end with a new line
* All your test files should be inside a folder `tests`
* You have to use the [unittest module](https://docs.python.org/3.4/library/unittest.html#module-unittest)
* All your test files should be python files (extension: `.py`)
* All your test files and folders should start by `test_`
* Your file organization in the tests folder should be the same as your project
* e.g., For `models/base_model.py`, unit tests must be in: `tests/test_models/test_base_model.py`
* e.g., For `models/user.py`, unit tests must be in: `tests/test_models/test_user.py`
* All your tests should be executed by using this command:`python3 -m unittest discover tests`
* You can also test file by file by using this command: `python3 -m unittest tests/test_models/test_base_model.py`
* All your modules should have a documentation `(python3 -c 'print(__import__("my_module").__doc__)')`
* All your classes should have a documentation`(python3 -c 'print(__import__("my_module").MyClass.__doc__)')`
* All your functions (inside and outside a class) should have a documentation `(python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')`
* We strongly encourage you to work together on test cases, so that you don’t miss any edge case

## More Info

### Execution

Your shell should work like this in interactive mode:

```bash
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

But also in non-interactive mode: (like the Shell project in C)

```bash
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
```

![ScreenShot](https://github.com/joer9514/AirBnB_clone/blob/master/.img/Diagram_.png)

## Authors

* **Jose Espinosa** - [Twiter](https://twitter.com/joer9514) - [GitHub](https://github.com/joer9514)

* **Andres Rodriguez** - [Twiter](https://twitter.com/anhujuju) - [GitHub](https://github.com/anhujuju)
