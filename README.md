# ml_course

You will need to install python (system python usually don't work) and several python libraries. asdf
One way to go is to install everything with [Anaconda](https://conda.io/docs/install/quick.html). 
Never tried, but it is a well-maintained project and it includes everything you can imagine.

The other way is to install everything manually. I prefer installing python via [pyenv](https://github.com/pyenv/pyenv), 
since it is a fork of rbenv project which should be familiar to any ruby developer and you don't need to deal with `python` / `python3` / `pip` / `pip3` issues. There are two active python versions, 2 vs 3. It is a good idea to start with python 3, but the old one will work too.

Then you need to install the jupyter project:
http://jupyter.readthedocs.io/en/latest/install.html

Once you're done, try to run it from the root directory of the repo:
```
jupyter-notebook
```

If it launches the browser window, you're almost there! Try to open any `.ipynb` file and run some cells. 
