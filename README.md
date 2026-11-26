# UEMotionSystem

UE 5.6 动作系统练习工程，面向 3C 动画 TA 方向。目标是用一套动画蓝图管线支撑多角色复用，重点打磨移动手感与脚步贴合。

## 进度

- W1 基础移动：单一 Base 动画蓝图 + 1D 速度混合空间，动画资产走数据表外置
- 进行中：脚步贴合、起停过渡手感标定

## 结构

| 路径 | 内容 |
| --- | --- |
| Content/Characters/Player/Base | 角色蓝图 |
| Content/Characters/Player/ABP | 动画蓝图 |
| Content/Characters/Player/Anims | 动画资产，按用途分目录 |
| Content/Data | 结构体与数据表 |
| Content/Input | 输入资产 |
| Content/Maps | 测试关卡 |

## 环境

UE 5.6 · Enhanced Input · Motion Warping · Animation Insights

## 说明

仓库用 Git LFS 管理 uasset / umap，克隆前先装 Git LFS。

工程内的角色与动画资产来自 Unreal Engine 第三人称模板，仅用于个人学习。
