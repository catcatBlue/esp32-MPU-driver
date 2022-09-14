# 姿态解算例程

我的 mpu6050 模块没有引出 int 引脚，所以我用轮询：

```c
#define ENABLE_POLLING 1
```

把 ENABLE_POLLING 设为零就可以使用中断方式。