# 测试和持续集成

官网英文原文地址：http://dev.px4.io/testing-and-ci.html

PX4支持广泛的单元测试和连续的集成设施。本页提供概述。
## 在本地机器上测试
这个命令可以打开一个新的带有PX4正在运行端口的shell。
```
make posix_sitl_shell none
```

这个shell中，一个可以被用作运行单元的例子：

```
pxh> tests mixer
```

或者也可以在bash中可以运行完整的测试单元： 

```
make tests
```

## 在云端测试

