# Skills Add

> 一键安装 GitHub 仓库中的 Skill，快速扩展你的工具链。

## 快速开始

```bash
npx skills add <repo_url> --skill <skill_name> -y -g
```

## 参数说明

| 参数 | 含义 | 示例 |
|------|------|------|
| `<repo_url>` | Skill 所在的 GitHub 仓库地址 | 固定：`https://github.com/susaijie-rgb/perfectaichz_jnsc` |
| `<skill_name>` | 要安装的 Skill 名称 | 例如：`ui-ux-pro-max` |

### 参数详解

- **`-y`** — 跳过交互式确认，自动同意安装
- **`-g`** — 全局安装，所有项目均可使用该 Skill

## 使用示例

```bash
# 安装 UI/UX 设计智能助手
npx skills add https://github.com/susaijie-rgb/perfectaichz_jnsc --skill ui-ux-pro-max -y -g
```

