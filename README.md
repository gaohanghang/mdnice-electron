# MarkdownNice 客户端

## 1. 使用效果

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gfis4tvibej30u00l4go8.jpg)

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gfirsytso1j31e20u0hdu.jpg)

![](https://tva1.sinaimg.cn/large/00831rSTgy1gdjvnu34tej31880u04qp.jpg)

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gfrsyf2123j31c00u01kx.jpg)


> [点击此处下载](https://github.com/gaohanghang/mdnice-electron/releases)


## 2. 如何进行开发

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/gaohanghang/mdnice-electron
# Go into the repository
cd electron-quick-start
# Install dependencies
npm install
# Run the app
npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## 3. Electron 学习资源

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs


## 4. 项目打包

参考文章：https://qii404.me/2019/07/10/electron.html

```
# Linux打包成AppImage文件
# 在Linux环境上执行
node_modules/.bin/electron-builder -l AppImage

# Windows打包成exe安装文件
# 在Windows环境下执行
node_modules/.bin/electron-builder -w nsis
# 如果在非Windows上打包win程序，也可以借助docker 如下
# docker run --rm -it -v ${PWD}:/project electronuserland/builder:wine sh -c "node_modules/.bin/electron-builder -w nsis"

# Mac打包成dmg文件
# 在Mac环境下执行
node_modules/.bin/electron-builder -m dmg

```

## 5. 参考文章

https://www.electronjs.org/docs/tutorial/first-app

[electron-builder打包见解](https://juejin.im/post/5bc53aade51d453df0447927)

[使用electron-builder，如何设置设置用户可选择安装目录？](https://newsn.net/say/electron-builder-install-directory/2.html)

## 6. License

[CC0 1.0 (Public Domain)](LICENSE.md)
