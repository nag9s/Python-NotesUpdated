From Documentation  - [https://docs.python.org/3/glossary.html](https://docs.python.org/3/glossary.html)

Python is an interpreted language, as opposed to a compiled one, though the distinction can be blurry because of the presence of the bytecode compiler. This means that source files can be run directly without explicitly creating an executable which is then run. Interpreted languages typically have a shorter development/debug cycle than compiled ones, though their programs generally also run more slowly.

[https://stackoverflow.com/questions/2998215/if-python-is-interpreted-what-are-pyc-files](https://stackoverflow.com/questions/2998215/if-python-is-interpreted-what-are-pyc-files)

.pyc files contain [byte code](http://en.wikipedia.org/wiki/Bytecode) , which is what the Python interpreter compiles the source to. This code is then executed by Python's virtual machine.

**a language is not "interpreted" or "compiled" as such. A specific implementation can be an interpreter or a compiler **\(or a hybrid or a JIT compiler\)  - For python , standard implementation is CPython 

.

