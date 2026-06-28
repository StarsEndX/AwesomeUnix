# pnpm

快速、节省磁盘空间的 Node.js 包管理器。

## 官方资源

- 仓库：<https://github.com/pnpm/pnpm>
- 网站：<https://pnpm.io>
- 文档：<https://pnpm.io/installation>

## 安装

### 通过 nvm 安装的 Node.js

```sh
npm install -g pnpm
```

### 独立安装

```sh
curl -fsSL https://get.pnpm.io/install.sh | sh -
```

安装后需按提示将 pnpm 加入 PATH。

## 常用命令

```sh
pnpm install             # 安装依赖
pnpm add <package>       # 添加依赖
pnpm remove <package>    # 移除依赖
pnpm run <script>        # 运行脚本
pnpm dlx <package>       # 临时执行包（类似 npx）
```

## 备注

- pnpm v11的特殊处理：allowBuilds在`~/.local/share/pnpm/global/v11/pnpm-workspace.yaml`维护
