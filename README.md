# CECS

This is my first attempt at creating a Python Module and is intended to assist with using the Cisco Enterprise Cloud Suite APIs. The initial work will be around UCS Director.

This have been inspired and influenced by https://github.com/hpreston/cisco_cloud. I initially intended to contribute to Hanks good work however as a learning exercise I wanted to create my own module and learn how to use unit testing for it.

Once you have pulled the module down you should browse into the directory and execute;

    python setup.py install


To use (with caution), simply do::

    >>> import cecs
    >>> print cecs.getsr()

I will at some stage (once it is in a useful state) publish on PyPI to allow much easier installation.


### Working Functions
The module is most defiantly work in progress, the following functions are working (these are only the ones that I think are useful rather than all in the module);

| Fuctions        | Purpose     |
| ------------- |:-------------:|
| getAllVMs      | Gets a list of all VMs for the user |
| sr_get      | Gets a list of all the service requests       |  
|   |       |    



### Example Scripts
Examples that have been created using the module are the following.

#### ui.py
This script provides a text base menu to do display various things. The menu should be self explanatory.