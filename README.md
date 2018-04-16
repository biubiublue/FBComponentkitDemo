# fbComponentkitDemo

这样集成Componentkit的原因是我发现Componentkit在pod和carthage上发布的release版本都不是最新的，很多东西都有改动，为了更方便学习最新的代码，所以就建了这个demo。

1.执行命令克隆代码
```
//获取demo的代码
git clone git@github.com:biubiublue/fbComponentkitDemo.git
```
![demo1.png](https://upload-images.jianshu.io/upload_images/4374748-d1984478fcd5eda4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```
//获取componentkit的代码
git clone git@github.com:facebook/componentkit.git
```
![demo2.png](https://upload-images.jianshu.io/upload_images/4374748-286d70d75d661f31.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

进入componentkit文件夹执行命令
```
carthage update
```
![carthage update.png](https://upload-images.jianshu.io/upload_images/4374748-477616014320f05d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2.打开工程FBComponentkitDemo.xcodeproj
将componentkit工程拖到FBComponentkitDemo工程中
![拖动到工程.png](https://upload-images.jianshu.io/upload_images/4374748-b953a17e838675cc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

添加library
![添加library.png](https://upload-images.jianshu.io/upload_images/4374748-e3c06901f3b6b099.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
