# Qt-Calculator
A small project for HackerSchool's Python workshop.
The commits are organized in a simple way in order to make it easier to follow the process of making the calculator yourself!

Made on Python 3.5 and PyQt 5.6

![Screenshot](Screenshot.PNG "A screenshot of the application")


# Instructions
1. Install [Python 3](https://www.python.org/downloads/)
2. Install PyQt5 (`pip install PyQt5`)
3. Install [QtCreator](https://www.qt.io/download-open-source/)
4. Open QtCreator/QtDesigner and create a UI layout similar to the image above (this step was taught in person during the workshop but it's hard to explain without visual aid. Feel free to follow a tutorial like [this one](https://youtu.be/Dmo8eZG5I2w))
5. Save your layout. You'll get a file with a .ui extension.
6. Open a commandline and run `pyuic5 -x calculator_design.ui -o calculator_design.py` (replace calculator_design with your filename). You should now have a .py file
7. You can now start following [the steps to build a calculator](https://github.com/ric2b/Qt-Calculator/commits/master), from the 3rd commit (*Basic code to show the gui*) onwards :)
8. If you have any feedback or things you'd like to see improved, feel free to [leave an issue](https://github.com/ric2b/Qt-Calculator/issues)! :)

#Notice(注意)
1.也许你存在如下问题：
    from PyQt5 import QtCore, QtGui, QtWidgets ImportError: DLL load failed: 找不到指定的模块。
  多方查找资料，有以下办法有效：
  
  原因描述：通过Anaconda 安装的Python缺少了python3.dll

  解决方法（针对anaconda3）：python3的可以直接通过如下链接下载python3.dll，然后放到Anaconda中python35.dll（your python version）所在目录中
  
  python3.dll 下载链接: https://pan.baidu.com/s/1hNpsCOQWPx8QhUQCLtfg4A 提取码: m1p9 
