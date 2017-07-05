sloth
=====

[![Build Status](https://travis-ci.org/cvhciKIT/sloth.svg)](https://travis-ci.org/cvhciKIT/sloth)

sloth is a tool for labeling image and video data for computer vision research.

The documentation can be found at http://sloth.readthedocs.org/ .

Latest Releases
===============

2013/11/29 v1.0: 2e69fdae40f89050fbaeef22491eee2a92e78b4f [.zip](https://github.com/cvhciKIT/sloth/archive/v1.0.zip) [.tar.gz](https://github.com/cvhciKIT/sloth/archive/v1.0.tar.gz)

For a full list, visit https://github.com/cvhciKIT/sloth/releases

---

## Cynny Documentation - How to install and start sloth (tested on MacOS Sierra)

###Install and start with Anaconda
```
conda create -n sloth python=2.7
source activate sloth
conda install pyqt==4.11.4
sudo pip install numpy pillow
```

How to start sloth (simple *python sloth* doesn't work)
```
python sloth/bin/sloth
```

How to start sloth example
```
python sloth/bin/sloth examples/example1_labels.json
```
