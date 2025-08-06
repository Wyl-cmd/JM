# JM下载器

一个简单易用的漫画下载和PDF转换工具，支持下载漫画并自动转换为PDF格式方便阅读。

## 功能特点
- 输入漫画ID即可下载
- 自动将下载的漫画图片转换为PDF
- 提供PDF文件管理功能（查看、删除）
- 支持打包为单文件可执行程序，无需安装Python环境

## 安装指南

### 方法1：直接使用可执行文件
1. 前往发布页面下载最新的可执行文件
2. 双击运行即可使用

### 方法2：从源码运行
1. 克隆本仓库
```bash
https://github.com/yourusername/JMbenzi.git
cd JMbenzi
```
2. 安装依赖
```bash
pip install -r requirements.txt
```
3. 运行程序
```bash
python main.py
```

## 使用说明
1. 在输入框中输入漫画ID
2. 点击"开始下载并转换"按钮
3. 等待下载和转换完成
4. 点击"管理PDF文件"按钮可以查看和管理已下载的PDF

## 注意事项
- 下载过程中请不要多次点击下载按钮，可能会导致线程中断
- 如遇下载未成功的情况，请关闭软件重新运行
- PDF管理功能中，双击列表项可打开PDF文件
- 程序会将漫画下载到当前运行目录

## 致谢
- 感谢[jmcomic](https://github.com/xxx/jmcomic)库提供的漫画下载功能
- 感谢[Pillow](https://python-pillow.org/)库提供的图片处理功能
- 感谢[CustomTkinter](https://github.com/TomSchimansky/CustomTkinter)库提供的GUI支持

## 联系方式
- QQ群：1154539255
- 二群：521292550
- B站主页：[https://space.bilibili.com/397706571](https://space.bilibili.com/397706571)
- B站小号：[https://space.bilibili.com/3546591426251062](https://space.bilibili.com/3546591426251062)