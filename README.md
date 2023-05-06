# micro:bit V2 stubs for VS Code
![GitHub license](https://img.shields.io/badge/license-MIT-red.svg?style=flat-square)
![V1](https://img.shields.io/badge/micro:bit-V1-green)
![V2](https://img.shields.io/badge/micro:bit-V2-blue)

---

## About this package
micro:bit stubs as a python package based on official [micro:bit documentation](https://microbit-micropython.readthedocs.io/en/v2-docs/).

---

## Usage
Copy the microbit package into your working directory. Use the import<br>
function to make it accessible in your code (e.g. `from microbit import *`)

---

Note:<br>
If you want to use the modules audio, neopixel, radio, speech, you<br>
need to move them from the microbit folder into the same directory<br>
as the microbit folder. Your working directory in VS Code should<br>
look like this:

![](img/VSCode-WorkingDirectoryExample.png)

In your code import the modules seperately, e.g:

```python
from microbit import *
import speech
```

---

## Git Repository
https://github.com/ElTrasho3000/Microbit-Stubs-Python-Package
