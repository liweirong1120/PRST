# Python Reservoir Simulation Toolbox

The Python Reservoir Simulation Toolbox is a Python version of the MATLAB
Reservoir Simulation Toolbox. The goal is to clone the functionality found in
MRST, and add tests.


## Installation

Currently there are no Python packages for this project. Download
the whole repository and copy the "PyRST/pyrst" folder into your project.


## Development:

To setup the development environment, and run tests, do the following:

    git clone https://github.com/roessland/PyRST.git
    cd PyRST
    virtualenv --python=python3 venv3
    source venv3/bin/activate
    pip install -r requirements.txt
    py.test

To resume working after the initial steps have been completed:

    cd PyRST
    source venv3/bin/activate
    py.test

## License

MRST is GPLv3-licensed, and since PyRST is a derivative work, it will also be
GPLv3-licensed. TODO: Add license.

