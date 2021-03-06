## 介绍
这个示例项目是为了帮助使用 LeanCloud 的开发者, 尽快的熟悉和使用SDK而建立的。主要展示 LeanCloud SDK的各种基础和高级用法.

![demo3](https://cloud.githubusercontent.com/assets/5022872/7852215/80862f34-052c-11e5-9e32-6dee5d584dc0.png)![demo2](https://cloud.githubusercontent.com/assets/5022872/7852211/71f4ac66-052c-11e5-868a-b98b34867a06.png)![demo1](https://cloud.githubusercontent.com/assets/5022872/7852220/8d7a0e86-052c-11e5-90f2-409db9dc6cc7.png)


## 如何运行

```
   pod install
   open LeanStorageDemo.xcworkspace
```

## 使用说明

### 登录后台查看数据

用 账号/密码 (leancloud@163.com/Public123) 登录 https://leancloud.cn ，选择应用 `LeanStorage-Demo` ，即可查看后台数据。强烈建议你边查看后台边运行 Demo。当在 Demo 运行代码来增删改查时，就可以在后台看到相应的数据变化。

![image](https://cloud.githubusercontent.com/assets/5022872/7763947/3b25548e-007b-11e5-9a1b-af3ca1806175.png)


### 编译警告
代码中有一些人为添加的编译,是为了引起您足够的重视, 如果觉得没问题可以删除掉该行

### 添加Demo

1. 新建一个继承`Demo`的类, 文件位置在项目的`LeanStorageDemo`文件夹
2. 在.m里的`@end`前加一句`MakeSourcePath` 用来在编译时生成返回这个文件的方法
3. 加一个demo方法. 方法必须以demo开头, 且必须是严格按照骆驼命名法, 否则方法名显示可能会有问题

----
## 其他

如果您在使用 LeanStorage SDK中, 有自己独特高效的用法, 非常欢迎您fork 并提交pull request, 帮助其他开发者更好的使用SDK. 我们将在本项目的贡献者中, 加入您的名字和联系方式(如果您同意的话)
