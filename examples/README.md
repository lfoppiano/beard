# Examples

General purpose and introductory examples of Beard.

## Getting started

This application works only on Python 2.x. On Linux should be already installed. 
On Mac OSX you can install it using Homebrew: `brew install python2`

To keep the installation separated from the general system, is better to use virtualenv: 
```
pip install virtualenv
mkdir virtualenv
cd virtualenv
source bin/activate
```

...and install all the required libraries: 

```
pip install numpy 
pip install scipy
```

Finally, we can install the library, after cloning the repository, we launch the setup.py  

```
python setup.py install
```

More detailed instruction on how run the examples are contained in  [README.rst](beard/examples/applications/author-disambiguation/README.rst)
