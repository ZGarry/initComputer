# initComputer

装机必备软件

## 原则

1. 此文档面向程序员。
2. 尽量使用开源软件。

## 初始化

此处列出了最重要的软件，先安装这些软件，一套工作流就可以创建，后续内容再根据需要安装即可。
软件安装：

1. 下载坚果云，登录，安装代理软件并激活代理（代理记得刷新成最新地址）
2. 下载google，登录
3. 下载idea（登录）、git、vscode（登录）、语雀（登录）、pycharm
4. 绘图工具:[Draw.io](https://github.com/jgraph/drawio-desktop)

然后就可以开始快乐的办公了。

## 物理准备

除了需要软件准备之外，现实世界中还需要准备。

1. 舒服椅子。
2. 双显示器。

## 其他

1. 截屏工具:[snipaste](https://zh.snipaste.com/)
2. Gif录制工具:[ScreenToGif](https://www.screentogif.com/)
3. 压缩包工具:[7Z](https://www.7-zip.org/download.html)
4. 网页下载工具:[httrack](https://www.httrack.com/)

## 量化相关

1. 国金量化qmt、miniqmt

## 初始化vscode

导出vscode所有插件：

> code --list-extensions > extensions.txt

导入：

> cat extensions.txt |% { code --install-extension $_}

## 初始化VScode

登录账号，点击同步即可。Vscode只会维护一份同步镜像，一直使用远程的即可。

## 初始化python

官网下载python。不推荐下载conda，没有必要，而且还导致速度变慢非常多。
IDE：vscode，下载Jupyter扩展，python扩展，autopep8扩展即可。(建议单行支持150字符，大显示器屏幕相对更宽)

设置清华镜像：

> pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple

导出python所有依赖:

> pip freeze > requirements.txt

你可以使用以下命令安装 `requirements.txt`文件中列出的所有包：

```
pip install -r requirements.txt
```
