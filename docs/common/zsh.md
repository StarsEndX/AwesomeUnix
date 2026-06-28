# Zsh + Oh My Zsh

## 官方资源

- 仓库：<https://github.com/ohmyzsh/ohmyzsh>
- 网站：<https://ohmyz.sh>
- 文档：<https://github.com/ohmyzsh/ohmyzsh/wiki>

## 安装

### 前置条件

- Zsh (v4.3.9+)，macOS 已预装，Linux 需自行安装
- curl 或 wget
- git

### 安装命令

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

或使用 wget：

```sh
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### 常用插件

omz：

```text
    git
```

其他：

```sh
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
```

```sh
source ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions/zsh-autosuggestions.zsh
source ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

deb:

```sh
source /usr/share/zsh-autosuggestions/zsh-autosuggestions.zsh
source /usr/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
```

## 备注

- `.zshrc`不额外维护，考虑`source ~/.envrc`。参考 `example/envrc`
