# Apache Shiro tags for Freemarker

����Ŀ�ǻ��� [shiro-freemarker-tags](https://github.com/jagregory/shiro-freemarker-tags) ����Ŀ������jar�汾��������

## ʹ��
### ����1��ʹ��maven

```
<dependency>
    <groupId>net.zwdesign</groupId>
    <artifactId>zwdesign-shiro-freemarker-tags</artifactId>
    <version>1.0.0</version>
</dependency>
```

����һ������ "shiro", Ȼ��� ShiroTags���ʵ������ȥ
```
cfg.setSharedVariable("shiro", new ShiroTags());
```

�����Freemarkerģ��Ϳ���ʹ��

```
<@shiro.guest>Hello guest!</@shiro.guest>

ע�⣺��jar��ʹ��jdk8���д����������ּ��������⣬��ʹ���Լ���jdk�汾���д����