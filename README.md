# Apache Shiro tags for Freemarker

本项目是基于 [shiro-freemarker-tags](https://github.com/jagregory/shiro-freemarker-tags) 对项目进行了jar版本的升级。

## 使用
### 方法1：使用maven

```
<dependency>
    <groupId>net.zwdesign</groupId>
    <artifactId>zwdesign-shiro-freemarker-tags</artifactId>
    <version>1.0.0</version>
</dependency>
```

定义一个变量 "shiro", 然后把 ShiroTags这个实例放入去
```
cfg.setSharedVariable("shiro", new ShiroTags());
```

在你的Freemarker模板就可以使用

```
<@shiro.guest>Hello guest!</@shiro.guest>

注意：该jar是使用jdk8进行打包，如果出现兼容性问题，请使用自己的jdk版本进行打包）