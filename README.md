cbenda
======

Interactive, simulatable robotics.

### General Installation

1.  Download V-REP http://www.coppeliarobotics.com/downloads.html
2. Install IPython Notebook with scipy, numpy, and matplotlib:
    ```
    $ sudo pip install ipython[notebook] --upgrade
    
    $ sudo pip install scipy --upgrade

    $ sudo pip install matplotlib --upgrade
    ```

### Setting up V-REP

1. See `V-REP/programming/remoteApiBindings/python/python/readMe.txt` Note that `vrep.py` and `vrepConst.py` are already in the repo.
 2. remoteAPI.so/dll/whatever is located at `V-REP/programming/remoteApiBindings/lib/lib/64Bit`
3. Copy remoteAPI.so to `notebook/`

For more details: http://www.coppeliarobotics.com/helpFiles/en/remoteApiClientSide.htm


### Getting Started


1. Start V-REP in your `V-REP` directory:

    ```
    ./vrep.sh
    ```
2. Load `scenes/starwhal2.ttt`. File > Open Scene...
3. Run IPython Notebook:

    ```
    $ ipython notebook
    ```
4. Try running `Narwhal Test.ipynb`
