### 内核将在遵循GPL协议后重新发布

[![GitHub release](https://img.shields.io/github/release/qlenlen/android_kernel_samsung_sm8550)](https://GitHub.com/qlenlen/android_kernel_samsung_sm8550/releases/) 
[![Github all releases](https://img.shields.io/github/downloads/qlenlen/android_kernel_samsung_sm8550/total)](https://GitHub.com/qlenlen/android_kernel_samsung_sm8550/releases/)
### :zap: Features
- 基于三星官方源码编译（不会缺失特定驱动）
- 定期合并AOSP的改动与其他优化
- 稳定亮屏快充（需要dlkm）更好的性能释放
- 集成Re:Kernel以提供更好的墓碑体验
- 更快速的lz4与鸿蒙lz4kd提供zram支持

### 🔖 Important Notice
- 使用TWRP或者 [kernel flasher](https://github.com/qlenlen/KernelFlasher/releases) 刷入
- GKI模式开机即可集成KSU激活root权限
- 若使用LKM模式则需自行修补init_boot
- 适配KernelSU但不包括Apatch
