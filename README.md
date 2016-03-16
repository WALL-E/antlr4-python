# ANTLR4 Python Example

This repository is a simple example of ANTLR4 in Python 2.

## Getting started

First, download the ANTLR complete JAR from [the ANTLR site][antlr].

[antlr]:http://www.antlr.org/

Next, install the ANTLR4 Python 2 runtime:

```
pip install antlr4-python2-runtime
```

Then, run ANTLR to compile the grammar and generate Python:

```
java -Xmx500M -cp <path to ANTLR complete JAR> org.antlr.v4.Tool -Dlanguage=Python2 Hello.g4
```

Finally, run the Python main and enter some text:

```
$ python Hello.py
hello sir
^D
```

Output:

```
Hello: sir
```
