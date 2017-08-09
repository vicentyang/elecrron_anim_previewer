* 平常有一些帧动画需要快速预览，没有找到合适的工具 就自己写了一个，原理很简单就是在定时器中循环调用canvas的drawImage方法
![](./img1.png>)
##  使用说明
* 初次启动 安装 electron-prebuilt 全局依赖
```
npm install -g electron-prebuilt
```
* 若需要打包 初次安装 electron-packager 打包全局依赖
```
npm install -g electron-packager
```
* 启动项目
```
electron .
```
* 打包
```
electron-packager 项目文件夹路径 打包后的名称 --overwrite to force
```

### 待完成
* 使用 chrome-har-capturer 将网站导出成 har 包 -- chrome headless 新特性
