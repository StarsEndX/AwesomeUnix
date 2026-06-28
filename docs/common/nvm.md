# nvm

Node Version Manager，用于管理 Node.js 版本。

## 官方资源

- 仓库：<https://github.com/nvm-sh/nvm>
- 文档：<https://github.com/nvm-sh/nvm#readme>

## 安装

### 安装命令

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.5/install.sh | bash
```

```sh
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.5/install.sh | bash
```

### 安装后配置

安装脚本会尝试自动写入 shell 配置文件，手动添加见最新的脚本输出。类似：

```sh
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

## 常用命令

```sh
nvm install --lts      # 安装最新 LTS 版本
nvm use --lts          # 使用 LTS 版本
nvm alias default lts/*  # 设置默认版本
nvm ls                 # 列出已安装版本
```

## 备注

- 安装路径：`~/.nvm`
- 支持 `.nvmrc` 文件自动切换版本
- 与 Oh My Zsh 的 nvm 插件配合使用可避免重复 source
