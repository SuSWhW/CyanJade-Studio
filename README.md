# CyanJade-Studio 基于Electron的青玉案客户端

[原项目仓库](https://github.com/SuSWhW/CyanJade-Studio-Online.git)

## 使用方法

和网页端一样，教程请去原项目作者的B站

## 从源代码构建（请cd到项目代码文件夹内）

安装electron

```bash
npm install electron --save-dev
```

全局安装electron-builder

```bash
npm install electron-builder -g
```


```bash
electron-builder
```

如果报错，多半是因为某些众所周知的原因造成的网络问题，请在该项目文件夹中打开powershell/cmd并运行

```bash
$env:ELECTRON_MIRROR="https://npmmirror.com/mirrors/electron/"
$env:ELECTRON_BUILDER_BINARIES_MIRROR="http://npm.taobao.org/mirrors/electron-builder-binaries/"
```