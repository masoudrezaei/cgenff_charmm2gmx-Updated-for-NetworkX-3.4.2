# cgenff_charmm2gmx-Updated-for-NetworkX-3.4.2
cgenff_charmm2gmx (Updated for NetworkX 3.4.2 and Python 3.12)

# Overview

This repository contains a modified version of the cgenff_charmm2gmx.py script, originally from the [Original Repository](https://github.com/Lemkul-Lab/cgenff_charmm2gmx)
repository. The script has been updated to ensure compatibility with:

NetworkX 3.4.2

Python 3.12

Changes & Compatibility Updates

Fixed deprecated Graph.node attribute usage by replacing it with Graph.nodes.

Ensured compatibility with the latest versions of NetworkX and Python.

Tested on NetworkX 3.4.2 and Python 3.12 to verify proper functionality.

# Installation

To use this updated script, install the required dependencies:

`pip install networkx==3.4.2`
`pip install numpy # (if required by the script)`

# Usage

Run the script as follows:

`python cgenff_charmm2gmx.py JZ4 jz4_fix.mol2 jz4.str charmm36-jul2022.ff`

For more details on usage, refer to the original Lemkul-Lab documentation.

# Acknowledgments

This script is based on the original cgenff_charmm2gmx.py from the Lemkul-Lab repository. All credits for the original implementation go to the respective authors.

# License

Refer to the original repository for licensing details.


