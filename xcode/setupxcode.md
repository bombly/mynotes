# 配置xcode环境

## 如何让xcode走系统代理

前提条件你已经配置好了代理

1. 执行

```
export all_proxy=your_proxy:your_port
```

2. 执行xcode命令

```
xcodebuild -resolvePackageDependencies -scmProvider system
```