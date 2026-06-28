# AwesomeUnix

Unix 环境初始化资源导航。个人收集为主，提供官方仓库链接，便于审查和安装。

## 使用方式

1. 浏览对应分类的工具
2. 点击官方链接，审查安装方式
3. 执行官方提供的安装命令
4. 参考 `example/` 中的配置示例，自行调整

## 通用工具

跨平台通用工具，支持 Linux 和 macOS。

- [Zsh + Oh My Zsh](docs/common/zsh.md) - Shell 和配置框架
- [nvm](docs/common/nvm.md) - Node.js 版本管理器
- [SDKMAN!](docs/common/sdkman.md) - Java/Gradle 等 SDK 版本管理器
- [pnpm](docs/common/pnpm.md) - Node.js 包管理器

## 平台特定

### macOS

- [Homebrew](docs/macos/homebrew.md) - 包管理器

### Linux

Linux 通常使用系统自带的包管理器（apt/dnf/pacman），无需额外安装。

## 参考配置

`example/` 目录包含配置示例，供参考。

## Vendor

所有关联项目均以 git submodule 形式管理，位于 `vendor/` 目录。
