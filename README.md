# 寻宝 (Treasure Hunt)

Unity 游戏「寻宝」的 Windows 构建版本。

## 项目信息

| 项目 | 内容 |
| --- | --- |
| 游戏名称 | 寻宝 |
| 引擎版本 | Unity 2022.3.17f1c1 |
| 目标平台 | Windows x64 |

## 运行方式

双击 `寻宝.exe` 即可启动游戏，无需安装。

## 目录结构

```
├── 寻宝.exe                  # 游戏主程序
├── 寻宝_Data/                # 游戏数据（场景、资源、脚本程序集）
│   ├── Managed/              # 托管程序集 (.NET/Mono)
│   ├── Resources/            # 运行时资源
│   ├── level0 / level1       # 场景数据
│   └── globalgamemanagers    # 全局设置
├── MonoBleedingEdge/         # Mono 运行时
├── UnityPlayer.dll           # Unity 引擎核心库
└── UnityCrashHandler64.exe   # 崩溃处理程序
```

## 环境要求

- Windows 7 及以上 64 位操作系统
- 支持 DirectX 11 的显卡

## 版本管理

- 构建产物中的大文件（`*.resS`）通过 Git LFS 管理，克隆前请先安装 [Git LFS](https://git-lfs.com/)：

```bash
git lfs install
```
