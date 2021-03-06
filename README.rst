py_entitymatching
=================

This project seeks to build a Python software package to match entities
between two tables using supervised learning. This problem is often
referred as entity matching (EM). Given two tables A and B, the goal of
EM is to discover the tuple pairs between two tables that refer to the
same real-world entities. There are two main steps involved in entity matching:
blocking and matching. The blocking step aims to remove obvious non-matching
tuple pairs and reduce the set considered for matching. Entity matching in
practice involves many steps than just blocking and matching. While performing EM
users often execute many steps, e.g. exploring, cleaning, debugging, sampling,
estimating accuracy, etc. Current EM systems however do not cover the entire
EM pipeline, providing support only for a few steps (e.g., blocking, matching), while
ignoring less well-known yet equally critical steps (e.g., debgging, sampling).
This package seeks to support all the steps involved in EM pipeline.

The package is free, open-source, and BSD-licensed.

Important links
===============

* Project Homepage: https://sites.google.com/site/anhaidgroup/projects/magellan/py_entitymatching
* Code repository: https://github.com/anhaidgroup/py_entitymatching
* Issue Tracker: https://github.com/anhaidgroup/py_entitymatching/issues

Dependencies
============

The required dependencies to build the packages are:

* pandas (provides data structures to store and manage tables). Tested on version 0.23.2.
* scikit-learn (provides implementations for common machine learning algorithms). Tested on version 0.18.0.
* joblib (provides multiprocessing capabilities). Tested on version 0.12.0.
* pyqt5 (provides tools to build GUIs). Tested on version 5.6.0.
* py_stringsimjoin (provides implementations for string similarity joins). Tested on version 0.3.0.
* py_stringmatching (provides a set of string tokenizers and string similarity functions). Tested on version 0.4.0.
* cloudpickle (provides functions to serialize Python constructs). Tested on version 0.2.1.
* pyprind (library to display progress indicators). Tested on version 2.10.0.
* pyparsing (library to parse strings). Tested on version 2.2.0.
* six (provides functions to write compatible code across Python 2 and 3). Tested on version 2.11.0.

Platforms
=========

py_entitymatching has been tested on Linux, OS X and Windows.
