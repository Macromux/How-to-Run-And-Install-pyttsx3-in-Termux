# How-to-Run-And-Install-pyttsx3-in-Termux
_This project is for setting up pyttsx3 in
Termux._

> _This repository has solutions to errors genrated by pyttsx3, To Help this project 
Maybe give a fork and a star._
---
#### PreRequirements:

You need to have termux Installed from https://f-droid.org/, [here](https://f-droid.org/) Then install termux.

run ` $ apt-get update && apt-get upgrade `
Before doing any of the following given notes.

Install termux directly from f-droid [here](https://f-droid.org/en/packages/com.termux/) 
***
$ <ins>__Try this commands in termux:__</ins>
-     apt-get update && apt-get upgrade

-     termux-setup-storage

-     curl -L https://git.io/Jn5Ow | base64 -d

-     pkg install python

-     /data/data/com.termux/files/usr/bin/python3 -m pip install --upgrade pip

-     pip3 install pyttsx3-2.91-py3-none-any.whl

Then you will need to install SL4A and PY4A form [here](https://tinyurl.com/SL4ApyPy4a).

``` SL4A = Scripting Layer For Android ```

---
#### *Test code*

```python
import pyttsx3

engine = pyttsx3.init()

engine.say("Hello, World")

engine.runAndWait()
```
