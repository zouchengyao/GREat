# GREat@背单词
## this is the Recite helper script that helps to recite words.

Intergrated with GRE-3000 and GRE-Red(6000). Have fun!
![screenshot](img/screen.png)
## Usage    如何使用:
```
python3 bei.py [-file-to-read-]

e.g.
python3 bei.py 08red/11.txt
```
Use mouse & keyboard [a, s, left, right] to control behavior.
使用鼠标及键盘a, s, 方向左右键控制。当所有单词背完时，此次背结束。

## Notice　注意事项:
Currently only for expert with Python knowledge. Modify code to run 08red/ or anything as you wish.


## Changelog　更新日志:

    - 2.0 Alpha: Rewrite whole logic. Fixed most bugs. Added Simple StatusBar.
    - 1.0 Alpha: Minimal functioning is done. Buggy and not user-friendly.　最初版本。只能保证跑起来。没有任何其他必要的功能。非常不稳定，Bug多。


### TODO List　未来任务:
- StatusBar add more functions
- Support files traversal and auto--move-to-next-file, button--move-to-next-file support
- Folder reselection support 
- Add Image API for automatic image hint (that huge red piece)
- Persistent Storaging: .json or self-defined file for keeping setttings 
- Add more setting options 
- Improve UI
- package it for dummy-use
- A whole new Cascade GUI for better recite (I just want to name it like this)
