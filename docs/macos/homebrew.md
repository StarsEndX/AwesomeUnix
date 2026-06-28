# Homebrew

macOS 包管理器。

## 官方资源

- 仓库：<https://github.com/Homebrew/brew>
- 网站：<https://brew.sh>
- 文档：<https://docs.brew.sh>

## 安装

### 安装命令

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### 安装后配置

Apple Silicon Mac 需要添加到 PATH：

```sh
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

## 常用命令

```sh
brew install <formula>   # 安装命令行工具
brew install --cask <app> # 安装 GUI 应用
brew update              # 更新 Homebrew
brew upgrade             # 升级已安装的包
brew list                # 列出已安装的包
brew bundle              # 通过 Brewfile 批量管理
```

## 备注

- Apple Silicon 安装路径：`/opt/homebrew`
- Intel Mac 安装路径：`/usr/local`
- 推荐使用 `brew bundle` 管理常用软件列表
