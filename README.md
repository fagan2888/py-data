
Creates a data folder named ```.proj-data``` in user's home directory and places a soft-link ```proj-data``` in the project's root directory 
(topmost folder containing a ```__init__.py``` file). 
Files placed in ```~/.proj-data``` can be shared across multiple projects without the need to copy/replicate for each 
different project. It is especially useful for storing large data-sets or tensorflow model files that can then be shared 
across multiple projects. If the data folders are created using this package, it automatically installs ```__init__.py``` 
into the data folders so that the folder's path can be accessed as though it was a python package.

To install the py-data as a ``pip`` package use the following command:
---

#### 1. For latest release:
```
pip install git+git://github.com/uniquetrij/py-data.git@release
```

#### 2. For a specific version:
```
pip install git+git://github.com/uniquetrij/py-data.git@<version-number>
```