Python Information
==================================================================================
> Created by Alex on 2019.06.04 
> Update by alex on 2022.10.22
----------------------------------------------------------------------------------

# Office Website
 - https://www.python.org/
 - https://www.python.org/downloads/
 - https://www.python.org/downloads/release/python-373/

# Windows Install
- Python Install Download package
   + https://www.python.org/downloads/
   + https://www.python.org/downloads/release/python-373/
      + Select: Windows x86-64 executable installer	Windows	for AMD64/EM64T/x64
   ```python
   $ python --version                              # Check your version of Python 
   $ python3 --version                             # Check your version of Python3
   ```

- Python Winget Install
   + https://winget.run/pkg/Python/Python.3.10
   ```
   > winget install -e --id Python.Python.3.10
   ```

- Python Pip Install (Usually, pip is automatically installed if you are using Python downloaded from python.org)
   + https://pypi.org/project/pip/
   + https://pip.pypa.io/en/stable/installation/
   ```python
   $ pip --version                                 # Python2.x 版本命令
   $ pip3 --version                                # Python3.x 版本命令
   $ pip --help
   ```
- Python Pip Usage
   + https://pip.pypa.io/en/stable/
   + https://pip.pypa.io/en/stable/getting-started/
   + https://packaging.python.org/en/latest/tutorials/installing-packages/
   ```python
   $ pip install SomePackage              # 安装包, 最新版本
   $ pip install SomePackage==1.0.4       # 安装包, 指定版本
   $ pip install --upgrade SomePackage    # 升级包
   $ pip uninstall SomePackage            # 卸载包
   $ pip search SomePackage               # 搜索包
   $ pip show                             # 显示安装包信息
   $ pip show -f SomePackage              # 查看指定包的详细信息
   $ pip list                             # 列出已安装的包
   $ pip list -o                          # 查看可升级的包
   $ pip install --upgrade pip            # Linux 或 macOS pip升级 python2.x
   $ pip3 install --upgrade pip           # Linux 或 macOS pip升级 python3.x
   $ python -m pip install -U pip         # Windows 平台升级 python2.x
   $ python -m pip3 install -U pip        # Windows 平台升级 python3.x

   $ pip install --target=path_name package_name      # 将package_name安装到path_name处

   $ py -m pip install --upgrade pip setuptools wheel # Ensure pip, setuptools, and wheel are up to date
   ```

- Python VENV (Optionally, create a virtual environment)
   ```python
   $ py -m venv tutorial_env
      tutorial_env\Scripts\activate
   
   ```

 - Python Install for VSCode Extensoin
    - Python, ms-python.python, Microsoft, Linting, Debugging (multi-threaded, remote), Intellisense, code formatting, refactoring, unit tests, snippets, and more.

# Linux Install

```python
$ python --version                              # Check your version of Python 
$ python3 --version                             # Check your version of Python3

$ sudo apt update                               # Update and Refresh Repository Lists
$ sudo apt install software-properties-common   # Install Supporting Software
$ sudo add-apt-repository ppa:deadsnakes/ppa
$ sudo apt update
$ sudo apt install python3.8                    # Install Python 3


$ sudo apt install python3-pyqt5
$ sudo apt install qt4-designer
$ sudo apt install pyqt4-dev-tools
$ sudo apt install pyqt5-dev-tools
$ pyuic4 -o a.py a.ui
$ pyuic5 -o a.py a.ui
```


# Python Studying Webiste
- Python : 
   + https://www.runoob.com/python/python-tutorial.html
- Python3: 
   + https://www.runoob.com/python3/python3-func-range.html
   + https://www.runoob.com/python3/python3-built-in-functions.html     # python3 built-in 
   + https://docs.python.org/3/library/functions.html                   # python3 org built-in

- Python pip install and usage
   + https://docs.python.org/3.10/tutorial/index.html
   + https://docs.python.org/3.10/index.html
   + https://www.runoob.com/w3cnote/python-pip-install-usage.html 
   + https://docs.python.org/3.10/using/windows.html

# XML-DOM NOTE
> 2020-04-16, Thursday ()
- This is easy and enough for us.
https://www.cnblogs.com/miniren/p/5092019.html


- This is so great sample code for us
http://www.java2s.com/Tutorial/Python/0400__XML/AccessingChildNodes.htm 
http://www.java2s.com/Tutorial/Python/0400__XML/AccessingElementAttributes.htm


- Python office org website: (This is for our reference about the all interface of DOM)
https://docs.python.org/zh-cn/3/library/xml.dom.html  
https://docs.python.org/zh-cn/3/library/xml.dom.html#node-objects
https://docs.python.org/zh-cn/3/library/xml.dom.html#dom-nodelist-objects


