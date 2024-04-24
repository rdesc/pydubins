# dubins

Forked repo from https://github.com/AndrewWalker/pydubins. See parent repo for full documentation. This repo provides a fix for working with newer python versions (tested with Python 3.9, 3.10 and 3.11).

## Installing

To install run the command
`````bash
pip install git+https://github.com/rdesc/pydubins.git
`````

To build manually, follow these steps:
1. Clone - `git clone https://github.com/rdesc/pydubins`
2. Build - `python setup.py build_ext --inplace`
3. Install with pip - `pip install .`

The cython generated *dubins.c* file may need to be deleted and regenerated with cython. See https://github.com/AndrewWalker/pydubins/issues/16 for additional discussion.
