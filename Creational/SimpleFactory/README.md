# 简单工厂模式

## 简介

提供了一种 **创建对象** 的最佳方式。

在工厂模式中，我们在创建对象时不会对客户端暴露创建逻辑，并且是通过使用一个 **共同的接口** 来 *指向新创建的对象*。

## 示例

> 场景：数据库访问; 当不知道最后系统采用哪一类数据库时