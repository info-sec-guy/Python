# Python Learning :snake:

## Virtual Environments (Mac OS)

Create a new virtual environment inside the directory

`python3 -m venv env`

In the above example, this command creates a directory called env, which contains a directory structure similar to this:

```
├── bin
│   ├── activate
│   ├── activate.csh
│   ├── activate.fish
│   ├── easy_install
│   ├── easy_install-3.5
│   ├── pip
│   ├── pip3
│   ├── pip3.5
│   ├── python -> python3.5
│   ├── python3 -> python3.5
│   └── python3.5 -> /Library/Frameworks/Python.framework/Versions/3.5/bin/python3.5
├── include
├── lib
│   └── python3.5
│       └── site-packages
└── pyvenv.cfg
```
Activate the Virtual Environment by running: 

`source env/bin/activate`

To exit the Virtual Environment:

`deactivate`

External Resources:

[Python Virtual Environments: A Primer](https://realpython.com/python-virtual-environments-a-primer/)
[Creation of virtual environments](https://docs.python.org/3/library/venv.html)
