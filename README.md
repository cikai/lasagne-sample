## lasagne 例子

---

### 下载代码到本地

桌面打开 Git Bash，执行

    git clone https://github.com/cikai/lasagne-sample.git

下载完成后进入项目根目录

    cd lasagne-sample

### Python环境

安装 Python 2.7 (或 3.6 版本)

Window 版下载地址

* 32位：[python-2.7.13.msi](https://www.python.org/ftp/python/2.7.13/python-2.7.13.msi)
* 64位：[python-2.7.13.amd64.msi](https://www.python.org/ftp/python/2.7.13/python-2.7.13.amd64.msi)

### 安装 Lasagne

python 终端下依次执行

    // 第一行挺长的，复制完整了
    pip install -r https://raw.githubusercontent.com/Lasagne/Lasagne/master/requirements.txt
    pip install Lasagne==0.1

下载安装完成后进入example目录下，运行例子

     cd example && python mnist.py

运行结果画面如下

![运行结果](https://github.com/cikai/lasagne-sample/tree/master/examples/result.png)
