# XlinTools

管理一组可复用的小工具项目。每个工具单独维护为 GitHub repository，
在本仓库中通过 Git submodule 组合，便于统一记录项目状态、文档和开发入口。

## Projects

- [`XlinDisk`](./XlinDisk) — 跨平台桌面磁盘管理工具，首个方向是基于 MCP
  的文件检查、重复文件筛选与安全清理。

## Repository layout

```text
XlinTools/
└── XlinDisk/       # git submodule: bigdo/XlinDisk
```

子项目拥有独立 issue、release 和版本节奏；本仓库只记录所引用的子模块
commit。更新子项目后，在本仓库提交 submodule 指针即可。
