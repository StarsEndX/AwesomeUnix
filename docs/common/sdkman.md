# SDKMAN!

Software Development Kit Manager，用于管理 Java、Gradle、Kotlin 等多种 SDK 版本。

## 官方资源

- 仓库：<https://github.com/sdkman/sdkman-cli>
- 网站：<https://sdkman.io>
- 文档：<https://sdkman.io/usage>

## 安装

### 安装命令

```sh
curl -s https://get.sdkman.io | bash
```

### 安装后配置

安装完成后需要 source 或重新打开终端：

```sh
source "$HOME/.sdkman/bin/sdkman-init.sh"
```

## 常用命令

```sh
sdk list java              # 列出可用的 Java 版本
sdk install java 21-tem    # 安装 Temurin JDK 21
sdk use java 21-tem        # 切换版本
sdk default java 21-tem    # 设置默认版本
sdk install gradle         # 安装 Gradle
```

## 备注

- 安装路径：`~/.sdkman`
- 支持 `.sdkmanrc` 文件实现项目级版本管理
- 项目正在用 Rust 重写，当前版本仍可用
