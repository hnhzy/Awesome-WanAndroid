<h1 align="center">Awesome-WanAndroid</h1>

<div align="center">
<img src="https://img.shields.io/badge/Version-V1.0-brightgreen.svg">
<img src="https://img.shields.io/badge/build-passing-brightgreen.svg">
<a href="https://developer.android.com/about/versions/android-5.0.html">
    <img src="https://img.shields.io/badge/API-21+-blue.svg" alt="Min Sdk Version">
</a>
<a href="http://www.apache.org/licenses/LICENSE-2.0">
    <img src="https://img.shields.io/badge/License-Apache2.0-blue.svg" alt="License" />
</a>
<img src="https://img.shields.io/badge/Gamil-chao.qu521@gmail.com-ff69b4.svg">
</div>

<div align="center">
<img src="https://diycode.b0.upaiyun.com/user/avatar/2468.jpg">
</div>

### 致力于打造一款极致体验的WanAndroid客户端，知识和美是可以并存的哦QAQn(*≧▽≦*)n   (持续打磨中~，敬请关注)

## Introduction

Awesome WanAndroid项目基于Material Design + MVP + Rxjava2 + Retrofit + Dagger2 + GreenDao + Glide

这是一款会让您觉得很nice的技术学习APP，所用技术基本涵盖了当前Android开发中常用的主流技术框架，阅读内容主要面向想在Android开发领域成为专家的朋友们。

#### Some honest proposals：

- Android Studio 上提示缺失Dagger生成的类，可以直接编译项目，会由Dagger2自动生成

- 本项目还有一些不够完善的地方，如发现有Bug，欢迎[issue](https://github.com/JsonChao/Awesome-WanAndroid/issues)、Email([chao.qu521@gmail.com]())、PR

- 项目中的API均来自于[WanAndroid网站](http://www.wanandroid.com)，纯属共享学习之用，不得用于商业用途！！大家有任何疑问或者建议的可以联系[chao.qu521@gmail.com]()

## Preview

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/GIF1.gif"><img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/GIF2.gif">
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/GIF3.gif"><img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/GIF4.gif">
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/GIF5.gif"><img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/GIF6.gif">
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/PNG1.png" width=40%><img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/PNG2.png" width=40%>
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/PNG3.png" width=40%><img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/PNG4.png" width=40%>
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/PNG5.png" width=40%><img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/PNG6.png" width=40%>
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/PNG7.png" width=40%><img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/PNG8.png" width=40%>
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/PNG9.png" width=40%>
</div>





## Apk download（Android 5.0 or above it）（V1.0.1）

<center>

![image](https://raw.githubusercontent.com/JsonChao/Awesome-WanAndroid/master/screenshots/apk.png)

</center>

## Skill points

- 项目代码尽力遵循了阿里巴巴Java开发规范和阿里巴巴Android开发规范，并有良好的注释。

- 使用Rxjava2结合Retrofit2进行网络请求。

- 使用Rxjava2的操作符对事件流进行进行转换、延时、过滤等操作，其中使用Compose操作符结合RxUtils工具类简化线程切换调用的代码数量。

- 使用Dagger2无耦合地将Model注入Presenter、Presenter注入View，更高效地实现了MVP模式。

- 使用BasePresenter对事件流订阅的生命周期做了集成管理。

- 使用Material Design中的Behavior集合ToolBar实现了响应式的“上失下现”特效。

- 多处使用了滑动到顶部的悬浮按钮，提升阅读的便利性。

- 使用SmartRefreshLayout丰富的刷新动画将项目的美提升了一个档次。

- 使用了腾讯Bugly，以便对项目进行Bug修复和CI。

- 项目中多处使用了炫目的动画及特效。

- 更多请Clone本项目进行查看。。。


## Version

### v1.0.1

1.合理化项目分包架构

2.优化搜索模块

3.增加自动登录

4.增加TabLayout智能联动RecyclerView

5.增加沉浸式状态栏

6.优化详情文章菜单样式

7.项目整体UI美化


### V1.0.0

1.提交Awesome WanAndroid第一版 

## Thanks

### API： 

鸿洋大大提供的
[WanAndroid API](http://www.wanandroid.com/blog/show/2)

### APP：

[GeekNews](https://github.com/codeestX/GeekNews)
提供了Dagger2配合MVP的架构思路

[Toutiao](https://github.com/iMeiji/Toutiao)
提供的MD特效实现思路

[diycode](https://github.com/GcsSloop/diycode)
提供的智能滑动悬浮按钮实现思路

[Eyepetizer-in-Kotlin](https://github.com/LRH1993/Eyepetizer-in-Kotlin)
提供的搜索界面切换特效实现思路

此外，还参考了不少国内外牛人的项目，感谢开源！

### UI design：

[花瓣](https://huaban.com/) 提供了很美的UI界面设计，感谢花瓣

### icon：

[iconfont](http://www.iconfont.cn/) 阿里巴巴对外开放的很棒的icon资源

### Excellent third-party open source library：

#### Rx

[Rxjava](https://github.com/ReactiveX/RxJava)

[RxAndroid](https://github.com/ReactiveX/RxAndroid)

#### Network

[Retrofit](https://github.com/square/retrofit)

[OkHttp](https://github.com/square/okhttp)

[Gson](https://github.com/google/gson)

#### Image Loader

[Glide](https://github.com/bumptech/glide)

#### DI

[Dagger2](https://github.com/google/dagger)

[ButterKnife](https://github.com/JakeWharton/butterknife)

#### DB

[GreenDao](https://github.com/greenrobot/greenDAO)

#### UI

[SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)

[Lottie-android](https://github.com/airbnb/lottie-android)

### 还有上面没列举的一些优秀的第三方开源库，感谢开源，愿我们一同成长

### About me

- #### Email:[chao.qu521@gmail.com]()
- #### Blog:[https://jsonchao.github.io/](https://jsonchao.github.io/)
- #### 掘金:[https://juejin.im/user/5a3ba9375188252bca050ade](https://juejin.im/user/5a3ba9375188252bca050ade)
    
### License

Copyright 2018 JsonChao

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
