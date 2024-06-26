# CryptoApp 加密解密工具箱

一个基于pycryptodome库实现的加密解密工具箱GUI程序，支持在Windows系统和Linux系统上运行。包含以下几个小工具，可通过选项菜单进行切换。Fork from [cforth/CryptoApp](https://github.com/cforth/CryptoApp)

可以选择使用AES-12B ECB模式或是CBC模式进行加密解密。

## 使用环境需要

* Python
    * Python 3.12 +
    * [pycryptodome 3.6.6 +](https://pypi.org/project/pycryptodome/#files)
    * chardet 3.0.4 +
    * Pillow 5.0.0 +
* Windows(32位/64位)
    * Windows 7及以上
* Linux
    * python3-tk

## 功能介绍

* Cryptor--加密解密器
   * 支持加密字符串、文件、文件夹，可以预览加密或解密后的文件名称。

* TextLook--文本查看器
   * 支持查看和保存，使用CFCrypto加密或者未加密过的文本文件。

* ImgLook--图片查看器
   * 支持常见图片格式（包括GIF动图）的显示，并且支持读取使用CFCrypto加密过的图片。

## 使用方法
```bash
# 创建虚拟环境
python3 -m venv .env
# windows下激活虚拟环境
.\.env\scripts\activate
# 安装依赖包
pip install -r requirements.txt

# 运行
.\.env\Scripts\python.exe CryptoApp.pyw


# 关闭虚拟环境
deactivate
```