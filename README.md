# CyanJade-Studio 基于Electron的青玉案客户端

[原项目仓库](https://github.com/Lazenander/CyanJade-Studio-Online.git)

**本项目会在原项目作者完成C艹客户端前持续更新，在C艹客户端完成后本项目会转为归档状态，不再更新**

## 使用方法

和网页端一样，教程请去原项目作者的B站

## 从源代码构建

安装electron

```bash
npm install electron --save-dev
```

全局安装electron-builder

```bash
npm install electron-builder -g
```

**请cd到源代码文件夹内**，然后运行

```bash
electron-builder
```

如果报错，多半是因为某些众所周知的原因造成的网络问题，请在该项目文件夹中打开powershell/cmd并运行

```bash
$env:ELECTRON_MIRROR="https://npmmirror.com/mirrors/electron/"
$env:ELECTRON_BUILDER_BINARIES_MIRROR="http://npm.taobao.org/mirrors/electron-builder-binaries/"
```
