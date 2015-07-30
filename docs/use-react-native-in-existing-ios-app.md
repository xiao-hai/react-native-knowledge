# React-Native 接入 Native 方案

### 安装
+ gem install cocoapods
+ brew install iojs
+ brew link iojs --force，这里有各种重写文件的错误，需要把npm干掉

### Pod
+ 在项目目录下新建 `Podfile` 文件
+ Podfie 文件里面添加下面的代码
```
pod 'React'
pod 'React/RCTText'
```
+ pod install