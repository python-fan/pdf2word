# pdf2word

~~60行~~40行代码实现多进程PDF转Word

> 新版本基于[https://github.com/dothinking/pdf2docx](https://github.com/dothinking/pdf2docx)实现

## 使用方法

* clone或下载项目到本地
```python
git clone git@github.com:simpleapples/pdf2word.git
```

* 进入项目目录，建立虚拟环境，并安装依赖

```python
cd pdf2word
python3 -m venv venv

# Linux
source venv/bin/activate

# Windows
venv\Scripts\activate

# Python < 3.10
pip install -r requirements.txt

# Python 3.10 or later
pip install -r requirements_3_10.txt
```

* 修改config.cfg文件，指定存放pdf和word文件的文件夹，以及同时工作的进程数
* 执行```python main.py```

## ModuleNotFoundError: No module named '_tkinter' 报错处理

### macOS环境

1. 安装homebrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. 使用homebrew安装tkinter
```bash
brew install python-tk
```

### Linux环境

以ubuntu为例

```bash
sudo apt install python3-tk
```

**欢迎Star**

## Python私房菜

![](http://ww1.sinaimg.cn/large/6ae0adaely1foxc0cfkjsj2076076aac.jpg)

## License

采用 MIT 开源许可证
