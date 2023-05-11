# numpy-for-python-2.7-64bit
Numpy packages built to link against Python 2.7 64bit

A loooong time ago, sometime in the early late 2000's, Autodesk added Python 2.7 to Maya's scripting languages. Around the same time they started shipping Maya as both a 32 and 64bit applications. This meant that they had to support a custom version of Python compiled for 64bit (Python 2.7 was only released as a 32bit app). On macOS this posed no issues, but on Windows this meant that any official python package with binary dependencies would not work in Maya unless they were specifically compiled for Python 2.7-64bit.

Over the years I compiled and maintained several versions of numpy, and shared them freely with Maya's community. It's been a great pleasure to see how it enabled TAs around the world in crafting incredible tools powered by numpy's powerful numeric applications.

This github repo represents a historical resting place for the last versions I compiled:

- Numpy 1.13.1 + intel mkl libraries
- Scipy 0.19.1
