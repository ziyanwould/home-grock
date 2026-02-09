# 📋 发布前准备清单

## 🎯 必须完成（发布前）

### 1. 拍摄产品截图和GIF
- [ ] 拍摄15张核心截图
- [ ] 录制5个GIF动画
- [ ] 查看 `screenshots/README.md` 了解详细要求
- [ ] 将截图放到 `screenshots/` 目录
- [ ] 更新 README.md 中的图片链接

### 2. 准备二维码
- [ ] 微信小程序二维码
- [ ] 放到 `screenshots/wechat-mini-qrcode.jpg`
- [ ] 更新 README.md 中的二维码

### 3. 更新链接
在 README.md 和文档中，替换所有占位链接：
- [ ] GitHub 仓库地址（`xxx` → 真实地址）
- [ ] Web 管理后台地址（如果有）
- [ ] Issue 链接
- [ ] Discussions 链接

### 4. 创建 GitHub 仓库
- [ ] 在 GitHub 创建新仓库 `home-grock`
- [ ] 设置仓库描述（重要！用于SEO）
- [ ] 添加 Topics 标签
- [ ] 推送代码

### 5. 配置仓库设置
- [ ] 开启 Issues
- [ ] 开启 Discussions
- [ ] 设置 Issue 模板（可选）
- [ ] 设置 Discussion 分类（可选）

---

## ✅ 推荐完成（提升效果）

### 6. 创建用户案例
在 `docs/cases/` 创建真实用户案例：
- [ ] 药品管理案例
- [ ] 调料管理案例
- [ ] 债务管理案例
- [ ] 省钱案例

### 7. 创建更多指南
在 `docs/guides/` 创建使用指南：
- [ ] 过期提醒设置指南
- [ ] 现金流预测指南
- [ ] 记账指南
- [ ] 盘点指南

### 8. 创建FAQ
在 `docs/` 创建常见问题：
- [ ] FAQ-items.md（物品管理问题）
- [ ] FAQ-billing.md（财务问题）
- [ ] FAQ-security.md（安全和隐私）

### 9. 开源工具库（可选）
在 `tools/` 创建可以开源的工具：
- [ ] 贷款计算器（loan-calculator）
- [ ] 条码生成器（barcode-generator）
- [ ] EAN-13校验（ean13-checksum）

---

## 🚀 发布流程

### 第一步：本地测试
```bash
# 1. 检查所有文件
cd /Users/liujiarong/Documents/Code/personal/Fullstack/home-grock-public
ls -la

# 2. 查看 Git 状态
git status

# 3. 添加所有文件
git add .

# 4. 提交
git commit -m "Initial commit: Home Grock - 家庭物品管理+财务记账系统"
```

### 第二步：创建 GitHub 仓库
1. 打开 GitHub
2. 点击 "New repository"
3. 仓库名：`home-grock`
4. 描述：
   ```
   🏠 完全免费的家庭物品管理+记账系统 | 避免药品/调料过期浪费 | 理清债务早日上岸 | AI识别 | 5000+用户
   ```
5. Public（公开）
6. 不要勾选 "Add README"（我们已经有了）
7. Create repository

### 第三步：推送代码
```bash
# 添加远程仓库
git remote add origin https://github.com/你的用户名/home-grock.git

# 推送
git branch -M main
git push -u origin main
```

### 第四步：配置仓库
1. 设置 Topics：
   ```
   home-management, inventory-management, financial-management,
   ai-recognition, debt-management, budget-tracker,
   loan-calculator, wechat-miniprogram, 家庭管理, 记账软件
   ```
2. 开启 Issues
3. 开启 Discussions
4. 设置 About（显示在右侧栏）

### 第五步：推广
- [ ] 在微信公众号发文推广
- [ ] 在小程序内添加 GitHub 链接
- [ ] 在知乎回答相关问题
- [ ] 在小红书发笔记
- [ ] 在朋友圈分享

---

## 📝 推广文案模板

### 朋友圈/微信群
```
【分享】我做了个工具，帮自己理清债务、避免浪费

之前：
- 药品、调料经常过期，浪费钱
- 信用卡、花呗搞不清，不知道欠多少

现在：
- 扫码记录，过期提醒，再也没扔过过期药
- 债务清清楚楚，知道还有多少期

完全免费，几个同学在用，说挺好的。

GitHub: [链接]
微信小程序: [二维码]
```

### 知乎回答
找这些问题回答：
- "如何管理家里的物品？"
- "有什么好用的记账软件？"
- "如何理清债务？"
- "怎么避免药品过期？"

### 小红书
标题：
- "终于不会让药品过期了！"
- "从欠3万到还清，我用了这个工具"
- "这样管理物品，一年省3000块"

---

## 📊 数据追踪

### GitHub 指标
- ⭐ Stars：目标 100+（第一个月）
- 👁️ Views：目标 1000+/周
- 💬 Discussions：鼓励用户互动

### 业务指标
- 注册用户数
- DAU/MAU
- 用户留存率

---

## ⚠️ 注意事项

### 发布前检查
- [ ] 所有链接都是有效的
- [ ] 没有占位符（xxx、TODO等）
- [ ] 没有敏感信息
- [ ] 截图清晰，没有隐私
- [ ] 文档语句通顺

### 隐私保护
- 不要上传包含真实用户数据的截图
- 不要上传真实的银行卡号、身份证号
- 使用测试数据拍摄截图

### 定期更新
- 每次功能更新，更新 CHANGELOG.md
- 收集用户反馈，持续改进文档
- 定期发布 Release

---

## 💡 后续计划

### 第1周
- [ ] 发布到 GitHub
- [ ] 推广到微信、知乎、小红书
- [ ] 收集初步反馈

### 第2周
- [ ] 根据反馈完善文档
- [ ] 回答用户问题（Issues/Discussions）
- [ ] 创建更多用户案例

### 第3周
- [ ] 开源工具库到 npm
- [ ] 录制视频教程
- [ ] 建立用户社群

### 第4周
- [ ] 整理第一个月数据
- [ ] 发布更新日志
- [ ] 规划下一步功能

---

**当前位置**：
```
/Users/liujiarong/Documents/Code/personal/Fullstack/home-grock-public
```

**下一步**：拍摄产品截图和GIF 📸
