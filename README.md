# HarmonyScaffolding

鸿蒙端脚手架，自动生成代码，快速查找Api，一键模板，让学习与开发效率大幅度提高。



## 最新提交

<p align="center" style="font-size:12px;"><img src="images/harmony_json" width="300px" /><br/>json转对象功能</p>

```
更新时间：2023年11月15日
更新日志：鸿蒙脚手架提交，完成json转对象功能。
文章学习地址：
```


## 快速使用

**温馨提示：只第一次需要执行三步，等前两步完成之后，以后只执行第三步即可，前两步无须再执行**

### 第一步：使用git down下项目

大家可以按照自己习惯的方式进行下载，比如使用IDE，使用TortoiseGit工具，或者使用命令，都行，以下是命令的形式下载：

```

git clone https://github.com/AbnerMing888/HarmonyScaffolding.git

```

### 第二步：执行下载安装包命令

**安装 Electron**

脚手架工具采用的是Electron进行开发的，它是一个使用 JavaScript、HTML 和 CSS 构建跨平台的桌面应用程序，既然要使用它，就需要进行安装，命令如下：


```
npm install --save-dev electron@^15.0.0
```

目前我是指定版本安装的，并配置在了package.json文件中devDependencies，主要用于开发阶段，大家可以和我的不一样，这个问题不大。

**安装模块remote**

remote 模块提供了一种在渲染进程和主进程之间进行进程间通讯的简便途径，使用 remote 模块，可以调用主进程对象的方法，而无需显式地发送进程间消息，这类似于 Java 的 RMI，虽然说13版本之后禁用了Remote模块，但是也提供了使用一个新的包 @electron/remote 来替代，一句话，主要用于dialog相关，比如弹窗，选择电脑路径等。

```
npm i -D @electron/remote

```

### 第三步：根项目下执行命令

执行完上述两步之后，以后在进入项目，只执行如下命令即可，使用此命令的前提，你已经安装好了鸿蒙的开发环境了，并也配好了环境变量。

```
npm start
```


### 欢迎关注作者

微信搜索【App开发干货铺】，或扫描下面二维码关注，查阅更多技术文章！

<img src="images/abner.jpg" width="200px" />

### 赞赏作者

看在作者这么努力的份上，微信赞赏随意，给个鼓励好不好~

<img src="images/wx_code.jpg" width="200px" />

### License

```
Copyright (C) AbnerMing, HarmonyScaffolding Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```


