# 📦 GitHub 项目设置完全指南

本文档包含 Home Grock 项目在 GitHub 上的完整配置信息。

---

## 项目基本信息

| 项目 | 内容 |
|------|------|
| **名称** | Home Grock |
| **仓库** | home-grock |
| **类型** | 开源项目 |
| **许可证** | MIT |
| **语言** | JavaScript (Vue 3, Node.js) |
| **可见性** | Public（公开） |

---

## GitHub 仓库描述

### 简短描述（仓库 Description）

```
A personal finance & inventory management tool. Track items, prevent waste, manage debts, forecast cash flow.
```

### 详细描述（About）

```
Home Grock - 帮你省钱、理债、早日上岸的家庭管理工具
Personal Finance & Inventory Manager to Save Money and Get Debt-Free
```

---

## GitHub Topics（标签）

复制以下标签到 GitHub Settings → About → Topics：

```
personal-finance
inventory-management
debt-management
expense-tracker
vue3
nodejs
chinese-app
open-source
wechat-mini-program
web-application
```

**标签解释**：
- `personal-finance` - 个人财务管理
- `inventory-management` - 物品/库存管理
- `debt-management` - 债务管理
- `expense-tracker` - 支出追踪
- `vue3` - 前端技术栈
- `nodejs` - 后端技术栈
- `chinese-app` - 中文应用
- `open-source` - 开源项目
- `wechat-mini-program` - 微信小程序
- `web-application` - Web 应用

---

## 项目链接配置

在 GitHub Settings → About 中配置：

| 链接类型 | URL | 说明 |
|---------|-----|------|
| **Website** | https://web.home-grock.com | Web 管理后台 |
| **文档** | [在 README 中] | 指向 docs/ 目录 |
| **微信小程序** | [二维码在 README] | 用户可扫码体验 |

---

## 推荐功能配置

### ✅ 应该开启

- **Issues** - 用户可以报告 Bug 和提出问题
- **Discussions** - 社区讨论和功能建议
- **Projects** - 项目管理和任务追踪（可选）

### ❌ 可以关闭

- **Wiki** - 文档已在 docs/ 目录中
- **Packages** - 本项目不发布包
- **Deployments** - 非部署仓库

---

## 分支保护规则（可选）

针对 `main` 分支的建议保护：

1. **Require pull request reviews**
   - 至少 1 个审核者
   - 解散过期的 PR 批准

2. **Require status checks to pass**
   - 配合 CI/CD 工具使用（如 GitHub Actions）

3. **Require branches to be up to date**
   - 推送前必须与 main 分支同步

---

## GitHub Actions（可选）

如果后续要配置自动化工作流，创建 `.github/workflows/` 目录：

```
.github/
├── workflows/
│   ├── test.yml         # 自动化测试
│   ├── lint.yml         # 代码检查
│   └── deploy.yml       # 自动部署（如适用）
├── ISSUE_TEMPLATE/
├── pull_request_template.md
└── CONTRIBUTING.md
```

目前项目暂不需要，后续可添加。

---

## 模板文件清单

已配置的 GitHub 模板：

✅ **Issue 模板**：
- `bug-report.md` - Bug 报告
- `feature-request.md` - 功能请求
- `question.md` - 问题咨询

✅ **Discussion 模板**：
- `feature-suggestion.md` - 功能建议

✅ **Pull Request 模板**：
- `pull_request_template.md` - PR 说明

✅ **贡献指南**：
- `.github/CONTRIBUTING.md` - 贡献规则

---

## 首页显示优化

GitHub 仓库首页会显示：

1. **仓库信息卡**
   - 名称、Description、Website 链接
   - Stars、Forks、Issues 统计
   - Topics 标签
   - Language 统计

2. **README.md**
   - 完整的项目介绍
   - 所有截图（35 张）
   - 二维码（扫码体验）
   - 使用指南链接

3. **快速链接**
   - Issues - 反馈问题
   - Discussions - 讨论功能
   - Releases - 版本发布

---

## 推送步骤

### 1. 创建 GitHub 仓库

访问 https://github.com/new

```
Repository name: home-grock
Description: A personal finance & inventory management tool. Track items, prevent waste, manage debts, forecast cash flow.
Visibility: Public ✅
Add a README file: ❌ (我们已有)
Add .gitignore: ✅ Node
Choose a license: MIT ✅
```

### 2. 本地推送

```bash
cd /Users/liujiarong/Documents/Code/personal/Fullstack/home-grock-public

# 更新远程地址
git remote set-url origin https://github.com/你的GitHub用户名/home-grock.git

# 推送到 GitHub
git push -u origin main
```

### 3. 配置 GitHub 设置

1. Settings → General
   - 确认 Visibility 为 Public
   - 开启 Issues 和 Discussions

2. Settings → About（右侧）
   - Description: `Personal finance & inventory management tool`
   - Website: `https://web.home-grock.com`
   - Topics: 复制上面列出的 10 个标签

### 4. 验证

访问 https://github.com/你的用户名/home-grock

检查：
- ✅ README 正确显示
- ✅ 35 张截图都能加载
- ✅ Topics 标签显示
- ✅ Issues / Discussions 已开启
- ✅ Website 链接可用

---

## 项目统计预期

推送后，GitHub 会显示：

```
Language Distribution:
├── JavaScript  45%  (前后端代码)
├── Vue         25%  (前端模板)
├── Markdown    20%  (文档)
├── CSS         10%  (样式)
```

---

## 后续更新

### 当有新版本发布时

1. 创建 Git tag
   ```bash
   git tag -a v3.1 -m "Version 3.1"
   git push origin v3.1
   ```

2. GitHub 自动创建 Release
   - 在 Releases 中补充说明

3. 更新 CHANGELOG.md

### 当收到 Issue 时

1. 及时回复
2. 标记优先级
3. 分配给开发者
4. 完成后关闭

### 当收到 PR 时

1. 代码审核
2. 测试改动
3. 合并或请求修改
4. 更新版本记录

---

## 分享策略

项目推送到 GitHub 后，可以分享给：

1. **技术社区**
   - Reddit: r/opensource, r/programming
   - HackerNews
   - Product Hunt
   - 少数派、掘金等中文平台

2. **相关讨论**
   - 微信公众号（自己的或相关号）
   - 技术博客
   - GitHub 讨论区

3. **社交媒体**
   - Twitter/X
   - 小红书（展示截图）
   - 知乎（写文章）

---

## 许可证说明

项目采用 **MIT 许可证**：
- 任何人都可以自由使用、修改、分发
- 必须保留原始版权声明
- 不提供担保

---

## 常见问题

**Q: 能开源源代码吗？**
A: 目前只开源文档和截图。核心代码暂不开源，后续评估。

**Q: 可以商业使用吗？**
A: MIT 许可证允许商业使用。

**Q: 如何联系作者？**
A: 在 Issues 或 Discussions 中提问。

**Q: 有其他平台的版本吗？**
A: 目前只有微信小程序和 Web 版本。

---

**最后更新**：2026-02-10

**项目地址**：https://github.com/你的用户名/home-grock
